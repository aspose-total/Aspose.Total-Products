---
title: การแปลงเอกสารผ่าน C++ 
url: /th/cpp/conversion/
description: แปลงรูปแบบเอกสารต่างๆ เช่น Word, Excel, PowerPoint, PDF, JSON, รูปภาพ และอื่นๆ โดยใช้ C++ API 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="การแปลงเอกสารโดยใช้ C++" h2="แปลง Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, รูปภาพ และรูปแบบอื่นๆ มากมายโดยใช้ไลบรารี C++" >}}

{{% blocks/products/pf/feature-page-summary %}}
[ไลบรารี C++ ทั้งหมด](https://products.aspose.com/total/cpp/) แก้ปัญหาการแปลงเอกสาร และนักพัฒนาสามารถทำให้โซลูชันการจัดการเอกสารและการจัดการเอกสารเป็นไปโดยอัตโนมัติ โดยการผสานรวม API ภายในแอปพลิเคชันที่พัฒนาขึ้นใหม่หรือในแอปพลิเคชันที่มีอยู่ โปรแกรมเมอร์ C++ สามารถเพิ่มฟังก์ชันต่างๆ เช่น สร้าง แก้ไข หรือแปลงเอกสารรูปแบบต่างๆ ภายในโซลูชันของตนโดยไม่ต้องพึ่งพาซอฟต์แวร์ใดๆ กรณีทั่วไปบางกรณีเช่น txt เป็น PDF, SVG เป็น PNG, XLSX เป็น CSV, JSON เป็น CSV, Word เป็น PDF, HTML เป็น PDF สามารถแปลงได้อย่างง่ายดาย นอกจากนี้ มีบางกรณีที่ API เกี่ยวข้องตามรายการด้านล่างและลิงก์บางส่วนที่ให้ไว้สำหรับกรณีการแปลงที่เกี่ยวข้อง 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Microsoft Word เป็น Excel" %}}
Total C++ API รองรับการแปลง Microsoft Word DOC/DOCX เป็น Excel  กระบวนการคือ โหลดไฟล์ Word DOC / DOCX โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) การอ้างอิงคลาสและเรียกใช้ [Save](https://reference. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) ฟังก์ชันสมาชิกที่จะแปลงเป็น HTML ในตอนแรก จากนั้นโหลดเอกสาร HTML โดยใช้ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) การอ้างอิงคลาสและเรียกใช้ [Save](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) ฟังก์ชันสมาชิกบันทึกเอกสารในรูปแบบ Excel 

{{% blocks/products/pf/feature-page-code h3="C ++ - การแปลง Word เป็น Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="การแปลง PDF เป็น Word" %}}
ไลบรารีการแปลง C++ ยังรองรับ PDF เป็น word DOC, DOCX และการแปลงรูปแบบอื่นๆ เมื่อพิจารณากรณีของการแสดง PDF เป็น RTF เป็นกระบวนการสองขั้นตอน ขั้นแรกให้แปลง PDF เป็นรูปแบบ Word DOC/DOCX แล้วแปลงเป็น RTF รวมขั้นตอนสำหรับสิ่งนี้ การโหลดไฟล์ PDF โดยใช้ [เอกสาร](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) การอ้างอิงคลาสและเรียกใช้ [บันทึก](https://reference.aspose) .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) ฟังก์ชันสมาชิกในการแปลง PDF เป็น Word ตอนนี้โหลดไฟล์ Word DOC / DOCX อีกครั้งโดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) การอ้างอิงคลาสของ Aspose.Words API และบันทึกเป็นรูปแบบ RTF โดยใช้ [บันทึก](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) ฟังก์ชันสมาชิก

{{% blocks/products/pf/feature-page-code h3="C++ - การแปลง PDF เป็น Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง JSON เป็น Word" %}}
สำหรับการแปลง JSON C++ API รองรับการผสมผสานที่หลากหลาย เช่น JSON เป็น Word, Json เป็น PowerPoint, Word เป็น JSON เป็นต้น พิจารณากรณีของการแปลง Word กระบวนการคือ อ่านข้อมูล JSON ที่ถูกต้องจากไฟล์โดยใช้วัตถุ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ใหม่ แล้วเรียกใช้ [บันทึก](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) วิธีบันทึก JSON เป็นไฟล์ PDF ตอนนี้โหลดไฟล์ที่บันทึกไว้โดยใช้คลาส [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) แล้วบันทึกเป็นรูปแบบเอกสาร word โดยใช้ [บันทึก](https://reference) .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) วิธีการ
{{% blocks/products/pf/feature-page-code h3="C ++ - การแปลง JSON เป็น Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}