# Yolov5ToOpenvino2022
YOLOv5 Model to OpenVINO IR
```
git clone https://github.com/a20820381/Yolov5ToOpenvino2022.git
```
```
cd Yolov5ToOpenvino2022
```
```
mo --input_model .\model\yolov5s.onnx
```
```
pip install -r requirements.txt
```
```
python .\inference.py .\yolov5s.xml .\img\elephants.jpg
```
