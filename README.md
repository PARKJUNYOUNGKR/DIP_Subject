# 딥러닝 얼굴 인식을 이용한 보안 및 개인화 시스템

## 팀 이름 : Happiness with Shim


### 팀 소개

- 팀장 : 김진원 
- 팀원 : 송민성
- 팀원 : 박준영
![image](https://user-images.githubusercontent.com/96164365/205486610-3e3a1484-7327-468b-b491-c7b3c744299b.png)


---

### 작품 개요

인구의 밀집화로 한 집에서 여러명이 사는 쉐어하우스가 늘어 나고 있는 추세입니다. 여러명이 한 집에 사는 만큼 서로의 가정집에서 얼굴 인식을 통해 출입만으로도 개인 방문을 잠굴 수 있고, 냉 난방 시스템, 컴퓨터 전원, 전등 등의 전원 제어를 구현하고 싶었습니다. 선택적으로 원하는 제어를 설정해서 본인에게 불필요한 제어를 원하지 않을 수 있는 시스템이며, 만약 타인이 시스템을 통하지 않고 개인의 방문을 열거나, 가전기기를 작동 시킬 시 경보음이 울리게 되고 이를 통해 보안과 가정집 안전 사고에 대비하여 사고를 줄이고 개인에게 높은 편의성을 제공할 수 있는 시스템을 제공하는 소프트웨어 및 간단한 목업을 제작해보았습니다.

---

### 작품 구성 및 상세 내용

- 딥 러닝을 통한 얼굴 인식
  - Adaboost는 검은색과 흰색 부분 각각의 밝기 값을 픽셀 합을 구하는 방식으로 진행되는데, 적분 이미지(Integral Images)를 사용해 빠르게 구함
  - 검흰의 네모(Haar feature)로 얼굴을 찾아내어 줌얼굴 검출은 OpenCV의 Haar Cascade Classifier알고리즘으로 이미지의 밝기차를 이용해 특징을 찾아냄
  - 특징에 따라 대상을 분류

---

![image](https://user-images.githubusercontent.com/96164365/205486237-5297f0b5-810d-4cb7-b528-be725b48b97d.png)

![image](https://user-images.githubusercontent.com/96164365/205485145-7aaf9b5b-0f89-4102-a3e6-c7d162ac24ef.png)

![FaceImage](https://user-images.githubusercontent.com/96164365/205485126-87172dd6-607d-4cb9-b409-aa91e976bde5.gif)

사진 출처 : https://justadudewhohacks.github.io/face-api.js/docs/index.html#live-demos

---

### 해당 모델의 장점

- 신속한 얼굴 검출


---


### 해당 시스템의 장점 및 기대 효과
- 쉐어하우스 내 개인 설정화를 통한 편리한 삶
  - 냉난방 시스템
  - 컴퓨터 전원
  - 전등
  - 블라인드
![image](https://user-images.githubusercontent.com/96164365/205485907-0b117447-1e67-42c7-ba05-1b017ddef05f.png)



- 얼굴 인식을 통한 보안
  - 비밀번호, 키보다 높은 보안률
  - 침입 경보 및 IOT를 이용한 메시지

### 구현 결과
- 0
- 0
- 0
- 0




