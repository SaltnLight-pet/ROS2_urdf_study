# ROS2_urdf_study

## 개요
- URDF(Unified Robot Description Format, 로봇 기술용 통일 포맷)란?
-   로봇을 구현하는데 사용되며, Navigation, Manipulation, Remote Control 등이 가능하며, 기본적으로 XML문법을 통해 만들어짐.
- 위의 코드는 URDF에 대해 공부하며 원통형 구조물 두개를 연결하여 pan, tilt가 가능하도록 구현한 코드입니다.


#### [환경]
|목록|VERSION|
|:--|:--:|
|Ubuntu|Ubuntu 20.04.6 LTS (Focal Fossa)| 
|ROS|Galactic Geochelone| 

#### 실행코드
```python
# urdf_study 워크스페이스로 이동
cd ~/urdf_study  
```
```python
# local_setup.bash 설정
source ./install.local_setup.bash  
```
```python
# 코드 실행
ros2 launch urdf_study simple_display.launch.py  
```

#### 실행 결과
<p align="center">
<img src="https://github.com/SaltnLight-pet/ROS2_urdf_study/assets/142612336/247e8931-54a8-4564-8771-674d3e05e843">
</p>
