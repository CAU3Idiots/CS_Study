# Transport Layer in Internet Protocol

컴퓨터 네트워크의 통신 모델인 OSI7계층을 보면, 
transport layer(통신 계층)은 4번째 단계로, end to end간 연결을 담당한다. 

인터넷 프로토콜의 전송 계층도 비슷한 역할을 한다. 

#### 인터넷 프로토콜에서 Transport Layer(전송계층)은 END to END 호스트간 연결을 해주는 통신 서비스를 제공하는 계층

![전송 계층 비교](https://user-images.githubusercontent.com/42037616/112122353-8808ca00-8c03-11eb-97e8-bb54eb960605.png)
 osi 와 인터넷 프로토콜 모델의 비교


> 전송계층 아래에 있는 계층은 END to END간의 서비스를 해주지 않는다. Next Hop Router나 Switch/Hub간 서비스를 지원한다. 


 
![End to End](https://user-images.githubusercontent.com/42037616/112122469-ab337980-8c03-11eb-98c2-4a44c8b3b98c.png)
End to End 그림

### 전송계층에는 여러 프로토콜이 존재하지만, 대표적인 것이 TCP와 UDP가 있음

 
## TCP/UDP


간단 정리 

| TCP | UDP |
   |--|--|
   | 신뢰성 보장 | 신뢰성 없음 |
   | with connection | connectionless |
   | 3-way-handshake | 사전 연결작업 없음 |
   | 속도 비교적 느림 | 속도 빠름 |
   



## Joke

![아마 처음으로 본 UDP](https://user-images.githubusercontent.com/42037616/112122545-bbe3ef80-8c03-11eb-95a3-ee383950598a.png)

#### 아마 처음으로 본 UDP

![image](https://user-images.githubusercontent.com/42037616/112122613-cf8f5600-8c03-11eb-8949-09a04285e40d.png)

#### 이것을 이해한다면 TCP UDP 마스터...


