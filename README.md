# Video inpainting dataset with a subjective study "VID-SS"

This project is the official implementation of the paper titled "Construction of a Video Inpainting Dataset Based on a Subjective Study", which will be published soon at the MMSP-2023 conference. (Current status = Accepted paper).

With this dataset, we aim to facilitate the evaluation and comparison of existing and future video inpainting methods.

"VID-SS" dataset includes three categories of video inpainting applications. Each of the three folders contains INPUT videos to be inpainted + masks used for inpainting. The categories are:

        -	Object removal       :  25 input videos + 25 masks.
        -	Video hole completion:  20 input videos + 7 masks. 
        -	Post-stabilization   :   7 input videos + 3 masks.

 ________________________________________________________________________________________________
       
This "VID-SS" dataset is accompanied by a subjective study of inpainting quality, based on the results of applying three inpainting algorithms to certain videos from this database. The used algorithms are:

    -	“Temporally coherent completion of dynamic video”  J.-B. Huang, S. B. Kang, N. Ahuja, and J. Kopf,  published in : ACM Transactions on Graphics (TOG), vol. 35, no. 6, pp. 1–11, 2016.
    -	“ Video inpainting of complex scenes “ by A. Newson, A. Almansa, M. Fradet, Y. Gousseau, and P. Pèrez, published in : Siam journal on imaging sciences, vol. 7,no. 4, pp. 1993–2019, 2014.
    -	“Deep flow-guided video inpainting” by R. Xu, X. Li, B. Zhou, and C. C. Loy, in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2019, pp. 3723–3732.


The MOS.xlsx file contains the mean opinion scores computed from the subjective scores collected in the psychophysical subjective test.

Finally, To get the videos of the dataset, please follow this [Google Drive link](https://drive.google.com/drive/folders/1Z_Uxh1Z_RFUTac9zbTaoKPN_8RneY48p?usp=sharing).
