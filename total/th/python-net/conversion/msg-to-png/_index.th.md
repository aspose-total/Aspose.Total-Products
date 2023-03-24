---
title: แปลง MSG เป็น PNG ใน Python
description: บันทึก MSG เป็น PNG ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องใช้ Microsoft Outlook หรือ Word 

family: total
platformtag: Python
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง MSG เป็น PNG โดยใช้ Python" h2="การแปลง MSG เป็น PNG ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องติดตั้ง Microsoft Word<sup>&reg;</sup> หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ใครกำลังพยายามเพิ่มคุณสมบัติการแปลง MSG เป็น PNG ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ รวมถึงรูปแบบอีเมล รูปภาพ และ Microsoft Word [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) และ [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) ทำให้การแปลงนี้ทำได้ง่ายโดยใช้ Python เป็นกระบวนการสองขั้นตอน ขั้นแรกให้โหลดอีเมลและแสดงผลเป็น HTML ผ่าน [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) ประการที่สอง โหลด HTML ที่แปลงแล้วโดยใช้ [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) และบันทึกเป็นรูปแบบ PNG

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง MSG เป็น PNG ใน Python" %}}

- เปิดไฟล์ MSG ต้นทางโดยใช้คลาส MailMessage.load
- เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์ HTML เอาต์พุตและตัวเลือกการบันทึก HTML ที่เกี่ยวข้องเป็นพารามิเตอร์ ดังนั้นไฟล์ MSG ของคุณจึงถูกแปลงเป็น HTML ตามเส้นทางที่ระบุ
- ตอนนี้โหลดไฟล์ HTML ที่บันทึกไว้โดยใช้ [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- เรียกวิธีการบันทึกด้วยเส้นทางของไฟล์ที่เกี่ยวข้อง ในที่สุด MSG ก็ถูกแปลง

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง MSG เป็น PNG จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) และ [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.words``` และ ```pip install Aspose.Email-for-Python-via-NET`` 
- นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Words](https://docs.aspose.com/words/python-net/system-requirements/) และ [Email](https://docs.aspose.com/email/python-net/system-requirements/)) และสำหรับ Linux ให้ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และทำตามคำแนะนำทีละขั้นตอน [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก MSG เป็น PNG ใน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}