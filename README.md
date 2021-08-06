# Music-to-Anyone

Transfer the Video with Music(The Music and Video is recommended to be aligned, but it is also avaliable when it is splited.) to anyone(Such as other pop-stars)

#  Transfer Line:
Music+Video --> Pose Estimation Data --> Photo Realistic Video for anyone


#  Main Project:

##  1.(Music+Video --> Pose Estimation Data)
When the Music is corresponding to the Video   --> Only to Analyse the Pose of Video

https://github.com/MVIG-SJTU/AlphaPose

When the Music is splited  -->  First use the music to generate pose for the pretrained target

Self-supervised Dance Video Synthesis Conditioned on Music
https://github.com/xrenaa/Music-Dance-Video-Synthesis

Dancing to Music
https://github.com/NVlabs/Dancing2Music

These two project does not apply the data generation method, so we should use the provided data or generate by ourselves.

##  2.(Pose Estimation Data  --> Photo Realistic Video)

Current Solution:(Which is similar in the EverybodyDanceNow)
Pose data  --> Corresponding Label data  -> Pix2Pix

Semantic Image Synthesis with Spatially-Adaptive Normalization.
https://github.com/NVlabs/SPADE

(Optional. Directly Generate corresponding Video

Few-shot Vid2Vid
https://github.com/NVlabs/few-shot-vid2vid
)



### Citation

```
@InProceedings{ren_mm_dance,
author = {Xuanchi Ren, Haoran Li, Zijian Huang, Qifeng Chen},
title = {Self-supervised Dance Video Synthesis Conditioned on Music},
booktitle = {ACM MM},
year = {2020}
}
```

@inproceedings{lee2019dancing2music,
  title={Dancing to Music},
  author={Lee, Hsin-Ying and Yang, Xiaodong and Liu, Ming-Yu and Wang, Ting-Chun and Lu, Yu-Ding and Yang, Ming-Hsuan and Kautz, Jan},
  booktitle={NeurIPS},
  year={2019}
}

@inproceedings{fang2017rmpe,
  title={{RMPE}: Regional Multi-person Pose Estimation},
  author={Fang, Hao-Shu and Xie, Shuqin and Tai, Yu-Wing and Lu, Cewu},
  booktitle={ICCV},
  year={2017}
}

@article{li2018crowdpose,
  title={CrowdPose: Efficient Crowded Scenes Pose Estimation and A New Benchmark},
  author={Li, Jiefeng and Wang, Can and Zhu, Hao and Mao, Yihuan and Fang, Hao-Shu and Lu, Cewu},
  journal={arXiv preprint arXiv:1812.00324},
  year={2018}
}

@inproceedings{xiu2018poseflow,
  author = {Xiu, Yuliang and Li, Jiefeng and Wang, Haoyu and Fang, Yinghong and Lu, Cewu},
  title = {{Pose Flow}: Efficient Online Pose Tracking},
  booktitle={BMVC},
  year = {2018}
}

@inproceedings{park2019SPADE,
  title={Semantic Image Synthesis with Spatially-Adaptive Normalization},
  author={Park, Taesung and Liu, Ming-Yu and Wang, Ting-Chun and Zhu, Jun-Yan},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2019}
}

@inproceedings{wang2019fewshotvid2vid,
   author    = {Ting-Chun Wang and Ming-Yu Liu and Andrew Tao 
                and Guilin Liu and Jan Kautz and Bryan Catanzaro},
   title     = {Few-shot Video-to-Video Synthesis},
   booktitle = {Conference on Neural Information Processing Systems (NeurIPS)},   
   year      = {2019},
}
