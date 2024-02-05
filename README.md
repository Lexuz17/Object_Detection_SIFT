# Object_Detection

⁤This project builds around OpenCV library object detection based on the Scale- Invariant Feature Transform (SIFT) algorithm in a scene. ⁤⁤The target image is preprocessed by making it grayscale, performing Gaussian blur, and histogram equalization. ⁤⁤The images of scenes in the specified directory undergo similar pretreatments. ⁤⁤SIFT algorithm detects keypoints and calculate descriptors from both target and scene. ⁤

⁤The script next uses the feature matcher, FLANN, from the theory of descriptor match Lowe. ⁤⁤It searches through scene image shapes, finding the best match iteratively based on the number of valid matches. ⁤⁤The final output is displayed as the match of the keypoints along with the best matched scene image. ⁤⁤The given script can be considered as a simple illustration of object recognition using SIFT and FLANN in computer vision. ⁤
