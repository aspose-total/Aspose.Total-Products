---
title: ส่งออก EMAIL เป็น IMAGE ผ่าน Java
description: Java API เพื่อแปลง EMAIL เป็น IMAGE โดยไม่ต้องใช้ Microsoft Word หรือ Outlook
url_ignore: /th/java/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: JPEG DOTM DOCX IMAGE OTT EPUB DOCM EMF FLATOPC DOT TEXT ODT SVG DOTX MD TIFF PNG DOC PCL PS PDF RTF WORDML XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อแสดงผล EMAIL เป็น IMAGE" h2="ส่งออก EMAIL เป็น IMAGE โดยใช้ Java API ในตัวโดยไม่ต้องใช้การขึ้นต่อกันของบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลงอีเมลเป็นคุณสมบัติที่ทรงพลังที่นักพัฒนา Java สามารถรวมเข้ากับแอปพลิเคชัน Java J2SE, J2EE, J2ME ผ่าน [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ด้วยการใช้สอง API ภายในแพ็คเกจ คุณสามารถแปลง Email EMAIL เป็น IMAGE โดยไม่ต้องพึ่งพาบุคคลที่สาม ประการแรก คุณสามารถใช้ Email Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) เพื่อแปลงรูปแบบไฟล์ EMAIL เป็น HTML ประการที่สอง คุณสามารถแสดง HTML เป็น IMAGE โดยใช้ Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง EMAIL เป็น IMAGE" %}}
1. เปิดไฟล์ EMAIL โดยใช้คลาส [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. แปลง EMAIL เป็น HTML โดยใช้ [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) กระบวนการ
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ IMAGE โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) วิธีการและตั้งค่า IMAGE เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
```
การแปลงอีเมลเป็นรูปแบบภาพ เช่น **JPG, PNG, หรือ TIFF** จะช่วยให้เลเอาท์และความสมบูรณ์ของข้อความยังคงคงที่ไว้เหมือนเดิม ด้วย Email Java API, นักพัฒนาสามารถอัตโนมัติกระบวนการนี้เพื่อสร้างภาพของอีเมลที่ปลอดภัย ป้องกันการแก้ไข และสามารถแชร์ได้

## ✅ การใช้งานหลัก

- **หลักฐานทางกฎหมาย**: เก็บอีเมลเป็นไฟล์ภาพที่ไม่สามารถแก้ไขได้ เพื่อปฏิบัติตามข้อบังคับและคดีศาล
- **การฝึกอบรมและการเผชิญสถานการณ์**: ฝังอีเมลตัวอย่างเช่นการโกงหรืออีเมลของบริษัทเป็นภาพในคู่มือการฝึกอบรม
- **การเก็บถาวรภาพ**: รักษาแกลเลอรีของการสื่อสารที่สำคัญที่ต้องการให้รูปแบบการจัดหน้าเหมือนเดิม
- **การแชร์อย่างรวดเร็ว**: แชร์อีเมลเป็นรูปภาพโดยไม่เปิดเผยส่วนหัวหรือเนื้อหาที่สามารถแก้ไขได้
- **ภาพของอีเมล**: สร้างรุ่นภาพที่มีเครื่องหมายเวลาสำหรับเส้นทางการตรวจสอบหรือเอกสารโครงการ

## ⚙️ สถานการณ์การอัตโนมัติ

- **ท่อการส่งออกเป็นชุด**: แปลงอีเมลที่เข้ามาเป็น **JPG/PNG** โดยอัตโนมัติและเก็บไว้เพื่ออ้างอิงในอนาคต
- **การอัตโนมัติตามข้อบังคับ**: เก็บอีเมลที่มีข้อมูลที่ละเอียดอย่างไร้ประสิทธิภาพเป็น **TIFF images** ในระบบการจัดการเอกสารที่ปลอดภัย
- **ระบบการเรียนการสอนออนไลน์**: นำรูปภาพอีเมลที่แปลงแล้วเข้าสู่แพลตฟอร์ม LMS เพื่อการฝึกอบรม
- **เอกสารโครงการ**: แนบภาพของอีเมลกับรายงานโครงการที่ต้องการหลักฐานทางภาพ
- **กระบวนการสืบสวน**: แปลงอีเมลที่น่าสงสัยหรือการโกงเป็นรูปภาพสำหรับ **ผู้สืบสวน** โดยไม่มีความเสี่ยงจากการเรียกใช้ลิงก์ที่เป็นอันตรายโดยไม่ตั้งใจ
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}