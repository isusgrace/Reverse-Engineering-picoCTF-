Hi, Can you speak Thai ?

Yes, I can speak Thai.

มา วันนี้เราจะมาทำข้อ vault-door-1 หมวด Reverse Engineering

Step 1 Notepad

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d1f8c61-9270-46bd-8e03-1d4f6b5a04d3" />

ภาพที่ 1

ข้อนี้จะมีไฟล์ที่มีชื่อว่า "VaultDoor1.java" มาให้ ให้เราเปิดไฟล์นี้ใน Notepad

Step 2 จัดเรียง

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b5c1ab56-db3f-4874-a78f-1f0396df779c" />

ภาพที่ 2

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b2d23894-342d-4cd7-8857-e7c6c92c7667" />

ภาพที่ 3

ครอบข้อความทั้งหมดที่เราต้องการ ดังภาพที่ 2 จากนั้นไปที่ edit -> ไปที่ Line Operations -> ไปที่ Sort Lines As Integers Ascending

Step 3 Replace (ลบหน้า)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/02f2fad5-0e97-48e3-8466-9d931de88d2b" />

ภาพที่ 4

ใช้ Shift + Tab (กดแป้นพิมพ์) เพื่อลบช่องว่างด้านหน้า

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/43e49256-bf54-4c06-ac9f-eb9a30f49d26" />

ภาพที่ 5

ไปที่ Seach -> ไปที่ Replace -> ไปที่ "Find what:..." แล้วพิมพ์ .* ' ลงไป -> กด Replace All ดังภาพที่ 5
```
.* '
```
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3caa4226-965b-4c59-981e-af9d0111eefc" />

ภาพที่ 6

จะได้ผล ดังภาพที่ 6

Step 4 Replace (ลบหลัง)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/34824e4f-740b-42ae-87e1-30357d6923c8" />

ภาพที่ 7

ไปที่ "Find what:..." กดลบ แล้วพิมพ์ '.* ลงไป -> กด Replace All ดังภาพที่ 7

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b0c1e7e7-afc3-4680-9fdc-f7bf9796c048" />

ภาพที่ 8

จะได้ผล ดังภาพที่ 8

หลังจากนั้น Copy แล้วนำไปส่งใน picoCTF แต่ก่อนส่ง พิมพ์รูปแบบ flag ด้วย
```
picoCTF
```
