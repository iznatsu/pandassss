
# DADS5001 Midterm Project: Insights ของอุตสาหกรรมเกม

Midterm Project นี้ เริ่มมาจากความสนใจใน Data ของอุตสาหกรรมเกม ในระหว่างช่วงปี 1980 - 2019 ซึ่งเป็นช่วงที่อุตสาหกรรมเกมกำลังเกิดขึ้นและเติบโตอย่างก้าวกระโดด เพื่อหาสิ่งที่น่าสนใจที่เกิดขึ้น

โดยสมมติฐานหลังจากที่เห็นชุดข้อมูลนี้ เกิดขึ้นอย่างมากมาย ไม่ว่าจะเป็น
- แพลตฟอร์มใดเป็นที่นิยมสุด
- ในแต่ละภูมิภาค มีฐานแฟนของเกมเหมือนกันหรือไม่
- เกมแต่ละประเภทมีความนิยมแตกต่างกันหรือไม่
- เกมไหนที่มียอดขายสูงที่สุด เพราะอะไร
- เกมที่ถูกผลิตออกมาหลายภาค ภาคใดฮิตที่สุด
- คะแนนจากผู้เล่นส่งผลต่อยอดขายมากน้อยเพียงใด
เป็นต้น
<br>
รายละเอียดเกี่ยวกับชุดข้อมูลที่ใช้อ้างอิง: <a href="https://github.com/iznatsu/pandassss/blob/main/Appendix.md">คลิกที่นี่</a>

<details>
  
<summary> <h2> 1. ภาพรวมของอุตสาหกรรมเกม</h2> </summary>

### 1.1 จำนวนเกมที่ถูกผลิตออกมาต่อปี (Fig 1)

  จากกราฟ จะพบว่า ปีที่มีการขายเกมสูงที่สุดจะอยู่ในช่วง 2008 - 2009 ซึ่งยอดส่วนใหญ่มาจาก Platform ชื่อดังอย่าง Nintendo DS และ Nintendo Wii ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%201.png"></div>

### 1.2 จำนวนเกมและยอดขาย แบ่งตามประเภทของเกม (Fig 2)

เมื่อเปรียบเทียบกันระหว่างจำนวนเกมและยอดขายรวม โดยแบ่งตามประเภทของเกม จะพบได้ว่า เกมประเภท Action มีจำนวนเกมและยอดขายสูงที่สุด ในขณะที่เกมประเภท Adventure มีจำนวนเกมปานกลาง แต่กลับได้ยอดขายต่ำ เนื่องจากเป็นเกมที่เกี่ยวข้องกับภาพยนตร์หรืออนิเมะ และเกมประเภท Shooter มีจำนวนเกมปานกลาง แต่กลับได้ยอดขายที่ดี จากการตีตลาดในฝั่งยุโรปและอเมริกาเหนือ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%202.png"></div>

### 1.3 ประเภทของเกมที่ถูกผลิตออกมาในแต่ละปี (Fig 3)

จะเห็นได้ว่าเกมต่างๆค่อนข้างได้รับความนิยมเป็นอย่างมากตั้งแต่ช่วงปี 2005 - 2015 ซึ่งเป็นช่วงที่มีการแข่งขันกันและสร้างเกมข้ามกันระหว่าง 3 Platform ชื่อดังอย่าง Nintendo Wii, Playstation 3, และ Microsoft XBOX360

ประเภทของเกมที่ได้รับความนิยมสูงที่สุดคือ Action ซึ่งจะมีจุดพีคในปี 2009 เกมส่วนมากที่ผลิตออกมาจะเกี่ยวข้องกับภาพยนตร์ชื่อดังในช่วงนั้น อย่างเช่น Star Wars The Clone Wars และ Harry Potter and the Half-Blood Prince

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%203.png"></div>

</details>

<details>

<summary> <h2> 2. การวิเคราะห์ยอดขาย</h2> </summary>

### 2.1 ยอดขายในแต่ละภูมิภาค (Fig 4)

