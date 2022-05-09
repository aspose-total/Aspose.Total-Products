---
title: แปลง DOTX เป็นรูปแบบ JSON ผ่าน Java
description: แปลงรูปแบบ DOTX เป็น JSON ผ่าน Java โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel
url_ignore: /th/java/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง DOTX เป็นรูปแบบ JSON ผ่าน Java" h2="บน Premise Java API เพื่อแปลง DOTX เป็น JSON โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลงรูปแบบ DOTX เป็นรูปแบบ JSON ผ่าน [Aspose.Total for Java](https://products.aspose.com/total/java/) เป็นกระบวนการสองขั้นตอนง่ายๆ เมื่อใช้ API การจัดการเอกสารและการแปลงที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะส่งออก DOTX เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณจะแปลง HTML เป็น JSON ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง DOTX เป็นรูปแบบ JSON ผ่าน Java" %}}
1. เปิดไฟล์ DOTX โดยใช้คลาส [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. แปลง DOTX เป็น HTML โดยใช้ [บันทึก](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ JSON โดยใช้ [บันทึก](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
คุณยังสามารถเปิดเอกสารที่มีการป้องกันด้วยรหัสผ่านได้โดยใช้ API หากเอกสาร DOTX ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็นรูปแบบ JSON ได้โดยไม่ต้องใช้รหัสผ่าน API อนุญาตให้คุณเปิดเอกสารที่เข้ารหัสโดยส่งรหัสผ่านที่ถูกต้องในออบเจกต์ LoadOptions ตัวอย่างโค้ดต่อไปนี้แสดงวิธีลองเปิดเอกสารที่เข้ารหัสด้วยรหัสผ่าน:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง DOTX ที่ได้รับการป้องกันเป็นรูปแบบ JSON ผ่าน Java" %}}
ขณะที่คุณกำลังแปลง DOTX เป็น JSON คุณยังสามารถตั้งค่าช่วงเป็นรูปแบบ JSON เอาต์พุตของคุณได้ ในการตั้งค่าช่วง คุณสามารถเปิด HTML ที่แปลงแล้วโดยใช้คลาสเวิร์กบุ๊ก สร้างช่วงของข้อมูลที่จะส่งออกโดยใช้เมธอด Cells.createRange เรียกเมธอด JsonUtility.exportRangeToJson ด้วยการอ้างอิงของ Range & ExportRangeToJsonOptions และเขียนสตริงข้อมูล JSON ไปยังไฟล์ผ่าน วิธีการ BufferedWriter.write 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlam/" name="DOTX ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlt/" name="DOTX ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-csv/" name="DOTX ถึง CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsx/" name="DOTX ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-fods/" name="DOTX ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xltm/" name="DOTX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsm/" name="DOTX ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xltx/" name="DOTX ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-ods/" name="DOTX ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsb/" name="DOTX ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-excel/" name="DOTX ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-sxc/" name="DOTX ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-tsv/" name="DOTX ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-dif/" name="DOTX ถึง DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}