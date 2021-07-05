## [Cross-View Cross-Scene Multi-View Crowd Counting (CVCS), CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Cross-View_Cross-Scene_Multi-View_Crowd_Counting_CVPR_2021_paper.pdf)

![alt text](http://visal.cs.cityu.edu.hk/wp/wp-content/uploads/pipeline-1.jpg)

Multi-view crowd counting has been previously proposed to utilize multi-cameras to extend the field-of-view of a single camera, capturing more people in the scene, and improve counting performance for occluded people or those in low resolution. However, the current multi-view paradigm trains and tests on the same single scene and camera-views, which limits its practical application. In this paper, we propose a cross-view cross-scene (CVCS) multi-view crowd counting paradigm, where the training and testing occur on different scenes with arbitrary camera layouts. To dynamically handle the challenge of optimal view fusion under scene and camera layout change and non-correspondence noise due to camera calibration errors or erroneous features, we propose a CVCS model that attentively selects and fuses multiple views together using camera layout geometry, and a noise view regularization method to train the model to handle non-correspondence errors. We also generate a large synthetic multi-camera crowd counting dataset with a large number of scenes and camera views to capture many possible variations, which avoids the difficulty of collecting and annotating such a large real dataset. We then test our trained CVCS model on real multi-view counting datasets, by using unsupervised domain transfer. The proposed CVCS model trained on synthetic data outperforms the same model trained only on real data, and achieves promising performance compared to fully supervised methods that train and test on the same single scene

![alt text](http://visal.cs.cityu.edu.hk/wp/wp-content/uploads/model.jpg)

### [Results](http://visal.cs.cityu.edu.hk/demos/cvcs_results/):

   [![Watch the video](https://img.youtube.com/vi/9dDvp92zNfY/hqdefault.jpg)](https://youtu.be/9dDvp92zNfY)

### Dataset Download:

- [Google Drive](https://drive.google.com/drive/folders/1fcUM4sXOdW-TJa2exLrwhxjvZ6lTbh-4?usp=sharing)
   
### Cite paper:
    @inproceedings{zhang2021cvcs,
    title={Cross-View Cross-Scene Multi-View Crowd Counting},
    author={Zhang, Qi, Lin, Wei, and Chan, Antoni B},
    booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
    pages={557-567},
    year={2021}
    }

