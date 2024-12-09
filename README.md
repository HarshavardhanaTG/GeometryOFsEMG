# Hand gesture decoding using EMG - a geometric perspective

The prevailing narrative in EMG-based hand gesture decoding emphasizes the necessity of massive pretrained models trained on data from hundreds of individuals. While these models can generalize across populations, they are resource-intensive and often overlook the intrinsic properties of EMG signals.

In contrast, we demonstrate that EMG signals exhibit a rich geometric structure, which can be harnessed to decode hand gestures for a given individual in an unsupervised manner using only the raw signals. Our approach leverages the characteristics of symmetric positive definite (SPD) covariance matrices derived from EMG data.

By operating on these SPD matrices within a Riemannian manifold framework, we respect the natural geometry of the data, enabling efficient and accurate decoding without the need for large-scale training datasets. This method challenges the need for scaling to massive, population-wide models, paving the way for lightweight, individualized solutions. 

Refer to our [paper published in the Journal of Neural Engineering](https://iopscience.iop.org/article/10.1088/1741-2552/ad5107).
We also make the data available from `30` individual subjects. [Download our data](https://www.doi.org/10.17605/OSF.IO/ZCR43).

You can use the scripts provided here to recreate results from the paper.


