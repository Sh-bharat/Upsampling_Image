# Image Upsampling Project

## Overview

This Python project focuses on the process of upsampling images to increase their resolution and visual quality. The technique involves inserting a pixel between every two adjacent pixels in each channel (R, G, and B) of the image. The value of the inserted pixel is computed as the mean value of its neighboring pixels. This method effectively enhances the level of detail and clarity in the image.

## How it Works

1. **Input Image**: The project starts by taking an image file as input. The image is then split into its three color channels - Red (R), Green (G), and Blue (B).

2. **Pixel Insertion**: For each channel, a new pixel is inserted in between every two adjacent pixels. The value of the inserted pixel is determined as the mean value of the neighboring pixels.

3. **Upsampling Process**: This step involves combining the three modified channels (R, G, and B) to form the new high-resolution image.

4. **Output Image**: The resulting high-resolution image is saved as an output file.

## Usage

To use this project, follow these steps:

1. **Clone the Repository**:

   ```
   git clone https://github.com/Sh-bharat/Upsampling_Image.git
   ```

2. **Navigate to the Project Directory**:

   ```
   cd image-upsampling
   ```

3. **Execute the Python Script**:

   ```
   python upsample_image.py 
   ```

   - `test.jpeg`: Input file: Replace your fle name with "test.jpeg" ,the image you want to upsample.
   - `hd_output.jpeg`: filename for the high-resolution output image.
   - Or you can update the filenames in the source-code.

    
4. **Note**:
   ```
   All files must be in a same directory.
   ```
  
     
  

## Dependencies

This project relies on the following Python libraries:

- NumPy: For efficient numerical operations on image data.
- OpenCV: To handle image input/output and basic image processing tasks.

You can install these dependencies using the following command:

```
pip install numpy opencv-python
```

## Example

To demonstrate the project, consider the input image `test.jpeg`. After running the script, the high-resolution output will be saved as `hd_output.jpeg`.
Name of the input file must be `test.jpeg` or you can change the filename in the source code.

## Notes

- This method of upsampling is a basic approach and may not yield the same quality improvement as more sophisticated techniques in professional image processing software.

- Experiment with different input images and parameters to achieve the best results for your specific use case.

Feel free to reach out if you have any questions or suggestions regarding this project!
