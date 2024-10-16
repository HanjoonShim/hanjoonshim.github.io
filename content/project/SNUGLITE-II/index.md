---
title: |-
    SNUGLITE-II (2019-2022)
summary: |-
  - 3U CubeSat mission (Launch: Jun 2022)
  - Funded by *Korea Aerospace Research Institute (KARI)* ($330,000 USD)
  - Finalist in the *2019 Korea CubeSat Competition*
date: 2019-09-01
# type: docs
math: false
tags:
  - SNUGLITE-II
image:
  caption: 'SNUGLITE-II CubeSat'
---

<!-------------------------------------------------------------------------------------->

### Seoul National University GNSS Laboratory Satellite (SNUGLITE)-II Project

The SNUGLITE-II CubeSat was selected as a finalist in the "2019 CubeSat Competition" organized by the Korea Aerospace Research Institute, with a total funding of 475 million KRW. The main mission was to develop a 2nd generation of dual-frequency L1/L2C GPS receiver which developed in [SNUGLITE-I CubeSat project](/project/snuglite-i/). 이것은 mm급의 반송파 측정치의 품질 향상과 소형화를 목표로 했다. 이를 활용하여 GPS Radio Occultation (RO)를 통해 3D 지구대기관측을 수행하는것이 임무이다. 기술임무로는 세계최초로 3U 큐브위성에 적용되는 GPS 단독 자세결정 시스템 개발, 그리고 독자적인 반작용휠 기반 자세제어 시스템 개발이다. SNUGLITE-II는 표준 3U 규격의 큐브위성으로, 대한민국 최초 실용위성 발사체인 누리호(KSLV-II)에 탑재된 성능검증위성의 P-POD 속에 탑재되어 2022년 6월 21일 발사되었다. SNUGLITE-II는 약 11일 간의 정상 동작 (시운전모드)를 거쳐 양방향 통신(UHF)를 통해 일부 임무데이터를 수신하였으나, 갑작스런 통신 두절이 발생하여 공식적인 운용을 종료하였다. For more details, refer to the paper on in-orbit results (in Korean) [here](/publication/ij_202001/).

이 프로젝트는 2019년부터 2022년까지 수행되었으며, 저는 SNUGLITE 팀의 팀장으로써 2019 CubeSat Competition의 예비설계 단계부터 발사까지의 모든 과정을 주도하였다. Project Manager을 수행하면서도, attitude control system enginneer의 역할을 수행하였고, flight software 개발, hardware 설계, 그리고 assembly, integration, and test의 모든 일련의 과정을 주도적으로 진행하여 서브시스템을 맡아 기술개발도 진행하여 큐브위성 프로젝트를 통해 위성 개발의 모든 일련 과정을 배웠다.

- **Project Manager**
     - SNUGLITE 팀 리더로써 프로젝트 주도 리더쉽 발휘
     - 시스템설계, 예비설계, 상세설계, 시험준비상태 검토회의, 선적검토회의 등으 모든 마일스톤 회의를 맡음
     - 예산관리, 일정관리, 보고서, 시스템설계 진행
-	**Developed Attitute Control System (ACS) Algorithm**
     - 쿼터니언 기반의 자세제어 시스템 개발
     - LQR-based attitude control system (반작용휠+자기토커)
     - Conducted SILS (Matlab), PILS (Linux-gcc, C), and HILS
-	**Developed Flight Software**
     - Real-time OS 기반 소프트웨어 개발 (FreeRTOS, Gomspace A3200 OBC)
     - round-robin based scheduling (ADCS) program
     - priority-based scheduling (CDH) program
- **Assembly, Integration, and Test (AIT)**
     - 위성 조립의 모든 과정 수행
     - 서브시스템 시험 후 전체 소프트웨어 통합 진행 (센서 캘리브레이션 포함)
     - 발사체 진동시험 및 우주환경시험

</br>

<!-------------------------------------------------------------------------------------->

## **Index**

