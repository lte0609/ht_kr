---
title: T-Tray ID
category: Manual
order: 1

---

　  
![id3](https://user-images.githubusercontent.com/85915538/125546900-944b81fc-0edd-48e1-82d2-cc63030ffeb6.png)

ID:3 T-Tray Block의 설정 예시.


### **T-Tray ID Block**
　  
T-Tray ID는 4-bit 이진법으로 구성되어 있습니다. 블록이 있으면 1, 없으면 0 입니다.

ID Block은 왼쪽부터 순서대로 1, 2, 4, 8의 값을 가집니다.


### **Parity Bit**
　  
Parity bit는 오류를 확인하기 위한 bit 입니다.

M500HT는 홀수 패리티를 사용합니다. 전체 bit에서 1의 갯수가 홀수가 되도록 Parity bit를 설정하세요.


### **4-Bit Binary Table**
　  
![id-table](https://user-images.githubusercontent.com/85915538/125050261-6826e480-e0d4-11eb-8f9c-1b7dcdac0b10.png)
