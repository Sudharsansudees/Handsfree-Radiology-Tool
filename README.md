# Gesture-Based Tool for Sterile Browsing of Radiology Images

A computer vision-based application designed to allow radiologists and surgeons to browse through radiology images (like X-rays, CT scans, or MRIs) using hand gestures, ensuring sterile interaction in operating rooms or clinical environments.

## 🚀 Features

- Hands-free, gesture-based navigation of medical images
- Sterile and contactless interface for use in surgical settings
- Real-time hand gesture recognition using a webcam
- Lightweight and responsive UI for image viewing
- Supports standard medical image formats (e.g., JPEG, PNG; extendable to DICOM)

## 🧠 Technologies Used

- Python
- OpenCV
- MediaPipe (for hand tracking)
- Tkinter / PyQt (for GUI, depending on implementation)
- NumPy

## 📁 Project Structure

```
gesture-based-tool/
├── images/               # Sample radiology images
├── src/                  # Source code
│   ├── gesture_control.py
│   ├── image_viewer.py
│   └── main.py
├── requirements.txt
├── README.md
└── LICENSE
```

## 🖐️ How It Works

1. The system accesses the webcam to track hand gestures.
2. Specific gestures (e.g., swipe left/right, pinch) are mapped to navigation actions.
3. The user can scroll through images without touching any input devices, maintaining sterility.

## 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/gesture-based-tool.git
   cd gesture-based-tool
   ```

2. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python src/main.py
   ```

## 🧪 Example Gestures

| Gesture | Action        |
|--------:|---------------|
| Swipe Right | Next Image  |
| Swipe Left  | Previous Image |
| Palm Open   | Pause Navigation |
| Fist        | Resume Navigation |

> You can customize gesture-to-action mappings in `gesture_control.py`.

## 📸 Screenshots / Demo

*Add demo images or a YouTube link showing the tool in use.*

## 🏥 Use Case

This tool is particularly useful in:
- Operating rooms where sterility is critical
- Radiology departments for hygienic browsing
- Medical education environments

## 📌 Future Enhancements

- DICOM support
- Voice control fallback
- Gesture customization by user
- Integration with PACS systems

## 📃 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributions

Pull requests and suggestions are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

Developed with ❤️ for smarter healthcare interaction.
