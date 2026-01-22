
# Pixel Art Generator 🎨

A simple Python project that converts normal images into pixel-art style images using OpenCV and K-Means clustering.  
This project downsamples the image into blocks, reduces the number of colors, and scales it back to create a pixelated effect.

## 🔧 Features
- Converts any image into pixel art
- Uses K-Means clustering for color reduction
- Adjustable pixel block size and number of colors
- Saves the final pixel art image automatically
- Works on Linux without OpenCV GUI support (uses matplotlib)

## 🛠️ Technologies Used
- Python 3  
- OpenCV  
- NumPy  
- Matplotlib  

## 📂 Project Structure


main.py
dog.jpg
pixel_art.png
README.md


## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Install dependencies:

pip install opencv-python numpy matplotlib


Place your input image in the project folder and update the filename in main.py if needed:

imagePath = "dog.jpg"


Run the script:

python main.py


Output will be saved as:

pixel_art.png

⚙️ Customization

You can control the pixel effect by changing:

blockAcross = 50   # number of pixel blocks across width
numColors = 16    # number of colors in the output


Lower blockAcross → bigger pixels

Lower numColors → more cartoon-like effect

📸 Sample Output

Original image vs Pixel Art (side-by-side comparison):

(Add a screenshot here after uploading your result)

🚀 Future Improvements

Add command-line arguments for block size and colors

Add batch image processing

Build a small GUI or web version

👤 Author

Aniesh
B.Tech Artificial Intelligence & Data Science Student
Learning Computer Vision and Image Processing
