# pullup_example1(23.03.29)
![pullup_example1](https://user-images.githubusercontent.com/129159977/235813786-8217038d-a54c-4d32-b0fb-7d24aad3539b.png)

<hr/>

## 풀업 예제 1

오늘은 외부 저항 없이 내부 저항으로 스위치 사용하기를 해보았습니다.<br>
입력 모드에 있는 핀의 값을 HIGH로 설정하여 내부 풀업 저항을 작동시킬 수 있습니다.<br>
setup()함수에서 입력 모드에 있는 핀 inputPin을 HIGH로 설정하면 내부 저항이 작동하는 것을 알 수 있습니다.

<hr/>

|함수|기능|설명|
|------|:---:|---|
|pinMode()|핀 입출력|pinMode(buttonPin, INPUT)<br>pinMode(ledPin, OUTPUT)|
|digitalWrite()|쓰기|digitalWrite(buttonPin, HIGH)<br>digitalWrite(ledPin, LOW)|
|digitalRead()|읽기|digitalRead(inputPin)|
