# ErrorCorrectCode

#### Description

sample output:

```
odd parity:
Data{data=[1, 1, 0, 1, 0, 1], size=6, parity=[0], parityType=Even, isCorrect=true}
--------------------------
Data{data=[1, 1, 0, 1, 0, 1], size=6, parity=[0], parityType=Even, isCorrect=true}
--------------------------
dataParity: [0]	computeParity: 0
********************
CRC:
Data{data=[0, 0, 1, 1, 0, 1], size=6, parity=[0, 0, 0], parityType=CRC, isCorrect=true}
--------------------------
Data{data=[0, 0, 0, 1, 0, 1], size=6, parity=[0, 0, 0], parityType=CRC, isCorrect=false}
--------------------------
dataParity: [0, 0, 0]	computeParity: [1, 1, 0]
********************
HM Code:
HMData{isCorrect=true, dataWithParity=[1, 0, 1, 0, 1, 0, 1]}
--------------------------
HMData{isCorrect=false, dataWithParity=[1, 1, 1, 0, 1, 0, 1]}
--------------------------
dataWithParity: [1, 1, 1, 0, 1, 0, 1]	computeParity: [0, 1, 0]
if Only 1 bit error, the bit position need to fix: 2
********************
```



