# Lightweight Spatial Pyramid Convolutional Neural Network for Traffic Sign Classification

Caffe Model for traffic sign classification described in
> "Lightweight Spatial Pyramid Convolutional Neural Network for Traffic Sign Classification"<br/>
> Reza Fuad Rachmadi, Gou Koutaki, and Kohichi Ogata<br/>
> 2018 Indonesian Association for Pattern Recognition (INAPR) International Conference<br/>
> [<a href="http://web.ee.its.ac.id/~fuad/papers/INAPR2018.pdf">Preprint</a>]

#### 1. Comparison between several different approaches and our method on GTSRB (Germany Traffic Sign Recognition Benchmark) dataset:

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

#### 2. Comparison between several different approaches and our method on BTSC (Belgium Traffic Sign Classification) dataset:

| Method                            | #Params       | Accuracy      |
| --------------------------------- |     :---:     |     :---:     |
| INNC + INNLP [2]                  |   -           |   98.32%      |
| SRGE [23]                         |   -           |   96.26%      |
| HOG + ELM [24]                    |   -           |   98.38%      |
| HOG + Kernel ELM [24]             |   -           |   98.62%      |
| HOS + GE [25]                     |   -           |   98.89%      |
| **Our approach (SP-ResNet20)**    |   **1.41 M**  | TBD    |
| **Our approach (SP-ResNet32)**    |   **2.39 M**  | TBD    |
| **Our approach (Ensemble)**       |   **3.80 M**  | TBD    |


#### 3. Comparison between several different approaches and our method on CURE-TSR (Challenging Unreal and Real Environments for Traffic Sign Recognition) dataset:

To do

### To Do
- [x] Experiments on GTSRB Dataset
- [ ] Experiments on BTSC Dataset
- [ ] Experiments on CURE-TSR Dataset

Last update: 24 Agustus 2018

