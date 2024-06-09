![header](https://capsule-render.vercel.app/api?type=slice&color=auto&height=200&section=header&text=Hello&rotate=13&fontAlign=70&fontAlignY=27&desc=I'm%20JaeHun&descAlign=75&descAlignY=45&fontSize=65)

<br/>
:point_down: 프로젝트 명

Turtlebot project KOSOMO

<br/>
:point_down: 개발 기간

2020-06-01 ~ 2020-11-15

<br/>
:point_down: 개발인원

:blush: 4명

<br/>
:point_down:  프로젝트 담당

표지판 인식, 판단

<br/>
:point_down:  개발 tool

ROS, Python, OpenCV

<br/>
:point_down: 진행 사유

SW 활동장학생, 교내 학술대회

<br/>
:point_down:  관련 전공

자율주행, 컴퓨터비전

<br/>
:point_down:  프로젝트 소개

주어진 트랙에 주차, 장애물, 좌회전, 우회전 미션을 수행하며 시간 안에 완주하는 프로젝트

<br/>
:point_down:  프로젝트 내용

Parking, Stop, Left, Right의 표지판을 인식, 판단하여 적절한 msg를 master노드한테 보내 적절한 행동을 취하도록 했습니다.<br/>
표지판 인식의 경우 720p Logitech 카메라를 사용하였으며 YOLO 딥러닝 모델을 사용하는 것이 아닌 OpenCV를 최대한 활용한 알고리즘을 설계하도록 하였습니다.<br/>
따라서 HSV색공간 마스크를 사용하여 표지판을 인식하도록 하였고, approxPolyDP함수를 사용하여 표지판의 모양을 판단하고, 내부 픽셀을 분석하여 표지판의 의미를 판단하도록 하였습니다.


![Screenshot from 2020-11-16 02-01-12](https://github.com/jaehun00/Turtlebot_project/assets/66196078/4f6207bb-3c0d-4314-959a-7f9eefa97059)

<br/>
:point_down:  느낀점

컴퓨터비전 기술에 관심을 가지게 된 프로젝트입니다.<br/>
당시 ChatGPT의 개념도 없었을 당시 개념을 배우고, 오류를 해결하는데에 큰 어려움이 있었습니다.<br/>
특히 YOLO 딥러닝 모델을 경량화를 시키고 싶었지만, 지식의 한계를 경험하였습니다.<br/>
하지만 구글링을 통해 쉽게 접할 수 있는 OpenCV의 개념들을 활용하여 최적화된 알고리즘을 설계할 수 있었습니다.<br/>
시간이 된다면 당시 진행하지 못했던 YOLO모델을 사용하여 성능 비교를 해볼 예정입니다.
