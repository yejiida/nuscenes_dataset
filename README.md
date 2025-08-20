## 📚 참고 레포지토리

nuScenes 오픈소스에 대한 이해를 높이고자 공부하고, 실행한 결과를 모아둔 레포지토리입니다.

---
[Timetable]

2025.08.19 nuScenes Official **fin.**

2025.08.20 ~ 3D Object Detection [CenterPoint]  

### 1. nuScenes Official
- [nuScenes-devkit (official)](https://github.com/nutonomy/nuscenes-devkit)  
  → nuScenes 공식 개발 키트. 데이터 로딩, 시각화, 평가 코드 포함.

### 2. 3D Object Detection
- [CenterPoint](https://github.com/tianweiy/CenterPoint)  
  → nuScenes에서 SOTA 성능 달성한 3D 객체 탐지 모델. LiDAR 기반.

## License
본 프로젝트(`nuscenes_dataset`의 CenterPoint 레포)는 [CenterPoint 원본 레포](https://github.com/tianweiy/CenterPoint?tab=readme-ov-file)의 코드를 일부 참고 및 활용하였으며, MIT License 하에 배포됩니다.
원본 코드의 저작권은 Tianwei Yin 및 Xingyi Zhou에게 있으며, MIT 라이선스 조건에 따라 사용 및 수정, 배포가 가능합니다.

- [mmdetection3d](https://github.com/open-mmlab/mmdetection3d)  
  → OpenMMLab의 3D 감지 프레임워크. 다양한 모델(SECOND, PointPillars, CenterPoint) 지원.

### 3. Sensor Fusion & Perception
- [BEVFusion](https://github.com/mit-han-lab/bevfusion)  
  → LiDAR + Camera 멀티센서 융합 모델. nuScenes 벤치마크 지원.  
- [OpenPCDet](https://github.com/open-mmlab/OpenPCDet)  
  → Point Cloud 기반 탐지 라이브러리. nuScenes/Waymo 등 지원.

### 4. Tracking & Prediction
- [AB3DMOT](https://github.com/xinshuoweng/AB3DMOT)  
  → nuScenes에서 자주 활용되는 3D 다중 객체 추적(MOT) 코드.  
- [Trajectron++](https://github.com/StanfordASL/Trajectron-plus-plus)  
  → 차량/보행자 궤적 예측 모델. nuScenes 지원.

---

