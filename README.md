# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![519811194-54db554a-1d50-44e1-93d1-d9b54882f86b](https://github.com/user-attachments/assets/b6f0200d-6ed8-4626-adf7-e8a14bdd0cfd)
![519811343-acedcfa1-390a-40b3-b002-49d408c66d63](https://github.com/user-attachments/assets/8c3b1f67-c169-4ed2-a7e0-8c40c2651ab4)
![514776134-820fb044-7e9c-4f94-99cb-7b9b1bec573e](https://github.com/user-attachments/assets/0f9fab93-f439-4983-a350-5b7229db6593)




## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```

## Output:
<img width="923" height="782" alt="Screenshot 2025-11-25 172033" src="https://github.com/user-attachments/assets/0be15db5-5a5b-4086-97ad-042a3817babd" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551 
