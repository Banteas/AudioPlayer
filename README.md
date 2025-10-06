# Java Audio Player 🎵

A simple Java console-based program that allows users to **play, stop, reset, and quit** an audio clip using commands entered from the keyboard.

---

## 🧩 Features

* Play an audio file (`.wav` format)
* Stop the audio playback
* Reset playback to the beginning
* Quit the program safely

---

## 🛠️ Technologies Used

* **Java SE**
* **javax.sound.sampled** for audio playback
* **Scanner** for user input

---

## 📁 Project Structure

```
project-root/
│
├── src/
│   ├── Main.java
│   └── future-design-344320.wav
│
└── README.md
```

---

## ▶️ How to Run

### 1. Prerequisites

* **Java 17+** installed on your system
  (You can check by running `java -version` in the terminal.)

### 2. Steps

1. Clone or download this repository.
2. Place your desired `.wav` audio file in the `src` folder (or update the file path in the code).
3. Open a terminal in the project directory.
4. Compile the code:

   ```bash
   javac src/Main.java
   ```
5. Run the program:

   ```bash
   java -cp src Main
   ```

---

## 🎧 Controls

| Key | Action         |
| --- | -------------- |
| P   | Play audio     |
| S   | Stop audio     |
| R   | Reset playback |
| Q   | Quit program   |

---

## ⚠️ Notes

* Only `.wav` files are supported.
* If you encounter a `FileNotFoundException`, ensure the file path is correct.
* Make sure your audio file isn’t corrupted and is supported by Java Sound API.

---

## 📄 License

This project is released under the [MIT License](LICENSE) — feel free to use and modify it for your own learning or projects.

---

## 👤 Author

**Banteas**
Student & Developer in training 🚀
