---
title: แยกข้อความและรูปภาพจากไฟล์ PDF ออนไลน์และใช้ Python
description: แอพแยกวิเคราะห์ไฟล์ PDF ออนไลน์ รหัส Python API เพื่อแยกรูปภาพและข้อความจากเอกสาร PDF

family: total
platformtag: Python
feature: Parse
informat: PDF
otherformats: Word DOCX DOC DOTX DOT RTF ODT OTT PDF Excel XLS XLSX XLSM XLSB ODS Powerpoint PPT PPTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="แยกไฟล์ PDF ออนไลน์ รวมถึงแยกข้อความหรือรูปภาพผ่าน Python" h2="พัฒนาแอพพลิเคชั่นยูทิลิตี้แยกวิเคราะห์เอกสาร PDF ที่ใช้ Python ที่ทรงพลังรหัสที่แสดงสำหรับรูปภาพเอกสาร PDF และการแยกข้อความผ่าน Python" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แยกวิเคราะห์เอกสาร PDF ผ่านแอปออนไลน์" %}}

1. นำเข้าไฟล์ PDF เพื่อแยกวิเคราะห์โดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปแยกวิเคราะห์
1. ขึ้นอยู่กับขนาดของไฟล์ PDF และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'แยกวิเคราะห์ตอนนี้' เพื่อแยกวิเคราะห์เอกสาร
1. ดาวน์โหลดไฟล์แยกวิเคราะห์เพื่อดูได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="แยกข้อความจากไฟล์ PDF ผ่าน Python" %}}

1. API อ้างอิงภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
1. โหลดไฟล์ PDF โดยใช้คลาส Document
1. ใช้วิธีการบันทึกเพื่อบันทึกเป็นไฟล์ .txt
1. เนื้อหา PDF ทั้งหมดถูกเรนเดอร์เป็นข้อความ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="ตัวอย่างโค้ดใน Python เพื่อแยกข้อความเอกสาร PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "5c38d534a5a47b6e6c0e62620a50c6b9" "extract-text-from-pdf.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="แยกรูปภาพจากไฟล์ PDF ผ่าน Python" %}}

1. API อ้างอิงภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
1. โหลด PDF โดยใช้อ็อบเจ็กต์คลาส Document
1. บันทึกไฟล์เป็นไฟล์ Word
1. โหลดไฟล์ Word โดยใช้วัตถุคลาสเอกสาร
1. รูปภาพที่จัดเก็บไว้ในโหนดรูปร่างในวัตถุเอกสาร
1. หากต้องการเลือกโหนดรูปร่างทั้งหมด ให้ใช้เมธอด Document.get_child_nodes
1. วนซ้ำคอลเลกชันโหนดผลลัพธ์
1. หาก Shape.has_image ส่งกลับค่าจริง
1. ใช้คุณสมบัติ Shape.image_data เพื่อแยกข้อมูลรูปภาพ
1. บันทึกข้อมูลภาพลงในไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="ตัวอย่างโค้ดใน Python เพื่อแยกรูปภาพเอกสาร PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "5c38d534a5a47b6e6c0e62620a50c6b9" "extract-images-from-pdf.py" >}}

{{% /blocks/products/pf/agp/code-block %}}


{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Develop PDF File Parser Application via Python</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้แยกวิเคราะห์ PDF หรือไม่ด้วย [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) ซึ่งเป็น API ลูกของ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) นักพัฒนาหลามทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันตัวแยกวิเคราะห์เอกสารได้ไลบรารี Python อันทรงพลังช่วยให้สามารถตั้งโปรแกรมโซลูชันการแยกวิเคราะห์เอกสารเพื่อแยกรูปภาพและข้อความได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ PDF<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ยูทิลิตี้ Python เพื่อประมวลผลไฟล์ PDF สำหรับแอป parser" %}}
มีตัวเลือกอื่นในการติดตั้ง "[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)" หรือ "[Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/)" ลงในระบบของคุณโปรดเลือกรายการที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:<br /><br />

