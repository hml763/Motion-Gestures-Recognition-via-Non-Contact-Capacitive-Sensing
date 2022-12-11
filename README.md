# Motion-Gestures-Recognition-via-Non-Contact-Capacitive-Sensing


This dataset is a capacitive value collected from four electrodes via non-contact hand motion gestures from three subjects with ten different hand gesture types.

The signal was preprocessed with schemes to take the denoising effect, which is illustrated in detail in our paper. Each framed dataset was extracted from a dynamic threshold and windowed to a certain window length, accommodating inclusive features to determine the gesture types.

The class labels are as follows.

    ├── Dataset
    │   ├── LR   ===> Class Type 0
    │   ├── RL   ===> Class Type 1
    │   ├── AB   ===> Class Type 2
    │   ├── AD   ===> Class Type 3
    │   ├── BA   ===> Class Type 4
    │   ├── CB   ===> Class Type 5
    │   ├── CD   ===> Class Type 6
    │   ├── DA   ===> Class Type 7
    │   ├── Down ===> Class Type 8
    │   ├── UP   ===> Class Type 9
    
Each gesture consists of 100 datasets, having 1000 gestures in total.

Currently, our paper "Designing Real-Time User-Interface Control System with Motion Gestures Recognition via Non-Contact Capacitive Sensing, H. Lee, et al.," is under review in Human–Computer Interaction Journal.

If using this dataset, please cite this GitHub: https://github.com/hml763/Motion-Gestures-Recognition-via-Non-Contact-Capacitive-Sensing
