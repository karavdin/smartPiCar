# smartPiCar
AI on RaspberryPi based car

1. Train model in Colab and create file for Edge TPU
2. Run the model at RaspberryPi, following intructions from [official Tensorflow repository](https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/raspberry_pi)


run on RaspberryPi
>>> cd smartPiCar/code
>>> python3 detect.py --model ../data/models/lego_500_efficientdet_lite2_wholemodelRetune_edgetpu.tflite --enableEdgeTPU