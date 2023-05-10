# LikeMonday
# 졸과 착수 보고서 
## 졸업과제 진행
### 과제 배경과 방향성
최근에 나온 아이오닉 자동차가 백미러 대신 카메라를 달고 있다는 사실에서 영감을 얻어 전방 유리도 카메라와 디스플레이로 대체해서 운전자의 시야 확보에 도움을 줄 수 있으면 좋겠다고 생각했다. 굳이 유리 대신 비싼 디스플레이를 사용하는가 라는 의문이 들 수 있지만 생각보다 많은 장점이 있다. 예를 들어 어두운 밤길과 반대편에서 쌍라이트를 킨 채로 다가오는 차량은 운전자에게 있어서 매우 큰 위협요소이다. 하지만 디스플레이를 통해서 본다면 이미지 처리 모델을 이용해서 이러한 위협 요소들을 최대한 배재하므로서 운전자에게 더 나은 환경을 제공할 수 있다.
또한 차선 인식기능을 넣어서 따라서 우리는 빛 번짐과 밝기를 개선해주는 ai 모델을 적용한 차량 시스템을 개발하기로 했다. 
### 요구 조건 분석
케라스 예제에 몇가지 방법과 모델이 존재한다.
#### 학습 데이터
#### 빛 번짐 모델
#### 밝기 개선 모델 
#### 어플레케이션
### 진행 방안 및 시스템 설계
.
.

### 예상 문제점
보통 인간이 인식할 수 있는 최대 frame이 초당 60 프레임 이라고 한다. 운전자가 부드러운 영상을 보기 위해서는 적어도 60 프레임을 사용해야 한다. 우리는 ai 모델을 적용할 것이고 60 프레임이라는 요구 조건을 만족시킬 만한 inference time이 필요하다. 적어도 이미지 한 장당 inference time이 20ms 이 되어야 한다.
또한 스마트폰의 컴퓨팅 능력이 받쳐줘야 한다. 카메라가 찍고 있는 영상을 view로 rendering해주는 동시에 ai모델의 inferece까지 처리해줘야 한다. 스마트폰 로컬에서 처리하기 어렵다면 클라우드를 사용해야 하는데 이 때는 동영상 스트리밍이 원할하게 가능할 정도의 네트워크 속도와 서버가 필요하다.
### 역할 분담 및 개발 일정
.
.
.
