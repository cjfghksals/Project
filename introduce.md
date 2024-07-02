### ✿ 프로젝트 소개

- 본 프로젝트는 Arduino를 이용해 제작한 프로젝트 입니다.
- CT센서로 전류를 측정하고, MCU로 전송합니다.
- 전류 측정 값을 A/D변환 합니다.
- 전력 사용량을 OLED를 통해 사용자에게 제공합니다.
- 전력 사용량을 블루투스 모듈을 통해 스마트폰으로 전송합니다.
- 스마트폰 앱에 전력 사용량을 표시합니다.
- 주 전원이 끊겨도 시간 및 전력 사용량 데이터를 유지할 수 있게 RTC와 보조 전원을 사용하였다.

---

### ✿ 하드웨어 설계 및 제작

- 하드웨어 설계
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/c41d64cf-7bed-4905-acfe-530221edf561/Untitled.png)
    

- 하드웨어 제작
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/fc33fb7f-91c4-48a0-8ac3-bfb5e6d581c4/Untitled.png)
    
    - 외관 설계
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/492faea2-548e-463d-a2ba-15696811abae/Untitled.png)
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/7a2ec15d-e177-4dff-b861-d2bb8be70377/Untitled.png)
        
    
    - 외관 제작
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/7aec764a-5801-4a0a-ac0c-39fae4b099da/Untitled.png)
        
- 하드웨어 완성

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/41dc9fa9-8723-4d56-8bfe-0917f7ac4e79/Untitled.png)

- 기기 설치
    1. 가정용 분전반을 개방한다.
    2. 배선용 차단기와 누전차단기의 전류를 모두 차단한다.
    3. 누전 차단기의 부하측에 기기의 전원공급 전선을 연결한다.
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/00e30f83-1c92-4799-ac46-470bb963db02/Untitled.png)
        
    4. 개방형 클램프를 배선용 차단기의 입출력 도선 중 하나에 고정한다.
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/3bcf8f60-063a-4b5a-9c41-6b087780053a/Untitled.png)
        
    5. 도선을 공간에 맞게 정리하고, 가정용 분전반을 닫는다.
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/66f43372-f8b5-42f1-a1c0-a406da42617a/Untitled.png)
        

- 동작
    - 첫 번째 화면
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/bf72e758-4107-48db-879b-6b760ba68002/Untitled.png)
        
        - 현재 전류, 전력, 총 전력 사용량, 이번달 전기 요금을 확인할 수 있다.
    - 두 번째 화면
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/40070850-391e-42ad-b0ee-2f0fed5aee34/Untitled.png)
        
        - 지난달의 총 전력 사용량, 지난달 전기 요금을 확인 할 수 있다.
    - 세 번째 화면
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/d5a32f82-9577-4355-acfd-400e684cecff/Untitled.png)
        
        - 현재 날짜, 시각, 온도를 확인할 수 있다.

- 스마트폰 앱 화면
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/d7edbbe7-74b4-4b8e-a6a1-fe5e396eec75/Untitled.png)
    
    - 기기에서 측정된 값이 블루투스 통신을 통해 안드로이드 앱에 출력되는 것을 확인 할 수 있다.

---

### ✿ 결과

- 실시간 전력 사용량과, 이번달 총 전력 사용량과 전기요금이 출력되는 것을 확인할 수 있다.
- 지난 달 전력 사용량과 전기 요금을 메모리에 저장한다.
- 주전원이 끊겼다 연결되어도 데이터가 유지되는 것을 확인할 수 있다.

---

### ✿ 사용 툴 및 스킬

**언어 및 기술**

<aside>
<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/32dd3980-54cb-440f-aed0-788a876ed4c9/URZD-xUaBUeelq-n-FqpO7ZBIErzuWhrn3oyBG8LXthkmM1O82YLo8uMbB-MK9Ydn2d9P9BVgtmVQfVgETf1gMxyb_HMG7j0gEApjrdbmlRrMLVDB21MOlWPCapyOktAtjuov6BgWKLoS9-cPC8iZw.svg" alt="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/32dd3980-54cb-440f-aed0-788a876ed4c9/URZD-xUaBUeelq-n-FqpO7ZBIErzuWhrn3oyBG8LXthkmM1O82YLo8uMbB-MK9Ydn2d9P9BVgtmVQfVgETf1gMxyb_HMG7j0gEApjrdbmlRrMLVDB21MOlWPCapyOktAtjuov6BgWKLoS9-cPC8iZw.svg" width="40px" /> **C
▰▰▰▰▰▰▰▰▱▱ `Lv.8`**

