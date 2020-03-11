# parallel TestAutomation for LINE App
Selenium Grid와 TestNG 프레임워크로 여러 디바이스를 동시에 테스트하는 스크립트 

## About Test
2대의 디바이스에서 두명의 라인유저가 채팅과 통화를 주고받는 시나리오로 구성

### Demo
![chatroom](https://user-images.githubusercontent.com/25470405/76373396-a3e85780-6383-11ea-9269-d100f22d626a.gif)

### Scenario
1. Device A: Device B 에게 텍스트 메시지 송신
2. Device B: 수신메시지 확인(텍스트 내용 & 송신시간)
3. Device A: Device B 에게 음성통화 발신
4. Device B: 통화 수락 후 5초간 대기(통화상태)
4. Device A: 통화 종료

### Test Devices
|Name|Device|OS version|
|------|------|------|
|Device A|Pixel 4|10.0|
|Device B|Galaxy S10|9.0|



## Test Result
* 테스트 결과 리포트

![2020-03-11_10h25_15](https://user-images.githubusercontent.com/25470405/76374294-1f4b0880-6386-11ea-8d1b-3524916f4860.gif)



## Description



## Directory Structure
![2020-03-11_10h29_32](https://user-images.githubusercontent.com/25470405/76376558-e877f100-638b-11ea-84c9-280291c78fc5.png)

## Usage
1. 병렬테스트환경 셋업
링크참조

2. TestNG

## References
* https://appiumpro.com/editions/5
* https://blog.naver.com/wisestone2007/221321329618