อเมริกาได้รับยอดขายสูงที่สุด รองลงมาเป็นยุโรป ญี่ปุ่น และประเทศอื่นๆ ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%204.png"></div>

### 2.2 การกระจายของยอดขายในแต่ละภูมิภาค (Fig 5)

จากกราฟแสดง distribution จะเห็นได้ว่า อเมริกาเหนือมียอดขายที่ได้เฉลี่ยเท่าๆกัน ทำให้มีการกระจายตัวที่ดี ในขณะที่ยุโรปมีเกมส่วนน้อยที่ได้ยอดขายค่อนข้างต่ำ แต่จะเห็นได้ว่า ยอดขายในญี่ปุ่นและภูมิภาคอื่นๆ มีหลายเกมที่ทำยอดขายได้ต่ำ ส่งผลให้กราฟเบ้ขวา (positive skewness) อย่างชัดเจน

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%205.png"></div>

### 2.3 ยอดขายทั่วโลกตามประเภทของเกม (Fig 6)

เมื่อแบ่งยอดขายตามประเภทเกม พบว่า Action ทำยอดขายได้สูงที่สุด รองลงมาเป็น Sports และ Shooter ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%206.png"></div>

### 2.4 ยอดขายในแต่ละภูมิภาคตามประเภทของเกม (Fig 7)

โดยส่วนที่น่าสนใจ คือ เกมประเภท Action, Sports, และ Shooter สามารถสร้างยอดขายได้โดดเด่นในทุกๆภูมิภาค ยกเว้นในญี่ปุ่น ที่เกมประเภท Role-Playing หรือ RPG สร้างยอดขายได้สูงที่สุด โดยเกม Role-Playing จะถูกสร้างจากการ์ตูนชื่อดัง อย่าง Dragon Ball, Final Fantasy, หรือ Digimon

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%207.png"></div>

</details>

<details>

<summary> <h2> 3. เครื่องเล่นเกม และ ผู้ผลิต </h2> </summary>

### 3.1 จำนวนเกมที่วางขายในแต่ละแพลตฟอร์ม (Fig 8)

หากเปรียบเทียบกันระหว่าง Platform จะพบว่า Playstation 2 และ Nintendo DS นั้น มีจำนวนเกมที่สูงที่สุด 

<div align="center"><img height="300" src="https://github.com/iznatsu/pandassss/blob/picture/fig%208.png"></div>

### 3.2 ยอดขายบนแต่ละแพลตฟอร์ม (Fig 9)

หากโฟกัสที่ยอดขาย Playstation 2, Microsoft XBOX360, และ Playstation 3 ได้รับยอดขายที่สูงเป็น 3 อันดับแรก ซึ่งสร้างตลาดในยุโรปและอเมริกาเหนือได้เป็นอย่างดี ในขณะที่ Nintendo DS หรือ Nintendo 3DS นั้น สร้างยอดขายในญี่ปุ่นได้ดีกว่าอย่างมีนัยยะสำคัญ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%209.png"></div>

### 3.3 Top 3 ผู้ผลิตเครื่องเกม (Fig 10)

โดยหากนำบริษัทผู้ผลิตอย่าง Sony (Playstation), Nintendo (Wii & DS), และ Microsoft (XBOX) มาเปรียบเทียบกัน จะพบว่า Platform ที่มาจากญี่ปุ่นอย่าง Nintendo และ Sony มียอดขายในญี่ปุ่นสูงกว่า Microsoft อย่างชัดเจน ซึ่ง Microsoft มียอดขายในอเมริกาเหนือเป็นส่วนใหญ่

<div align="center"><img height="300" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2010.png"></div>

### 3.4 ยอดขายเกมแต่ละประเภท จาก Top 3 ผู้ผลิต (Fig 11)

Sony ครองตลาดเกม Action กับ Sports อย่างเห็นได้ชัด ในขณะที่ Nintendo ครองตลาดเกม Platform กับ Misc และ Microsoft มีส่วนแบ่งการตลาดจากเกม Shooter กับ Action เป็นหลัก

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2011.png"></div>

