---
title: ส่งออก EMLX เป็น EPUB ผ่าน Java
description: Java API เพื่อแปลง EMLX เป็น EPUB โดยไม่ต้องใช้ Microsoft Word หรือ Outlook
url_ignore: /th/java/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: PNG XPS FLATOPC MD TIFF DOTX EMF PDF DOTM EPUB RTF DOCM GIF TEXT SVG JPEG WORDML PS DOC DOT ODT OTT PCL DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อแสดงผล EMLX เป็น EPUB" h2="ส่งออก EMLX เป็น EPUB โดยใช้ Java API ในตัวโดยไม่ต้องใช้การขึ้นต่อกันของบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลงอีเมลเป็นคุณสมบัติที่ทรงพลังที่นักพัฒนา Java สามารถรวมเข้ากับแอปพลิเคชัน Java J2SE, J2EE, J2ME ผ่าน [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ด้วยการใช้สอง API ภายในแพ็คเกจ คุณสามารถแปลง Emlx EMLX เป็น EPUB โดยไม่ต้องพึ่งพาบุคคลที่สาม ประการแรก คุณสามารถใช้ Emlx Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) เพื่อแปลงรูปแบบไฟล์ EMLX เป็น HTML ประการที่สอง คุณสามารถแสดง HTML เป็น EPUB โดยใช้ Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง EMLX เป็น EPUB" %}}
1. เปิดไฟล์ EMLX โดยใช้คลาส [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. แปลง EMLX เป็น HTML โดยใช้ [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)) กระบวนการ
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ EPUB โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) วิธีการและตั้งค่า EPUB เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}