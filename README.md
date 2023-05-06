# Facial-Expression-Detection
A Facial-Expression-Recognition System using DEEP Learning



## Dependencies

* Python 3, [OpenCV](https://opencv.org/), [Tensorflow](https://www.tensorflow.org/)
* To install the required packages, run `pip install -r requirements.txt`.

## Basic Usage

The repository is currently compatible with `tensorflow-2.0` and makes use of the Keras API using the `tensorflow.keras` library.

* Download the FER-2013 dataset inside the `src` folder.
* Download from here -> https://drive.google.com/file/d/1SkLR_fZsFhBLVvST-JRFYLWAQxP88jXN/view?usp=sharing

* If you want to train this model, use:  

```bash
cd src
python emotions.py --mode train
```

* If you want to view the predictions without training again,  

```bash
cd src
python emotions.py --mode display
```
