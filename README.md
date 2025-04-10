# 🔌 Serial Port Interface
<img width="657" alt="image" src="https://github.com/user-attachments/assets/96b19043-1f2c-420f-9c68-a088e5f8a5b0" />

Electron 기반으로 개발된 데스크톱 애플리케이션으로, 시리얼 포트를 통해 외부 장치와 통신할 수 있는 기능을 제공합니다.  
사용자는 COM 포트 설정, 데이터 송신/수신, 실시간 모니터링, 파일 업로드, 텍스트 전송, 콘솔 출력 등의 기능을 손쉽게 사용할 수 있습니다.

---

## 🧑‍💻 프로젝트 개요

- **프로젝트명**: Serial Port Interface
- **기술 스택**: Electron, Node.js, SerialPort, HTML, CSS, JavaScript, Bootstrap
- **문서화 도구**: Doxygen, MkDocs
- **개발 환경**: Visual Studio Code

---

## 🧩 주요 기능

### 📡 포트 설정 및 연결
- COM 포트 선택
- Baudrate, Data bits, Stop bits, Parity, Flow Control 설정
- 포트 열기 및 닫기 (Open/Close 버튼)

### 📝 데이터 송수신
- 텍스트 입력 후 ASCII/Hex 전송
- 텍스트 파일을 선택하여 파일 기반 송신
- 송수신 결과 실시간 콘솔창 출력
- 송수신 일치 여부 검증 (Lookback Test)

### 🧹 콘솔 관리
- 송수신 결과 콘솔창 출력
- Clear 버튼으로 콘솔 내용 초기화
- Lookback Test를 통해 TX/RX 연결된 포트 간 송수신 테스트
- 파일 전송, 텍스트 송신, 콘솔 출력 확인 가능
- 예외 발생 시 에러 메시지 출력

---

## 📚 문서화

### MkDocs
- 프로젝트 설명, 설치 방법, 실행 방법, 배포 방법 등을 정리
- 정적 사이트 형태로 배포 가능

### Doxygen
- 소스코드 자동 문서화
- 주요 클래스, 함수, 모듈 기능 설명

---

