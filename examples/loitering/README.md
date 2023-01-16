# Detect people loitering example

## Setup

You can follow the instructions [here](../../vqpy/README.md) to prepare your environment for VQPy. No other dependency is used.

## Run example

[Video](https://youtu.be/EuLMrUFNRxQ) needs to be downloaded to local before running the example.

Local environment:

```shell
python VQPy/examples/loitering/main.py
    --path /path/to/video
    --save_folder /path/to/output/folder
    -d /path/to/yolox/model/folder
```

- `--path`: path of video;
- `--save_folder`: the folder that you preferred to save the query result;
- `-d`: directory containing pre-trained models (only model for YOLOX is used).

Or use [demo.ipynb](./demo.ipynb). Notebook tested in Google Colab, it's advised to use a unused, clean Python3.8 environment if you prefer to run it locally.

Please see the Jupyter notebook for more details about the query.