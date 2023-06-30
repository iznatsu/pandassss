**<h1>DADS5001 Midterm Project: Insights ของอุตสาหกรรมเกม</h1>**

Midterm Project นี้ เริ่มมาจากความสนใจใน Data ของอุตสาหกรรมเกม ในระหว่างช่วงปี 1980 - 2016 ซึ่งเป็นช่วงที่อุตสาหกรรมเกมกำลังเกิดขึ้นและเติบโตอย่างก้าวกระโดด เพื่อหาสิ่งที่น่าสนใจที่เกิดขึ้น

โดยสมมติฐานหลังจากที่เห็นชุดข้อมูลนี้ เกิดขึ้นอย่างมากมาย ไม่ว่าจะเป็น
<li>แพลตฟอร์มใดเป็นที่นิยมสุด</li>
<li>ในแต่ละภูมิภาค มีฐานแฟนของเกมเหมือนกันหรือไม่</li>
<li>เกมแต่ละประเภทมีความนิยมแตกต่างกันหรือไม่</li>
<li>เกมไหนที่มียอดขายสูงที่สุด เพราะอะไร</li>
<li>เกมที่ถูกผลิตออกมาหลายภาค ภาคใดฮิตที่สุด</li>
<li>คะแนนจากผู้เล่นส่งผลต่อยอดขายมากน้อยเพียงใด</li>
เป็นต้น
<br>
<br>
รายละเอียดเกี่ยวกับชุดข้อมูลที่ใช้อ้างอิง: <a href="https://github.com/iznatsu/pandassss/blob/main/Appendix.md">คลิกที่นี่</a>

**<h1>สรุปภาพรวมของอุตสาหกรรมเกม</h1>**

Part นี้ จะเป็นการแสดงผลกราฟที่ได้ หลังนำข้อมูลมาหาความสัมพันธ์ในแต่ละด้าน ได้แก่ ยอดขาย จำนวนเกม ภูมิภาค แพลตฟอร์ม ประเภทเกม และคะแนนต่างๆ

**<div align="center"><h2>Fig 1: จำนวนเกมที่ถูกผลิตออกมาต่อปี</h2></div>**

จากกราฟ จะพบว่า ปีที่มีการขายเกมสูงที่สุดจะอยู่ในช่วง 2018 - 2019 ซึ่งยอดส่วนใหญ่มาจาก Platform ชื่อดังอย่าง Nintendo DS และ Nintendo Wii ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%201.png"></div>

**<div align="center"><h2>Fig 2: จำนวนเกมและยอดขาย แบ่งตามประเภทของเกม</h2></div>**

เมื่อเปรียบเทียบกันระหว่างจำนวนเกมและยอดขายรวม โดยแบ่งตามประเภทของเกม จะพบได้ว่า เกมประเภท Action มีจำนวนเกมและยอดขายสูงที่สุด ในขณะที่เกมประเภท Adventure มีจำนวนเกมปานกลาง แต่กลับได้ยอดขายต่ำ เนื่องจากเป็นเกมที่เกี่ยวข้องกับภาพยนตร์หรืออนิเมะ และเกมประเภท Shooter มีจำนวนเกมปานกลาง แต่กลับได้ยอดขายที่ดี จากการตีตลาดในฝั่งยุโรปและอเมริกาเหนือ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%202.png"></div>

**<div align="center"><h2>Fig 3: ประเภทของเกมที่ถูกผลิตออกมาในแต่ละปี</h2></div>**

จะเห็นได้ว่าเกมต่างๆค่อนข้างได้รับความนิยมเป็นอย่างมากตั้งแต่ช่วงปี 2005 - 2015 ซึ่งเป็นช่วงที่มีการแข่งขันกันและสร้างเกมข้ามกันระหว่าง 3 Platform ชื่อดังอย่าง Nintendo Wii, Playstation 3, และ Microsoft XBOX360

ประเภทของเกมที่ได้รับความนิยมสูงที่สุดคือ Action ซึ่งจะมีจุดพีคในปี 2009 เกมส่วนมากที่ผลิตออกมาจะเกี่ยวข้องกับภาพยนตร์ชื่อดังในช่วงนั้น อย่างเช่น Star Wars The Clone Wars และ Harry Potter and the Half-Blood Prince

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%203.png"></div>

**<div align="center"><h2>Fig 4: ยอดขายในแต่ละภูมิภาค</h2></div>**

อเมริกาได้รับยอดขายสูงที่สุด รองลงมาเป็นยุโรป ญี่ปุ่น และประเทศอื่นๆ ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%204.png"></div>

**<div align="center"><h2>Fig 5: การกระจายของยอดขายในแต่ละภูมิภาค</h2></div>**

