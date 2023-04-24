# MotionSense 데이터 시각화

해당 논문(https://github.com/iantangc/ContrastiveLearningHAR) 을 참고하여 MotionSense 데이터를 시각화하고 

Transform을 적용한 이후의 데이터 또한 시각화하였습니다.

MotionSense 데이터 수집: https://github.com/mmalekzadeh/motion-sense

MotionSense 데이터 시각화 

<img src="/image/MotionSenseRawData.png">

MotionSense 데이터의 X,Y,Z축을 분리 후 데이터 시각화

<img src="/image/MotionSenseRawData.png">

SimCLR 모델 안의 Transformation을 적용하고 MotionSense 데이터의 변화를 시각화했습니다.

Transformation 예시: 

<img src="/image/Transformation.png">

출처:https://github.com/iantangc/ContrastiveLearningHAR

상세한 파일에 대한 설명은 다음과 같습니다.

# MotionSense_Visualization

MotionSense 데이터 시각화 및 Transform 했을 때의 데이터를 시각화하는 코드를 SimCLR 코드에 추가하였습니다.

MotionSense 데이터에 Transformation을 적용한 결과

<img src="/image/MotionSense_Transformation.png">

MotionSense 데이터에 Transformation을 적용하고 X,Y,Z축을 분리한 결과

<img src="/image/MotionSense_Transformation_Split.png">

# axis_angle_to_rotation_matrix_3d_vectorized

transform의 8가지 종류 중 특히 3D rotation에 대한 내용을 세부적으로 분석하였습니다. 

# rotation

rotation code를 random한 각도로 rotation하는 것에서 각도를 입력받는 방식으로 변형하였습니다. 

# Citation


```
@article{tang2020exploring,
  title={Exploring Contrastive Learning in Human Activity Recognition for Healthcare},
  author={Tang, Chi Ian and Perez-Pozuelo, Ignacio and Spathis, Dimitris and Mascolo, Cecilia},
  journal={arXiv preprint arXiv:2011.11542},
  year={2020}
}
```