### References
[1] J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel, “The german traffic sign recognition benchmark: a multi-class classification competition,” in Neural Networks (IJCNN), The 2011 International Joint Conference on. IEEE, 2011, pp. 1453–1460.<br/>
[2] M. Mathias, R. Timofte, R. Benenson, and L. Van Gool, “Traffic sign recognition how far are we from the solution?” in Neural Networks
(IJCNN), The 2013 International Joint Conference on. IEEE, 2013, pp. 1–8.<br/>
[3] A. Madani and R. Yusof, “Malaysian traffic sign dataset for traffic sign detection and recognition systems,” Journal of Telecommunication, Electronic and Computer Engineering (JTEC), vol. 8, no. 11, pp. 137–143, 2016.<br/>
[4] R. F. Rachmadi, Y. Komokata, K. Uchimura, and G. Koutaki, “Road sign classification system using cascade convolutional neural network,” International Journal of Innovative Computering, Information, and Control, vol. 13, no. 1, pp. 95–109, 2017.<br/>
[5] D. Temel, G. Kwon, M. Prabhushankar, and G. AlRegib, “Cure-tsr: Challenging unreal and real environments for traffic sign recognition,” arXiv preprint arXiv:1712.02463, 2017.<br/>
[6] Z. Zhu, D. Liang, S. Zhang, X. Huang, B. Li, and S. Hu, “Traffic sign detection and classification in the wild,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2016, pp. 2110–2118.<br/>
[7] Y. Zeng, X. Xu, Y. Fang, and K. Zhao, “Traffic sign recognition using extreme learning classifier with deep convolutional features,” in The 2015 international conference on intelligence science and big data engineering (IScIDE 2015), Suzhou, China, vol. 9242, 2015, pp. 272–280.<br/>
[8] A. Wong, M. J. Shafiee, and M. S. Jules, “µnet: A highly compact deep convolutional neural network architecture for real-time embedded traffic sign classification,” arXiv preprint arXiv:1804.00497, 2018.<br/>
[9] D. Cires¸An, U. Meier, J. Masci, and J. Schmidhuber, “Multi-column deep neural network for traffic sign classification,” Neural networks, vol. 32, pp. 333–338, 2012.<br/>
[10] J. Jin, K. Fu, and C. Zhang, “Traffic sign recognition with hinge loss trained convolutional neural networks,” IEEE Transactions on Intelligent Transportation Systems, vol. 15, no. 5, pp. 1991–2000, Oct 2014.<br/>
[11] lvaro Arcos-Garca, J. A. lvarez Garca, and L. M. Soria-Morillo, “Deep neural network for traffic sign recognition systems: An
analysis of spatial transformers and stochastic optimisation methods,” Neural Networks, vol. 99, pp. 158 – 165, 2018.<br/>
[12] H. H. Aghdam, E. J. Heravi, and D. Puig, “A practical approach for detection and classification of traffic signs using convolutional neural networks,” Robotics and Autonomous Systems, vol. 84, pp. 97 – 112, 2016.<br/>
[13] P. Sermanet and Y. LeCun, “Traffic sign recognition with multi-scale convolutional networks,” in Neural Networks (IJCNN), The 2011 International Joint Conference on. IEEE, 2011, pp. 2809–2813.<br/>
[14] A. Krizhevsky, I. Sutskever, and G. E. Hinton, “Imagenet classification with deep convolutional neural networks,” in Advances in neural information processing systems, 2012, pp. 1097–1105.<br/>
[15] R. F. Rachmadi, K. Uchimura, and G. Koutaki, “Spatial pyramid convolutional neural network for social event detection in static image,” in International Student conference on Advanced Science and Technology (ICAST), 2016.<br/>
[16] ——, “Road sign classification using spatial pyramid convolutional neural network,” in IIEEJ International Workshop on Image Electronics and Visual Computing, 2017.<br/>
[17] K. Zuiderveld, “Contrast limited adaptive histogram equalization,” Graphics gems, pp. 474–485, 1994.<br/>
[18] Y. Jia, E. Shelhamer, J. Donahue, S. Karayev, J. Long, R. Girshick, S. Guadarrama, and T. Darrell, “Caffe: Convolutional architecture for fast feature embedding,” in Proceedings of the 22Nd ACM International Conference on Multimedia, ser. MM ’14, 2014, pp. 675–678.<br/>
[19] I. Sutskever, J. Martens, G. Dahl, and G. Hinton, “On the importance of initialization and momentum in deep learning,” in International conference on machine learning, 2013, pp. 1139–1147.<br/>
[20] K. He, X. Zhang, S. Ren, and J. Sun, “Deep residual learning for image recognition,” in Proceedings of the IEEE conference on computer vision and pattern recognition, 2016, pp. 770–778.<br/>
[21] J. Stallkamp, M. Schlipsing, J. Salmen, and C. Igel, “Man vs. computer: Benchmarking machine learning algorithms for traffic sign recognition,” Neural networks, vol. 32, pp. 323–332, 2012.<br/>
[22] A. Canziani, A. Paszke, and E. Culurciello, “An analysis of deep neural network models for practical applications,” arXiv preprint
arXiv:1605.07678, 2016.
[23] K. Lu, Z. Ding, and S. Ge, "Sparse-Representation-Based Graph Embedding for Traffic Sign Recognition," IEEE Transactions on Intelligent Transportation Systems, 13(4), 2012, pp. 1515–1524.
[24] Z. Huang, Y. Yu, J. Gu, and H. Liu, "An Efficient Method for Traffic Sign Recognition Based on Extreme Learning Machine," IEEE Transactions on Cybernetics, 47(4), 2017, pp. 920–933. 
[25] A. Gudigar, S. Chokkadi, U. Raghavendra, and U. R. Acharya, "Local texture patterns for traffic sign recognition using higher order spectra," Pattern Recognition Letters, 94, 2017, pp. 202-210.



