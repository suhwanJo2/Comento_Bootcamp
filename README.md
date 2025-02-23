# Comento_Bootcamp
The purpose of this project is to design a high-performance digital circuit by identifying user needs, defining key specifications, and optimizing core components such as the CPU and ALU to enhance processing speed, power efficiency, and overall system performance.

1. 과제 선택의 근원적 이유
디지털 회로 설계 과제는 단순한 회로 구현이 아니라, 실제 산업에서 요구하는 니즈(Needs)와 직접적으로 연결됩니다. 과제가 선정된 이유는 다음과 같은 과정으로 설명할 수 있습니다.

  1. 사용자의 요구
  사용자들은 모바일 게임을 원활하게 실행할 수 있는 빠르고, 전력 효율이 높은, 발열이 적은 스마트폰을 원함.
  이러한 요구를 충족하려면 고성능 저전력의 SoC(System on Chip) 가 필요함.
  2. SoC 기획 단계
  삼성전자의 엑시노스, 퀄컴의 스냅드래곤 등 최신 SoC는 다양한 기능을 통합한 칩.
  모바일 게임 최적화를 위해 CPU, GPU, NPU, 모뎀 등의 구성요소가 포함됨.
  과거 GOS(Game Optimization Service) 논란에서 볼 수 있듯이, 성능 최적화는 중요한 이슈.
  3. SoC의 핵심 요소 – CPU
  SoC 내부에는 연산을 담당하는 CPU가 핵심적인 역할을 수행.
  CPU는 ARM Cortex 계열을 기반으로 하며, 명령어 처리를 통해 연산을 수행.
  CPU의 성능은 ALU(Arithmetic Logic Unit) 의 구조와 최적화에 따라 결정됨.

2. 과제 목표 – ALU 설계
과제에서는 CPU 내부에서도 연산을 담당하는 ALU에 집중하여 설계함.

  1. ALU의 역할
  덧셈, 뺄셈, 곱셈, 나눗셈, 논리 연산 수행.
  CPU의 핵심 연산 장치이며, 기본적인 덧셈 회로(Adder)를 포함.
  2. ALU 내부 구조
  기본적으로 Ripple Carry Adder(RCA) 또는 Carry Look-Ahead Adder(CLA) 등의 구조를 가짐.
  연산 속도를 개선하기 위한 다양한 최적화 기법이 적용됨.

3. 다음 단계 – 최적화 기법 조사
ALU 설계에서 중요한 것은 성능 최적화이며, 이를 위해 고려해야 할 주요 요소는 다음과 같음.

  1. 연산 속도(Performance) – 빠른 데이터 처리를 위해 어떤 구조를 사용할 것인지 결정.
  2. 전력 소비(Power Efficiency) – 배터리 사용 시간을 고려하여 저전력 설계를 적용.
  3. 면적(Area Efficiency) – 반도체 칩 크기를 최소화하여 비용 절감.
  4. 
이러한 배경을 바탕으로 과제에서는 ALU 설계를 통해 CPU의 핵심 연산 단위를 직접 구현하고, 최적화 방법을 적용하는 과정을 경험하는 것이 목표임.
