---
title: การแปลงเอกสารผ่าน Android API 
url: /th/android-java/conversion/
description: แปลงรูปแบบ Word, Excel, PowerPoint, HTML, PDF และรูปภาพโดยใช้ Android conversion API Android แปลง Office docx, xlsx, pptx เป็น PDF 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="การแปลงเอกสารโดยใช้ Android API" h2="แปลง Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, รูปภาพ และรูปแบบอื่นๆ โดยใช้ Aspose.Total สำหรับ Android ผ่าน Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) ให้การแปลงเอกสารและโซลูชันการจัดการสำหรับแอปพลิเคชัน Android โดยไม่ต้องพึ่งพาซอฟต์แวร์อื่นใด โปรแกรมเมอร์สามารถทำให้โซลูชันการจัดการเอกสารและการจัดการเอกสารเป็นไปโดยอัตโนมัติได้อย่างง่ายดายโดยการรวม API ภายในแอปพลิเคชันที่พัฒนาขึ้นใหม่หรือในแอปพลิเคชันที่มีอยู่ การรวม API ทำให้โปรแกรมเมอร์สามารถเพิ่มฟังก์ชันการทำงานเพื่อสร้าง แก้ไข หรือแปลงเอกสารรูปแบบต่างๆ ภายในแอปพลิเคชันได้อย่างง่ายดาย PDF Converter API ใน Android จัดการกรณีการแปลงเช่น Office DOCX, XLSX, PPTX เป็น PDF หรือในทางกลับกัน นอกจากนี้ มีบางกรณีที่ API เกี่ยวข้องตามรายการด้านล่างและลิงก์บางส่วนที่ให้ไว้สำหรับกรณีการแปลงที่เกี่ยวข้อง 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง PDF เป็น CSV" %}}
Total Android API รองรับการแปลง PDF เป็น Excel XLSX และ CSV เป็นกระบวนการสองขั้นตอน Total API สองรายการ [Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) และ Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/เซลล์/android-java/) ที่เกี่ยวข้อง กระบวนการคือคุณสามารถแปลงรูปแบบ PDF เป็น Excel XLSX ก่อนจากนั้นจึงเปลี่ยน XLSX เป็น CSV รายละเอียดเพิ่มเติม โหลดไฟล์ PDF ผ่าน [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) คลาสและแสดงผลเป็น XLSX ผ่าน [บันทึก](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) วิธี ถัดไป ให้โหลดเอกสาร XLSX ที่แสดงผลโดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) และเรียกใช้ [save](https://reference.aspose.com) /cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธี

{{% blocks/products/pf/feature-page-code h3="Android - การแปลง PDF เป็น Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="การแปลง Excel เป็น Word" %}}
Android API จัดการการแปลง Excel เช่นกัน กระบวนการคือ โหลดไฟล์ EXCEL XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) และแปลง EXCEL เป็น PDF โดยตั้งค่า SaveFormat เป็น AUTO ก่อน ถัดไปโหลดไฟล์ PDF ที่บันทึกไว้โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเรียกใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) วิธีการบันทึกเอกสารในรูปแบบ Word DOC / DOCX

{{% blocks/products/pf/feature-page-code h3="Android - การแปลง Excel เป็น Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง POWERPOINT เป็น HTML และ MHTML" %}}
Android Total API เกี่ยวข้องกับรูปแบบต่างๆ รวมถึงไฟล์ PowerPoint จึงสามารถแปลงงานนำเสนอเป็น HTML และ MHTML ได้ กระบวนการคือ โหลดไฟล์ POWERPOINT PPT/ PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) และเรียกใช้ [บันทึก](https://reference.aspose) วิธีการแปลง POWERPOINT เป็น HTML ยิ่งกว่านั้น ตอนนี้ให้โหลดเอกสาร HTML ที่แปลงแล้วโดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) แล้วโทร [save](https://reference.aspose) .com/cells/java/com.aspose.cells/) สำหรับการแปลง MHTML 
{{% blocks/products/pf/feature-page-code h3="Android - การแปลงสไลด์ PowerPoint เป็น HTML และ MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}