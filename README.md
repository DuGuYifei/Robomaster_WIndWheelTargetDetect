# Robomaster_WIndWheelTargetDetect

Display:https://www.bilibili.com/video/BV1tW4y1y7Zy?vd_source=6beebf17d5aa6fb3d9fb4b629d0b319a

After watching DJI Robomaster match 2022, I realize this function which can detect the shoot target that changes in rotating wind wheel.

Use AI detect and recognize shoot target. Use openCV handle the image and train SVM.

1. Split BGR channels

2. Binaryzation

3. Flood fill algorithm

3. Find contours

5. Perspective Transformation

4. SVM train

5. SVM recognize
