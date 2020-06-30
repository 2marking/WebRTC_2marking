# WebRTC_2marking

1. WebRTC(Web Real-Time Communication)
  - 웹 어플리케이션(Android, IOS) 및 사이트들이 별도의 소프트웨어 없이 음성, 영상 미디어 혹은 텍스트, 파일 같은 데이터를 브라우저끼리 주고 받을 수 있게 만든 기술
  - WebRTC로 구성된 프로그램들은 별도의 플러그인이나 소프트웨어 없이 p2p 화상회의 및 데이터 공유를 함.
  - 서로 상호작용하는 API와 프로토콜로 구성되어 있음.
  - 결론적으로는 별도의 플러그인 없이 음성, 화상, 데이터 전송이 가능한 기술로 최근에는 Android, IOS도 지원.
  
2. 상호 운용성
  - WebRTC의 구현이 계속 진화하고 있으며 브라우저마다 코덱 및 기능에 대한 지원 수준이 다름.
  - 더 자세한 내용은 https://developer.mozilla.org/ko/docs/Web/API/WebRTC_API/adapter.js
  
3. WebRTC 개념 
  - 피어들 간의 커넥션이 만들어지는데 어떤 드라이버나 플러그인도 필요하지 않음.
  - 두 피어 간의 커넥션은 RTCPeerConnection 인터페이스를 통해 이루어짐. 

4. WebRTC 인터페이스
  - 연결 설정 및 관리
    이 인터페이스들을 사용하여 WebRTC 연결을 설정할 수 있고, 연결을 맺을 수 있으며 WebRTC 연결을 관리
    - RTCPeerConnection
      - 로컬 컴퓨터와 원격 피어 간의 WebRTC 연결을 나타낸다. 두 피어 간의 효율적인 데이터 스트리밍을 처리하는데 사용된다.
    - RTCDataChannel
      - 연결된 두 피어간의 양방향 데이터 채널을 나타낸다.
    - RTCDataChannelEvent
      - RTCDataChannel을 RTCPeerConnection에 연결하는 동안 발생하는 이벤트를 나타낸다. 이 인터페이스와 함께 전송되는 유일한 이벤트는 datachannel이다.
    - MediaStream
      - 카메라/마이크 등 Data Stream 접근
    - RTCSessionDescription
      - Session에 대한 offer/answer
    - RTCStateReport
      - connection이나 connection의 개별 트랙에 대한 정보를 제공
      - RTCPeerConnection.getStats()를 통해 정보를 얻을 수 있음
    - RTCIceCandidate
      - RTCPeerConnection을 설정하기 위한 인터넷 연결 설정 서버를 나타냄
    - RTCIceTransport
    - RTCPeerConnectionIceEvent
    - RTCRtpSender
    - RTCRtpReceiver
    - RTCTrackEvent

5. 샘플 코드 예시

6. Demo Project Description(작성 중 - 추가예정)
  6-1. Evirironment
  6-2. Featrues
  6-3. Architecture
  6-4. Usage
  6-5. PreView
  6-6. UI
  6-7. Apk Download 경로
  
* 기타 내용들은 필요한 부분을 우선적으로 다룰 예정

https://developer.mozilla.org/ko/docs/Web/API/WebRTC_API
