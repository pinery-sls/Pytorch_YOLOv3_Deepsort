# Pytorch_YOLOv3_Deepsort
 Yolov3 and Deepsort


![demo](demo_yolov3_deepsort.gif)

## Download
### Deepsort
Download [ckpt.t7](https://drive.google.com/drive/folders/1xhG0kRH1EX5B9_Iz8gQJb7UNnn_riXi6) and copy to deep_sort_pytorch/deep_sort/deep/checkpoint/

### YOLOv3
Downlod Yolov3 model and copy to yolov3/weights/

[assets]: https://github.com/ultralytics/yolov3/releases

|Model |
| ------ |
|[YOLOv3-tiny][assets] |
|[YOLOv3][assets] |
|[YOLOv3-SPP][assets] |

## Tracking sources

Tracking can be run on most video formats

```bash
python3 track.py --source ... --show-vid  # show live inference results as well
```

- Video:  `--source file.mp4`
- Webcam:  `--source 0`
- RTSP stream:  `--source rtsp://170.93.143.139/rtplive/470011e600ef003a004ee33696235daa`
- HTTP stream:  `--source http://wmccpinetop.axiscam.net/mjpg/video.mjpg`
