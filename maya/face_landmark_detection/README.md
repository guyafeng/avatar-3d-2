# Facial Landmark Detection
Facial landmark detection example using dlib.

## Dependencies
* OpenCV (>=2.4.3)
* dlib

## Usage
### Compile

```
mkdir build
cd build
cmake .. -DUSE_AVX_INSTRUCTIONS=1
make -j8
```

### Run
```
./face_landmark_detection
```

## Face Landmarks positions
![](face_landmark.jpg)
