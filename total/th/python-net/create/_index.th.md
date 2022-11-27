---
title: สร้างไฟล์โดยใช้ Python 

description: สร้างข้อความและเอกสาร Microsoft Word โดยไม่ต้องติดตั้ง Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="สร้างเอกสารโดยใช้ Python" h2="สร้างไฟล์ Text และ Microsoft Word DOCX, DOC ภายใน Python Applications โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}
การจัดเก็บข้อมูลเป็นพื้นฐานของแอปพลิเคชันซอฟต์แวร์ใดๆ ขึ้นอยู่กับลักษณะแอปพลิเคชัน ตำแหน่งการจัดเก็บอาจเป็นฐานข้อมูล, XML, JSON, ไฟล์ข้อความ, รายงาน Excel หรือเอกสาร Microsoft Word ไฟล์ I/O เป็นส่วนหนึ่งของภาษาใดๆ และส่วนใหญ่ ภาษารวมถึง Python รองรับการเขียนข้อมูลลงในไฟล์ข้อความ ลองพิจารณาภาษาไพทอน การเขียนไฟล์ข้อความที่มีอยู่โดยใช้ Python มีวิธีการเปิด เขียน และปิดสำหรับงานนี้ ขั้นแรกให้เปิดไฟล์ที่มีเส้นทางของไฟล์ที่เกี่ยวข้องและผนวกหรือเขียนคุณลักษณะเป็นอาร์กิวเมนต์ จากนั้นเขียนข้อความที่ต้องการลงในไฟล์และปิดไฟล์โดยใช้เมธอด close() 

สำหรับการสร้างเอกสาร Microsoft Word โดยใช้ Python เราใช้แพ็คเกจ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API ที่มี [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API เป็นส่วนหนึ่งของแพ็คเกจ API นี้มอบโซลูชันการทำเอกสารอัตโนมัติแบบเต็มรูปแบบสำหรับใบแจ้งหนี้ รายงาน และบทความทางเทคนิค ขั้นตอนการสร้างเอกสารคำตามรายการด้านล่าง

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="วิธีสร้างไฟล์ข้อความโดยใช้ Python" %}}

การสร้างและเขียนไปยังไฟล์ข้อความเป็นเรื่องง่าย Python จัดเตรียมเมธอด open() พร้อมพารามิเตอร์สามตัวและต้องใช้พารามิเตอร์ตัวใดตัวหนึ่งพร้อมกับพา ธ ของไฟล์ สามพารามิเตอร์คือ "x", "a" และ "w" โดยการให้ "x" ไฟล์ใหม่จะถูกสร้างขึ้น แต่แสดงข้อผิดพลาดในกรณีที่ไฟล์นั้นมีอยู่แล้ว โดยการระบุ "a" ไฟล์ข้อความใหม่จะถูกสร้างขึ้นหากไม่มีอยู่ และในกรณีที่มีอยู่ เนื้อหาจะถูกเพิ่มต่อท้าย และสุดท้ายให้ "w" เอกสารข้อความใหม่จะถูกสร้างขึ้นและเขียนทับด้วยเนื้อหาใหม่ในกรณีที่มีอยู่แล้ว

{{% blocks/products/pf/feature-page-code h3="Python - สร้างไฟล์ข้อความ" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างเอกสาร Microsoft Word" %}}

Total Python Word API มีคุณสมบัติหลายอย่างรวมถึงการสร้างไฟล์ Microsoft Word การแทรกรูปภาพและข้อความภายในเอกสาร เพิ่มตารางและรายการภายในไฟล์ ตลอดจนแก้ไขเอกสารที่มีอยู่ได้อย่างง่ายดาย ในการสร้างกระบวนการเอกสาร Microsoft Word ให้สร้างวัตถุของคลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) และ [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/) เพิ่มข้อความ ย่อหน้า รายการ และตารางที่จำเป็นภายในเอกสาร และสุดท้ายบันทึก

{{% blocks/products/pf/feature-page-code h3="Python - สร้างเอกสาร Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create">}}