# PrimaDNN':A Characteristics-aware DNN Customization for Singing Technique Detection


## Abstract
```
Professional vocalists modulate their voice timbre or pitch to make their vocal performance more expressive. Such fluctuations are called singing techniques. 
Automatic detection of singing techniques from audio tracks can be beneficial to understand how each singer expresses the performance, yet it can also be difficult due to the wide variety of the singing techniques. 
A deep neural network (DNN) model can handle such variety; however, there might be a possibility that considering the characteristics of the data improves the performance of singing technique detection. 
In this paper, we propose PrimaDNN, a CRNN model with a characteristics-oriented improvement. 
The features of the model are: 1) input feature representation based on auxiliary pitch information and multi-resolution mel spectrograms, 2) Convolution module based on the Squeeze-and-excitation (SENet) and the Instance normalization.
In the results of J-POP singing technique detection, PrimaDNN achieved the best results of 44.9\% at the overall macro-F measure, compared to conventional works.
We also found that the contribution of each component varies depending on the type of singing technique. 
```

<div style="text-align: center;">
    <img src="assets/img/overview.png" width="600px">
</div>


