
# CT519-AOM
การออกแบบฐานข้อมูล
และหลักการออกแบบweb ออกแบบเป็น single page application
ใช้ MogoDB สร้าง database my contact and create my contact สามารถ Add and Delete (ชื่อ-เบอร์โทร)
การอธิบายส่วนของ code ที่สำคัญ
จะเป็นด้านการทำระบบหลังบ้าน
โดยเว็บจะมี 1 หน้า ใช้ NodeJs เป็นหลังบ้าน หน้าบ้านเป็น React แบ่งเป็น Front end และ backand และ Database แยก container กัน


การเตรียมการระบบ Cloud
เป็นการใช้ ec2 โดยใช้ instance type t2micro , Architecture x86
ในการทำ และ install docker environment รวมถึง git เพืื่อ clone data มาเพื่อ deploy


การ deploy ตัว code มาทำงาน
1.สร้างเว็บและ sql ให้เรียบร้อย พร้อมทั้ง dockerfile และ docker-compose.yaml
2.เตรียม git ให้พร้อม
3.สร้าง repositories CT519-AOM
4.อัพโหลด 1 ขึ้น repositories CT519-AOM
5.ใน Aws install docker engine ให้เรียบร้อย
6.ใน Aws install docker compose ให้เรียบร้อย
7.ใน command line git clone https://github.com/omletteey/CT519-AOM/new/main?readme=1
8.cd CT519-AOM
9.chmod -R 777 all file and folder
10.docker-compose up --build
