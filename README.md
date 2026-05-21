# Vision-Blend-Smart-Sunglasses-Overlay-using-Image-Processing
## Aim

To design a system that digitally places sunglasses onto a human face image using image processing techniques.

### Objective
To explore image overlay and compositing techniques
To implement masking and alpha blending
To understand Region of Interest (ROI) handling
To generate a simple augmented visual output

### Introduction

Image processing enables us to enhance and modify digital images for various applications. In this project, we simulate an augmented effect by placing sunglasses onto a face image.

A PNG image of sunglasses (with a transparent background) is aligned with the eye region of a face. The alpha channel of the PNG ensures smooth blending, making the sunglasses appear naturally integrated with the face.

### Methodology
1. Import the face image
2. Import the sunglasses image (PNG format with transparency)
3. Adjust the size of the sunglasses to fit the face
4. Separate the alpha channel for masking
5. Identify and extract the eye region (ROI)
6. Use masking to eliminate unwanted portions
7. Blend the sunglasses with the ROI
8. Insert the modified region back into the original image
### Algorithm
1. Begin
2. Read the input face image
3. Read the sunglasses image
4. Resize the sunglasses based on face dimensions
5. Split the image into color and alpha channels
6. Generate a mask using the alpha channel
7. Define the eye region (ROI)
8. Apply the mask to remove background from ROI
9. Apply the mask to isolate sunglasses
10. Merge both images using blending
11. Replace the ROI in the original image.
12. Display the final output
13. End
Output
### 1. Input Face Image

<img width="388" height="427" alt="image" src="https://github.com/user-attachments/assets/bf049bd1-1997-4278-9427-30834ab3e77a" />


### 2. Masked eye region

<img width="236" height="82" alt="image" src="https://github.com/user-attachments/assets/3a21e034-769b-4c12-a37e-ca058e13d1af" />


### 3. Masked sunglass region

<img width="243" height="86" alt="image" src="https://github.com/user-attachments/assets/76e5f438-1b27-4e46-baad-a4aa6e3657d3" />



### 4. Augmented Eye and Sunglass

<img width="241" height="83" alt="image" src="https://github.com/user-attachments/assets/2a6a91f0-c71a-437f-babe-1e54433fa065" />



### 5. Final Augmented Image

<img width="351" height="417" alt="image" src="https://github.com/user-attachments/assets/7292f999-5ab7-49f3-99cc-bdf1991bb0dc" />



### Limitations
1. Eye region selection is done manually
2. Cannot handle multiple faces simultaneously
3. Alignment may differ depending on face orientation
4. Future Enhancements
5. Integration of automatic face and eye detection
6. Support for live webcam processing
7. Addition of multiple accessories like caps, masks, etc.
8. Improved scaling and rotation handling

### Result
The system successfully overlays sunglasses onto the face image using masking and blending techniques, resulting in a visually realistic augmented image.
