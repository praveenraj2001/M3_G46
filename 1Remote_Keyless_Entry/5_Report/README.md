# Table of content (V1.1)
1. About the BiCom System
    1. Description
    1. Identifying features
    1. State of art
    1. 5W’s & 1H and S.W.O.T analysis
1. Requirements
    1. High level requirements
    1. Low level requirements
1. Architecture
    1. Behavioural Diagram
        1. High Level Flow chart Behavioural Diagram
        1. Low Level Flow chart Behavioural Diagram
    1. Structural Diagram
        1. High Level UML Use Case Structural Diagram
        1. Low Level UML Use Case Structural Diagram
1. Test plan and Output
    1. High level test plan
    1. Low level test plan


#  1 About the RKE
## i Description
 * This Project is an __Remote keyless entry (RKE) system__,and is designed to remotely lock or unlock access to automobiles, RKE operates by broadcasting radio waves on a particular frequency unidirectionally,RKE systems implement encryption algorithms to prevent car thieves from intercepting and spoofing the telegrams

---

## ii Identifying features
 * It shall Lock the car when Button is pressed ONCE
 * It shall Unlock the car when Button is pressed TWICE
 * It shall activation/deactivation alarm when the Button is pressed THREE times
 * It shall approach light when the Button is pressed FOUR times

## iii State of art
 * The main focus point here is controlling the car remotely
 * And also securing our car with a reliable __Encryption System__
 * Now this two features are combined and made into one product i.e. __RKE__
 * As the world PACE-FORWARD our technology needs to catch up to the world  

---
## iv 5W's & 1H and S.W.O.T analysis is in the below table 

| 5W's & 1H | S.W.O.T analysis |
| -------- | -------------- |
| ![5W1H](https://github.com/praveenraj2001/M3_G46/blob/main/1Remote_Keyless_Entry/6_ImagesAndVideos/5W1H.png) | ![SWOT](https://github.com/praveenraj2001/M3_G46/blob/main/1Remote_Keyless_Entry/6_ImagesAndVideos/SWOT.png)|

---

## 2 Requirements


### i High Level Requirements

| ID | High Level Requirements |
| -------- | -------------- |
| HLR1 | It shall LOCK THE CAR|
| HLR2 | It shall UNLOCK THE CAR |
| HLR3 | It shall ACTIVATE / DEACTIVATE THE ALARM |
| HLR4 | It shall APPROACH LIGHT |


### ii Low Level Requirements

| ID | Low Level Requirements for HLR1|       |ID | Low Level Requirements for HLR2|
| ----- | ----- | ---- |----- | ----- |
| LLR1.1 | If the User Button is pressed ONCE, ON LED ORANGE, GREEN along with other LED's |     |LLR2.1 | If the User Button is pressed TWICE, OFF LED ORANGE, GREEN along with other LED's  |
| LLR1.2 | If the User Button is pressed ONCE, ON LED RED, BLUE along with other LED's|     |LLR2.2 | If the User Button is pressed TWICE, OFF LED RED, BLUE along with other LED's |



| ID | Low Level Requirements for HLR3|  |ID | Low Level Requirements for HLR4|
| -------- | -------------- | ---- | -------- | -------------- |
| LLR3.1 |  If the User Button is pressed THREE times, ON All LED's in CLOCKWISE manner  |  | LLR4.1 | If the User Button is pressed FOUR times, ON All LED's in ANTI-CLOCKWISE manner |
| LLR3.2 | i.e. GREEN➡ORANGE➡RED➡BLUE➡GREEN |  | LLR4.2 | i.e. GREEN➡BLUE➡RED➡ORANGE➡GREEN |


# 3 Architecture
* ##  i Behavioral Diagram
    * ### a High Level Flow chart Behavioral Diagram
    ![HLFBD](https://github.com/praveenraj2001/M3_G46/blob/main/1Remote_Keyless_Entry/6_ImagesAndVideos/HLFBD_BG.png)
    * ### b Low Level Flow chart Behavioral Diagram
    ![LLFBD](https://github.com/praveenraj2001/M3_G46/blob/main/1Remote_Keyless_Entry/6_ImagesAndVideos/LLFBD_BG.png)
* ## ii Structural Diagram
    * ### a High Level UML Use Case Structural Diagram
    ![HL_UML](https://github.com/praveenraj2001/M3_G46/blob/main/1Remote_Keyless_Entry/6_ImagesAndVideos/HL_UML.png)
    * ### b Low Level UML Use Case Structural Diagram
    ![LL_UML](https://github.com/praveenraj2001/M3_G46/blob/main/1Remote_Keyless_Entry/6_ImagesAndVideos/LL_UML.png)
---

# 4 Test plan and output

### Test plan is created and verified

## i HIGH LEVEL TEST PLAN / Integrated test plan

| Test ID | Description | Input | Expected output | Actual Output | 
| --- | --- | --- | --- | --- | 
| 01 | LOCK | USER BUTTON PRESS ONCE  | Shall LOCK the car | Shall LOCK the car  | 
| 02 | UNLOCK | USER BUTTON PRESS TWICE | Shall UNLOCK the car |  Shall UNLOCK the car | 
| 03 | ALARM ACTIVATE / DEACTIVATE | USER BUTTON PRESS THREE TIMES | Shall ACTIVATE / DEACTIVATE ALARM  | Shall ACTIVATE / DEACTIVATE ALARM |
| 04 | APPROACH LIGHT | USER BUTTON PRESS FOUR TIMES | Shall turn On approach light | Shall turn On approach light |
| 05 |  ENCRYPTION | 1 OR 2 0R 3 0R 4 | encrypted data for 1/2/3/4 | encrypted data for 1/2/3/4 |


## ii LOW LEVEL TEST PLAN

| Test ID (for LOCK)| Description | Input | Expected output | Actual Output | passed/not |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for LOCK | USER BUTTON PRESS ONCE  | Shall ON all LED's as per ENCRYPTION | Shall ON all LED's as per ENCRYPTION | ✅ |
| 02 | Check for UNLOCK | USER BUTTON PRESS TWICE  | Shall OFF all LED's as per ENCRYPTION | Shall OFF all LED's as per ENCRYPTION | ✅ |
| 03 | Check for ALARM ACTIVATE/DEACTIVATE | USER BUTTON PRESS THREE TIMES | Shall ON LED's ONCE clockwise as per ENCRYPTION |  Shall ON LED's ONCE clockwise as per ENCRYPTION | ✅ |
| 04 | Check for APPROACH LIGHT | USER BUTTON PRESS FOUR TIMES | Shall ON LED's once anti-clockwise as per ENCRYPTION |  Shall ON LED's once anti-clockwise as per ENCRYPTION | ✅ |
| 05 | Check for ENCRYPTION | 1/2/3/4  | 1244/1843/6789/5478 | 1244/1843/6789/5478 | ✅ |
| 06 | Check for btn_press() | counts no of button press  | 1/2/3/4 | 1/2/3/4 | ✅ |

