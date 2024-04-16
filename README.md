# RGB-T-Tracking-Papers-and-Results
A selection of RGB-TIR object tracking papers and their performance on various benchmarks.

| **Tracker**    | Year | **GTOT50-PR/SR** | **RGBT210-PR/SR** | **RGBT234-PR/SR** | **LasHeR-PR/SR** | Code                                                           | Paper                                                                                                                                                                 |
|----------------|------|------------------|-------------------|-------------------|------------------|----------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [1]            | 2018 | 0.852/0.626      | -/-               | -/-               | -/-              | [[Code]]                                                       | [[Paper](https://doi.org/10.1016/j.neucom.2017.11.068)]                                                                                                                                                             |
| mfDiMP [2]     | 2019 | -/-          | 0.786 /0.555       | 0.785/0.559       | 0.447/0.344           | [[Code](https://github.com/zhanglichao/end2end_rgbt_tracking)] | [[Paper](https://arxiv.org/pdf/1908.11714v1.pdf)]                                                                                                                     |
| MANet [3]      | 2019 | 0.894/0.724      | -/-               | 0.777/0.539       | 0.457/0.33       | [[Code](https://github.com/Alexadlu/MANet)]                    | [[Paper](https://ieeexplore.ieee.org/document/9022360)]                                                                                                               |
| DAPNet [4]     | 2019 | 0.882/0.707      | -/-               | 0.766/0.537       | 0.431/0.314      | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1145/3343031.3350928)]                                                                                                                  |
| DAFNet [5]     | 2019 | 0.891/0.712      | -/-               | 0.796/0.544       | 0.449/0.311      | [[Code](https://github.com/mjt1312/DAFNet)]                    | [[Paper](https://openaccess.thecvf.com/content_ICCVW_2019/papers/VISDrone/Gao_Deep_Adaptive_Fusion_Network_for_High_Performance_RGBT_Tracking_ICCVW_2019_paper.pdf)]  |
| [6]            | 2019 | 0.843/0.677      | -/-               | 0.787/0.545       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/ICIP.2019.8803528)]                                                                                                                                                             |
| [7]            | 2019 | -/-              | -/-               | 0.610/0.428       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.23919/FUSION43075.2019.9011253)]                                                                                                                                                             |
| SiamFT [8]     | 2019 | 0.826/0.700      | -/-               | 0.688/0.486       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/ACCESS.2019.2936914)]                                                                                                              |
| MaCNet [9]     | 2020 | 0.880/0.714      | -/-               | 0.790/0.554       | 0.483/0.352      | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.3390/s20020393)]                                                                                                                        |
| DMCNet [10]    | 2022 | 0.909/0.733      | 0.797/0.555       | 0.839/0.593       | 0.491/0.357      | [[Code]]                                                       | [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9737634)]                                                                                           |
| CMPP [11]      | 2020 | 0.926/0.738      | -/-               | 0.823/0.575       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/CVPR42600.2020.00709)]                                                                                                             |
| CAT [12]       | 2020 | 0.889/0.717      | 0.792/0.533       | 0.804/0.561       | 0.451/0.317      | [[Code](https://github.com/liulei970507/CAT)]                                                       | [[Paper](http://arxiv.org/abs/2007.13143)]                                                                                                                            |
| DSiamMFT [13]  | 2020 | -/-              | 0.642/0.432       | -/-               | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1016/j.image.2019.115756)]                                                                                                              |
| JMMAC [14]     | 2021 | 0.902/0.732      | -/-               | 0.790/0.573       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/TIP.2021.3060862)]                                                                                                                 |
| MANet++ [15]   | 2021 | 0.901/0.723      | -/-               | 0.800/0.554       | 0.467/0.317      | [[Code]]                                                       | [[Paper](https://arxiv.org/pdf/2011.07189.pdf)]                                                                                                                       |
| CBPNet [16]    | 2022 | 0.885/0.716      | -/-               | 0.794/0.541       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/TMM.2021.3055362)]                                                                                                                 |
| TFNet [17]     | 2022 | 0.886/0.729      | 0.777/0.529       | 0.806/0.560       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/TCSVT.2021.3067997)]                                                                                                               |
| FANet [18]     | 2018 | 0.891/0.728      | -/-               | 0.787/0.553       | 0.442/0.309      | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/TIV.2020.2980735)]                                                                                                                 |
| ADRNet [19]    | 2021 | 0.904/0.739      | -/-               | 0.809/0.571       | -/-              | [[Code](https://github.com/zhang-pengyu/ADRNet)]                                                       | [[Paper](http://dx.doi.org/10.1007/s11263-021-01495-3)]                                                                                                               |
| M 5 L [20]     | 2022 | 0.896/0.710      | -/-               | 0.795/0.542       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/TIP.2021.3125504)]                                                                                                                 |
| SiamCDA [21]   | 2022 | 0.877/0.732      | -/-               | 0.760/0.569       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1109/TCSVT.2021.3072207)]                                                                                                               |
| DuSiamRT [22]  | 2022 | 0.766/0.628      | -/-               | 0.567/0.384       | -/-              | [[Code]]                                                       | [[Paper](http://dx.doi.org/10.1007/s00371-021-02131-4)]                                                                                                               |
| APFNet [23]    | 2022 | 0.905/0.739      | -/-               | 0.827/0.579       | 0.500/0.362      | [[Code](https://github.com/yangmengmeng1997/APFNet)]           | [[Paper](https://doi.org/10.1609/aaai.v36i3.20187)]                                                                                                                   |
| MFGNet [24]    | 2022 | 0.889/0.707     | 0.749/0.494               | 0.783/0.535       | -/-       | [[Code](https://github.com/wangxiao5791509/MFG_RGBT_Tracking_PyTorch)]           | [[Paper](https://doi.org/10.48550/arXiv.2107.10433)]                                       |
| ViPT [25]    | 2023 |   -/-   |       -/-        | 0.835/0.617      | 0.651/0.525       | [[Code](https://github.com/jiawen-zhu/ViPT)]           | [[Paper](https://doi.org/10.48550/arXiv.2303.10826)]                                       |
| ProTrack [26]    | 2023 |   -/-   |       -/-        |    0.786/0.587   | 0.509/0.421       | [[Code]]           | [[Paper](https://doi.org/10.48550/arXiv.2207.14571)]                                       |

REFERENCES

[1] C. Li, X. Wu, N. Zhao, X. Cao, and J. Tang, “Fusing two-stream convolutional neural networks for rgb-t object tracking,” Neurocomputing, vol. 281, pp. 78–85, 2018.

[2] L. Zhang, M. Danelljan, A. Gonzalez-Garcia, J. van de Weijer, and F. S. Khan, “Multi-modal fusion for end-to-end rgb-t tracking,” pp. 2252–2261, IEEE, 10 2019.

[3] C. Li, A. Lu, A. Zheng, Z. Tu, and J. Tang, “Multi-adapter rgbt tracking,” pp. 2262–2270, 2019.

[4] Y. Zhu, C. Li, B. Luo, J. Tang, and X. Wang, “Dense feature aggregation and pruning for rgbt tracking,” pp. 465–472, 2019.

[5] Y. Gao, C. Li, Y. Zhu, J. Tang, T. He, and F. Wang, “Deep adaptive fusion network for high performance rgbt tracking,” pp. 91–99, Institute of Electrical and Electronics Engineers Inc., 10 2019.

[6] R. Yang, Y. Zhu, X. Wang, C. Li, and J. Tang, “Learning target-oriented dual attention for robust rgb-t tracking,” 8 2019.

[7] X. Zhang, P. Ye, D. Qiao, J. Zhao, S. Peng, and G. Xiao, “Object fusion tracking based on visible and infrared images using fully convolutional siamese networks,” pp. 1–8, IEEE, 7 2019.

[8] X. Zhang, P. Ye, S. Peng, J. Liu, K. Gong, and G. Xiao, “Siamft: An rgb-infrared fusion tracking method via fully convolutional siamese networks,” IEEE Access, vol. 7, pp. 122122–122133, 2019.

[9] H. Zhang, L. Zhang, L. Zhuo, and J. Zhang, “Object tracking in rgb-t videos using modal-aware attention network and competitive learning,” Sensors (Switzerland), vol. 20, 1 2020.

[10] A. Lu, C. Qian, C. Li, J. Tang, and L. Wang, “Duality-gated mutual condition network for rgbt tracking,” IEEE Transactions on Neural Networks and Learning Systems, pp. 1–14, 2022.

[11] C. Wang, C. Xu, Z. Cui, L. Zhou, T. Zhang, X. Zhang, and J. Yang, “Cross-modal pattern-propagation for rgb-t tracking,” pp. 7062–7071, IEEE Computer Society, 2020.

[12] C. Li, L. Liu, A. Lu, Q. Ji, and J. Tang, “Challenge-aware rgbt tracking,” 7 2020.

[13] X. Zhang, P. Ye, S. Peng, J. Liu, and G. Xiao, “Dsiammft: An rgb-t fusion tracking method via dynamic siamese networks using multi-layer feature fusion,” Signal Processing: Image Communication, vol. 84, 5 2020.

[14] P. Zhang, J. Zhao, C. Bo, D. Wang, H. Lu, and X. Yang, “Jointly modeling motion and appearance cues for robust rgb-t tracking,” IEEE Transactions on Image Processing, vol. 30, pp. 3335–3347, 2021

[15] A. Lu, C. Li, Y. Yan, J. Tang, and B. Luo, “Rgbt tracking via multi-adapter network with hierarchical divergence loss,” IEEE Transactions on Image Processing, vol. 30, pp. 5613–5625,2021.

[16] Q. Xu, Y. Mei, J. Liu, and C. Li, “Multimodal cross-layer bilinear pooling for rgbt tracking,” IEEE Transactions on Multimedia, vol. 24, pp. 567–580, 2022.

[17] Y. Zhu, C. Li, J. Tang, B. Luo, and L. Wang, “Rgbt tracking by trident fusion network,” IEEE Transactions on Circuits and Systems for Video Technology, vol. 32, pp. 579–592, 2 2022.

[18] Y. Zhu, C. Li, B. Luo, and J. Tang, “Fanet: Quality-aware feature aggregation network for robust rgb-t tracking,” 11 2018.

[19] P. Zhang, D. Wang, H. Lu, and X. Yang, “Learning adaptive attribute-driven representation for real-time rgb-t tracking,” International Journal of Computer Vision, vol. 129, pp. 2714–2729, 9 2021.

[20] Z. Tu, C. Lin, W. Zhao, C. Li, and J. Tang, “M <sup>5</sup> l: Multi-modal multi-margin metric learning for rgbt tracking,” IEEE Transactions on Image Processing, vol. 31, pp. 85–98, 2022.

[21] T. Zhang, X. Liu, Q. Zhang, and J. Han, “Siamcda: Complementarity- and distractor-aware rgb-t tracking based on siamese network,” IEEE Transactions on Circuits and Systems for Video Technology, vol. 32, pp. 1403–1417, 3 2022.

[22] C. Guo, D. Yang, C. Li, and P. Song, “Dual siamese network for rgbt tracking via fusing predicted position maps,” The Visual Computer, vol. 38, pp. 2555–2567, 7 2022.

[23] Y. Xiao, M. Yang, C. Li, L. Liu, and J. Tang, “Attribute-based progressive fusion network for rgbt tracking,” Proceedings of the AAAI Conference on Artificial Intelligence, vol. 36, pp. 2831–2838,6 2022.

[24] Xiao Wang, Xiujun Shu, Shiliang Zhang, Bo Jiang, Yaowei Wang, Yonghong Tian, Feng Wu, "Dynamic Modality-Aware Filter Generation for RGB-T Tracking", Accepted by IEEE Transactions on Multimedia (TMM), 2022.

[25] J. Zhu, S. Lai, X. Chen, D. Wang, and H. Lu, “Visual Prompt Multi-Modal Tracking,” arXiv.org, Mar. 20, 2023. https://arxiv.org/abs/2303.10826 (accessed Apr. 24, 2023).

  
[26] J. Yang, Z. Li, F. Zheng, A. Leonardis, and J. Song, “Prompting for Multi-Modal Tracking,” arXiv.org, Jul. 29, 2022. https://arxiv.org/abs/2207.14571 (accessed Apr. 25, 2023).
  

