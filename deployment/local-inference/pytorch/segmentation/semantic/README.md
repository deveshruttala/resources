# Datature PyTorch Semantic Segmentation Model Guide

This guide is for carrying out predictions using exported Datature PyTorch Semantic Segmentation models.


## Requirements

To use GPU, the CUDA requirement is >= 11.3. Install the required packages using:

`pip install -r requirements.txt --extra-index-url https://download.pytorch.org/whl/cu113`


For CPU usage, install the required packages using:

`pip3 install -r requirements.txt`


## Making Predictions

The `predict.py` file can be run as follows:

```shell
python3 predict.py \
    -i input_folder_path \
    -o output_folder_path \
    -m model_path
```

**input_folder_path** refers to the path to the folder where the images for prediction are stored.

**output_folder_path** refers to the path to the folder where the output images after prediction are to be stored. Do note that the output image names will be the same as the input image names so this should not be the same folder as the input folder.

**model_path** refers to the path to the model (not the model directory)
