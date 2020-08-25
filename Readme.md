# Billboard Hot 100 EDA Practice
โปรเจคนี้เป็นการฝึกการทำ Exploratory data analysis โดยใช้ข้อมูลจาก Billboard Hot 100 ที่เป็นชาร์จเพลงที่อยู่ในช่วง  8/2/1958 ถึง 12/28/2019

ลิงก์ข้อมูล:
https://data.world/kcmillersean/billboard-hot-100-1958-2017

## รายละเอียดของข้อมูล
- Billboard Chart URL (ลิ้งของชาร์จเพลง Billboard Hot 100 ในแต่ละสัปดาห์)
- WeekID (วัน/เดือน/ปี) ของชาร์จที่จัด
- Song name ชื่อเพลง
- Performer name ชื่อนักดนตรี
- SongID - Concatenation of song & performer (ชื่อเพลงและนักดนตรีรวมกัน)
- Current week on chart ตำแหน่งประจำสัปดาห์
- Instance (this is used to separate breaks on the chart for a given song. Example, an instance of 6 tells you that this is   the sixth time this song has appeared on the chart) จำนวนครั้งที่เข้ามาในชาร์จ
- Previous week position ตำแหน่งในสัปดาห์ที่แล้ว
- Peak Position (as of the corresponding week) ตำแหน่งสูงสุดที่ทำได้
- Weeks on Chart (as of the corresponding week) จำนวนสัปดาห์ที่อยู่ในชาร์จ

## คำถามที่ตั้งไว้
1. 10 เพลงที่ติดชาร์จนานที่สุดใน Billboard Hot 100
2. 10 นักร้องที่มีเพลงติดในชาร์จมากที่สุดใน Billboard Hot 100
3. เพลงที่สามารถทำอันดับ 1 ภายในสัปดาห์แรกเมื่อติดชาร์จของ Billboard Hot 100
4. เพลงที่ทำกลับมาติดชาร์จมากที่สุด