### 3.5 ยอดขายบนแต่ละแพลตฟอร์มในแต่ละภูมิภาค (Fig 12)

อเมริกาเหนือได้ยอดขายสูงสุดจาก Microsoft XBOX360 และ Playstation 2 ในขณะที่ญี่ปุ่นได้ยอดขายสูงสุดจาก Nintendo DS และ Playstation ส่วนภาพรวมของตลาดฝั่งยุโรปและภูมิภาคอื่นๆ ค่อนข้างใกล้เคียงกัน โดยได้ยอดขายสูงสุดจาก Playstation 2 และ Playstation 3 ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2012.png"></div>

</details>

<details>

<summary> <h2> 4. เกมที่น่าจับตามอง </h2> </summary>

### 4.1 Top 20 เกมที่มียอดขายสูงสุด (Fig 13)

เกมที่ได้รับยอดขายสูงที่สุด คือ Wii Sports ซึ่งถูกวางขายพร้อมกับเครื่องเล่นเกม Nintendo Wii ที่มีจอยคอนโซลต่างกับเกมอื่นๆในขณะนั้น เหมาะกับการเล่นเกมที่ช่วยในการออกกำลังกาย ทำให้เกิดความนิยมสูงในอเมริกาเหนือ ยุโรป และภูมิภาคอื่นๆ

ในขณะที่ฝั่งญี่ปุ่น เกมที่ได้รับยอดขายที่สูงที่สุด คือ Pokemon Red & Blue

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2013.png"></div>

### 4.2 Pokemon Insights (Fig 14)

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ Red/Blue, Gold/Silver, และ Diamond/Pearl ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform Nintendo DS

<div align="center"><img src="https://github.com/iznatsu/pandassss/blob/picture/fig%2014.png"></div>

### 4.3 Final Fantasy Insights (Fig 15)

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ VII, X, และ VIII ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform Playstation ไม่ว่าจะเป็น Playstation 2, PSP, และ Playstation

โดยภาคที่ถูกจัดจำหน่ายบ่อยที่สุด จะเป็นภาคแรกๆที่ยังคงเล่นบน Platform รุ่นเก่า ซึ่งจะมีการขายพร้อมกันในหลาย Platform อย่าง Playstation, SNES, และ NES

<div align="center"><img src="https://github.com/iznatsu/pandassss/blob/picture/fig%2015.png"></div>

### 4.4 Mario Insights (Fig 16)

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ Super Mario Bros., Mario Kart Wii, และ New Super Mario Bros. ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform Nintendo 3DS, Gameboy Advance, และ Wii
ยอดขายที่ได้รับส่วนใหญ่มาจากเกม Mario ที่เป็นแนวตะลุยด่าน ในขณะที่ความหลากหลายในการจัดจำหน่ายบนแพลตฟอร์มจะเป็นเกมกีฬามากกว่า เช่น Mario Tennis และ Olympic Games

<div align="center"><img src="https://github.com/iznatsu/pandassss/blob/picture/fig%2016.png"></div>

### 4.5 Call of Duty Insights (Fig 17)

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ Black Ops, Modern Warfare 3 และ Black Ops II ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform XBOX360, PC, และ Playstation 3 มากที่สุด ซึ่งจะเป็น Platform ในฝั่งอเมริกาเป็นส่วนใหญ่

ภาคที่ถูกขายลงบนหลากหลาย Platform มากที่สุดอย่าง Ghosts และ World at War จะอยู่ในช่วงที่อุตสาหกรรมเกมมีการแข่งขันกัน ระหว่างเกมบน PC และ Platform ชั้นนำอย่าง XBOX360, Wii, และ Playstation 3

<div align="center"><img src="https://github.com/iznatsu/pandassss/blob/picture/fig%2017.png"></div>

</details>

<details>

<summary> <h2> 5. คะแนนจากผู้เล่น และนักวิจารณ์ </h2> </summary>

### 5.1 User Score VS Critic Score (Fig 18)

