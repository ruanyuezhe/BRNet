# BRNet
## Background
The cultural heritage suffer from the inevitable destruction more or less over time. It is of great necessity to carry out the preservation and the restoration of cultural heritage to prolong their life span. Image acquisition of these cultural heritage is one of the most commonly used technique due to its non-destruction to the fragile relics. The current status of the cultural heritage can be recorded and and saved as electronic data. The electronic data can be further permanently stored in databases for other applications such as digital display and information mining.  
Palm-leaf manuscripts are one of the most valuable relics in the world. However, there are various factors including change of the climate or damages from the microorganism, which contribute jointly to the inevitable destruction of the palm-leaf manuscripts. Image acquisition becomes significant for preservation and restoration of these manuscripts. The acquired images are not always ideal for the existence of the background, which seriously affects the aesthetics of displaying and the subsequent processing of the images.  
The **b**ackground **r**emoval **net**work (BRNet) is proposed to remove the background from palm-leaf manuscript image. The BRNet follows the typical U-Net where a image of palm-leaf manuscript can be fed into the network and a background distribution map can be consequently and automatically generated.
## Depends
[Anaconda for Python 3.8](https://www.python.org/)  
[conda install PyTorch](https://pytorch.org)  
[conda install OpenCV](https://opencv.org/)  
## Contrast Method
Canny edge detection (Canny) method was applied for the comparison of the performance on background removal. The implementation of Canny method is shown in [Contrast Method](https://github.com/ruanyuezhe/BRNet/blob/main/Contrast%20Method/Canny_br.py)
