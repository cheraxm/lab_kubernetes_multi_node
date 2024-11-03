# ใช้ base image ของ Apache HTTP Server
FROM httpd:latest

# คัดลอกไฟล์ HTML ของเว็บเพจไปยังโฟลเดอร์เริ่มต้นของ Apache
COPY ../webpublic-html/ /usr/local/apache2/htdocs/

# เปิดพอร์ต 3002 สำหรับ Apache HTTP Server
EXPOSE 3002