สิ่งที่น่าสนใจ คือ Critic Score จะมีคะแนนที่เป็น Minimum Outlier ที่น้อยกว่า User Score อย่างเห็นได้ชัด เนื่องจากเป็นคะแนนจากการวิจารณ์โดยผู้เชี่ยวชาญ ซึ่งอาจจะมีการวิเคราะห์โดยใช้หลักการมากกว่าการให้คะแนนจาก User

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2018.png"></div>

### 5.2 Critic VS User Score ตามประเภทของเกม (Fig 19)

เมื่อดูจาก Boxplot ของฝั่ง User Score จะเห็นได้ว่า เกมประเภท Role-Playing ได้คะแนน User Score ที่เฉลี่ยค่อนข้างสูง ซึ่งส่วนมากเกมประเภท Role-Playing จะผูกเรื่องราวกับตัวละครที่เป็นที่รู้จัก เช่น Final Fantasy, Monster Hunter, Star Wars, X-Men เป็นต้น

ในฝั่งของ Critic Score จะพบว่าเกมประเภท Role-Playing มีคะแนนเฉลี่ยต่ำลงมา แต่ยังคงมีคะแนนเฉลี่ยที่สูงกว่าเกมประเภทอื่นๆ

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2019.png"></div>

### 5.3 Critic VS User Score บนแต่ละแพลตฟอร์ม (Fig 20)

Platform เก่าอย่าง DC (Dreamcast) ได้รับคะแนนที่ค่อนข้างสูง เนื่องจากเกมที่ถูกผลิตในช่วงนั้นยังไม่มีหลากหลายมากนั้น ในขณะที่ Platform อื่นๆ มีการให้คะแนนจาก Critic ที่เกาะกลุ่มมากกว่า User เนื่องจากเป็นช่วงที่อุตสาหกรรมเกมและเครื่องเล่นเกมมีการแข่งขันสูงขึ้น

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2020.png"></div>

### 5.4 ความสัมพันธ์ระหว่างยอดขายและ User Score (Fig 21)

จาก Trendline และกราฟ พบว่า เกมที่ได้รับ User Score ที่ดี มีแนวโน้มที่จะได้รับยอดขายที่สูงด้วยเช่นกัน

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2021.png"></div>

</details>

**<div align="center"><h2> สรุป </h2></div>**
### ช่วงปีทองของอุตสาหกรรมเกม คือ 2005 - 2015 ซึ่งเป็นช่วงมีการผลิตเกมสู่แพลตฟอร์มชื่อดังกันอย่างแพร่หลาย โดยเกม Action นั้นได้รับความนิยมสูงที่สุด
### เกมประเภท Action มียอดขายสูงสุด ตามมาด้วย Sport และ Shooter ยกเว้นในญี่ปุ่น ที่เกมประเภท Role-Playing หรือ RPG กลับได้รับกระแสสูงสุด จากกระแส pop culture อย่างอนิเมะ
### ในขณะที่ Playstation 2 และ Playstation 3 ได้รับความนิยมจากทั่วทุกภูมิภาค แต่ Microsoft XBOX360 กลับสร้างตลาดได้เพียงในอเมริกาเหนือ และในญี่ปุ่นกลับกลายเป็น Nintendo DS ที่มีเกมผลิตออกมาให้เล่นกันอย่างแพร่หลาย เนื่องจากเป็นแพลตฟอร์มที่ถูกผลิตโดยญี่ปุ่น
### ผู้คนให้ความสนใจกับประสบการณ์การเล่นเกมใหม่ๆในยุคสมัยนั้น โดยเฉพาะ Nintendo Wii ที่มีเกม Wii Sports ซึ่งได้รับความนิยมสูง ในขณะเดียวกัน เกมชื่อดังหลายๆเกม ก็มักจะผลิตเกมออกมาขายบนหลายแพลตฟอร์มในเวลาเดียวกัน ทำให้เข้าถึงผู้เล่นได้หลากหลายมากขึ้น
### คะแนนจากนักวิจารณ์และผู้เล่น มีผลต่อยอดขายโดยตรง ซึ่งหากได้รับคะแนนที่ดี ยอดขายก็มีโอกาสที่จะสูงตามไปด้วย
