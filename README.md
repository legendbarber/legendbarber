---

## Projects

| 프로젝트명 | 내용 요약 | 기술스택 | 세부내용 |
| --- | --- | --- | --- |
| **Autoware·CARLA 연동 자율주행 스택 학습 (인턴)** | Autoware 기반 자율주행 모듈을 CARLA 서버와 연동하며 스택 구조와 데이터 흐름 분석·실습 | `Autoware` `CARLA` `ROS2` `Ubuntu` `Python/C++` `rviz2` | - 인턴십에서 **Autoware 기반 자율주행 모듈**을 CARLA 서버와 연동하며 시뮬레이션 환경에서 스택 동작 구조 학습<br>- 센서/인지/판단/제어 모듈 간 **ROS2 토픽·데이터 흐름**을 추적하며 자율주행 파이프라인 이해도 향상<br>- 시나리오 주행 및 모듈 연동 테스트를 통해 **자율주행 스택 통합 관점**의 실무 환경 경험 |
| **CARLA·ROS2 자율주행 시뮬레이션 스택** | CARLA에서 ROS2 기반으로 인지→판단→제어까지 연결해 시나리오 주행 | `CARLA` `ROS2(Foxy/Humble)` `Ubuntu` `Python/C++` `OpenCV` `rviz2` | - CARLA 환경에서 ROS2 기반 **인지→판단→제어** 파이프라인을 통합해 주행 기능 구현<br>- 객체 인식/추적 + 장애물 회피 경로 생성 + 추종 제어까지 연결해 시나리오 주행 수행 |
| **YOLO 실시간 객체인식 최적화** | YOLO 학습·평가 파이프라인 구축 후 TensorRT 등으로 추론 성능 개선, 실시간 시각화까지 구성 | `Python` `PyTorch` `YOLOv11` `CUDA` `ONNX` `TensorRT` `OpenCV` | - YOLO 기반 객체탐지 학습 파이프라인 구성 및 성능 비교/평가<br>- TensorRT 변환 등으로 **추론 속도** 개선, 후처리/시각화 포함 실시간 탐지 흐름 완성 |
| **BMS 상태추정 알고리즘** | 3RC 등가회로 모델 + EKF로 SOC 추정, 실측 기반 파라미터 추정과 SOC별 LUT로 전압 오차 감소 | `Python` `MATLAB` `Simulink` | - 3RC 등가회로 모델과 EKF로 **SOC 상태추정** 구현<br>- 실측 데이터 기반 파라미터 추정 + SOC별 LUT로 전압 추정 오차 감소 |
| **민원 도우미 AI 에이전트 (해커톤)** | n8n 워크플로우로 민원 글 자동 분류 및 답변 초안 생성 | `n8n` `Upstage LLM` `Webhook/REST` | - n8n 워크플로우로 **민원 자동 분류·답변 보조 에이전트** 설계/구현<br>- 제목·본문 분석으로 담당 부서 추천 + **답변 초안** 자동 생성으로 처리 시간 단축 |
| **Verilog 기반 미니 CPU/컴퓨터 시스템 구현** | Verilog로 32-bit ALU + 소형 메모리 + 제어로직 구성, 기본 ISA 흐름 검증 | `Verilog HDL` `Quartus Prime` `ModelSim` | - 32bit ALU + 8Byte 메모리 + 컨트롤 로직 설계/구현<br>- AND/SUB/LOAD/STORE/BEQ/BNE 지원, LOAD/STORE/분기 검증으로 ISA 흐름(연산→메모리→분기) 완성 |
| **UART 드라이버** | BeagleBone에서 하드웨어 UART 없이 GPIO 토글로 UART 송수신 구현 | `C` `Linux(Ubuntu)` | - **하드웨어 UART 없이** 소프트웨어만으로 2핀 UART 통신 구현<br>- GPIO 토글/타이밍 제어로 프레이밍 구성, 송수신 루틴 분리로 드라이버 형태 정리 |
| **감정 인식 기반 스마트 디퓨저** | 라즈베리파이에서 얼굴 감정(7종) 분류 후 향을 자동 발향, 외부 장치 연동까지 통합 | `Python` `OpenCV` `TensorFlow` | - Raspberry Pi 5에서 얼굴 이미지를 **7가지 감정 분류** 후 향 자동 발향 구현<br>- 모터/디스플레이/카메라 연동으로 **인식→판단→구동** 통합 동작 완성 |
| **FPGA 기반 SoC IP 설계** | 버튼 입력을 이벤트로 바꾸는 HW IP를 설계해 SoC에 통합, SW에서 받아 게임 로직 데모 | `Vivado` `Verilog` `Zynq/SoC` | - 버튼 입력을 이벤트로 변환하는 **HW IP** 설계 후 SoC 통합<br>- SW로 이벤트 전달받아 **간단한 게임 로직** 구현, HW–SW 연동 데모 완성 |
