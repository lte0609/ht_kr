---
title: T-Tray ID
category: Manual
order: 1
---

　  
![id3_en](https://user-images.githubusercontent.com/85915538/125014167-c5547300-e09f-11eb-80db-d73c8689ad35.png)

ID:3 T-Tray의 ID Block 설정 예시입니다.


### T-Tray ID Block
　  
T-Tray ID는 4-Bit의 2진법으로 구성되어 있다. Block이 있으면 1, 없으면 0 입니다.

ID Block은 왼쪽부터 차례대로 1, 2, 4, 8의 값어치을 가진다. 


### Parity Bit
　  
Parity는 오류를 확인하기 위한 Bit 입니다.

M500HT에서는 홀수 패리티를 사용합니다. 전체 비트에서 1의 개수가 홀수가 되도록 패리티 비트를 설정합니다.


### 4-Bit Binary Table
　  
![id-table](https://user-images.githubusercontent.com/85915538/125050261-6826e480-e0d4-11eb-8f9c-1b7dcdac0b10.png)
