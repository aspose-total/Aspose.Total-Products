---
title: แปลงรูปแบบ JSON เป็น SVGZ ผ่าน Java
description: แยก JSON เป็น SVGZ ใน Java โดยไม่ต้องใช้ Microsoft PowerPoint
url_ignore: /th/java/conversion/json-to-svgz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: SVGZ
otherformats: IMAGE DICOM TGA WMF WMZ EMZ PSD SVGZ JPEG2000 DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น SVGZ ผ่าน Java" h2="Java API เพื่อแยกวิเคราะห์รูปแบบ JSON เป็น SVGZ ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
เมื่อใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณจะแปลงรูปแบบ JSON เป็น SVGZ ภายในแอปพลิเคชัน Java ใดก็ได้ใน 2 ขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น JPEG หลังจากนั้น เมื่อใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) คุณจะสามารถแปลง JPEG เป็น SVGZ
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น SVGZ ผ่าน Java" %}}
1. สร้างวัตถุ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และเปิดไฟล์ JSON
2. บันทึก JSON เป็น JPEG โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ SVGZ โดยใช้ [บันทึก](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
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
นอกจากนี้ API ยังช่วยให้คุณแยกวิเคราะห์ JSON เป็น SVGZ ด้วยตัวเลือกเค้าโครงที่ระบุ ในการระบุตัวเลือกเลย์เอาต์ คุณสามารถใช้คลาส [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ได้ ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่าว่าง ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น SVGZ ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถแปลง JSON เป็น SVGZ ด้วยลายน้ำในเอกสาร SVGZ ของคุณ ในการเพิ่มลายน้ำให้คุณสามารถแปลง JSON เป็น JPEG และเพิ่มลายน้ำลงไปก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://reference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ SVGZ ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น SVGZ** เป็นสิ่งจำเป็นสำหรับการสร้าง **กราฟิกเวกเตอร์ที่มีขนาดเล็กและสามารถยืดหดได้** โดยตรงจากข้อมูลโครงสร้าง  SVGZ เป็นรูปแบบ SVG ที่ถูกบีบอัดด้วย GZIP ทำให้มีขนาดไฟล์เล็กลงพร้อมรักษาความสามารถในการปรับความละเอียด ทำให้เหมาะสำหรับการใช้งานบนเว็บ มือถือ และความต้องการในการแสดงผลขององค์กร  โดยการแปลงชุดข้อมูล JSON เป็น SVGZ องค์กรสามารถส่งผลงานที่มีน้ำหนักเบา สามารถโต้ตอบและมีขนาดเปลี่ยนได้ในทุกแพลตฟอร์ม

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

- **กราฟิกที่สามารถยืดหดได้** – สร้างกราฟที่ถูกบีบอัดที่ยังคงชัดเจนที่ความละเอียดใดๆ
- **แดชบอร์ดที่สามารถโต้ตอบ** – ให้พลังให้แดชบอร์ดที่ขับเคลื่อนด้วยข้อมูลด้วยกราฟิก SVGZ ที่มีน้ำหนักเบา
- **ไดอะแกรมเวกเตอร์ที่ใช้ JSON เป็นฐาน** – แปลงข้อมูลโครงสร้างเป็นไดอะแกรมโดยใช้พื้นที่จัดเก็บข้อมูลขั้นต่ำ
- **กราฟิกที่ปรับเปลี่ยนได้สำหรับมือถือ** – ส่งผลงานที่โหลดเร็วขึ้นสำหรับแอปและเว็บไซต์ที่ตอบสนอง
- **ระบบการแสดงผลขององค์กร** – มาตรฐานกราฟิกที่สามารถยืดหดได้ในกระบวนการทำงานของบริษัท

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}

- **ท่อการทำงาน JSON เป็น SVGZ** – อัตโนมัติการแปลงข้อมูลเป็นไฟล์เวกเตอร์ที่ถูกบีบอัด
- **การบีบอัดกราฟิกโดยอัตโนมัติ** – ลดขนาดของการแสดงผลขนาดใหญ่โดยไม่สูญเสียคุณภาพ
- **การสร้างภาพเวกเตอร์จาก JSON** – สร้างภาพเคลื่อนไหวจากชุดข้อมูลโครงสร้าง
- **กระบวนการทำงานกราฟิก跨แพลตฟอร์ม** – ให้ความสม่ำเสมอในการแสดงผลที่ยืดหดได้ในเดสก์ท็อป มือถือ และคลาวด์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}