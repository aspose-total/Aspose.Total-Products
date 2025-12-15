---
title: สร้าง DOC ใน Python
description: สร้างไฟล์ DOC โดยใช้แอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Word 

family: total
platformtag: Python
feature: create
informat: DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="สร้าง DOC โดยใช้ Python" h2="สร้าง DOC ผ่านแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนาที่กำลังพยายามสร้างไฟล์ DOC ผ่านแอพพลิเคชั่น Python? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการสร้างเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ รวมถึงไฟล์ Microsoft Office และรูปภาพ [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) ทำให้กระบวนการสร้างนี้ง่ายขึ้น นอกจากนี้ นักพัฒนายังสามารถปรับปรุงแอปพลิเคชันเพื่อแก้ไขไฟล์ DOC ได้อย่างง่ายดาย 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้างไฟล์ DOC ใน Python" %}}

- สร้างวัตถุคลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- สร้างคลาสอ็อบเจ็กต์ [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/)
- เพิ่มข้อความลงในไฟล์โดยใช้วิธี [DocumentBuilder.write()](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/write/)
- บันทึกโดยใช้วิธี [save()](https://reference.aspose.com/words/python-net/aspose.words/document/save/) โดยส่งเส้นทางเอกสาร DOC ที่เกี่ยวข้อง

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirements" %}}

- สำหรับการสร้างเอกสาร DOC จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) 
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.words``` 
- นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Words](https://docs.aspose.com/words/python-net/system-requirements/)) และสำหรับ Linux ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และปฏิบัติตาม [INSTALL](https://docs.aspose.com/words/python-net/installation/) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="สร้าง DOC ใน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



DOC — การสร้างไฟล์ `.doc` (ไฟล์ Word ที่เป็นรูปแบบไบนารีเก่า) ผ่าน Python APIs ช่วยให้การอัตโนมัติสำหรับระบบที่เก่าและรักษาความเข้ากันได้กับเครื่องมือเก่าได้ การใช้ Python โดยทั่วไปจะพึงพอใจกับไลบรารีที่สามารถสร้างโครงสร้างไบนารีหรือใช้ COM automation บน Windows เพื่อส่งออกหรือบันทึกเอกสารไบนารีแบบคลาสสิกจากเนื้อหาโปรแกรม



การสร้างสคริปต์ DOC เป็นประโยชน์เมื่อต้องการความเข้ากันได้ย้อนหลัง เอกสารที่สร้างขึ้นสามารถรวมข้อความโครงสร้าง การจัดรูปแบบพื้นฐาน หัวกระดาษ/ท้ายกระดาษ และวัตถุฝังอยู่ได้ตามที่รองรับ



การอัตโนมัติช่วยให้มีท่อการแปลงที่ยอมรับแหล่งที่มาที่เป็นรูปแบบใหม่ (markdown, HTML, DOCX) และส่งออก `.doc` สำหรับการเก็บถาวรหรือการรวมกับแอปพลิเคชันเก่า



{{% blocks/products/pf/agp/feature-section-col title="กรณีการใช้งานหลัก" %}}



* **การบูรณาการระบบเก่า**

&nbsp; สร้างไฟล์ .doc สำหรับซอฟต์แวร์องค์กรที่เก่าที่ต้องการรูปแบบไบนารี



* **การส่งออกเพื่อเก็บถาวร**

&nbsp; แปลงเอกสารที่เป็นรูปแบบใหม่เป็น .doc เพื่อการเก็บรักษาในระยะยาวเมื่อต้องการตามนโยบายเก่า



* **ความสามารถในการทำงานร่วมกับเครื่องมือเก่า**

&nbsp; สร้างผลลัพธ์ .doc เพื่อให้มั่นใจในความเข้ากันได้กับระบบการผสานจดหมายหรือการพิมพ์ที่เก่า



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}



* **การแปลงรูปแบบโดยอัตโนมัติ**

&nbsp; แปลงจำนวนมากของ DOCX เป็น DOC ในงานที่กำหนดเวลาสำหรับการทดสอบความเข้ากันได้



* **การส่งออกจากเทมเพลตโดยสคริปต์**

&nbsp; ใช้การสร้างตามเทมเพลตที่บังคับให้เอกสารสุดท้ายเป็น .doc สำหรับกระบวนการต่อท้าย



* **การรวมกับท่อ ETL**

&nbsp; รวมการสร้าง DOC เข้ากับงาน ETL ที่เตรียมเอกสารสำหรับผู้บริโภคเก่า



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}