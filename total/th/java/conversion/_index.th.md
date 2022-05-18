---
title: การแปลงรูปแบบไฟล์ผ่าน Java 
url: /th/java/conversion/
description: แปลง Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, รูปภาพ 3 มิติ, ไดอะแกรม, รูปแบบวิดีโอ และรูปแบบอื่น ๆ ด้วยโค้ด Java เพียงไม่กี่บรรทัด
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="การแปลงรูปแบบไฟล์ผ่าน Java" h2="แปลงเอกสาร Microsoft<sup>&reg;</sup>, PDF, รูปภาพ, HTML และไฟล์อื่น ๆ หลายไฟล์โดยไม่ต้องใช้ซอฟต์แวร์อื่น" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) เร่งความเร็วในการพัฒนาโซลูชันการจัดการเอกสารตั้งแต่เริ่มต้น หรือปรับปรุงแอปพลิเคชันที่มีอยู่เพื่อจัดการเอกสารได้อย่างง่ายดาย API ไม่เพียงแต่สร้าง แก้ไข และแปลงเอกสาร Microsoft Office แต่ยังจัดการ PDF, HTML, รูปภาพ TIFF, JPG, PNG, BMP และ SVG, ไฟล์อีเมล, รูปแบบวิดีโอ, 3D, CAD และอีกมากมาย เป็นชุดของโซลูชันการจัดการเอกสารและการจัดการเอกสาร API โดยไม่ต้องพึ่งพาซอฟต์แวร์ใด ๆ ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โปรแกรมเมอร์สามารถสร้าง อัปเดต แสดงผล พิมพ์ และแปลงระหว่างรูปแบบที่ได้รับความนิยมส่วนใหญ่ภายในแอปพลิเคชันที่ใช้ Java ได้อย่างง่ายดาย

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="การแปลงคำเป็น Excel" %}}
Total API รองรับไม่เพียงแต่การแปลงระหว่างรูปแบบ Microsoft Word แต่ยังแปลง Word เป็น Excel, PDF, HTML, รูปภาพ, EPUB, Markdown และ XPS ขั้นตอนการแปลงเป็นเรื่องง่าย ลองพิจารณากรณีของการแปลง **Word to Excel** โหลดไฟล์ Microsoft Word โดยใช้คลาส [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) และแปลง **WORD เป็น HTML** โดยใช้ [Save method](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) ถัดไป เปิดเอกสาร HTML ที่แปลงแล้วโดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) และบันทึกเอกสารเป็นรูปแบบ XLSX โดยใช้ [Save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธี
 นักพัฒนายังสามารถแปลง [Word เป็น PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/)


{{% blocks/products/pf/feature-page-code h3="Java การแปลงคำเป็น Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="แปลง PDF เป็นรูปภาพ" %}}
API รองรับการแปลงไฟล์ PDF เป็นรูปภาพ เช่น JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel และรูปแบบอื่นๆ สำหรับการแปลง PDF เป็นรูปภาพ ให้พิจารณาว่ารูปภาพ JPG เป็นไฟล์เป้าหมาย กระบวนการคือ โหลดไฟล์ PDF โดยใช้คลาสเอกสารและเริ่มต้นวัตถุ [คลาส JpegDevice](https://apireference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) และแสดง PDF เป็น JPEG ผ่าน [กระบวนการ](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) วิธีการ
โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://apireference.aspose.com/imaging/java/aspose.imaging/image) แล้วเรียกใช้เมธอดบันทึกในที่สุด

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ PowerPoint เป็น Excel" %}}

สำหรับการแปลงไฟล์ Microsoft PowerPoint เป็นไฟล์ต่างๆ รวมถึง Excel Word, MHTML, API ย่อยที่เกี่ยวข้องซึ่งเกี่ยวข้องกับ Aspose.Total หลักสำหรับ Java API ขั้นตอนการแปลงไฟล์ PowerPoint เป็นเอกสาร Excel โหลดไฟล์ PowerPoint โดยใช้ [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) และแปลง **PowerPoint เป็น HTML** โดย โดยใช้วิธี [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) ถัดไปโหลดเอกสาร HTML ที่แปลงแล้วโดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) และบันทึกเอกสารเป็นรูปแบบ EXCEL โดยใช้ [save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธี รหัสสำหรับการแปลง **PowerPoint เป็น Word** อยู่ในรายการด้วย

{{% blocks/products/pf/feature-page-code h3="การแปลง Java PowerPoint เป็น Excel" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint เป็น Word Conversion" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}