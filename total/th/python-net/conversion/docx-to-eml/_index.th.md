---
title: แปลง DOCX เป็น EML ใน Python
description: บันทึก DOCX เป็น EML ภายในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Word หรือ Outlook
url: /th/python-net/conversion/docx-to-eml/
family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง DOCX เป็น EML โดยใช้ Python" h2="การแปลง DOCX เป็น EML ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องติดตั้ง Microsoft Word<sup>&reg;</sup> หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ใครกำลังพยายามเพิ่มคุณสมบัติการแปลง DOCX เป็น EML ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ รวมถึงรูปแบบอีเมล รูปภาพ และ Microsoft Word [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) และ [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) ทำให้การแปลงนี้ทำได้ง่ายโดยใช้ Python เป็นกระบวนการสองขั้นตอน ขั้นแรกให้โหลดไฟล์ DOCX และแสดงผลเป็น HTML ผ่าน [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) ประการที่สอง โหลด HTML ที่แปลงแล้วโดยใช้ [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) และบันทึกเป็นรูปแบบ EML

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง DOCX เป็น EML ใน Python" %}}

- เปิดไฟล์ DOCX ต้นทางโดยใช้คลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์ HTML เอาต์พุตและตัวเลือกการบันทึก HTML ที่เกี่ยวข้องเป็นพารามิเตอร์ ดังนั้นไฟล์ DOCX ของคุณจึงถูกแปลงเป็น HTML ตามเส้นทางที่ระบุ
- ตอนนี้โหลดไฟล์ HTML ที่บันทึกไว้โดยใช้ MailMessage.load
- เรียกวิธีการบันทึกด้วยเส้นทางของไฟล์ที่เกี่ยวข้อง ในที่สุด DOCX ก็ถูกแปลง

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง DOCX เป็น EML จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) และ [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.words``` และ ```pip install Aspose.Email-for-Python-via-NET`` 
- นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Words](https://docs.aspose.com/words/python-net/system-requirements/) และ [Email](https://docs.aspose.com/email/python-net/system-requirements/)) และสำหรับ Linux ให้ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และทำตามคำแนะนำทีละขั้นตอน [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก DOCX เป็น EML ใน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-email/" name="DOCX ถึง EMAIL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-msg/" name="DOCX ถึง MSG" description="" >}},
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-pst/" name="DOCX ถึง PST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-ost/" name="DOCX ถึง OST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-oft/" name="DOCX ถึง OFT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-eml/" name="DOCX ถึง EML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-emlx/" name="DOCX ถึง EMLX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-mbox/" name="DOCX ถึง MBOX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-ics/" name="DOCX ถึง ICS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/docx-to-vcf/" name="DOCX ถึง VCF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}