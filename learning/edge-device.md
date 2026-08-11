## How to deploy ML model on CCTV

[Article](https://www.thinkautonomous.ai/blog/how-to-deploy-a-deep-learning-model-at-the-edge/)

### Deployment architecture
First decide where inference will run:

- Edge (on/near camera)
    - Devices: Raspberry Pi, NVIDIA Jetson, smart cameras
    - Pros: low latency, works offline
    - Cons: limited compute
- Server-based (most common)
    - CCTV streams → server → ML inference
    - Pros: powerful, scalable
    - Cons: network delay
### Access the CCTV video stream

Most CCTV cameras provide streams via:

* **RTSP (Real Time Streaming Protocol)** ← most common
* HTTP/MJPEG streams
* ONVIF protocol

Example RTSP format:

```
rtsp://username:password@camera_ip:554/stream
```

Use Python + OpenCV:

```python
import cv2

cap = cv2.VideoCapture("rtsp://username:password@camera_ip:554/stream")

while True:
    ret, frame = cap.read()
    if not ret:
        break

    cv2.imshow("frame", frame)
    if cv2.waitKey(1) == 27:
        break
```