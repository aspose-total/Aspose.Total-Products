---
title: แปลง DOCM เป็นรูปแบบ JSON ผ่าน Java
description: แปลงรูปแบบ DOCM เป็น JSON ผ่าน Java โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel
url_ignore: /th/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง DOCM เป็นรูปแบบ JSON ผ่าน Java" h2="บน Premise Java API เพื่อแปลง DOCM เป็น JSON โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลงรูปแบบ DOCM เป็นรูปแบบ JSON ผ่าน [Aspose.Total for Java](https://products.aspose.com/total/java/) เป็นกระบวนการสองขั้นตอนง่ายๆ เมื่อใช้ API การจัดการเอกสารและการแปลงที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะส่งออก DOCM เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณจะแปลง HTML เป็น JSON ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง DOCM เป็นรูปแบบ JSON ผ่าน Java" %}}
1. เปิดไฟล์ DOCM โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. แปลง DOCM เป็น HTML โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ JSON โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
คุณยังสามารถเปิดเอกสารที่มีการป้องกันด้วยรหัสผ่านได้โดยใช้ API หากเอกสาร DOCM ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็นรูปแบบ JSON ได้โดยไม่ต้องใช้รหัสผ่าน API อนุญาตให้คุณเปิดเอกสารที่เข้ารหัสโดยส่งรหัสผ่านที่ถูกต้องในออบเจกต์ LoadOptions ตัวอย่างโค้ดต่อไปนี้แสดงวิธีลองเปิดเอกสารที่เข้ารหัสด้วยรหัสผ่าน:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง DOCM ที่ได้รับการป้องกันเป็นรูปแบบ JSON ผ่าน Java" %}}
ขณะที่คุณกำลังแปลง DOCM เป็น JSON คุณยังสามารถตั้งค่าช่วงเป็นรูปแบบ JSON เอาต์พุตของคุณได้ ในการตั้งค่าช่วง คุณสามารถเปิด HTML ที่แปลงแล้วโดยใช้คลาสเวิร์กบุ๊ก สร้างช่วงของข้อมูลที่จะส่งออกโดยใช้เมธอด Cells.createRange เรียกเมธอด JsonUtility.exportRangeToJson ด้วยการอ้างอิงของ Range & ExportRangeToJsonOptions และเขียนสตริงข้อมูล JSON ไปยังไฟล์ผ่าน วิธีการ BufferedWriter.write 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## กรณีการใช้งานหลัก

- **การเผยแพร่ข้อมูลเอกสารไปยัง REST/GraphQL APIs**
  ให้บริการเนื้อหา DOCM ที่ถูกสกัดออกมาเป็น JSON เพื่อการใช้งานโดยตรงในแอปเว็บและมือถือ

- **การเติบโตในฐานข้อมูล NoSQL และ Data Lakes**
  โหลดข้อมูลที่มีโครงสร้างที่ได้มาจาก DOCM เข้า MongoDB, Elasticsearch, หรือ Data Lakes บนคลาวด์

- **การขับเคลื่อนแดชบอร์ดด้วยการส่งข้อมูล JSON แบบ Real-Time**
  สตรีม KPIs และ metrics ที่เกี่ยวข้องกับเอกสารเข้าไปยังแดชบอร์ด BI และเครื่องมือตรวจสอบ

- **การตรวจสอบข้อมูลนำเข้าตาม JSON Schema**
  รักษาความสอดคล้องและความสมบูรณ์โดยการจับคู่ข้อมูลฟิลด์ของ DOCM กับกฎของ JSON Schema

- **การเปิดใช้งาน Headless CMS หรือโครงสร้างของ Microservice**
  รวมเนื้อหา DOCM เข้าสู่ระบบที่กระจายอย่าง API-first ที่ JSON เป็นภาษาสำคัญ

## สถานการณ์การอัตโนมัติ

- **การสกัดข้อมูลจาก DOCM เป็น JSON พร้อมกับการจับคู่ฟิลด์**
  กำหนดการจับคู่เพื่อแปลงตาราง, ส่วนหัว, และฟิลด์เป็นวัตถุ JSON ที่มีโครงสร้าง

- **ฟังก์ชันแบบ Serverless ที่แปลงและส่งออกเหตุการณ์ JSON**
  เรียกใช้การแปลงเมื่ออัปโหลดไฟล์, ส่งเหตุการณ์ JSON ไปยังระบบที่ขับเคลื่อนด้วยเหตุการณ์

- **งาน ETL ที่ปรับปรุงประเภทและคีย์**
  มาตรฐานข้อมูลที่ส่งออกมาจาก DOCM เป็นโครงสร้าง JSON ที่สม่ำเสมอสำหรับการวิเคราะห์ด้านล่าง

- **Webhooks ที่ผลักดัน JSON ไปยังระบบที่ขับเคลื่อนด้วยเหตุการณ์**
  อัตโนมัติการส่งออกจาก DOCM เป็น JSON ที่เข้าไปใน CRM, เครื่องมือ ERP, หรือแอปพาร์ตี้บุค

- **กฎการบริหารที่ลบแมโครและข้อมูลส่วนบุคคลก่อนการส่งออกเป็น JSON**
  ปรับใช้การตรวจสอบความปลอดภัยเพื่อให้ได้ผลลัพธ์ JSON ที่ปลอดภัยและถูกทำความสะอาดจากไฟล์ที่เปิดใช้งานแมโคร
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}