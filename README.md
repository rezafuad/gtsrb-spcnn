# Lightweight Spatial Pyramid Convolutional Neural Network for Traffic Sign Classification

Caffe Model for traffic sign classification described in
> "Lightweight Spatial Pyramid Convolutional Neural Network for Traffic Sign Classification"<br/>
> Reza Fuad Rachmadi, Gou Koutaki, and Kohichi Ogata<br/>
> 2018 Indonesian Association for Pattern Recognition (INAPR) International Conference<br/>
> [Preprint]

Comparison between several different approaches and our method on GTSRB (Germany Traffic Sign Recognition Benchmark) dataset:

| Method                            | #Params       | Accuracy      |
| --------------------------------- |     :---:     |     :---:     |
| Human Performance [21]            |     -         |   98.84%      |
| EPCNN [12]                        |   5.22 M      |   99.70%      |
| STDCNN [11]                       |   14.6 M      |   99.71%      |
| EHLDCNN [10]                      |   23.2 M      |   99.65%      |
| MCDCNN [9]                        |   38.5 M      |   99.46%      |
| µNet [8]                          |   0.51 M      |   98.90%      |
| **Our approach (SP-ResNet20)**    |   **1.41 M**  | **99.39%**    |
| **Our approach (SP-ResNet32)**    |   **2.39 M**  | **99.70%**    |
| **Our approach (Ensemble)**       |   **3.80 M**  | **99.75%**    |

### To Do
- [x] Experiments on GTSRB Dataset
- [ ] Experiments on BTSC Dataset
- [ ] Experiments on CURE-TSR Dataset

Last update: 24 Agustus 2018
