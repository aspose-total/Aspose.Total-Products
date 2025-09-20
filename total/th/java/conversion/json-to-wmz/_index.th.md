---
title: แปลงรูปแบบ JSON เป็น WMZ ผ่าน Java
description: แยก JSON เป็น WMZ ใน Java โดยไม่ต้องใช้ Microsoft PowerPoint
url_ignore: /th/java/conversion/json-to-wmz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMZ
otherformats: SVGZ WMZ JPEG2000 TGA DICOM IMAGE EMZ DXF PSD WMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น WMZ ผ่าน Java" h2="Java API เพื่อแยกวิเคราะห์รูปแบบ JSON เป็น WMZ ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
เมื่อใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณจะแปลงรูปแบบ JSON เป็น WMZ ภายในแอปพลิเคชัน Java ใดก็ได้ใน 2 ขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น JPEG หลังจากนั้น เมื่อใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) คุณจะสามารถแปลง JPEG เป็น WMZ
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น WMZ ผ่าน Java" %}}
1. สร้างวัตถุ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และเปิดไฟล์ JSON
2. บันทึก JSON เป็น JPEG โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ WMZ โดยใช้ [บันทึก](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
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
นอกจากนี้ API ยังช่วยให้คุณแยกวิเคราะห์ JSON เป็น WMZ ด้วยตัวเลือกเค้าโครงที่ระบุ ในการระบุตัวเลือกเลย์เอาต์ คุณสามารถใช้คลาส [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ได้ ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่าว่าง ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น WMZ ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถแปลง JSON เป็น WMZ ด้วยลายน้ำในเอกสาร WMZ ของคุณ ในการเพิ่มลายน้ำให้คุณสามารถแปลง JSON เป็น JPEG และเพิ่มลายน้ำลงไปก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://reference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ WMZ ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น WMZ** เป็นสิ่งจำเป็นสำหรับการสร้าง **กราฟิก Windows Metafile ที่ถูกบีบอัดจากข้อมูลโครงสร้าง** ไฟล์ WMZ ให้กราฟิกเวกเตอร์ที่กระชับและสามารถปรับขนาดได้เหมาะสำหรับฝังตัวในเอกสาร รายงาน และระบบองค์กร โดยการแปลง JSON เป็น WMZ องค์กรสามารถปรับปรุงการจัดเก็บ ปรับปรุงความเข้ากันได้ของแพลตฟอร์ม และอัตโนมัติการผลิตกราฟิกที่มีน้ำหนักเบาและคุณภาพสูง

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

- **การจัดเก็บกราฟิกที่มีน้ำหนักเบา** – บีบอัดกราฟิกเวกเตอร์เพื่อการจัดเก็บและถ่ายโอนอย่างมีประสิทธิภาพ
- **การฝัง WMZ ในเอกสาร** – ผสานกราฟิก WMZ อย่างไม่มีรอยต่อในไฟล์ Word, PowerPoint, และ Excel
- **ความเข้ากันได้ของแพลตฟอร์ม** – รักษากราฟิกที่สามารถปรับขนาดได้ใน Windows และสภาพแวดล้อมอื่น ๆ
- **ภาพประกอบการรายงานธุรกิจ** – อัตโนมัติการสร้างแผนภูมิและแผนภาพสำหรับรายงานบริษัท
- **การจัดเรียงไดอะแกรมองค์กรที่ถูกปรับปรุง** – ผลิตภาพที่มีมาตรฐานและถูกบีบอัดสำหรับเอกสารองค์กร

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

- **ท่อการทำงาน JSON เป็น WMZ** – อัตโนมัติการแปลงข้อมูลโครงสร้างเป็นกราฟิก WMZ ที่ถูกบีบอัด
- **การลดขนาดไฟล์อัตโนมัติ** – ลดขนาดไฟล์พร้อมรักษาคุณภาพเวกเตอร์
- **การปรับปรุงภาพด้วย JSON** – สร้างภาพที่มีคุณภาพสูงและมีข้อมูลอย่างมีประสิทธิภาพ
- **กระบวนการงานภาพประกอบที่มีน้ำหนักเบาพร้อมใช้งานในองค์กร** – ขยายการสร้าง WMZ ในแผนกและระบบต่าง ๆ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}