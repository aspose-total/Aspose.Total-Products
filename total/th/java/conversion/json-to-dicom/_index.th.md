---
title: แปลงรูปแบบ JSON เป็น DICOM ผ่าน Java
description: แยก JSON เป็น DICOM ใน Java โดยไม่ต้องใช้ Microsoft PowerPoint
url_ignore: /th/java/conversion/json-to-dicom/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DICOM
otherformats: DICOM DXF WMF TGA SVGZ EMZ IMAGE JPEG2000 PSD WMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น DICOM ผ่าน Java" h2="Java API เพื่อแยกวิเคราะห์รูปแบบ JSON เป็น DICOM ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
เมื่อใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณจะแปลงรูปแบบ JSON เป็น DICOM ภายในแอปพลิเคชัน Java ใดก็ได้ใน 2 ขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น JPEG หลังจากนั้น เมื่อใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) คุณจะสามารถแปลง JPEG เป็น DICOM
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น DICOM ผ่าน Java" %}}
1. สร้างวัตถุ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และเปิดไฟล์ JSON
2. บันทึก JSON เป็น JPEG โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ DICOM โดยใช้ [บันทึก](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
นอกจากนี้ API ยังช่วยให้คุณแยกวิเคราะห์ JSON เป็น DICOM ด้วยตัวเลือกเค้าโครงที่ระบุ ในการระบุตัวเลือกเลย์เอาต์ คุณสามารถใช้คลาส [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ได้ ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่าว่าง ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น DICOM ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถแปลง JSON เป็น DICOM ด้วยลายน้ำในเอกสาร DICOM ของคุณ ในการเพิ่มลายน้ำให้คุณสามารถแปลง JSON เป็น JPEG และเพิ่มลายน้ำลงไปก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://reference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ DICOM ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น DICOM (Digital Imaging and Communications in Medicine)** เป็นสิ่งสำคัญสำหรับการแปลง **ข้อมูลสุขภาพที่มีโครงสร้าง** เป็นรูปแบบภาพการแพทย์มาตรฐาน  DICOM เป็นมาตรฐานที่ใช้ทั่วไปสำหรับการเก็บข้อมูล ส่งข้อมูล และแสดงภาพการแพทย์ ทำให้ผู้ให้บริการด้านสุขภาพ นักวิจัย และระบบ AI สามารถทำงานกับข้อมูลที่สอดคล้องและสามารถทำงานร่วมกันได้ โดยการแปลง JSON เป็น DICOM ข้อมูลผู้ป่วยที่มีโครงสร้างและข้อมูลคลินิกสามารถนำเข้าไปในกระบวนการทำภาพได้อย่างราบรื่น สนับสนุนการวินิจฉัยอย่างแม่นยำและผลลัพธ์ด้านสุขภาพที่ดีขึ้น

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

- **การแสดงข้อมูลผู้ป่วย** – แปลงข้อมูลสุขภาพที่มีโครงสร้างเป็นรูปแบบภาพ
- **การทำภาพการแพทย์โดยใช้ AI** – เปิดให้ระบบเรียนรู้ของเครื่องประมวลผลข้อมูลที่มาจาก JSON
- **ความสามารถในการทำงานร่วมกันด้านสุขภาพ** – มาตรฐานข้อมูลที่มีโครงสร้างเป็นรูปแบบ DICOM ที่ได้รับการยอมรับในระดับโลก
- **กระบวนการทำงานของวิทยาศาสตร์การแพทย์** – นำรายงานที่มีโครงสร้างจาก JSON เข้าระบบภาพและระบบวินิจฉัย
- **การนำเข้าข้อมูลการวิจัยทางคลินิก** – แปลงชุดข้อมูลที่มีโครงสร้างเป็นรูปแบบที่เหมาะสมกับการศึกษา

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}

- **การสร้างท่อไป DICOM โดยใช้ JSON** – ทำให้การแปลงข้อมูลสุขภาพเป็นรูปแบบที่พร้อมใช้งานในการทำภาพเป็นอัตโนมัติ
- **การแปลงรายงานการแพทย์อัตโนมัติ** – สร้างไฟล์ DICOM โดยตรงจากรายงานคลินิกที่มาจาก JSON
- **การทำภาพการแพทย์ในระบบคลาวด์** – เปิดให้การแลกเปลี่ยนข้อมูลภาพที่สามารถทำงานร่วมกันได้ในระบบคลาวด์
- **ระบบวินิจฉัยโดยใช้ AI** – ให้กำลังใจให้เครื่องมือวินิจฉัยขั้นสูงด้วยการแปลงข้อมูลที่มีโครงสร้างเป็นภาพ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}