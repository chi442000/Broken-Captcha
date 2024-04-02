# Broken-Captcha
### Contents
- [Khái niệm Broken-Captcha](https://github.com/chi442000/broken-captcha#Concept)
- [Khai thác](https://github.com/chi442000/broken-captcha#exploit)
### Concept
Đây là lỗ hổng cho phép captcha có thể dùng lại được nhiều lần. Điều này là cực kì nguy hiểm khi kẻ tấn công có thể thực hiện tấn công Brute Force để dò mật khẩu.
### Exploit

![image](https://github.com/chi442000/Broken-Captcha/assets/84699930/9fda8014-9592-48ef-a2a6-afd34da12cf1)

Ta có thể thấy trong form đăng nhập trên có dùng captcha để xác thực. Nghi ngờ captcha này có thể dùng lại được nên ta thử dùng Intercept của burp suite để bắt Request và chuyển sang Intruder để giả lập cuộc tấn công Brute Force dò mật khẩu và dùng lại captcha. 
![image](https://github.com/chi442000/Broken-Captcha/assets/84699930/6dd228c4-896f-45a4-8dbd-e6d5ec45c90c)
![image](https://github.com/chi442000/Broken-Captcha/assets/84699930/180ed071-bc98-4aa1-8387-ad2da8173615)
![image](https://github.com/chi442000/Broken-Captcha/assets/84699930/066f7657-5927-4144-9833-9b9fa9456503)
![image](https://github.com/chi442000/Broken-Captcha/assets/84699930/77a98de5-ad87-4f47-94b5-6564922d748c)
Sau khi attack ta thấy Response thông báo Successful login!
![image](https://github.com/chi442000/Broken-Captcha/assets/84699930/648ee4ca-1479-4058-8f89-ba0f736c776b)





