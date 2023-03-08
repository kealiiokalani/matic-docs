---
id: avail-consensus
title: ฉันทามติ Avail
sidebar_label: Consensus
description: เรียนรู้ เกี่ยวกับ กลไก ฉันทามติ ของ Avail
keywords:
  - docs
  - polygon
  - avail
  - consensus
  - proof of stake
  - nominated proof of stake
  - pos
  - npos
image: https://wiki.polygon.technology/img/thumbnail/polygon-avail.png
slug: avail-consensus
---

# ฉันทามติ Avail {#avail-s-consensus}

## Data availability committees {#data-availability-committees}

จนถึงปัจจุบัน วิธีการในการรักษาวูปรูป DA โดยทั่วไปจะได้รับผ่าน คณะกรรมการพร้อมใช้งานของข้อมูล)DAC มีหน้าที่ในการส่งลายเซ็นกลับไปยังเชนหลักและตรวจสอบความพร้อมของข้อมูลออฟไลน์ ระบบ DAC จะต้องตรวจสอบให้แน่ใจว่าข้อมูลพร้อมใช้งาน

ผ่าน การใช้ DAC โซลูชัน ในส่วน การปรับขนาด ใช้ DAC เพื่อ ถึง Validium ปัญหาสำหรับ DACs คือการใช้งานของข้อมูลจะกลายเป็นบริการที่เชื่อถือได้สำหรับสมาชิกคณะกรรมการขนาดเล็กที่รับผิดชอบในการจัดเก็บข้อมูลการรายงานและรายงานอย่างแท้จริง

Avail ไม่ใช่ DAC, แต่เครือข่ายบล็อกที่แท้จริงพร้อมกลไกการยอมรับของตัวเอง และมีโหนดและผู้สร้างบล็อกตัวตรวจสอบความถูกต้องของตัวเอง

## Proof of Stake {#proof-of-stake}

:::caution ผู้ตรวจสอบ ปัจจุบัน

ใน การเปิดใช้งาน ครั้งแรก ของ Testnet avail ผู้ตรวจสอบ จะถูก
ดำเนินการ จากภายใน และ รับการรักษา จาก Polygon

:::

การพิสูจน์อักษรแบบดั้งเดิมของระบบเดิมพันต้องใช้ผู้เขียนผู้สร้างบล็อกที่ต้องมีการฝากข้อความเพื่อรอรับสาย (ส่วน) บนโซ่เพื่อสร้างบล็อกโดยตรงข้ามกับทรัพยากรการคำนวณทั่วไป (ทำงาน)

ผลิตภัณฑ์ ของ Polygon ใช้ PoS (หลักฐานการเดิมพัน) หรือการปรับแต่งของ PoSโดยทั่วไปตัวตรวจสอบความถูกต้องในระบบ PoS ดั้งเดิมที่มีเดิมพันมากที่สุดมีอิทธิพลและการควบคุมของเครือข่าย

ระบบที่มีผู้ดูแลเครือข่ายหลายคนมีแนวโน้มที่จะสร้างอึแบบออฟห่วงโซ่เพื่อเพิ่มรายได้สูงสุด โดยการลดตัวแปรการจ่ายด้วยการท้าทายการรวมรวมกลุ่มนี้จะช่วยบรรเทาปัญหาเมื่อรวมอึบนโซ่ซึ่งช่วยให้ผู้ถือโทเค็นไปยังผู้ดูแลเครือข่ายที่พวกเขารู้สึกดีที่สุดเป็นตัวแทนและผลประโยชน์ของเครือข่ายนอกจากนี้ ยังจัดเตรียมความเข้มข้นของตัวตรวจสอบความถูกต้อง โดยสมมติว่ากลไกการโหวตและกลไกการเลือกตั้งที่ถูกต้องจะอยู่ในตำแหน่ง เนื่องจากเดิมพันโดยรวมบนเครือข่ายจะถูกจัดสรรเป็นความสัมพันธ์แบบหนึ่งต่อหลายต่อหรือหลายต่อหลายอย่างแทนที่จะพึ่งพาความสัมพันธ์แบบตัวต่อตัวเดียวเท่านั้น ซึ่งมีการตั้งค่าความไว้วางใจไว้ในตัวตรวจสอบความถูกต้องที่ฝังแน่นสูงสุด"

