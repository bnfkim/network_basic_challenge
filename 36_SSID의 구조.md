# 36. SSID의 구조

### 1. SSID란 ?
- 무선 액세스 포인트와 무선 클라이언트를 연결하려면 혼선을 피하기 위해 SSID를 사용한다.
- SSID는 액세스 포인트의 고유 이름을 사용한다.
- 네트워크 이름, 인증, 암호화, 암호화 키를 설정해야 한다.
- 무선 액세스 포인트와 무선 클라이언트의 연결 과정
  - 무선 공유기   ---------비컨 전송-------->  컴퓨터
  - 무선 공유기   <----같은 SSID 인지 문의----  컴퓨터
  - 무선 공유기   ----같은 SSID 라고 응답---->  컴퓨터
  - 무선 공유기   <---------- 인증 ---------->  컴퓨터
  - 무선 공유기   <--------접속 요구--------   컴퓨터
  - 무선 공유기   --------승인 응답-------->   컴퓨터
- 비컨
  - 무선 액세스 포인트가 자기를 알리는 신호이다. 
  - 네트워크에 있는 모든 기기에 주기적으로 전송한다. 
  - 무선 클라이언트는 이 신호를 잡아서 연결한다.

### 2. 채널이란?
- 무선 액세스 포인트를 여러 대 설치하기 위해 사용한다.
- 무선 랜은 여러 기기를 동시에 연결할 수 있도록 분할하는데, 그 주파수 대역을 채널이라고 한다. 
- 여러 무선 공유기가 있다 해도 같은 채널로 설정하면 같은 주파수 대역을 사용한다. 
- 무선 공유기의 전파가 겹치게 되면 전파 간섭이 생기고 통신 속도가 느려진다.
- 서로 다른 채널이더라도 규격에 따라 일부 같은 주파수를 사용할 수 있다.
- 무선 액세스 포인트는 기본적으로 자동으로 최적의 채널을 찾아준다.
