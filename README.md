วิธีการสร้าง model ทำนาย power ในด้านต่อไป
1. import library ที่จำเป็น
2. อ่าน data จาก file csv
3. ทำ data cleansing โดยการ
     3.1 อ่านจำนวน null space เพื่อดูว่ามี null space กี่ช่องในแต่ละ column
     3.2 ใช้คำสั่ง dropna() เพื่อลบ null space และ drop_duplicates() เพื่อลบแถวที่ซ้ำกัน
4. นำ data มา plot เพื่อดู trend ของ power เทียบกับ temperarue และ humidity
5. สร้าง model ทำนาย โดย assume ว่า power เป็น function เชิงเส้นกับ temperarue และ humidity ทำการสุ่มชุด train มาโดยใช้ train_test_split โดยอัตราส่วน train : test = 30 :70 แล้วใช้คำสั่ง reg.fit() และ ใช้ reg.score() ในการประเมิน model

หมายเหตุ เนื่องจากยังไม่มีความรู้มากพอในการทำ project ด้านนี้ หากเป็นไปได้ก็อยากจะลองหาโอกาสที่จได้ศึกษาเพิ่มเติม แต่ยังไม่สามารถเข้าร่วมกับโครงการได้ ก็ไม่เป็นไรนะครับ(พี่ๆ จะได้ไม่ลำบากใจ) แล้วก็ขอบคุณที่ได้ลองให้โอกาสมาทำครับ ^^