- ติดตั้ง [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) จาก [PyPI](https://pypi.org/project/aspose-words/)
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose-pdf```

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

- ติดตั้ง Python 3.5 หรือใหม่กว่าแล้ว
- ไลบรารีรันไทม์ GCC-6 (หรือใหม่กว่า)
- สำหรับ Python 3.5-3.7: จำเป็นต้องมี pymalloc build ของ Python
<br /><br />
สำหรับรายละเอียดเพิ่มเติม โปรดดูที่ [Product Documentation](https://docs.aspose.com/words/python-net/system-requirements/)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


```
{{< blocks/products/pf/agp/feature-section >}}



การวิเคราะห์ **เอกสาร PDF** ด้วย Python APIs ช่วยให้สามารถสกัดข้อความและข้อมูลเค้าโครงร่างจากรูปแบบเลเยอร์คงที่ที่ใช้กันอย่างแพร่หลาย ไฟล์ PDF เป็นไฟล์ที่พบบ่อยในรายงาน ใบแจ้งหนี้ และบันทึกทางการ.



การวิเคราะห์ PDF อัตโนมัติช่วยปลดล็อคเนื้อหาที่ไม่สามารถแก้ไขได้สำหรับการวิเคราะห์ การค้นหา และการรวมระบบโดยไม่ต้องมีการแทรกแซงด้วยมือ.



{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}



* **การสกัดข้อมูลจากรายงาน**  

&nbsp; ดึงข้อมูลข้อความจากรายงาน PDF แบบคงที่.



* **การประมวลผลเก็บถาวรเอกสาร**  

&nbsp; แปลง PDF เป็นข้อความที่สามารถค้นหาและทำดัชนี.



* **ระบบการค้นหาข้อมูล**  

&nbsp; เปิดโอกาสให้ค้นพบเนื้อหาในคอลเลกชันขนาดใหญ่ของ PDF.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}



* **การนำเข้า PDF ตามกำหนดเวลา**  

&nbsp; ประมวลผล PDF ที่เข้ามาโดยอัตโนมัติตามระยะเวลาที่กำหนด.



* **การประมวลผลข้อความเป็นลำดับมาตรฐาน**  

&nbsp; ทำความสะอาดและมาตรฐานข้อความ PDF ที่สกัดได้โดยโปรแกรม.



* **การเปิดใช้งานการวิเคราะห์ล่าสุด**  

&nbsp; นำเนื้อหา PDF ที่วิเคราะห์ได้เข้าสู่การทำงานทางวิเคราะห์หรือการทำงานด้าน Machine Learning.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="คำถามที่พบบ่อย" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>คำถามที่พบบ่อย</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ฉันสามารถใช้โค้ด Python ข้างต้นในแอปพลิเคชันของฉันได้หรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ใช่ คุณสามารถดาวน์โหลดโค้ดนี้และใช้เพื่อวัตถุประสงค์ในการพัฒนาแอปพลิเคชันตัวแยกวิเคราะห์เอกสารที่ใช้ Pythonโค้ดนี้ทำหน้าที่เป็นทรัพยากรอันมีค่าในการปรับปรุงฟังก์ชันการทำงานและความสามารถของโปรเจ็กต์ของคุณในโดเมนของการประมวลผลเอกสารแบ็กเอนด์ เช่น การอ่านโหนด และการโหลดเอกสารเพื่อแยกข้อความและรูปภาพ</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>แอพแยกวิเคราะห์เอกสารออนไลน์นี้ใช้งานได้บน Windows เท่านั้นหรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณมีความยืดหยุ่นในการเริ่มแยกวิเคราะห์เอกสารบนอุปกรณ์ใดก็ได้ โดยไม่คำนึงถึงระบบปฏิบัติการที่อุปกรณ์ทำงาน ไม่ว่าจะเป็น Windows, Linux, Mac OS หรือ Androidสิ่งที่คุณต้องมีคือเว็บเบราว์เซอร์ร่วมสมัยและการเชื่อมต่ออินเทอร์เน็ตที่ใช้งานได้</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การใช้แอปออนไลน์เพื่อแยกวิเคราะห์เอกสาร PDF ปลอดภัยหรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แน่นอน! ไฟล์เอาต์พุตที่สร้างผ่านบริการของเราจะถูกลบออกจากเซิร์ฟเวอร์ของเราโดยอัตโนมัติอย่างปลอดภัยภายในกรอบเวลา 24 ชั่วโมงด้วยเหตุนี้ ลิงก์ที่แสดงที่เกี่ยวข้องกับไฟล์เหล่านี้จะหยุดทำงานหลังจากช่วงเวลานี้</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>เบราว์เซอร์ใดที่ควรใช้แอพ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณสามารถใช้เว็บเบราว์เซอร์สมัยใหม่เช่น Google Chrome, Firefox, Opera หรือ Safari สำหรับโปรแกรมแยกวิเคราะห์เอกสาร PDF ออนไลน์ อย่างไรก็ตาม หากคุณกำลังพัฒนาแอปพลิเคชันบนเดสก์ท็อป เราขอแนะนำให้ใช้ API การประมวลผลเอกสาร Aspose.Total เพื่อการจัดการที่มีประสิทธิภาพ</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}