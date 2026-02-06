# 8-Bit-Odd-or-Even-Using-8085
Name:PRABHA B G
Register No. 212224050029

## Aim:
To write an 8085 microprocessor program to check whether a given 8-bit number is odd or even.

## Apparatus Required:
•	Laptop with an internet connection

## Algorithm:
1.	Load the number from a specified memory location into register A.
2.	Perform an AND operation with 01H to check the least significant bit (LSB).
3.	If the result is 0, the number is even; otherwise, it is odd.
4.	Store the result in a specific memory location (odd or even flag).


## Program:
```
LDA 4200H
ANI 01H
JZ L1
MVI A, 01H
JMP L2
L1:MVI A, 02H
L2:STA 4300H
HLT
```
## Verification ODD:
![WhatsApp Image 2026-02-03 at 11 19 36 AM](https://github.com/user-attachments/assets/3b59987c-1824-4e4d-b0eb-889c894bd49f)
![WhatsApp Image 2026-02-03 at 11 20 49 AM](https://github.com/user-attachments/assets/b8f06bfe-b53a-4c4f-bbfc-0cfed25836d0)

## Input ODD:
<img width="1900" height="817" alt="Screenshot 2026-02-03 102900" src="https://github.com/user-attachments/assets/da4433bd-47b0-4db0-94e2-39ccd3532629" />

## Output ODD:
<img width="1894" height="807" alt="Screenshot 2026-02-03 102919" src="https://github.com/user-attachments/assets/1aaa8dd9-d6fb-42dd-859d-666005e082a8" />

## Verification EVEN:
![WhatsApp Image 2026-02-03 at 11 22 19 AM](https://github.com/user-attachments/assets/46d113c5-5a31-4acb-8299-14fe3a8b6526)
![WhatsApp Image 2026-02-03 at 11 23 28 AM](https://github.com/user-attachments/assets/eb69a56f-4efc-4c29-a5b8-380734f2eb21)

## Input EVEN:
<img width="1902" height="831" alt="Screenshot 2026-02-03 103222" src="https://github.com/user-attachments/assets/56fabb2a-69e2-4d9d-bfe3-e26177ecd0a8" />

## Output EVEN:
<img width="1898" height="826" alt="Screenshot 2026-02-03 103244" src="https://github.com/user-attachments/assets/b60869b5-9040-457f-b862-fbe295f3d331" />

## Result:
The 8085 microprocessor successfully checks whether a given number is odd or even and stores the result in memory.

