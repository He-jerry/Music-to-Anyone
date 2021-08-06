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

##  2.(Pose Estimation Data  --> Photo Realistic Video)

Current Solution:(Which is similar in the EverybodyDanceNow)
Pose data  --> Corresponding Label data  -> Pix2Pix

Semantic Image Synthesis with Spatially-Adaptive Normalization.
https://github.com/NVlabs/SPADE

(Optional. Directly Generate corresponding Video

Few-shot Vid2Vid
https://github.com/NVlabs/few-shot-vid2vid
)
