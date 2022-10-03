# Digital Forensic 06
Import ไฟล์ .ova เข้า VMWare หรือ VirtualBox
![image](https://user-images.githubusercontent.com/16158569/193491285-79f72f72-3859-4ef7-99d0-a37d48254bf2.png)  
จะพบว่ามี user account อยู่ 2 บัญชีซึ่งติดรหัสทั้งคู่  
ทำการโหลด [HirenBoot](https://www.hirensbootcd.org/download/) และ Boot เข้า VM เพื่อเปลี่ยนรหัสโดยใช้เครื่องมือ NT Password Edit   
![image](https://user-images.githubusercontent.com/16158569/193491752-b1a29580-0a40-4891-8275-09b0de26b8dd.png)  
เปลี่ยนเสร็จ เข้าสู่ระบบของ winxp ด้วยรหัสผ่านที่ตั้งใหม่  
หลังจากนั้นลองค้นหา keyword ในแต่ละไฟล์ดู
![image](https://user-images.githubusercontent.com/16158569/193492073-9b0d463b-3fb4-47c6-96b6-9a4f512c9aaa.png)  
![image](https://user-images.githubusercontent.com/16158569/193492136-0ba48653-18aa-4f64-b359-be7582c5c469.png)
เอ๋! hackernote ใช่แน่ๆ
![image](https://user-images.githubusercontent.com/16158569/193492180-796eafb2-f2a6-4df6-b871-15e13a717ec1.png)  
แค่นี้เราก็ได้ flag ในการไปตอบแล้วนั้นคือ
`tctt2022{Expl0it_windows/smb/ms08_067_netapi}`
นั้นเอง  
![image](https://media.tenor.com/MThz30WrMWQAAAAd/the-rock-chinese-the-rock.gif)
