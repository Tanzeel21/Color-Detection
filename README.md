# Color-Detection
This project detects colors in an image using **OpenCV** and a dataset of color names.  
When you double-click on a pixel in the image, it shows the closest color name and its RGB values.

## How to Run
1. Install requirements:
   ```bash
   pip install opencv-python pandas
   ```
2. Place your image as `colorpic.jpg` in the project folder.  
3. Run the script:
   ```bash
   python color_detection.py
   ```
4. Double-click anywhere on the image window to detect the color.  
5. Press **Esc** to exit.

## Files
- `color_detection.py` → Main code  
- `colors.csv` → Color dataset (865 colors)  
- `colorpic.jpg` → Sample image  

## Example
Double-click on a pixel →  
```
Color: Blue | R=0 G=48 B=143
```
