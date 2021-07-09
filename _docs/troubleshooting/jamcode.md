---
title: Jamcode
category: Trouble Shooting
order: 1

---

　  
### 010203
　  
**1. JAM CODE:** 010203

**2. JAM CONTENT:** No. %s Plate was not UP.

**3. JAM IMAGE:**

![010203](https://user-images.githubusercontent.com/85915538/125031298-060fb480-e0bf-11eb-984c-86b0b600eef0.png)

**4. CHECK POINT & ACTION PROCESS**

* If the C-Tray is properly seated.  
  → Check the Plate Up/Down Sensor.

* If the C-Tray is not seated properly.  
  → Check if there is something between C-Tray and Plate.
  
* If the X-axis alignment of C-Tray and Plate does not match.  
  → Adjust Tray Transfer's X-axis Teaching.
  
* If the Y-axis alignment of C-Tray and Plate does not match.  
  → Adjust the Stacker's stopper to align the Y-axis.
  
  > ⚠ When adjusting the Stacker's Stopper, be careful because other Stacker and Plate will also be affected.


### 030003
　  
**1. JAM CODE:** 030003

**2. JAM CONTENT:** Loading Index Robot picking device failed.

**3. JAM IMAGE:**

![030003](https://user-images.githubusercontent.com/85915538/125031285-0314c400-e0bf-11eb-904e-dd5172caaa41.png)

**4. CHECK POINT & ACTION PROCESS**

* LD Buffer의 Device가 흐트러져 있다.  
  → LD XY Robot의 Teaching을 확인하세요.  
  → LD Index Robot의 VSC Level을 확인하세요.

* LD Plate의 Device가 흐트러져 있다.  
  → Tray Transfer를 확인하세요. 
  

### 040003
　  
**1. JAM CODE:** 040003 / 041003

**2. JAM CONTENT:** Front Unloading Index Robot picking failed.

**3. JAM IMAGE:**

![040003](https://user-images.githubusercontent.com/85915538/125031467-496a2300-e0bf-11eb-8ea9-66fdc9c83d8b.png)

**4. CHECK POINT & ACTION PROCESS**

　  
　**Device가 Carrier 안에 있는 경우**

* ULD Index Robot의 Teaching이 맞지 않다.  
  → ULD Index Robot의 Teaching을 확인하세요.

* VSC Level이 충족되지 않는다.  
  → Picker Pad 상태를 확인하세요.  
  → Air Hose 상태를 확인하세요.  
  → Fitting이 풀렸는지 확인하세요.  
  → Ejector 상태를 확인하세요.

* Index Robot의 Picker Cylinder가 다 내려오지 못했다.  
  → Air Hose의 길이가 충분한지 확인하세요.  

　  
　**Device가 Carrier 안에 없는 경우**

* LD Index Robot의 Teaching이 맞지 않다.  
  → LD Index Robot의 Teaching을 확인하세요.

* LD Hear Pusher에 이물질이 존재한다.  
  → 이물질을 제거하세요.

* 동일한 위치에서 연속으로 발생하였다.  
  → Carrier 상태를 확인하세요.
  

### 050229
　  
**1. JAM CODE:** 050229

**2. JAM CONTENT:** The existing ID info(=%s) and currently checked ID info(=%s) is not identical.

**3. JAM IMAGE:**

![050229](https://user-images.githubusercontent.com/85915538/125031475-4c651380-e0bf-11eb-8eb2-de94bd6a1ea1.png)

**4. CHECK POINT & ACTION PROCESS**

* T-Tray의 ID 설정이 잘못되었다.  
  → T-Tray의 ID Block을 올바르게 구성한다.  

* T-Tray의 ID Block이 오염되었다.  
  → T-Tray의 ID Block을 깨끗하게 닦으세요.

* Sensor의 감지 상태가 이상하다.  
  → Sensor의 상태를 확인하세요.  
  → NX12 Module의 상태를 확인하세요.  

> 💡 [How to set T-Tray ID](https://lte0609.github.io/ht/manual/tray-id/)

  

### 060300
　  
**1. JAM CODE:** 060300

**2. JAM CONTENT:** Head Pusher#1 Up/Down Check Sensor in the Exchanger was not UP.

**3. JAM IMAGE:**

![060300](https://user-images.githubusercontent.com/85915538/125031480-4ec76d80-e0bf-11eb-857e-c29e30a2c5c6.png)

**4. CHECK POINT & ACTION PROCESS**

* Head Pusher가 올라왔다.  
  → Up/Down Check Sensor를 확인하세요.

* Head Pusher가 올라오지 못했다.  
  → LD Shifter의 Teaching을 확인하세요.  
  → Head Pusher에 이물질이 있는지 확인하세요.
  

### 060600
　  
**1. JAM CODE:** 060600

**2. JAM CONTENT:** Rotator Tray Holder Lock/Unlock Check Sensor in the Exchanger was not Lock.

**3. JAM IMAGE:**

![060600](https://user-images.githubusercontent.com/85915538/125031482-50913100-e0bf-11eb-8362-7c1fa3114f38.png)

**4. CHECK POINT & ACTION PROCESS**

* T-Tray의 이동이 원활하다.  
  → LD Shifter의 Teaching을 확인하세요.

* T-Tray의 이동이 원활하지 않다.  
  → Main & Chamber의 Docking 상태를 확인하세요.
  

### 060601
　  
**1. JAM CODE:** 060601

**2. JAM CONTENT:** Rotator Tray Holder Lock/Unlock Check Sensor in the Exchanger was not Unlock.

**3. JAM IMAGE:**

![060601](https://user-images.githubusercontent.com/85915538/125032090-09f00680-e0c0-11eb-90a4-6d41b8ce4a2b.png)

**4. CHECK POINT & ACTION PROCESS**

* T-Tray의 Hole과 Pin의 위치가 맞지 않는다.  
  → P/H Front Lifter의 높이를 조정하세요. 
  

### 061400
　  
**1. JAM CODE:** 061400

**2. JAM CONTENT:** ULD Step Move Hook On/Off Check in the Exchanger was not On.

**3. JAM IMAGE:**

![061400](https://user-images.githubusercontent.com/85915538/125032203-33109700-e0c0-11eb-9650-7614da561adf.png)

**4. CHECK POINT & ACTION PROCESS**

* T-Tray의 Hole과 Pin의 위치가 맞지 않는다.  
  → ULD Shifter의 Teaching을 확인하세요.
  

### 061900
　  
**1. JAM CODE:** 061900 / 062000 / 062100 / 062200

**2. JAM CONTENT:** ULD Head Pusher #1 Up/Down Check in the Exchanger was not Up.

**3. JAM IMAGE:**

![061900](https://user-images.githubusercontent.com/85915538/125032276-50ddfc00-e0c0-11eb-9ac8-4b0f80beeade.png)

**4. CHECK POINT & ACTION PROCESS**

* T-Tray의 Hole과 Pin의 위치가 맞지 않는다.  
  → ULD Shifter의 Teaching을 확인하세요. 
  

### 063200
　  
**1. JAM CODE:** 063200 / 063201 / 064600 / 064601

**2. JAM CONTENT:** Front Pusher Front/Rear Check in the Preheater was not On.

**3. JAM IMAGE:**

![063200](https://user-images.githubusercontent.com/85915538/125031505-59820280-e0bf-11eb-8842-6edbe42200d0.png)

**4. CHECK POINT & ACTION PROCESS**

* Pusher Pin이 오염되었다.  
  → Pin의 오염을 제거하세요.

* Pusher Pin의 움직임이 불안하다.  
  → Cylinder의 상태를 점검하세요.
  

### 063400
　  
**1. JAM CODE:** 063400 / 063401

**2. JAM CONTENT:** ID Check Block Front/Rear Check in the Preheater was not On.

**3. JAM IMAGE:**

![063400](https://user-images.githubusercontent.com/85915538/125031512-5ab32f80-e0bf-11eb-9275-a957f03ac565.png)

**4. CHECK POINT & ACTION PROCESS**

* ID Check Pin이 움직이지 않았다.  
  → 기구물의 간섭을 확인하세요.

* ID Check Pin이 제대로 동작하였다.  
  → Sensor 상태를 확인하세요.
  

### 063800
　  
**1. JAM CODE:** 063800 / 063801 / 063900 / 063901

**2. JAM CONTENT:** Left Pocker Lock/Unlock Check in the Rear Shifter was not On.

**3. JAM IMAGE:**

![063800](https://user-images.githubusercontent.com/85915538/125031518-5c7cf300-e0bf-11eb-8a9e-b195b8729de7.png)

**4. CHECK POINT & ACTION PROCESS**

* T-Tray의 Hole과 Pocker Pin의 위치가 맞지 않다.  
  → Rear Shifter의 Teaching을 확인하세요.

* Pocker의 동작상태가 원활하지 않다.  
  → LM Guide 상태를 확인하세요.  
  → Cylinder 상태를 확인하세요.  
  → Shaft 및 Bush 상태를 확인하세요.
