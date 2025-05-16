# RobotControl


  

https://github.com/user-attachments/assets/4bd0e0fb-4497-49aa-8365-082f547f0d36  


주요 기능 요약
YOLOv5 객체 감지: 실시간으로 웹캠 영상을 받아 포트홀 감지.

포트 감지 시 동작 실행: 포트홀이 감지되면 인사를 실행.

포트가 없을 때: 3초 후 으로 기본 자세로 복귀.

포트 선택 GUI: SerialPortSelector로 사용자에게 포트를 선택하도록 함.

멀티스레딩: YOLO 감지를 별도의 QThread로 실행하여 UI가 멈추지 않도록 설계됨
