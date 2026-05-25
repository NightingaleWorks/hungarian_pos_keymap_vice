# hungarian_pos_keymap_vice
Hungarian Positional Keymap for VICE (Commodore 64)

This repository contains a custom **Hungarian positional keyboard mapping** (`gtk3_pos_hu.vkm`) for the **VICE C64 emulator**.  
The goal of this project is to provide support to type C64 characters with Hungarian keyboard in VICE emulator,
but without Hungarian special characters (á, é, ó, ö, ő, ú, ü, ű).

---

## 🎯 Features

- ✔ Correct handling of **C64-specific keys** (C=, CTRL, RUN/STOP, RESTORE)  
- ✔ Proper mapping of **PI (π)** on **Shift + P**  
- ✔ Relocation of **slash (/)** to type in your BASIC program in VICE  
- ✔ Compatible with **GTK3 POS** mode  
- ✔ Clean, readable `.vkm` structure for easy modification  

---

## 📂 Files in this repository

- `gtk3_pos_hu.vkm` – The main Hungarian POS keymap  
- `README.md` – Documentation  

---

## 🔧 Installation

1. Download the `gtk3_pos_hu.vkm` file.
2. Copy the file, where the other keymap files stored, for example /usr/local/share/vice/C64
2. Open VICE.
3. Go to:  
   **Preferences → Settings → Input devices → Keyboard → Keyboard mapping → Positional (user)**
4. Select the downloaded file.
5. You can use it instantly.

---

## 🧪 Testing the layout

Recommended test steps:

- Verify C64‑specific keys:
  - Esc → RUN/STOP
  - Tab → C= (Commodore) 
  - Left CTRL → CTRL
  - Tab + Home → CLS
  - AltGr + q → Pound
- Test PI (Shift + p)
- Test relocated slash ALT (Left) → /

## 📘 Usage

You can type the majority of the characters in the Hungarian keybord.
I try to list the special ones:
- C= (Tab) -> screen control characters: Tab + 1 : orange, Tab + 2: brown, and so on
- CONTROL (Ctrl Left) -> screen control characters: Ctrl + 1 : black, Ctrl + 2: white, and so on
- CLS (Tab + Home)
- π (Shift + p)
- / (Alt (left))
- £ (AltGr + q)
- RUN/STOP (you can STOP your program with Esc, Shift + Esc -> RUN (LOAD))
 
---

## 🎮 Optional: NumPad modes

This project supports three optional configurations:

### 1. **JOYSTICK MODE (If Preferences → Allow keyset joysticks is checked && Numlock is ON)**
- KP_8 = UP  
- KP_2 = DOWN  
- KP_4 = LEFT  
- KP_6 = RIGHT  
- KP_0 = FIRE
- KP_Add, KP_Subtract, KP_Multiply, KP_Divide → math operators 

### 2. **NUMERIC KEYPAD MODE (If Preferences → Allow keyset joysticks is unchecked && NumLock is ON)**
- KP_0–9 → C64 digits  
- KP_Add, KP_Subtract, KP_Multiply, KP_Divide → math operators  
- KP_Enter → RETURN

### 3. **MATH OPERATORS → NumLock is OFF (Math operators still available)**
- KP_Add, KP_Subtract, KP_Multiply, KP_Divide

---

## 📜 License

This project is released under the **MIT License**.  
Feel free to modify, improve, or redistribute.

---

## 🤝 Contributions

Pull requests are welcome!  
If you have improvements, bug fixes, or alternative layouts, feel free to contribute.

---

## 💬 Contact

If you have questions or suggestions, open an Issue on GitHub or contact the maintainer.

This project was created with assistance from Microsoft Copilot (Conversational AI).
