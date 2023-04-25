# footballprospect

## IT응용공학과 인공지능응용 수업 과제
![image](https://user-images.githubusercontent.com/85356161/234281035-1f5a73f0-0eef-48bc-b619-908f4d717a85.png)

굉장히 프리한 과제
## About
AI해커톤 플랫폼 DACON의 축구선수 유망 여부 예측 경진대회 데이터를 이용, AI분류 모델 개발

## Preprocessing

현재 데이터에 수치값이 아닌 문자열 데이터가 있는데, 선수ID, 포지션, 주로 사용하는 발, 공격비율, 수비비율이다. 
선수ID는 삭제, 
포지션 또한 전체 능력치로 유망 여부를 판단할 것이므로 삭제, 
주발 또한 유망 여부에 근거되지 않으므로 삭제,
공격 비율과 수비 비율은 value값을 보았을 때 Medium, high, low 3개의 값이 분포되어 있어 순서대로 2,1,0값으로 치환하였다.
  
![image](https://user-images.githubusercontent.com/85356161/234281595-d1a472b2-421e-45bf-bc63-43163b9a6208.png)![image](https://user-images.githubusercontent.com/85356161/234281612-9c39781d-e6e3-4633-96f6-b114b410a0e7.png)

## ML
![image](https://user-images.githubusercontent.com/85356161/234281854-1bcff695-1b6a-45ff-ac85-cda879ed6882.png)

### feature importance
![image](https://user-images.githubusercontent.com/85356161/234281880-c46d4ce7-566e-43b1-9256-70474d912745.png)

### RandomForest
![image](https://user-images.githubusercontent.com/85356161/234281943-aa0158a0-4ec6-4830-bdc2-275327784d03.png)

### SVM
![image](https://user-images.githubusercontent.com/85356161/234282069-985f933b-95bb-472d-b695-3d32d6941c87.png)

### LogisticRegrssion
![image](https://user-images.githubusercontent.com/85356161/234282156-cc97f4a2-904a-4076-8722-0b9c1177ed9c.png)