จากกราฟแสดง distribution จะเห็นได้ว่า อเมริกาเหนือมียอดขายที่ได้เฉลี่ยเท่าๆกัน ทำให้มีการกระจายตัวที่ดี ในขณะที่ยุโรปมีเกมส่วนน้อยที่ได้ยอดขายค่อนข้างต่ำ แต่จะเห็นได้ว่า ยอดขายในญี่ปุ่นและภูมิภาคอื่นๆ มีหลายเกมที่ทำยอดขายได้ต่ำ ส่งผลให้กราฟเบ้ขวา (Right Skewed) อย่างชัดเจน

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%205.png"></div>

**<div align="center"><h2>Fig 6: ยอดขายทั่วโลกตามประเภทของเกม</h2></div>**

เมื่อแบ่งยอดขายตามประเภทเกม พบว่า Action ทำยอดขายได้สูงที่สุด รองลงมาเป็น Sports และ Shooter ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%206.png"></div>

**<div align="center"><h2>Fig 7: ยอดขายในแต่ละภูมิภาคตามประเภทของเกม</h2></div>**

โดยส่วนที่น่าสนใจ คือ เกมประเภท Action, Sports, และ Shooter สามารถสร้างยอดขายได้โดดเด่นในทุกๆภูมิภาค ยกเว้นในญี่ปุ่น ที่เกมประเภท Role-Playing หรือ RPG สร้างยอดขายได้สูงที่สุด โดยเกม Role-Playing จะถูกสร้างจากการ์ตูนชื่อดัง อย่าง Dragon Ball, Final Fantasy, หรือ Digimon

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%207.png"></div>

**<div align="center"><h2>Fig 8: จำนวนเกมที่วางขายในแต่ละแพลตฟอร์ม</h2></div>**

หากเปรียบเทียบกันระหว่าง Platform จะพบว่า Playstation 2 และ Nintendo DS นั้น มีจำนวนเกมที่สูงที่สุด 

<div align="center"><img height="300" src="https://github.com/iznatsu/pandassss/blob/picture/fig%208.png"></div>

**<div align="center"><h2>Fig 9: ยอดขายบนแต่ละแพลตฟอร์ม</h2></div>**

หากโฟกัสที่ยอดขาย Playstation 2, Microsoft XBOX360, และ Playstation 3 ได้รับยอดขายที่สูงเป็น 3 อันดับแรก ซึ่งสร้างตลาดในยุโรปและอเมริกาเหนือได้เป็นอย่างดี ในขณะที่ Nintendo DS หรือ Nintendo 3DS นั้น สร้างยอดขายในญี่ปุ่นได้ดีกว่าอย่างมีนัยยะสำคัญ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%209.png"></div>

**<div align="center"><h2>Fig 10: Top 3 ผู้ผลิตเครื่องเกม</h2></div>**

โดยหากนำบริษัทผู้ผลิตอย่าง Sony (Playstation), Nintendo (Wii & DS), และ Microsoft (XBOX) มาเปรียบเทียบกัน จะพบว่า Platform ที่มาจากญี่ปุ่นอย่าง Nintendo และ Sony มียอดขายในญี่ปุ่นสูงกว่า Microsoft อย่างชัดเจน ซึ่ง Microsoft มียอดขายในอเมริกาเหนือเป็นส่วนใหญ่

<div align="center"><img height="300" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2010.png"></div>

**<div align="center"><h2>Fig 11: ยอดขายเกมแต่ละประเภท จาก Top 3 ผู้ผลิต</h2></div>**

Sony ครองตลาดเกม Action กับ Sports อย่างเห็นได้ชัด ในขณะที่ Nintendo ครองตลาดเกม Platform กับ Misc และ Microsoft มีส่วนแบ่งการตลาดจากเกม Shooter กับ Action เป็นหลัก

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2011.png"></div>

**<div align="center"><h2>Fig 12: ยอดขายบนแต่ละแพลตฟอร์มในแต่ละภูมิภาค</h2></div>**

อเมริกาเหนือได้ยอดขายสูงสุดจาก Microsoft XBOX360 และ Playstation 2 ในขณะที่ญี่ปุ่นได้ยอดขายสูงสุดจาก Nintendo DS และ Playstation  ส่วนภาพรวมของตลาดฝั่งยุโรปและภูมิภาคอื่นๆ ค่อนข้างใกล้เคียงกัน โดยได้ยอดขายสูงสุดจาก Playstation 2 และ Playstation 3 ตามลำดับ

<div align="center"><img height="400" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2012.png"></div>

**<div align="center"><h2>Fig 13: Top 20 เกมที่มียอดขายสูงสุด</h2></div>**

เกมที่ได้รับยอดขายสูงที่สุด คือ Wii Sports ซึ่งถูกวางขายพร้อมกับเครื่องเล่นเกม Nintendo Wii ที่มีจอยคอนโซลต่างกับเกมอื่นๆในขณะนั้น เหมาะกับการเล่นเกมที่ช่วยในการออกกำลังกาย ทำให้เกิดความนิยมสูงในอเมริกาเหนือ ยุโรป และภูมิภาคอื่นๆ

