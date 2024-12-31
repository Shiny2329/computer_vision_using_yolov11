# Implementation of YOLOv11 on Corrosion Instance Segmentation Dataset

## Overview

This project focuses on training the YOLOv11 object detection models for detecting corrosion in various materials. The aim is to obtain the performance of the model in terms of accuracy, speed, and robustness when identifying corrosion in images.

## Dataset

The dataset consists of 4942 corrosion images. The split is as following:
- Training images : 4325
- Validation images : 412
- Testing images : 205

The corrosion dataset was downloaded for YOLOv11 format. The link for the dataset is provided below:
- [https://universe.roboflow.com/cawilai-interns-july-2023/corrosion-instance-segmentation-sfcpc/dataset/16]

## Resources

- Microsoft Visual Studio 2022 was used.
- NVIDIA GeForce GTX 1050 was used.
- The model YOLO11n was used.
- The model was trained on 30 epochs.

## Prerequisites

Execute the commands given below in Developer Powershell / Console to install the dependencies required.

```bash
pip install ultralytics
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
pip install numpy opencv-python
pip install pyyaml
pip install onnx
```

## Training

- Create the .py and .YAML files and write the code provided.
- Modify the files as needed
- Run the .py file

## Results

The performance of the model I trained is given below:

- Results of YOLOv11:

<h3>YOLOv11</h3>
<table>
  <tr>
    <th rowspan="2">Model</th>
    <th colspan="3">Precision</th>
    <th colspan="3">Recall</th>
    <th colspan="3">mAP@50</th>
    <th colspan="3">mAP@50-95</th>
    <th rowspan="2">Training time (hours)</th>
  </tr>
  <tr>
    <th>Train.</th>
    <th>Val.</th>
    <th>Test.</th>
    <th>Train.</th>
    <th>Val.</th>
    <th>Test.</th>
    <th>Train.</th>
    <th>Val.</th>
    <th>Test.</th>
    <th>Train.</th>
    <th>Val.</th>
    <th>Test.</th>
  </tr>
  <tr>
    <td>YOLO11n</td>
    <td>0.606</td>
    <td>0.570</td>
    <td>0.523</td>
    <td>0.419</td>
    <td>0.416</td>
    <td>0.397</td>
    <td>0.453</td>
    <td>0.442</td>
    <td>0.395</td>
    <td>0.259</td>
    <td>0.262</td>
    <td>0.218</td>
    <td>3.308</td>
  </tr>
</table>

## Acknowledgments

YOLO model:

- [YOLOv11 Repository](https://github.com/ultralytics/ultralytics)

Dataset sources and contributors:

- [Dataset Owner : CawilAI Interns July 2023](https://universe.roboflow.com/cawilai-interns-july-2023)
- [Dataset](https://universe.roboflow.com/cawilai-interns-july-2023/corrosion-instance-segmentation-sfcpc/dataset/16)

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or feedback, feel free to contact:

- **Name**: Muhammad Ahmad Abbas
- **Email**: ahmad.abbas.2329@gmail.com