การดัดแปลงหลักฐานของเดิมพันนี้สามารถบริหารโดยคณะผู้แทนหรือการเสนอชื่อ โดยทั่วไปจะเรียกว่า DPoS (การเตรียมตัว) หรือ NPoS (การเสนอตัวหลักฐานการเดิมพัน)โซลูชั่นการเลื่อนของ Polygon ได้ปรับเปลี่ยนกลไกแบบปรับปรุงนี้ รวมถึง ที่ใช้ Polygon

avail ใช้ npos พร้อมกับ การปรับปรุง การตรวจสอบความถูกต้องของ บล็อก ตัวแสดงที่เกี่ยวข้องยังคงเป็นตัวตรวจสอบความถูกต้องและตัวตรวจสอบความถูกต้องต่อไป

ลูกค้า ประเภท Light ยัง มีส่วนร่วม ใน การให้มี ความพร้อม ของ ข้อมูล ใน avail ฉันทามติของพร้อมใช้ว่า สองในสามและอีก 1 ตัวของตัวตรวจสอบความถูกต้องถึงข้อกำหนดสำหรับความถูกต้อง

## ผู้แต่งตั้ง {#nominators}

ตัวสร้างสรรค์สามารถเลือกที่จะส่งคืนชุดตัวตรวจสอบความถูกต้องของผู้สมัคร Avail ด้วยเดิมพันของพวกเขาตัวสร้างสรรค์จะเสนอชื่อตัวตรวจสอบความถูกต้องที่พวกเขารู้สึกว่าจะให้บริการของข้อมูลได้อย่างมีประสิทธิภาพ

## ความแตกต่างระหว่าง DPoS และ NPoS {#difference-between-dpos-and-npos}

โดยค่าหน้า คณะผู้แทนและการเสนอชื่อดูเหมือนการกระทำเดียวกันโดยเฉพาะอย่างยิ่งจากมุมมองของผู้สร้างตัวยงอย่างไรก็ตาม ความแตกต่างวางไว้ในกลไกการยอมรับแบบข้างต้นและวิธีการเลือกตัวตรวจสอบความถูกต้องเกิดขึ้น

ใน DPoS ระบบเลือกตั้งแบบศูนย์กลางจะกำหนดจำนวนตัวตรวจสอบความถูกต้องที่คงที่เพื่อรักษาความปลอดภัยของเครือข่ายตัวจัดการสามารถมอบหมายให้เดิมพันกับตัวตรวจสอบความถูกต้องของเครือข่ายผู้สมัคร โดยใช้มันเป็นพลังการโหวตไปยังการกลับผู้รับมอบหมาย ตัวเลเลเยอร์ มักจะสนับสนุนตัวตรวจสอบความถูกต้องบนแสตนด์ที่สูงที่สุด เนื่องจากตัวตรวจสอบความถูกต้องที่เย็บติดสูงมีโอกาสในการเลือกตั้งตัวมอบหมายด้วยคะแนนส่วนใหญ่กลายเป็นตัวตรวจสอบความถูกต้องของเครือข่าย และสามารถตรวจสอบธุรกรรมได้ในขณะที่ใช้เดิมพันเพื่อเป็นอำนาจการโหวตโดยพร้อมใช้งาน แต่พวกเขาก็ไม่ได้อยู่ภายใต้การดำเนินการต่อไปด้วยการตัดหากตัวตรวจสอบความถูกต้องที่ได้รับเลือกตั้งทำงานอย่างไม่ถูกต้องในระบบอื่นๆ ตัวมอบหมายอาจอยู่ภายใต้การเลื่อนตำแหน่ง

ใน NPoS ตัวแทน จะกลายเป็นผู้เสนอชื่อ และใช้เดิมพันในลักษณะเดียวกันเพื่อเสนอตัวตรวจสอบความถูกต้องของผู้จัดการที่สามารถเข้ารักษาความปลอดภัยของเครือข่ายStake ถูกล็อก บนเชน และขัดกับ DPoS ผู้เสนอชื่อจะถูกล้อมไว้ในการตัดตามพฤติกรรมอันร้ายแรงของแนวโน้มของการเสนอชื่อของตนในข้อนี้ NPoS คือกลไกการเดิมพันที่รุกมากขึ้นเมื่อเทียบกับการเดิมพันที่ "ตั้งค่าและลืม" โดยเป็นผู้สร้างสรรค์คอยระวังสำหรับการบีเวนและตัวตรวจสอบความถูกต้องที่ยั่งยืนนอกจากนี้ ยังสนับสนุนตัวตรวจสอบความถูกต้องเพื่อสร้างปฏิบัติการตัวตรวจสอบความถูกต้องที่แข็งแกร่งเพื่อดึงดูดและรักษาการเสนอชื่อ