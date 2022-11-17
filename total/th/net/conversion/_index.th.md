---
title: การแปลงรูปแบบไฟล์ผ่าน C# 

description: แปลง Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, รูปภาพ 3 มิติ, ไดอะแกรม, รูปแบบวิดีโอ และไฟล์ยอดนิยมอื่น ๆ อีกมากมายด้วยโค้ด C# เพียงไม่กี่บรรทัด
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="การแปลงรูปแบบไฟล์ผ่าน C# .NET" h2="แปลง Microsoft<sup>&reg;</sup> ไฟล์ Office, PDF, รูปภาพ, HTML และรูปแบบอื่นๆ โดยไม่ต้องใช้ซอฟต์แวร์อื่น" >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET รวมไลบรารี](https://products.aspose.com/total/net/) เร่งความเร็วในการพัฒนาโซลูชันการจัดการเอกสารตั้งแต่เริ่มต้น หรือปรับปรุงแอปพลิเคชันที่มีอยู่เพื่อจัดการกับการจัดการเอกสารได้อย่างง่ายดาย API ไม่เพียงจัดการเอกสาร Microsoft Office เท่านั้น แต่ยังจัดการ PDF, HTML, รูปภาพ TIFF, JPG, PNG, BMP และ SVG, ไฟล์อีเมล, รูปแบบวิดีโอ, รูปแบบข้อมูล GIS และอีกมากมาย เป็นชุดที่สมบูรณ์ของ API โซลูชันการจัดการเอกสารและการจัดการเอกสารโดยไม่ต้องพึ่งพาซอฟต์แวร์ใดๆ โปรแกรมเมอร์สามารถสร้าง อัปเดต แสดงผล พิมพ์ และแปลงระหว่างรูปแบบที่ได้รับความนิยมส่วนใหญ่ภายในแอปพลิเคชันที่ใช้ .NET ได้อย่างง่ายดาย

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Word เป็น PDF" %}}
Total API รองรับไม่เพียงแต่การแปลงระหว่างรูปแบบ Microsoft Word แต่ยังแปลง Word เป็น PDF, HTML, รูปภาพ, EPUB, Markdown และ XPS ขั้นตอนการแปลงเป็นเรื่องง่าย โหลดเอกสารผ่านคลาสเอกสารและเพียงเรียกวิธีการบันทึกด้วยรูปแบบเป้าหมาย มันง่ายมาก นักพัฒนาสามารถตรวจสอบ [ผลการแปลง](https://products.aspose.com/words/net/conversion/word-to-pdf/) ก่อนการรวมโค้ดของ **Word to PDF**


{{% blocks/products/pf/feature-page-code h3="C# - การแปลง Word เป็น PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="แปลง PDF เป็นรูปภาพ" %}}
API รองรับการแปลง PDF เป็นรูปภาพ, Powerpoint, Excel และรูปแบบอื่นๆ สำหรับการแปลง PDF เป็นรูปภาพ ให้พิจารณาว่ารูปภาพ JPG เป็นไฟล์เป้าหมาย กระบวนการคือ โหลดไฟล์ PDF โดยใช้คลาสเอกสารและเริ่มต้นวัตถุ [คลาส JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) และแสดง PDF เป็น JPEG ผ่าน [กระบวนการ](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) วิธีการ
โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) และสุดท้ายเรียกวิธีการบันทึก

{{% blocks/products/pf/feature-page-code h3="C# - การแปลง PDF เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Excel เป็น Word และ PowerPoint" %}}

สำหรับการแปลงรูปแบบ Microsoft Excel เป็นไฟล์ต่างๆ รวมถึง Word และ PowerPoint API ย่อยที่เกี่ยวข้องซึ่งเกี่ยวข้องกับ Aspose.Total หลักสำหรับ .NET API ขั้นตอนการแปลงไฟล์ Excel เป็นเอกสาร Word โหลดไฟล์ EXCEL โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) และแปลง EXCEL เป็น PDF ก่อน แล้วตั้งค่า SaveFormat เป็น Auto จากนั้นโหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาสเอกสารแล้วเรียกเมธอดบันทึกและตั้งค่า Doc, Docx เป็น SaveFormat รหัสยังระบุไว้สำหรับการแปลง Microsoft **Excel เป็น Powerpoint**

{{% blocks/products/pf/feature-page-code h3="C# - การแปลง JSON เป็น Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - การแปลง Excel เป็น JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}