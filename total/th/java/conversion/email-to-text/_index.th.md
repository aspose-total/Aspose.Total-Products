---
title: ส่งออก EMAIL เป็น TEXT ผ่าน Java
description: Java API เพื่อแปลง EMAIL เป็น TEXT โดยไม่ต้องใช้ Microsoft Word หรือ Outlook
url_ignore: /th/java/conversion/email-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: DOT PS SVG PDF XPS FLATOPC WORDML JPEG DOCM PCL DOCX RTF GIF TIFF PNG EPUB TEXT MD OTT DOC ODT DOTM DOTX EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อแสดงผล EMAIL เป็น TEXT" h2="ส่งออก EMAIL เป็น TEXT โดยใช้ Java API ในตัวโดยไม่ต้องใช้การขึ้นต่อกันของบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลงอีเมลเป็นคุณสมบัติที่ทรงพลังที่นักพัฒนา Java สามารถรวมเข้ากับแอปพลิเคชัน Java J2SE, J2EE, J2ME ผ่าน [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ด้วยการใช้สอง API ภายในแพ็คเกจ คุณสามารถแปลง Email EMAIL เป็น TEXT โดยไม่ต้องพึ่งพาบุคคลที่สาม ประการแรก คุณสามารถใช้ Email Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) เพื่อแปลงรูปแบบไฟล์ EMAIL เป็น HTML ประการที่สอง คุณสามารถแสดง HTML เป็น TEXT โดยใช้ Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง EMAIL เป็น TEXT" %}}
1. เปิดไฟล์ EMAIL โดยใช้คลาส [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. แปลง EMAIL เป็น HTML โดยใช้ [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) กระบวนการ
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ TEXT โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) วิธีการและตั้งค่า TEXT เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
```
การแปลงอีเมลเป็น **ข้อความธรรมดา (.txt)** ช่วยให้เนื้อหาสำคัญของข้อความถูกสกัดออกมาในรูปแบบที่ง่ายที่สุดและสามารถพกพาได้ง่ายที่สุด รูปแบบนี้จะลบการจัดรูปแบบที่ไม่จำเป็นออกไป ทำให้ข้อมูลมีน้ำหนักเบา สามารถค้นหาได้ง่าย และเข้ากันได้สูงขึ้นทั้งบนแพลตฟอร์มต่าง ๆ  


## ✅ การใช้งานหลัก  
- **เก็บถาวรและปฏิบัติตามกฎระเบียบ**: เก็บอีเมลในรูปแบบข้อความเพื่อการเก็บถาวรที่มีน้ำหนักเบาและยาวนาน  
- **การค้นพบอิเล็กทรอนิกส์และกฎหมาย**: สกัดเฉพาะข้อความเบื้องต้นเพื่อการสอบสวนหรือการสนับสนุนการดำเนินคดี  
- **ขุดข้อมูลและการวิเคราะห์ข้อมูล**: เตรียมข้อความอีเมลที่ไม่มีโครงสร้างสำหรับ NLP, AI หรือการจัดดัชนีค้นหา  
- **การย้ายไปสู่ระบบที่เป็นที่เชื่อถือได้**: ให้เนื้อหาอีเมลในรูปแบบข้อความที่ยอมรับได้ทั่วไป  
- **การเข้าถึงแบบออฟไลน์**: อ่านอีเมลบนอุปกรณ์หรือแอปพลิเคชันที่ไม่รองรับการจัดรูปแบบที่มีความหลากหลาย  


## ⚙️ สถานการณ์การใช้งานอัตโนมัติ  
- **ส่งออกเป็นชุด**: แปลงพันธุ์พันอีเมลเป็น `.txt` เพื่อการเก็บรักษาหรือการวิเคราะห์  
- **สกัดเอาเนื้อหา**: อัตโนมัติเอาเอาข้อมูลเฉพาะ, HTML และลายเซ็นเจอร์ โดยเก็บเฉพาะข้อความที่สะอาด  
- **การสร้างดัชนีเครื่องมือค้นหา**: สร้างผลลัพธ์ `.txt` อัตโนมัติเพื่อสร้างเอกสารเก็บข้อมูลที่สามารถค้นหาได้  
- **กระบวนการสร้างท่อนข้อมูลอีเมล**: ใช้ผลลัพธ์ `.txt` เป็นรูปแบบกลางสำหรับการสกัดข้อมูลโครงสร้าง  
- **อัตโนมัติปฏิบัติตามกฎระเบียบ**: สร้างบันทึกข้อความธรรมดาอัตโนมัติจากอีเมลขาเข้าและขาออก  
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}