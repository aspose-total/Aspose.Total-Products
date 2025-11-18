---
title: แปลง POTX เป็นรูปแบบ JSON ผ่าน Java
description: แปลงรูปแบบ POTX เป็น JSON ผ่าน Java โดยไม่ต้องใช้ Microsoft Excel หรือ PowerPoint
url_ignore: /th/java/conversion/potx-to-json/
family: total
platformtag: net
feature: conversion
informat: POTX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง POTX เป็นรูปแบบ JSON ผ่าน Java" h2="บน Premise Java API เพื่อส่งออก POTX ไปยัง JSON โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลงรูปแบบ POTX เป็นรูปแบบ JSON ผ่าน [Aspose.Total for Java](https://products.aspose.com/total/java/) เป็นกระบวนการสองขั้นตอนง่ายๆ ในขั้นตอนแรก คุณสามารถส่งออก POTX เป็น HTML ได้โดยใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ประการที่สอง โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแปลง HTML เป็น JSON
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง POTX เป็นรูปแบบ JSON ผ่าน Java" %}}
1. เปิดไฟล์ POTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง POTX เป็น HTML โดยใช้ [บันทึก](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides ISaveOptions-) วิธีการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ JSON โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
คุณยังสามารถเปิดเอกสารที่มีการป้องกันด้วยรหัสผ่านได้โดยใช้ API หากเอกสาร POTX ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็นรูปแบบ JSON ได้โดยไม่ต้องใช้รหัสผ่าน API อนุญาตให้คุณเปิดเอกสารที่เข้ารหัสโดยส่งรหัสผ่านที่ถูกต้องในออบเจกต์ LoadOptions  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง POTX ที่ได้รับการป้องกันเป็นรูปแบบ JSON ผ่าน Java" %}}
ขณะที่คุณกำลังแปลง POTX เป็น JSON คุณยังสามารถตั้งค่าช่วงเป็นรูปแบบ JSON เอาต์พุตของคุณได้ ในการตั้งค่าช่วง คุณสามารถเปิด HTML ที่แปลงแล้วโดยใช้คลาสเวิร์กบุ๊ก สร้างช่วงของข้อมูลที่จะส่งออกโดยใช้เมธอด Cells.createRange เรียกเมธอด JsonUtility.exportRangeToJson ด้วยการอ้างอิงของ Range & ExportRangeToJsonOptions และเขียนสตริงข้อมูล JSON ไปยังไฟล์ผ่าน วิธีการ BufferedWriter.write 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```

{{< blocks/products/pf/agp/feature-section >}}



การแปลง POTX เป็น JSON จะเปลี่ยนเนื้อหาของสไลด์เป็นโครงสร้างของ JavaScript Object Notation ที่เหมาะสำหรับการใช้ในเว็บแอปพลิเคชัน แดชบอร์ด และการประมวลผลข้อมูลด้วย API



{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}



* การส่งออกตารางและกราฟในงานนำเสนอสำหรับแดชบอร์ดเว็บ

* การแปลงสไลด์เป็น JSON เพื่อการนำเข้าข้อมูลสำหรับ AI หรือ machine learning

* เตรียมเครื่องมือรายงานแบบอินเทอร์แอคทีฟจากข้อมูลงานนำเสนอ

* แบ่งปันเนื้อหาที่มีสไลด์กับแอปพลิเคชันเว็บและแพลตฟอร์ม SaaS



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}



* การแปลง JSON แบบกลุ่มสำหรับการวิเคราะห์และการรายงาน

* การผสานระบบที่ใช้ API เพื่อการบริโภคข้อมูลสไลด์แบบ real-time

* การแปลงโดยเรียกใช้สำหรับแดชบอร์ดเว็บหรือมือถือแบบไดนามิก

* การสกัดเนื้อหาของสไลด์อัตโนมัติเป็น JSON โครงสร้างเพื่อการประมวลผล



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}