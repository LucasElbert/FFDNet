# FFDNet for SAR image despeckling
Repository for the project of the class 'Remote sensing data'. The speckle phenomenon is a noise like effect inherent to all SAR satellite images, that lowers the visual image quality. We investiage the effectivity of the FFDNet architecture for SAR image despeckling.

![example image](example.png)

Students: Lucas Elbert, Björn Michele
### References:

"Zhang, K., Zuo, W., & Zhang, L. (2018). FFDNet: Toward a fast and flexible solution for CNN-based image denoising" https://arxiv.org/abs/1710.04026.

Code references: The Network blocks and the architecture of the FFDNet are adapted from the original implementation at https://github.com/cszn/KAIR. Additionally, some functions (Speckle injection, PSNR calculation) from Mr. Emanuele Dalsasso were used. All those parts are accordingly marked in the code.

The project was developed and tested mainly using Google Colab to have GPU support.

The model development relied on SAR-images of the Image, Data, Signal Department of Telecom Paris that constitutes a part of their ongoing research, which the reason for which we do not publish the data.