</aside>

<aside>
<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/5258a7d7-6104-4519-9ae2-85ec3f8b9037/3OqqtdlxerBqgGfkk_lOyw1xQGtNUn0IUzSp1JOm-KMjjKIVLcIxYrbivRxnkOZYfZJ-DwCOAJfKCvKeCl5X0V9LHemQGH4wb1KsHHEtkr3a6_mWTNA-DRboJAGV59MfgrcxSdulwAcvxkiRRH7YTQ.svg" alt="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/5258a7d7-6104-4519-9ae2-85ec3f8b9037/3OqqtdlxerBqgGfkk_lOyw1xQGtNUn0IUzSp1JOm-KMjjKIVLcIxYrbivRxnkOZYfZJ-DwCOAJfKCvKeCl5X0V9LHemQGH4wb1KsHHEtkr3a6_mWTNA-DRboJAGV59MfgrcxSdulwAcvxkiRRH7YTQ.svg" width="40px" /> **C++
▰▰▰▰▰▰▱▱▱▱ `Lv.6`**

</aside>

**TOOL**

<aside>
<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/1cdc1ab1-aec6-449a-b6fe-8ecb569b81cc/arduino_logo.png" alt="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/1cdc1ab1-aec6-449a-b6fe-8ecb569b81cc/arduino_logo.png" width="40px" /> **ArduinoIDE
▰▰▰▰▰▰▱▱▱▱ `Lv.6`**

</aside>

<aside>
<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/500bc41d-97bb-4d2f-8ab0-c3d346f08cc6/517642_2fcffbf9b8b14a5fade496e388d89915mv2.webp" alt="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/500bc41d-97bb-4d2f-8ab0-c3d346f08cc6/517642_2fcffbf9b8b14a5fade496e388d89915mv2.webp" width="40px" /> **Tinkercad
▰▰▰▰▰▱▱▱▱▱ `Lv.5`**

</aside>

<aside>
<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/5f7a750a-5685-4cc2-a460-2bdceb024d06/AI2_logo2.png" alt="https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/5f7a750a-5685-4cc2-a460-2bdceb024d06/AI2_logo2.png" width="40px" /> **App Inventor
▰▰▰▰▱▱▱▱▱▱ `Lv.4`**

</aside>

---

### 코드

