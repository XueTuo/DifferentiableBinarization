# DifferentiableBinarization
This is an implementation of [Real-time Scene Text Detection with Differentiable Binarization](https://arxiv.org/abs/1911.08947) in Keras and Tensorflow,
Most portions of code are borrowed from the official implementation [MhLiao/DB](https://github.com/MhLiao/DB).

## Build Dataset
Build dataset in the same way as the official implementation.
```
  datasets/total_text/train_images
  datasets/total_text/train_gts
  datasets/total_text/train_list.txt
  datasets/total_text/test_images
  datasets/total_text/test_gts
  datasets/total_text/test_list.txt
```
## DataSets
The root of the dataset directory can be DB/datasets/.

Download the converted ground-truth and data list [Baidu Drive](https://pan.baidu.com/s/1BPYxcZnLXN87rQKmz9PFYA) (download code: mz0a), [Google Drive](https://drive.google.com/drive/folders/12ozVTiBIqK8rUFWLUrlquNfoQxL2kAl7). The images of each dataset can be obtained from their official website.

## Train
`python train.py`
You can download a trained model weights on TotalText by [baidu netdisk](https://pan.baidu.com/s/1SGKgI6pMuGvUb8RlHePQxA) code:jy6m or [google driver](https://drive.google.com/open?id=1ausCBrADzlhqoo6viuWP_e_zYdiqUKA7)

## Test
`python inference.py`

![image1](test/img192.jpg) 
![image2](test/img795.jpg)
![image3](test/img1095.jpg)
