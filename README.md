# ClumzyBird
It's a game named [ClumsyBird](https://github.com/Maxine-Gao/ClumzyBird) that uses gesture and eye blinking to controller the bird.



### Installation

Make sure you've got the following packages:

cv2、dlib、numpy、os、pygame、imutils


```shell
$ pip install opencv-python
$ pip install dlib
$ pip install numpy
$ pip install os
$ pip install pygame
$ pip install imuyils
```

### Method
Uses OpenCV to recognize hand gestures.

Uses OpenCV and [shape_predictor_68_face_landmarks.dat](https://github.com/AKSHAYUBHAT/TensorFace/tree/master/openface/models/dlib) to find eyes and their points.