- Arduino
    
    ```arduino
    #include <Arduino.h>
    #include <U8g2lib.h>
    #include <RTClib.h>
    
    RTC_DS3231 rtc; // DS3231 RTC 객체 생성
    
    char daysOfTheWeek[7][12] = {"Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"};
    
    //실제로는 128X32 지만 128X64와 같게 사용
    U8G2_SSD1306_128X64_NONAME_F_SW_I2C u8g2(U8G2_R0, /* clock=*/ PB11, /* data=*/ PB10, /* reset=*/ U8X8_PIN_NONE);
    
    // 아날로그 핀 설정
    const int analogPin = PA0;
    const int switchPin = PA1; // 스위치 핀 설정
    
    // 변수 선언
    float current = 0.0; // 전류 (A)
    float power = 0.0;   // 현재 전력 (W)
    float totalPower = 0.0; // 누적 전력 (kWh)
    float LastMonth = 0.0;  // 이전 달 누적 전력 (kWh)
    float LastCost = 0.0;  // 이전 달 누적 전력 (kWh)
    unsigned long lastReadingTime = 0;
    const unsigned long readingInterval = 1000; // 1초마다 읽음
    
    // 전기 요금 관련 변수 (원화)
    float baseCost1 = 910.0; // 기본 요금 (원)
    float baseCost2 = 1600.0; // 기본 요금 (원)
    float baseCost3 = 7300.0; // 기본 요금 (원)
    float ratePerKWh1 = 120.0; // 1 kWh당 요금 (원) - 0kWh부터 200kWh까지
    float ratePerKWh2 = 214.6; // 1 kWh당 요금 (원) - 201kWh부터 400kWh까지
    float ratePerKWh3 = 307.3; // 1 kWh당 요금 (원) - 401kWh 이상
    
    float monthlyCost = 0.0; // 한 달 동안의 요금 누적
    
    // 시간 관련 변수
    int lastDayOfMonth = 0; // 이전에 체크한 달
    boolean isFirstDay = true; // 매달 1일인지 여부
    
    // 화면 상태 변수
    enum ScreenState { POWER_STATE, LAST_STATE, TIME_STATE };
    ScreenState currentState = POWER_STATE;
    ScreenState previousState = POWER_STATE; // 이전 화면 상태를 저장
    
    void setup() {
      Serial2.begin(9600);
      Serial.begin(9600);
      u8g2.begin();
    
      // 아날로그 핀과 스위치 핀 초기화
      pinMode(analogPin, INPUT);
      pinMode(switchPin, INPUT_PULLUP); // 스위치 핀을 내부 풀업 저항 사용으로 설정
    
      // RTC 초기화
      rtc.begin();
    
      // RTC 시간 설정 (시간이 오차 발생 시 사용 후 다시 주석처리)
       //rtc.adjust(DateTime(F(__DATE__), F(__TIME__)));
    }
    
    void loop() {
      unsigned long currentTime = millis();
    
      // DS3231 RTC에서 현재 시간 가져오기
      DateTime now = rtc.now();
      int currentDay = now.day(); 
    
      // 매달 1일인 경우 누적 전력 값 리셋 및 이전 달 요금 저장
      if (currentDay == 1 && now.second() == 0 && currentDay != lastDayOfMonth) {
        LastMonth = totalPower; // 이전 달 누적 전력값을 저장
        LastCost = monthlyCost; // 이전 달 전기요금을 저장
        totalPower = 0.0;  // 전력값 초기화
        monthlyCost = 0.0; // 전기요금 초기화
        isFirstDay = true;
      }
      
      // 아날로그 핀에서 값을 읽어온다.
      int rawValue = analogRead(analogPin);
    
      // 변환 계수 설정
      float currentScale = 0.0125;
      
      // 전류 계산
      current = rawValue * currentScale;
      
      // 전력 계산
      power = 220.0 * current; // 볼트 대신 220V 사용
      
      // 누적 전력 계산
      if (!isFirstDay) {
        totalPower += (power / 1000.0) * ((currentTime - lastReadingTime) / 3600000.0); // 시간 간격을 이용하여 kWh로 변환
      }
      isFirstDay = false;
    
      // 결과를 시리얼 모니터에 출력
      Serial.print("I: ");
      Serial.print(current, 3); // 소수점 3자리까지 출력
      Serial.print(" A, P: ");
      Serial.print(power, 3); // 소수점 3자리까지 출력
      Serial.print(" W\nTotal : ");
      Serial.print(totalPower, 3); // 누적 전력 출력 (kWh)
      Serial.print(" kWh, Cost: ");
    
      // 월간 요금 계산
      if (totalPower <= 200.0) {
        monthlyCost = baseCost1 + (totalPower * ratePerKWh1);
      } else if (totalPower <= 400.0) {
        monthlyCost = (baseCost2 + ((totalPower - 200.0) * ratePerKWh2) + 24000) * 1.137;
      } else {
        monthlyCost = (baseCost3 + ((totalPower - 400.0) * ratePerKWh3) + 24000 + 42920) * 1.137;
      }
    
      Serial.print(int(monthlyCost / 10.0) * 10); // 소수점 이하 자리수를 버림
      Serial.println(" KRW");
      Serial.print("Last TTL: ");
      Serial.print(LastMonth,3);
      Serial.print(" kWh");
      Serial.print("\nLast Cost: ");
      Serial.print(int(LastCost / 10.0) * 10);
      Serial.print(" kWR\n---------------------------------\n");
      Serial.print(now.year(), DEC);
      Serial.print('/');
      Serial.print(now.month(), DEC);
      Serial.print('/');
      Serial.print(now.day(), DEC);
      Serial.print(" (");
      Serial.print(daysOfTheWeek[now.dayOfTheWeek()]);
      Serial.print(")\n");
      Serial.print(now.hour(), DEC);
      Serial.print(':');
      Serial.print(now.minute(), DEC);
      Serial.print(':');
      Serial.print(now.second(), DEC);
      Serial.print("\nTemp: ");
      Serial.print(rtc.getTemperature());
      Serial.println(" ℃");
      
      //HC-06을 통해 안드로이드폰에 출력
      Serial2.print("ThisMonth\n");
      Serial2.print("I: ");
      Serial2.print(current, 3); // 소수점 3자리까지 출력
      Serial2.print(" A\nP: ");
      Serial2.print(power, 3);
      Serial2.print(" W\nTotal : ");
      Serial2.print(totalPower, 3);
      Serial2.print(" kWh\nCost: ");
      Serial2.print(int(monthlyCost / 10.0) * 10); // 소수점 이하 자리수를 버림
      Serial2.print(" KRW");
      Serial2.print("\n\nLastMonth\n");
      Serial2.print("Total: ");
      Serial2.print(LastMonth,3);
      Serial2.print(" kWh");
      Serial2.print("\nCost: ");
      Serial2.print(int(LastCost / 10.0) * 10);
      Serial2.print(" kWR\n\nTIME\n");
      Serial2.print(now.year(), DEC);
      Serial2.print('/');
      Serial2.print(now.month(), DEC);
      Serial2.print('/');
      Serial2.print(now.day(), DEC);
      Serial2.print(" (");
      Serial2.print(daysOfTheWeek[now.dayOfTheWeek()]);
      Serial2.print(")\n");
      Serial2.print(now.hour(), DEC);
      Serial2.print(':');
      Serial2.print(now.minute(), DEC);
      Serial2.print(':');
      Serial2.print(now.second(), DEC);
      Serial2.print("\nTemp: ");
      Serial2.print(rtc.getTemperature());
      Serial2.println(" ℃");
      
    
      lastDayOfMonth = currentDay;
      lastReadingTime = currentTime;
    
      // 스위치 입력을 감지하고 화면 상태 변경
      if (digitalRead(switchPin) == LOW) { // 스위치가 눌린 경우
        delay(100); // 디바운싱
        if (currentState == POWER_STATE) {
          currentState = LAST_STATE; // 화면 전환1
        } else if (currentState == LAST_STATE) {
          currentState = TIME_STATE; // 화면 전환2
        } else if (currentState == TIME_STATE) {
          currentState = POWER_STATE; // 화면 전환3
        }
      }
    
      // OLED 화면 출력
      u8g2.firstPage();
      do {
        u8g2.setFont(u8g2_font_ncenB10_tr); // 폰트 선택
        if (currentState == POWER_STATE) {
          // 현재 전력 사용량 및 전기사용료 표시
          u8g2.setCursor(0, 20);
          u8g2.print("I: ");
          u8g2.print(current, 3); 
          u8g2.print(" A");
          u8g2.setCursor(0, 35);
          u8g2.print("P: ");
          u8g2.print(power, 3);  
          u8g2.print(" W");
          u8g2.setCursor(0, 50);
          u8g2.print("TTL: ");
          u8g2.print(totalPower, 3);
          u8g2.print(" kWh");
          u8g2.setCursor(0, 65);
          u8g2.print("Cost: ");
          u8g2.print(int(monthlyCost / 10.0) * 10);
          u8g2.print(" KRW");
        } else if (currentState == TIME_STATE) {
          // 시간, 온도 표시
          u8g2.setCursor(0, 20);
          u8g2.print(now.year(), DEC);
          u8g2.print('/');
          u8g2.print(now.month(), DEC);
          u8g2.print('/');
          u8g2.print(now.day(), DEC);
          u8g2.print(" (");
          u8g2.print(daysOfTheWeek[now.dayOfTheWeek()]);
          u8g2.print(") ");
          u8g2.setCursor(0, 35); 
          u8g2.print(now.hour(), DEC);
          u8g2.print(':');
          u8g2.print(now.minute(), DEC);
          u8g2.print(':');
          u8g2.print(now.second(), DEC);
          u8g2.setCursor(0, 50);
          u8g2.print("Temp: ");
          u8g2.print(rtc.getTemperature());
          u8g2.print(" 'C");
        } else {
          // 지난달 비용 상태 화면 출력
          u8g2.setCursor(0, 20);
          u8g2.print("Last Month");
          u8g2.setCursor(0, 35);
          u8g2.print("TTL: ");
          u8g2.print(LastMonth,3);
          u8g2.print(" kWh");
          u8g2.setCursor(0, 50);
          u8g2.print("Cost: ");
          u8g2.print(int(LastCost / 10.0) * 10);
          u8g2.print(" KRW");
        }
      } while (u8g2.nextPage());
    }
    
    ```
    
- App Inventor
    - 블록
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/54535322-82c8-4d55-87be-89196eb670ee/Untitled.png)
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/26e1895e-8d04-488d-ac59-7e5b25426bee/Untitled.png)
        
    - 디자인
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/cf5adbe4-4243-4b97-9bb3-82d137fe5dc4/3ffdce0f-a574-41aa-ba4e-e1aa6698039a/Untitled.png)
