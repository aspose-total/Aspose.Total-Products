---
title: แปลงรูปแบบ JSON เป็น PPS ผ่าน Java
description: แยก JSON เป็น PPS ใน Java โดยไม่ต้องใช้ Microsoft PowerPoint
url_ignore: /th/java/conversion/json-to-pps/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPS
otherformats: POT PPTM PPSM POTM OTP POWERPOINT PPSX PPS PPT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น PPS ผ่าน Java" h2="Java API เพื่อแยกวิเคราะห์รูปแบบ JSON เป็น PPS โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
เมื่อใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณจะแปลงรูปแบบ JSON เป็น PPS ภายในแอปพลิเคชัน Java ใดก็ได้ใน 2 ขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PPTX หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) คุณจะสามารถแปลง PPTX เป็น PPS ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น PPS ผ่าน Java" %}}
1. สร้างวัตถุ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และเปิดไฟล์ JSON
2. บันทึก JSON เป็น PPTX โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ PPS โดยใช้วิธี [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
นอกจากนี้ API ยังช่วยให้คุณแยกวิเคราะห์ JSON เป็น PPS ด้วยตัวเลือกเค้าโครงที่ระบุ ในการระบุตัวเลือกเลย์เอาต์ คุณสามารถใช้คลาส [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ได้ ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่าว่าง ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น PPS ผ่าน Java" %}}
เมื่อใช้ API คุณจะแปลง JSON เป็น PPS ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร PPS ของคุณ ก่อนอื่นให้แยก JSON เป็น PPTX และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PPTX ที่สร้างขึ้นใหม่โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) วนซ้ำทุกสไลด์ เพิ่มข้อความ ใช้ addTextFrame ตั้งค่าตัวเลือกที่เกี่ยวข้องทั้งหมด เช่น สี ประเภทการเติม และอื่นๆ และสามารถบันทึกเอกสารไปยัง PPS 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น PPS** เป็นสิ่งจำเป็นสำหรับการสร้าง **ไฟล์ PowerPoint slideshow โดยตรงจากข้อมูลที่มีโครงสร้าง** ไฟล์ PPS เปิดในรูปแบบสไลด์เต็มหน้าจอ ทำให้เหมาะสำหรับการนำเสนอโดยอัตโนมัติ การสาธิตแบบอินเทอร์แอคทีฟ และการนำเสนอบริษัทหรือการศึกษาอย่างสม่ำเสมอ โดยการแปลง JSON เป็น PPS องค์กรสามารถปรับปรุงการผลิตสไลด์ ลดการจัดรูปแบบด้วยมือ และให้ผลลัพธ์ของสไลด์มีมาตรฐาน

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

- **การส่งสไลด์โดยอัตโนมัติ** – สร้างงานนำเสนอพร้อมเล่นสำหรับการประชุมและการกระจายออนไลน์
- **การสาธิตทางการตลาด** – ผลิตสไลด์แบบอินเทอร์แอคทีฟสำหรับโปรโมชั่นผลิตภัณฑ์และแคมเปญ
- **การอบรม** – มาตรฐานการนำเสนอการศึกษาและการบริการใหม่ในขอบเขตขนาดใหญ่
- **การนำเสนอในงานสัมมนา** – ส่งสไลด์ที่มีคุณภาพและมืออาชีพสำหรับเหตุการณ์และสัมมนา
- **การเล่าเรื่องข้อมูล** – แปลงชุดข้อมูลที่มีโครงสร้างเป็นเรื่องราวสไลด์ที่ดึงดูดสายตา

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

- **ท่อการทำงาน JSON เป็น PPS** – อัตโนมัติการสร้างไฟล์สไลด์จากชุดข้อมูลที่มีโครงสร้าง
- **การสร้างสไลด์โดยอัตโนมัติ** – ลดความพยายามในการออกแบบงานนำเสนอที่ซ้ำซาก
- **การส่งสไลด์ทั่วบริษัท** – กระจายสไลด์มีมาตรฐานในแผนกและทีมต่างๆ
- **การอัตโนมัติการนำเสนอที่รวม JSON** – ฝังข้อมูลแบบไดนามิกลงในสไลด์สำหรับการแสดงผลแบบเรียลไทม์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}