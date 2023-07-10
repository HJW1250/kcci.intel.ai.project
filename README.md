# Project name
Media Mosaic
1.영상재생
2.실시간으로 얼굴과 자동차 번호판을 인식한다.
3.얼굴은 이모티콘으로 대체하고 번호판은 모자이크 처리한다.


## Requirement

CPU:	Intel(R) Core(TM) i7-9700 CPU @ 3.00GHz
memory:	32.0GB
GPU:Intel(R) UHD Graphics 630



## Clone code



```shell
[git clone https://github.com/desafin/intel_AI_squat_counter]
```




## Steps to run

얼굴인식
python face_recog.py -d GPU -i C:\Users\teee\Media_Mosaic\human.mp4 -m C:\Users\teee\test\.venv\Scripts\open_model_zoo\demos\object_detection_demo\python\intel\face-detection-adas-0001\FP16\face-detection-adas-0001.xml -at ssd



번호판인식
python car_plate_detection.py -d GPU -i C:\Users\teee\Media_Mosaic\car_human.mp4 -m C:\Users\teee\test\.venv\Scripts\open_model_zoo\demos\object_detection_demo\python\intel\vehicle-license-plate-detection-barrier-0106\FP16\vehicle-license-plate-detection-barrier-0106.xml -at ssd



## Output

![image](https://github.com/kithousand/kcci.intel.ai.project/assets/96045246/05f1a475-6799-41cb-b085-0d3d0bcfdd50)


