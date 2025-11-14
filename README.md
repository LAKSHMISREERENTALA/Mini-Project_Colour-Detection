🎨 Image Color Detector – Python Project


The Image Color Detector is a Python-based desktop application built using Tkinter, OpenCV, PIL, Pandas, and ReportLab.
It allows users to:
Upload an image
Use live webcam
Detect colors by double-clicking on any pixel
Display color name & RGB values
Save detected colors as a PDF
Print/view selected image
This project is useful for designers, developers, artists, and color enthusiasts.

🧰 Tech Stack & Libraries Used
Python Libraries
Tkinter → GUI
OpenCV → Image processing & webcam
Pillow (PIL) → Image display
Pandas → Read color dataset
ReportLab → PDF generation
Install required libraries
pip install opencv-python pillow pandas reportlab

✨ Features
✔ Image Upload
Select and load any image from your system.
✔ Live Camera Mode
Capture colors in real-time using your webcam.
✔ Color Detection
Double-click any point to get:
Color name
RGB values
Color preview rectangle
✔ Color History
All detected colors appear in a Tkinter Listbox.
✔ Save as PDF
Exports all detected colors to detected_colors.pdf.
✔ Print / View Image
Opens the uploaded image using the default system viewer.
✔ User-Friendly GUI
Stylish buttons & easy navigation.

📂 Project Structure
Image_Color_Detector/
│
├── main.py
├── colors.csv
├── detected_colors.pdf   # auto-generated
└── README.md

colors.csv contains color names & RGB values.
🚀 How to Run the Application
1. Clone the repository
git clone <your-github-ssh-url>
2. Open project folder
cd Image_Color_Detector
3. Install dependencies
pip install -r requirements.txt
(Or install manually)
4. Run the app
python main.py


🔮 Future Enhancements
Add HEX code copy feature
Save detected colors to CSV
Multi-languag UI
More themes
Color picker with HSV wheel
