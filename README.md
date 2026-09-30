# Human and Forklift Detection (YOLOv3)

Object detection of people and forklifts with YOLOv3 (TensorFlow 2), built in Google Colab in 2020.

<!-- Project description to be added. -->

## Notebooks

| Notebook | What it does |
|---|---|
| [`01_scrape_imagenet_images.ipynb`](notebooks/01_scrape_imagenet_images.ipynb) | Scrapes image URLs for the ImageNet **person** (`n00007846`) and **forklift** (`n03384352`) synsets with `requests` + BeautifulSoup and downloads the images |
| [`02_download_imagenet_bounding_boxes.ipynb`](notebooks/02_download_imagenet_bounding_boxes.ipynb) | Downloads ImageNet bounding-box annotations for both classes |
| [`03_yolov3_tf2_baseline.ipynb`](notebooks/03_yolov3_tf2_baseline.ipynb) | YOLOv3-TF2 set-up, pretrained-weight conversion and a baseline transfer-learning run |
| [`04_yolov3_custom_training_and_detection.ipynb`](notebooks/04_yolov3_custom_training_and_detection.ipynb) | Trains the custom person/forklift detector on the labeled dataset and runs it on images and forklift videos |

The notebooks are kept as they were used in Colab, so Google Drive paths are hard-coded. The ImageNet URL API used in notebooks 1 and 2 has since been retired.

**Not included:** the scraped images, the hand-labeled annotations, trained weights and videos.

## Built on

- [zzh8829/yolov3-tf2](https://github.com/zzh8829/yolov3-tf2) (MIT)
- [pythonlessons/TensorFlow-2.x-YOLOv3](https://github.com/pythonlessons/TensorFlow-2.x-YOLOv3) (MIT)
- [tzutalin/ImageNet_Utils](https://github.com/tzutalin/ImageNet_Utils)
- [ImageNet](https://www.image-net.org/) for the source images

## Author

Sriparvathi Shaji Bhattathiri
