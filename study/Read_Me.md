
# Read Me

### 특정 물체 트래킹 시스템 구현
```
개발 목표: 사람, 사물을 자동으로 따라오는 트래킹 구현

응용 범위: 여행용 캐리어, 의료용 링거 폴대, 장난감

제작 기반: 아두이노 사용, pixy2 camera 사용

```
<img src="https://user-images.githubusercontent.com/73927761/123641082-d2ca5b80-d85c-11eb-8cbf-c8dd95208946.png" width="300" height="300"><img src="https://user-images.githubusercontent.com/73927761/123641624-69971800-d85d-11eb-8435-72df2ec2feb8.png" width="300" height="300"><img src="https://user-images.githubusercontent.com/73927761/123641806-9e0ad400-d85d-11eb-8069-bf48dceccc3a.png" width="300" height="300">


# 제작 기반: 아두이노 사용, pixy2 camera 사용

<img src="https://user-images.githubusercontent.com/73927761/123642309-1a9db280-d85e-11eb-9915-d12a15319396.png" width="300" height="250"><img src="https://user-images.githubusercontent.com/73927761/123642314-1d000c80-d85e-11eb-8452-67065bc0b56b.png" width="300" height="250">



# 물체나 특정 대상 트레킹(특정 물체나 대상을 따라오는 시스템을 아두이노로 구현)
```
-Pixy2 카메라를 이용한 색 감지

-Pixy2 카메라에 등록시킨 색을 인식하여 카메라가 보고있는 색의 데이터  x, y좌표 값을 계산한다.

-X, y 좌표값을 이용해 서보모터를 사용하여 픽시카메라를 물체에 고정시킨다.(서보모터 2개로 pixy의 상하좌우 방향 조절 가능)

-서보모터의 각도값을 이용해 모터를 제어하여 rc카를 카메라가 보고있는 방향으로 움직인다.

```
![image](https://user-images.githubusercontent.com/73927761/123642870-bd563100-d85e-11eb-944d-47388f0a32d8.png)



# 부품과 활용 
```
-PixyCam   : 대상이나 물체 색을 인식하는 카메라

-초음파 센서  : 물체 충돌 방지를 위한 부품으로 활용 (초음파로 대상과의 거리 측정)

-esp32Cam  : Wifi 를 통해 실시간 스트리밍과 스트리밍 녹화기능을 가지고 있는 cam

-아두이노RC카 : 트래킹을 구현하기위해 사용. (아두이노 우노보드와 모터실드사용)

```
![image](https://user-images.githubusercontent.com/73927761/123642978-df4fb380-d85e-11eb-88ae-8c5cfcb1e080.png)

![image](https://user-images.githubusercontent.com/73927761/123642991-e37bd100-d85e-11eb-9672-19c450b7898f.png)


# 아두이노 esp32cam 으로 실시간 스트리밍
```
-와이파이 연결후 해당 IP주소에 접속하여  실시간 스트리밍 가능.

```
![image](https://user-images.githubusercontent.com/73927761/123643130-0a3a0780-d85f-11eb-8ef4-d7573bbe3a23.png)

# 완성본 이미지 와 간단설명
```
1. Pixy카메라를 이용한 물체 트래킹

2. pixy카메라가 바라보는 방향을 esp32cam 으로 실시간 스트리밍 가능

3. 양쪽에 초음파 센서 2개로 RC카 장애물 회피나 충돌 방지 가능

4. 바퀴 위 양쪽 LED로 주위 밝기에 따라 밝기 자동 조절  

```
![image](https://user-images.githubusercontent.com/73927761/123643439-55ecb100-d85f-11eb-8610-4948242e8371.png)

<!-- 
### 잘했던 점
```
```

### 어려웠거나 못했던점과 해결부분
```

``` -->

### 시연 영상 링크
```
[클릭시 시연영상으로 이동](https://youtube/wEXscKJdYp0)

[유튜브](https://youtu.be/wEXscKJdYp0)
//https://youtu.be/wEXscKJdYp0
```

