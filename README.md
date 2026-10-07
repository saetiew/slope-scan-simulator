# Slope Scan Simulator

**เปิดใช้งาน:** https://saetiew.github.io/slope-scan-simulator/

**แบบมี beam steering:** ติ๊ก "มี beam steering" ที่แผงปรับค่า (กระจก M1, M2 หักแสง 90° สองครั้งก่อนเข้า beam splitter) หรือเปิด https://saetiew.github.io/slope-scan-simulator/?steering=1 (ลิงก์ steering.html เดิมจะพามาที่นี่)

หน้าเว็บจำลองการวัด slope ของกระจกด้วย autocollimator + pentaprism สแกน (แบบเลนส์อยู่หน้า CMOS)

- ลำแสงแบบเหมือนจริง: ความเข้มแบบ Gaussian สีตามความยาวคลื่น และแสงที่ BS แยกออก (เลือกกลับเป็นเส้นแผนภาพได้)
- ปรับโปรไฟล์ slope ของกระจก ตำแหน่ง/มุมเอียงของ pentaprism ค่า f และระยะต่างๆ แล้วดูเส้นแสงกับจุดบน CMOS ได้ทันที
- กดสแกนทั้งกระจก ดูกราฟ slope, ความสูงผิว และ slope error
- ภาพหน้า CMOS พร้อมแว่นขยายตำแหน่ง centroid
- หาระยะ d บน sensor ระหว่างจุดของ 2 ตำแหน่ง: d ≈ 2f(θB − θA)

สมการหลัก: Δ = f·tan(2θ) ≈ 2fθ

แบบจำลอง 2 มิติในระนาบแสง คิดการสะท้อนในปริซึม ไม่คิดการหักเห เลนส์เป็นเลนส์บาง

เปิดใช้งานออนไลน์ที่ https://saetiew.github.io/slope-scan-simulator/ หรือดาวน์โหลด `index.html` มาเปิดในเบราว์เซอร์