ในขณะที่ฝั่งญี่ปุ่น เกมที่ได้รับยอดขายที่สูงที่สุด คือ Pokemon Red & Blue

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2013.png"></div>

**<div align="center"><h2>Fig 14: Pokemon Insights</h2></div>**

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ Red/Blue, Gold/Silver, และ Diamond/Pearl ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform Nintendo DS

<div align="center"><img height="800" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2014.png"></div>

**<div align="center"><h2>Fig 15: Final Fantasy Insights</h2></div>**

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ VII, X, และ VIII ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform Playstation ไม่ว่าจะเป็น Playstation 2, PSP, และ Playstation

โดยภาคที่ถูกจัดจำหน่ายบ่อยที่สุด จะเป็นภาคแรกๆที่ยังคงเล่นบน Platform รุ่นเก่า ซึ่งจะมีการขายพร้อมกันในหลาย Platform อย่าง Playstation, SNES, และ NES

<div align="center"><img height="800" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2015.png"></div>

**<div align="center"><h2>Fig 16: Mario Insights</h2></div>**

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ Super Mario Bros., Mario Kart Wii, และ New Super Mario Bros. ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform Nintendo 3DS, Gameboy Advance, และ Wii
ยอดขายที่ได้รับส่วนใหญ่มาจากเกม Mario ที่เป็นแนวตะลุยด่าน ในขณะที่ความหลากหลายในการจัดจำหน่ายบน Platform จะเป็นเกมกีฬามากกว่า เช่น Mario Tennis และ Olympic Games

<div align="center"><img height="800" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2016.png"></div>

**<div align="center"><h2>Fig 17: Call of Duty Insights</h2></div>**

ภาคที่ได้รับความนิยมสุด 3 อันดับแรก คือ Black Ops, Modern Warfare 3 และ Black Ops II ตามลำดับ ส่วนใหญ่จะถูกขายบน Platform XBOX360, PC, และ Playstation 3 มากที่สุด ซึ่งจะเป็น Platform ในฝั่งอเมริกาเป็นส่วนใหญ่

ภาคที่ถูกขายลงบนหลากหลาย Platform มากที่สุดอย่าง Ghosts และ World at War จะอยู่ในช่วงที่อุตสาหกรรมเกมมีการแข่งขันกัน ระหว่างเกมบน PC และ Platform ชั้นนำอย่าง XBOX360, Wii, และ Playstation 3

<div align="center"><img height="800" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2017.png"></div>

**<div align="center"><h2>Fig 18: User Score VS Critic Score</h2></div>**

สิ่งที่น่าสนใจ คือ Critic Score จะมีคะแนนที่เป็น Minimum Outlier ที่น้อยกว่า User Score อย่างเห็นได้ชัด เนื่องจากเป็นคะแนนจากการวิจารณ์โดยผู้เชี่ยวชาญ ซึ่งอาจจะมีการวิเคราะห์โดยใช้หลักการมากกว่าการให้คะแนนจาก User

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2018.png"></div>

**<div align="center"><h2>Fig 19: Critic VS User Score ตามประเภทของเกม</h2></div>**

เมื่อดูจาก Boxplot ของฝั่ง User Score จะเห็นได้ว่า เกมประเภท Role-Playing ได้คะแนน User Score ที่เฉลี่ยค่อนข้างสูง ซึ่งส่วนมากเกมประเภท Role-Playing จะผูกเรื่องราวกับตัวละครที่เป็นที่รู้จัก เช่น Final Fantasy, Monster Hunter, Star Wars, X-Men เป็นต้น

ในฝั่งของ Critic Score จะพบว่าเกมประเภท Role-Playing มีคะแนนเฉลี่ยต่ำลงมา แต่ยังคงมีคะแนนเฉลี่ยที่สูงกว่าเกมประเภทอื่นๆ

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2019.png"></div>

**<div align="center"><h2>Fig 20: Critic VS User Score บนแต่ละแพลตฟอร์ม</h2></div>**

Platform เก่าอย่าง DC (Dreamcast) ได้รับคะแนนที่ค่อนข้างสูง เนื่องจากเกมที่ถูกผลิตในช่วงนั้นยังไม่มีหลากหลายมากนั้น ในขณะที่ Platform อื่นๆ มีการให้คะแนนจาก Critic ที่เกาะกลุ่มมากกว่า User เนื่องจากเป็นช่วงที่อุตสาหกรรมเกมและเครื่องเล่นเกมมีการแข่งขันสูงขึ้น

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2020.png"></div>

**<div align="center"><h2>Fig 21: ความสัมพันธ์ระหว่างยอดขายและ User Score</h2></div>**

จาก Trendline และกราฟ พบว่า เกมที่ได้รับ User Score ที่ดี มีแนวโน้มที่จะได้รับยอดขายที่สูงด้วยเช่นกัน

<div align="center"><img height="500" src="https://github.com/iznatsu/pandassss/blob/picture/fig%2021.png"></div>

