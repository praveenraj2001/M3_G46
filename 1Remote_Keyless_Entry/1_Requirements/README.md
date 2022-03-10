
#  About the RKE
## Description
 * This Project is an __Remote keyless entry (RKE) system__,and is designed to remotely lock or unlock access to automobiles, RKE operates by broadcasting radio waves on a particular frequency unidirectionally,RKE systems implement encryption algorithms to prevent car thieves from intercepting and spoofing the telegrams

---

## Identifying features
 * It shall Lock the car when Button is pressed ONCE
 * It shall Unlock the car when Button is pressed TWICE
 * It shall activation/deactivation alarm when the Button is pressed THREE times
 * It shall approach light when the Button is pressed FOUR times

## State of art
 * The main focus point here is controlling the car remotely
 * And also securing our car with a reliable __Encryption System__
 * Now this two features are combined and made into one product i.e. __RKE__
 * As the world PACE-FORWARD our technology needs to catch up to the world  

---
## 5W's & 1H and S.W.O.T analysis is in the below table 

| 5W's & 1H | S.W.O.T analysis  |
| -------- | -------------- |
| ![5W1H](https://github.com/praveenraj2001/M3_G46/blob/main/1RKE/6_ImagesAndVideos/5W1H.png) | ![SWOT](https://github.com/praveenraj2001/M3_G46/blob/main/1RKE/6_ImagesAndVideos/SWOT.png)|

---

## Requirements


### High Level Requirements

| ID | High Level Requirements |
| -------- | -------------- |
| HLR1 | It shall LOCK THE CAR|
| HLR2 | It shall UNLOCK THE CAR |
| HLR3 | It shall ACTIVATE / DEACTIVATE THE ALARM |
| HLR4 | It shall APPROACH LIGHT |


### Low Level Requirements

| ID | Low Level Requirements for HLR1|       |ID | Low Level Requirements for HLR2|
| ----- | ----- | ---- |----- | ----- |
| LLR1.1 | If the User Button is pressed ONCE, ON LED ORANGE, GREEN along with other LED's |     |LLR2.1 | If the User Button is pressed TWICE, OFF LED ORANGE, GREEN along with other LED's  |
| LLR1.2 | If the User Button is pressed ONCE, ON LED RED, BLUE along with other LED's|     |LLR2.2 | If the User Button is pressed TWICE, OFF LED RED, BLUE along with other LED's |



| ID | Low Level Requirements for HLR3|  |ID | Low Level Requirements for HLR4|
| -------- | -------------- | ---- | -------- | -------------- |
| LLR3.1 |  If the User Button is pressed THREE times, ON All LED's in CLOCKWISE manner  |  | LLR4.1 | If the User Button is pressed FOUR times, ON All LED's in ANTI-CLOCKWISE manner |
| LLR3.2 | i.e. GREEN➡ORANGE➡RED➡BLUE➡GREEN |  | LLR4.2 | i.e. GREEN➡BLUE➡RED➡ORANGE➡GREEN |