**[1. SNUGLITE-II CubeSat](#1-snuglite-i-cubesat)**</br>
&nbsp;&nbsp;&nbsp;[1.1. SNUGLITE Team (2019)](#11-snuglite-team-2019) </br>
&nbsp;&nbsp;&nbsp;[1.2. System Configuration](#12-system-configuration) </br>
&nbsp;&nbsp;&nbsp;[1.3. Operation Scenario](#13-operation-scenario) </br>
**[2. Attitude Control System (ADCS)](#2-attitude-control-system-acs)**</br>
&nbsp;&nbsp;&nbsp;[2.1. Overall Block Diagram](#21-software-in-the-loop-simulation-sils) </br>
&nbsp;&nbsp;&nbsp;[2.2. Software-In-the-Loop Simulation (SILS)](#21-software-in-the-loop-simulation-sils) </br>
&nbsp;&nbsp;&nbsp;[2.3. Processor-In-the-Loop Simulation (PILS)](#22-hardware-in-the-loop-simulation-hils) </br>
&nbsp;&nbsp;&nbsp;[2.4. Hardware-In-the-Loop Simulation (HILS)](#22-hardware-in-the-loop-simulation-hils) </br>
**[3. Assembly, Integration, and Test (AIT)](#1-snuglite-i-cubesat)**</br>
&nbsp;&nbsp;&nbsp;[3.1. Hardware Design (PCB)](#21-software-in-the-loop-simulation-sils) </br>
&nbsp;&nbsp;&nbsp;[3.2. Assembly and Integration](#21-software-in-the-loop-simulation-sils) </br>
&nbsp;&nbsp;&nbsp;[3.3. Environment Test](#21-software-in-the-loop-simulation-sils) </br>
**[4. Operation Results](#4-operation-results)**</br>
&nbsp;&nbsp;&nbsp;[4.1. Launch and Initial Operation](#41-launch-and-initial-operation) </br>
&nbsp;&nbsp;&nbsp;[4.2. CubeSat GPS L1/L2C Receiver](#42-cubesat-gps-l1l2c-receiver) </br>
&nbsp;&nbsp;&nbsp;[4.3. ACS](#43-acs) </br>

</br>

<!-------------------------------------------------------------------------------------->

## **1. SNUGLITE-II CubeSat**

<!-------------------------------------------------------------------------------------->

### 1.1. SNUGLITE Team (2019)

**Table. SNUGLITE Team Member and Role (2019)**
<p style="font-size: 0.8em;">
<sup>1</sup> PM: Project Manager, 
<sup>2</sup> SYS: Satellite System,
<sup>3</sup> FSW: Flight Software,
<sup>4</sup> ACS: Attitude Control System,
<sup>5</sup> AIT: Assembly, Integration, and Test
<sup>6</sup> EPS: Electrical Power System,
<sup>7</sup> COM: Comuunication Sytstem,
<sup>8</sup> GND: Ground Station,
<sup>9</sup> STR: Structure System, 
<sup>10</sup> THR: Thermal System,
<sup>11</sup> PAY1: Payload1 (GPS Receiver),
<sup>12</sup> PAY2: Payload2 (GPS Attitude Determination),
<sup>13</sup> PAY3: Payload3 (Camera)
<sup>14</sup> EOP: End of Project
</p>

| Name                                      | Role                                          | Participation Period |
|-------------------------------------------|-----------------------------------------------|-----------|
| [Changdon Kee](/author/changdon-kee/)     | Supervisor                                    | -         |
| [O-Jong Kim](/author/o-jong-kim/)         | Technical Adviser (SNUGLITE-I Team Leader)    | ~'20.8    |
| [Kybeom Kwon](/author/kybeon-kwon/)       | Adviser (Associate Professor)                 | '21.2~EOP |
| [**Hanjoon Shim**](/author/hanjoon-shim/) | **<sup>1</sup>PM, <sup>2</sup>SYS, <sup>3</sup>FSW, <sup>4</sup>ACS, <sup>5</sup>AIT, <sup>11</sup>PAY1** | **~EOP** |
| [Yonghwan Bae](/author/yonghwan-bae)      | <sup>7</sup>COM, <sup>8</sup>GND, <sup>12</sup>PAY2 | ~EOP |
| [Hojoon Jeong](/author/hojoon-jeong)      | <sup>5</sup>AIT, <sup>9</sup>STR, <sup>10</sup>THR  | ~EOP |
| [Jaeuk Park](/author/jaeuk-park)          | <sup>6</sup>EPS, <sup>7</sup>COM, <sup>11</sup>PAY3 | ~EOP |
| [Jikang Lee](/author/jikang-lee)      | <sup>5</sup>AIT, <sup>9</sup>STR, <sup>10</sup>THR  | '20.7~EOP |

<br>

<!-------------------------------------------------------------------------------------->

### 1.2. System Configuration

**Table. System Configuration of the SNUGLITE-I CubeSat** </br>
*DQPSK: differential quadrature phase-shift keying; GMSK: Gaussian minimum shift keying;*
*UHF: ultra-high frequency*
| System     | Description         |
|------------|---------------------|
| Mass       | 3.15 kg             | 
| Dimension  | 100x100x340 mm (3U, undeployed) |
|            | 100x414x340 mm (deployed)       |
| Orbit      | 700 km, SSO         |
| Uplink     | VHF (145.9 MHz), AX.25, GMSK 9.6 kbps (telecommand)  |
| Downink    | UHF (436.49 MHz), AX.25, GMSK 9.6 kbps (telemetry)   |
|            | S-Band (2405 MHz), DQPSK, 1 Mbps (mission data)      |
| Payloads   | SNU L1/L2C GPS Receiver x2 (2nd gen)                 |
|            | CubeSat GPS Attitude Determination Module (World 1st)|
|            | Commercial Camera (Gopro Hero8)                      |
| Actuators  | Reaction wheel x3, Magnetorquer x3                   |
| Reference  | NORAD 52899, [SatNOGS](https://db.satnogs.org/satellite/YFNZ-9504-4902-9033-1722), [Gunter's Space](https://space.skyrocket.de/doc_sdat/snuglite-2.htm) |

<!-------------------------------------------------------------------------------------->

### 1.3. Operation Scenario

![Operation Scenario](fig1.jpg)

**1) Intial Mode (~5days)**
  - Flight software initialization
  - VHF/UHF antenna deployment (60 seconds after ejection)
  - Beacon transmission (every 20 seconds)
  - Detumbling control and convergence check
  - Solar panel deployment (automatic operation or ground station command after angular velocity converged)

**2) Standby mode (1 week ~ end of operation)**
  - Activate the GPS receiver
  - Beacon transmission (every 10 seconds)
  - Waiting for ground command
  - Satellite commissioning and condition check
  - Nadir pointing control

**3) Mission mode (1 month ~ end of operation)**
  - Collect GPS measurements
  - Collect camera image
  - Collect magnetometer, gyroscope, and sun sensor measurements
  - Nadir pointing control

**4) Communication mode (command  switching)**
  - Transmission of mission data (S-Band, UHF)
  - Ground station tracking control

**5) Safe mode (command switching)**
  - Beacon transmission (every 20 seconds)
  - Angular velocity decay control

SNUGLITE-II 큐브위성의 운용에서 수집된 데이터는 초기모드~대기모드에서 수행된 위성의 시운전 및 상태 점검 상황에서 수집된 것이다. 데이터는 시스템 운용 시나리오에 따라, 대기모드에서 단계적으로 지상국 명령을 통해 수집된 위성 상황 발생 기록, 연속 비콘 기록 데이터, 그리고 서울대 지상국과 해외 아마추어 지상국(SatNOGS)를 통해 수집된 비콘 데이터들로 구성된다. 

</br>
</br>

<!-------------------------------------------------------------------------------------->

## **2. Attitude Control System (ACS)**

Related to my Master’s thesis [here](/publication/thesis_master/).

### 2.1. Software-In-the-Loop Simulation (SILS)

#### Algorithm design: Developed based on work inherited from previous graduates
 - SILS based on MATLAB 
 - Attitude determination: Extended Kalman filter (combined with coarse sun sensor, magnetometer, and gyroscope)
 - Attitude control: LQR controller (magnetorquer only)

![Overall Block Diagram](fig2.jpg)


**Video**:
    {{< youtube BvxYcQGIri8 >}}
</br>
</br>

<!-------------------------------------------------------------------------------------->

### 2.2. Hardware-In-the-Loop Simulation (HILS)

#### Helmholtz cage design and assembly
 - 3-axis magnetic cotrol based classical control (PI controller, 50Hz)
 - Codevision based on Atemega 128, C language
</br>

**Video**:
    {{< youtube UxprlKqgqGU >}}

</br>

#### Single-axis HILS verification using Helmholtz cage
 - ADCS implamentation based on C (linux-gcc, FreeRTOS, Gomspace A3200 OBC). For more details, refer to the paper on HILS verification results [here](/publication/ij_202302/).

![HILS Verification](fig3.jpg)

 **Video (50x Fast)**:
    {{< youtube 57kuwjo1NHc >}}

</br>
</br>

<!-------------------------------------------------------------------------------------->

## **3. Assembly, Integration, and Test (AIT)**

### 3.1. Hardware Design (PCB)

Due to a failure in the communication module's uplink, the primary mission of the SNUGLITE-I CubeSat could not be fully verified, resulting in a partial success. However, the GPS receiver development, the core mission of SNUGLITE-I, was successfully completed. The beacon transmits navigation information every 10 seconds, and this data has been used for orbit determination, successfully validating the GPS receiver.

</br>

<!-------------------------------------------------------------------------------------->

### 3.2. Assembly and Integration 

After launch and ejection from P-POD, SNUGLITE-I successfully damped its angular velocity and entered standby mode. The satellite has been performing nadir-pointing control in standby mode. Using attitude data received via the beacon, the ADCS was indirectly evaluated, demonstrating approximately 15° accuracy in attitude determination and control, achieved solely using magnetorquers without reaction wheels.

</br>

<!-------------------------------------------------------------------------------------->

### 3.3. Environment Test

After launch and ejection from P-POD, SNUGLITE-I successfully damped its angular velocity and entered standby mode. The satellite has been performing nadir-pointing control in standby mode. Using attitude data received via the beacon, the ADCS was indirectly evaluated, demonstrating approximately 15° accuracy in attitude determination and control, achieved solely using magnetorquers without reaction wheels.

</br>

<!-------------------------------------------------------------------------------------->

## **4. Operation Results**

### 4.1. Launch and Initial Operation

Due to a failure in the communication module's uplink, the primary mission of the SNUGLITE-I CubeSat could not be fully verified, resulting in a partial success. However, the GPS receiver development, the core mission of SNUGLITE-I, was successfully completed. The beacon transmits navigation information every 10 seconds, and this data has been used for orbit determination, successfully validating the GPS receiver.

</br>

<!-------------------------------------------------------------------------------------->

### 4.2. CubeSat GPS L1/L2C Receiver

Due to a failure in the communication module's uplink, the primary mission of the SNUGLITE-I CubeSat could not be fully verified, resulting in a partial success. However, the GPS receiver development, the core mission of SNUGLITE-I, was successfully completed. The beacon transmits navigation information every 10 seconds, and this data has been used for orbit determination, successfully validating the GPS receiver.

</br>

<!-------------------------------------------------------------------------------------->

### 4.3. ACS

Due to a failure in the communication module's uplink, the primary mission of the SNUGLITE-I CubeSat could not be fully verified, resulting in a partial success. However, the GPS receiver development, the core mission of SNUGLITE-I, was successfully completed. The beacon transmits navigation information every 10 seconds, and this data has been used for orbit determination, successfully validating the GPS receiver.

</br>

 For more details, refer to the paper on in-orbit results [here](/publication/ij_202001/).

</br>


<!-------------------------------------------------------------------------------------->

 # For more information, refer to the related publications below. :)