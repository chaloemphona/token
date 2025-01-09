ตัวที่ชื่อ index.html(Map) จำเป็นต้องเเก้ไข TOKEN ตลอด 60 นาที

ก่อนจะทำอะไร ต้องเเก้ไข Base_URL ก่อน

ทำการเปิด ngrok.exe จากนั้นพิม token ของ ngrok ที่ได้จากหน้า setup & install
รัน ngrok http 8000 จะได้ URL ที่ ngrok ทำให้มาใช้งาน ตัวอย่าง https://.....ngrok-free.app
เอา URL ที่ได้ไปเเก้ไขใน index.html(Map) index.html(Token) ในส่วนของ const BASE_URL = "URL";
ทำการรัน uvicorn main:app --reload ใน vs code terminal

ส่วนวิธีหาโทเค็น

ให้ไปที่ https://token-1ziv.onrender.com
ทำการใส่ชื่อ เเล้วคลิก"ส่งคำขอ"
จากนั้นจะได้ Token ให้ทำการ copy Token มา
นำ Token ที่ได้ไปเเก้ไข Token ใน index.html(Map) ในส่วนของ const token = "Token";
save and run
Code Token https://github.com/chaloemphona/token.git Depkoy Token https://token-1ziv.onrender.com

Code Map https://github.com/chaloemphona/map_parge.git Deploy Map https://map-2t04.onrender.com
