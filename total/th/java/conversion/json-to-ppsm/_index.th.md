---
title: แปลงรูปแบบ JSON เป็น PPSM ผ่าน Java
description: แยก JSON เป็น PPSM ใน Java โดยไม่ต้องใช้ Microsoft PowerPoint
url_ignore: /th/java/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: PPS POT POWERPOINT PPSM PPTM POTM PPSX OTP POTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น PPSM ผ่าน Java" h2="Java API เพื่อแยกวิเคราะห์รูปแบบ JSON เป็น PPSM โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
เมื่อใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณจะแปลงรูปแบบ JSON เป็น PPSM ภายในแอปพลิเคชัน Java ใดก็ได้ใน 2 ขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PPTX หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) คุณจะสามารถแปลง PPTX เป็น PPSM ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น PPSM ผ่าน Java" %}}
1. สร้างวัตถุ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และเปิดไฟล์ JSON
2. บันทึก JSON เป็น PPTX โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ PPSM โดยใช้วิธี [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
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
นอกจากนี้ API ยังช่วยให้คุณแยกวิเคราะห์ JSON เป็น PPSM ด้วยตัวเลือกเค้าโครงที่ระบุ ในการระบุตัวเลือกเลย์เอาต์ คุณสามารถใช้คลาส [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ได้ ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่าว่าง ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น PPSM ผ่าน Java" %}}
เมื่อใช้ API คุณจะแปลง JSON เป็น PPSM ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร PPSM ของคุณ ก่อนอื่นให้แยก JSON เป็น PPTX และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PPTX ที่สร้างขึ้นใหม่โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) วนซ้ำทุกสไลด์ เพิ่มข้อความ ใช้ addTextFrame ตั้งค่าตัวเลือกที่เกี่ยวข้องทั้งหมด เช่น สี ประเภทการเติม และอื่นๆ และสามารถบันทึกเอกสารไปยัง PPSM 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น PPSM** เป็นสิ่งจำเป็นสำหรับการสร้าง **ไฟล์สไลด์โชว์ PowerPoint ที่เปิดใช้งานแมโครจากข้อมูลโครงสร้าง** ไฟล์ PPSM สนับสนุนแมโครที่ฝังอยู่ เพื่อให้เกิดความสามารถในการปฏิสัมพันธ์โดยอัตโนมัติ เนื้อหาแบบไดนามิก และฟังก์ชันการนำเสนอขั้นสูง โดยการแปลง JSON เป็น PPSM องค์กรสามารถสร้างสไลด์โชว์ที่มีมาตรฐานและปฏิสัมพันธ์ได้ที่เพิ่มประสิทธิภาพในการนำเสนอของบริษัท การฝึกอบรม และการรายงานที่มีข้อมูลเชิงข้อมูล

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

- **การนำเสนอสำหรับบริษัทที่มีปฏิสัมพันธ์** – สร้างสไลด์โชว์ที่น่าสนใจพร้อมกับการอัตโนมัติที่ฝังอยู่สำหรับการนำเสนอลูกค้าหรือภายใน
- **กระบวนการทำงานการฝึกอบรมด้วยการอัตโนมัติ** – มาตรฐานการเริ่มต้นและการฝึกอบรมด้วยการปฏิสัมพันธ์ที่ใช้แมโคร
- **สไลด์โชว์ธุรกิจที่มีข้อมูลเชิงข้อมูล** – สร้างรายงานและแดชบอร์ดที่ไดนามิกจากชุดข้อมูลโครงสร้าง
- **การเล่าเรื่องการตลาด** – สร้างสไลด์ที่เปิดใช้แมโครสำหรับแคมเปญโฆษณาและการเปิดตัวผลิตภัณฑ์
- **การรายงานที่มีการประมวลผลไดนามิกของระดับองค์กร** – อัตโนมัติสไลด์โชว์ที่เกิดซ้ำให้ใช้สำหรับการรายงานของผู้บริหารและแผนก

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

- **การสร้างท่อการส่ง JSON เป็น PPSM อัตโนมัติ** – อัตโนมัติการแปลงข้อมูลโครงสร้างเป็นไฟล์สไลด์โชว์ที่เปิดใช้แมโคร
- **การสร้างสไลด์โชว์ที่เปิดใช้แมโครอัตโนมัติ** – กำจัดการผลิตสไลด์ด้วยมือซ้ำๆ
- **ชุดสไลด์ที่มีการปฏิสัมพันธ์จาก JSON** – เติมสไลด์โชว์ด้วยข้อมูลโครงสร้างและแมโครไดนามิก
- **การอัตโนมัติการนำเสนอที่มีความไดนามิกในองค์กร** – ขยายการนำเสนอที่มีการปฏิสัมพันธ์ได้ทั่วทั้งทีมและแผนก

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}