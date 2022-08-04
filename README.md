راه اندازی سرور فیلترشکن شخصی

لینک ویدیو آموزشی: 

ساخت یک سرور با سیستم عامل: Centos 7 x86_64

لاگین کردن به سرور با نرم افزار putty و اجرای دستور زیر:

cd /tmp/ && yum install git -y && git clone https://github.com/AlefbeMedia/Personal-vpn.git && cd OPEN-VPN-ACCESS-SERVER/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh 

دستورات زیر برای اضافه کردن کاربر به سرور:

useradd yourusername
passwd yourpassword

با لایک و کامنت این ویدیو از ما حمایت کنید
