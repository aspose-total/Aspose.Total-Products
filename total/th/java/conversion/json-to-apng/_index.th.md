---
title: แปลงรูปแบบ JSON เป็น APNG ผ่าน Java
description: แยก JSON เป็น APNG ใน Java โดยไม่ต้องใช้ Microsoft PowerPoint
url_ignore: /th/java/conversion/json-to-apng/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: APNG
otherformats: JPEG2000 EMZ PSD WMF WMZ DXF IMAGE SVGZ DICOM TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น APNG ผ่าน Java" h2="Java API เพื่อแยกวิเคราะห์รูปแบบ JSON เป็น APNG ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
เมื่อใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณจะแปลงรูปแบบ JSON เป็น APNG ภายในแอปพลิเคชัน Java ใดก็ได้ใน 2 ขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น JPEG หลังจากนั้น เมื่อใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) คุณจะสามารถแปลง JPEG เป็น APNG
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น APNG ผ่าน Java" %}}
1. สร้างวัตถุ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และเปิดไฟล์ JSON
2. บันทึก JSON เป็น JPEG โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ APNG โดยใช้ [บันทึก](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
นอกจากนี้ API ยังช่วยให้คุณแยกวิเคราะห์ JSON เป็น APNG ด้วยตัวเลือกเค้าโครงที่ระบุ ในการระบุตัวเลือกเลย์เอาต์ คุณสามารถใช้คลาส [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ได้ ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่าว่าง ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น APNG ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถแปลง JSON เป็น APNG ด้วยลายน้ำในเอกสาร APNG ของคุณ ในการเพิ่มลายน้ำให้คุณสามารถแปลง JSON เป็น JPEG และเพิ่มลายน้ำลงไปก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://reference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ APNG ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น APNG (Animated Portable Network Graphics)** เป็นสิ่งจำเป็นสำหรับสร้าง **การแสดงผลแบบเคลื่อนไหว** โดยตรงจากข้อมูลโครงสร้าง ไฟล์ APNG สนับสนุนการสร้างภาพเคลื่อนไหวคุณภาพสูงพร้อมกับความโปร่งใส ทำให้เหมาะสำหรับเว็บ เช่น แดชบอร์ด และการนำเสนอข้อมูลที่มีการเคลื่อนไหว โดยการแปลง JSON เป็น APNG องค์กรสามารถให้ชีวิตให้ข้อมูล ปรับปรุงความสามารถในการโต้ตอบ และสร้างกราฟิกเคลื่อนไหวที่มีน้ำหนักเบาที่ถูกปรับแต่งให้เหมาะสำหรับสภาพแวดล้อมดิจิทัลที่ทันสมัย

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

- **การเคลื่อนไหวที่ขับเคลื่อนด้วยข้อมูล** – แสดงโครงสร้างข้อมูลที่ซับซ้อนด้วยการเคลื่อนไหวอย่างนุ่มนวล
- **แดชบอร์ดที่สามารถโต้ตอบ** – เสริมสร้างแดชบอร์ดรายงานด้วยกราฟิกเคลื่อนไหว
- **การแสดงผลของการจำลองที่ใช้ JSON** – แสดงผลการจำลองเวลาจริงโดยตรงจากข้อมูลโครงสร้าง
- **กราฟิกเคลื่อนไหวที่มีน้ำหนักเบา** – ส่งผลกราฟิกด้วยขนาดไฟล์เล็กสำหรับการใช้งานบนเว็บ
- **องค์ประกอบเว็บที่เปลี่ยนไปตามเวลา** – สนับสนุนภาพเคลื่อนไหวโปร่งใสที่ใช้ในเว็บไซต์อย่างน่าสนใจ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}

- **การทำงานของท่อน้ำ JSON เป็น APNG** – อัตโนมัติการแปลงข้อมูลโครงสร้างเป็นภาพเคลื่อนไหว
- **การแสดงผลข้อมูลแบบเคลื่อนไหวแบบเรียลไทม์** – สตรีมข้อมูลสดเข้าสู่ภาพเคลื่อนไหว APNG อย่างไดนามิก
- **การสร้างอินโฟกราฟิกโดยอัตโนมัติ** – สร้างอินโฟกราฟิกที่ใช้การเคลื่อนไหวโดยตรงจากชุดข้อมูล JSON
- **การอัตโนมัติการแสดงผลบนเว็บ** – ผสานภาพเคลื่อนไหว APNG เข้ากับการทำงานของเว็บที่ทันสมัยสำหรับเนื้อหาที่สามารถโต้ตอบ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}