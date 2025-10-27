Hi, Can you speak Thai ?

Yes, I can speak Thai.

มา วันนี้เราจะมาทำข้อ vault-door-4 หมวด Reverse Engineering

Step 1 Visual Studio Code

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7356bd48-7e61-4946-bb8c-8de209255c89" />
ภาพที่ 1

ข้อนี้จะมีไฟล์ที่มีชื่อว่า "VaultDoor4.java" มาให้ ให้เปิดไฟล์นี้ใน Visual Studio Code ดังภาพที่ 1

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d099b11-caa3-4e70-8bef-2d57ee766a65" />
ภาพที่ 2

แล้วเลื่อนลงมา ดังภาพที่ 2

Step 2 Decimal
```
106 , 85  , 53  , 116 , 95  , 52  , 95  , 98
```
เอาสัญลักษณ์ลูกน้ำออก จากนั้น copy ส่วนนี้ไปถอดรหัส

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/43fd573e-f292-417c-b6a1-d231875ed903" />
ภาพที่ 3

โดยการเข้า CyberChef ไปที่ Operations แล้วเลือก From Decimal จะได้ผล ดังภาพที่ 3

นี่คือ flag ส่วนที่ 1

Step 3 Hex
```
0x55, 0x6e, 0x43, 0x68, 0x5f, 0x30, 0x66, 0x5f
```
เอาสัญลักษณ์ลูกน้ำออก จากนั้น copy ส่วนนี้ไปถอดรหัส

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/02195d47-c2aa-42aa-a109-80eaa3d41f5a" />
ภาพที่ 4

โดยการเข้า CyberChef ไปที่ Operations แล้วเลือก From Hex จะได้ผล ดังภาพที่ 4

นี่คือ flag ส่วนที่ 2

Step 4 Octal
```
0142, 0131, 0164, 063 , 0163, 0137, 0143, 061
```
เอาสัญลักษณ์ลูกน้ำออก จากนั้น copy ส่วนนี้ไปถอดรหัส

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/528c8dd7-76c9-4be2-ace6-9f40da472a35" />
ภาพที่ 5

โดยการเข้า CyberChef ไปที่ Operations แล้วเลือก From Octal จะได้ผล ดังภาพที่ 5

นี่คือ flag ส่วนที่ 3

Step 5 
```
'9' , '4' , 'f' , '7' , '4' , '5' , '8' , 'e'
```
พิมพ์ออกมาได้เลย
```
94f7458e
```
นี่คือ flag ส่วนที่ 4

นำ flag ทุกส่วนมารวมกัน แล้วนำไปส่งใน picoCTF แต่ก่อนส่ง พิมพ์รูปแบบ flag ด้วย
```
picoCTF
```

