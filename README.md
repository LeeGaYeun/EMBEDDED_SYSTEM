# EMBEDDED_SYSTEM

## 1. 프로젝트

- 프로젝트 명 : EMBEDDED SYSTEM
- 시나리오
    - 사용자의 입력을 받아 UART 통신으로 STM32F411RE 를 제어한다.
    - 1번은 LED의 불빛의 이동 및 제어
    - 2번은 PWM을 사용하여 무드 램프 제어
    - 3번은 PWM을 사용하여 피아노 소리 만들기
    - 4번은 조도 센서를 사용하여 가로등 제어
    - 5번은 온습도 센서를 사용하여 현재 온습도 측정
    - 6번은 초음파 센서를 사용하여 물체와의 거리를 측정

## 2. 작업순서

[간트차트](https://www.notion.so/71d7fa2e5d9142a1ad09d9f46a654a54?pvs=21)

[칸반보드](https://www.notion.so/a384b3ba1f08410594e076cec00b4e84?pvs=21)

## 3. 다이어그램

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/de458be3-9f2d-41fc-b9d0-2f0b628fafc9/822ead24-b672-46b7-bc4a-83b20cbc5e7c/Untitled.png)

## 4. 소스코드 분석

## 5. 프로젝트 성과 결과

- UART 통신으로 STM32 제어
- HAL 라이브러리 사용하여 SMT32 제어
- 조도 센서, 온습도 센서, 초음파 센서를 사용하여 센서 활용 방법 이해
- PWM 제어
- 타이머 기능 사용

## 6. 참고

[um1724-stm32-nucleo64-boards-mb1136-stmicroelectronics.pdf](https://prod-files-secure.s3.us-west-2.amazonaws.com/de458be3-9f2d-41fc-b9d0-2f0b628fafc9/b41bb7f3-907a-49a7-b656-a9ae137e862c/um1724-stm32-nucleo64-boards-mb1136-stmicroelectronics.pdf)

[STM32F411RE.pdf](https://prod-files-secure.s3.us-west-2.amazonaws.com/de458be3-9f2d-41fc-b9d0-2f0b628fafc9/55ec39e8-6fa3-4d98-af85-fef33d5468d9/STM32F411RE.pdf)

[STM32F4_ProgrammingManual.pdf](https://prod-files-secure.s3.us-west-2.amazonaws.com/de458be3-9f2d-41fc-b9d0-2f0b628fafc9/b028b99f-7d74-43ca-bbe9-1fa097ab8900/STM32F4_ProgrammingManual.pdf)

https://l0ve11.tistory.com/23

[https://vuzwa.tistory.com/entry/STM32-10-HTS221-온습도-센서-제어하기B-L475E-IOT01A1-개발보드-활용하기](https://vuzwa.tistory.com/entry/STM32-10-HTS221-%EC%98%A8%EC%8A%B5%EB%8F%84-%EC%84%BC%EC%84%9C-%EC%A0%9C%EC%96%B4%ED%95%98%EA%B8%B0B-L475E-IOT01A1-%EA%B0%9C%EB%B0%9C%EB%B3%B4%EB%93%9C-%ED%99%9C%EC%9A%A9%ED%95%98%EA%B8%B0)

https://m.blog.naver.com/hwidong0102/221747102724

https://thewanderer.tistory.com/57

https://spokehouse.tistory.com/94

https://eteo.tistory.com/155

## 7. 시연
