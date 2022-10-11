# Mobile Security 02
ใช้ Apktool ใน Linux ในการ Reverse APK  
![image](https://user-images.githubusercontent.com/16158569/194994772-7f393e95-8a62-447b-9ef9-29a080f62182.png)  
จะได้ folder ที่เป็น source code มา  
หลังจากนั้นใช้คำสั่ง grep หาเบาะแสของ flag  
![image](https://user-images.githubusercontent.com/16158569/194994958-06c1f743-2268-4168-9285-0b23089e6654.png)  
เหมือนจะเจอคำใบ้ ลองไปที่ไฟล์นั้นกัน  
![image](https://user-images.githubusercontent.com/16158569/194995055-a182d330-80e9-41f3-84cb-d0d3ab82af43.png)  
และเราก็เจอคำตอบแล้ว นั้นคือ  
"Hello World! . .t. .c. .t. .t. .2. .0. .2. .2. . {. .K. .4. .n. ._. .4. .N. .Y. .o. .N. .e. ._. .f. .1. .n. .d. ._. .O. .u. .R. ._. .H. .1. .d. .D. .E. .n. ._. .W. .O. .r. .l. .d. .}"  
ลบจุดออกด้วย CyberChef  
![image](https://user-images.githubusercontent.com/16158569/194995231-a102cb35-51eb-4407-ae40-911a346891fa.png)  
ได้ Flag แล้วนั้นคือ tctt2022 {K4n_4NYoNe_f1nd_OuR_H1dDEn_WOrld}
