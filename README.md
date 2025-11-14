🎨 Image Color Detector – Python Project

The Image Color Detector is a Python-based desktop application built using Tkinter, OpenCV, PIL, and Pandas.
It allows users to:
Upload an image or use the live webcam
Detect colors by double-clicking on any pixel
Display the color name and RGB values
Generate a PDF report of detected colors
View or print the selected image
This project is highly useful for designers, developers, artists, and color enthusiasts.
🧰 Tech Stack & Libraries Used
Python Libraries
Tkinter → GUI
OpenCV → Image processing & webcam
Pillow (PIL) → Image viewing
Pandas → Color dataset (CSV) processing
ReportLab → PDF generation
Install required libraries:
pip install opencv-python pillow pandas reportlab
✨ Features
✔ Image Upload
Select and load any image from your system.
✔ Live Camera Mode
Capture colors in real-time using your webcam.
✔ Color Detection
Double-click any pixel to detect:
Color name
RGB values
Display rectangle with color previe
✔ Color History
All detected colors are listed in a Tkinter Listbox.
✔ Save as PDF
Detected colors can be exported to detected_colors.pdf.
✔ Print Image
Opens the uploaded image using the default system viewer.
✔ User-Friendly GUI
Beautiful buttons, labels, and easy navigation.
📂 Project Structure
Image_Color_Detector/
│
├── main.py
├── colors.csv
├── detected_colors.pdf (auto-generated)
└── README.md
colors.csv contains color names and RGB values used for comparison.
🚀 How to Run the Application
1. Clone the repository
git clone <your-github-ssh-url>
2. Open the project folder
cd Image_Color_Detector
3. Install dependencies
pip install -r requirements.txt


(Or manually install libraries listed earlier)

4. Run the application
python main.py
