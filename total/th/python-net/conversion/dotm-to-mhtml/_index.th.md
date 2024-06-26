---
title: แปลง DOTM เป็น MHTML ใน Python
description: รูปแบบไฟล์เก็บถาวรเว็บ DOTM เป็น mhtml และการแปลงไฟล์ HtmlFixed ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องใช้ Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง DOTM เป็น MHTML โดยใช้ Python" h2="การแปลง DOTM เป็น MHTML, HtmlFixed และ HTML ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องติดตั้ง Microsoft Word<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่กำลังพยายามเพิ่มคุณสมบัติการแปลง DOTM เป็น MHTML (รูปแบบไฟล์เก็บถาวรบนเว็บ) หรือ HtmlFixed หมายถึงต้องการบันทึกเอกสารในรูปแบบ HTML โดยใช้องค์ประกอบที่จัดตำแหน่งไว้อย่างสมบูรณ์ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ 

เราใช้ [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API ซึ่งเป็นส่วนหนึ่งของ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) Package เพื่อเพิ่มคุณลักษณะการแปลง DOTM เป็น MHTML ในกรณีที่ไฟล์ DOTM ง่าย ๆ ก็จะมีโค้ดเพียงสองบรรทัด โหลดไฟล์ DOTM และเรียกวิธีการบันทึกด้วยเส้นทางไฟล์ที่เหมาะสมพร้อมกับการแจงนับ SaveFormat เป็น MHTML หรือ HTML_FIXED แต่ในกรณีที่จำเป็นต้องคืนค่ารูปแบบเอกสารให้ใกล้เคียงกับต้นฉบับ ก็จำเป็นต้องบันทึกข้อมูลเพิ่มเติมไว้ในเอกสารผลลัพธ์ที่เรียกว่า ข้อมูลการเดินทางไปกลับ

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ทำอย่างไร แปลง DOTM เป็น MHTML ใน Python" %}}
- โหลดไฟล์ DOTM ต้นทางโดยใช้คลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- สร้างอินสแตนซ์ของ [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- ตั้งค่า export_roundtrip_information เป็น True
- ระบุ [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) เป็น MHTML
- เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat เป็นพารามิเตอร์ ดังนั้นไฟล์ DOTM ของคุณจะถูกแปลงเป็น MHTML ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลงรูปแบบ DOTM เป็น MHTML หรือ HtmlFixed จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.words```
- นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Words](https://docs.aspose.com/words/python-net/system-requirements/)) และสำหรับ Linux ให้ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และปฏิบัติตามคำแนะนำทีละขั้นตอน [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก DOTM เป็น MHTML ใน Python - Simple" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การแปลง DOTM เป็น MHTML ใน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}