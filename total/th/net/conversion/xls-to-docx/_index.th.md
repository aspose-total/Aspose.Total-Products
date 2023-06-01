---
title: แปลง XLS เป็น DOCX ด้วย .NET หรือด้วยตัวแปลงออนไลน์ฟรี
description: แปลง XLS เป็น DOCX บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms หรือทางออนไลน์ ทดสอบตัวแปลง XLS เป็น DOCX ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด

family: total
platformtag: net
feature: conversion
informat: XLS
outformat: DOCX
otherformats: DOC POWERPOINT PPTX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="แปลง XLS เป็น DOCX ผ่าน C# หรือแอพออนไลน์" h2="ส่งออก Excel&reg; XLS เป็น DOCX บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="การแปลง XLS เป็น DOCX บน .NET" %}}
1. เปิดไฟล์ XLS โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. แปลง XLS เป็น PDF และตั้งค่า SaveFormat เป็น Auto
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. บันทึกเอกสารในรูปแบบ DOCX โดยใช้วิธี [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) และตั้งค่า Docx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code สำหรับการแปลง XLS เป็น DOCX" gistPath="" %}}
```cs
// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ XLS เป็น DOCX</h3>

<iframe title="เครื่องมือออนไลน์สำหรับการแปลง xls เป็น docx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>คำถามที่พบบ่อย</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ฉันจะแปลง XLS เป็น DOCX ออนไลน์ได้อย่างไร</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แอพออนไลน์สำหรับการแปลง XLS ถูกรวมไว้ด้านบน ในการเริ่มกระบวนการแปลง คุณสามารถลากและวางไฟล์ XLS ของคุณหรือคลิกภายในพื้นที่ที่กำหนดเพื่อนำเข้าเอกสาร จากนั้นคลิกที่ปุ่ม "แปลง" เพื่อเริ่มการแปลง XLS เป็น DOCX เมื่อกระบวนการเสร็จสิ้น คุณสามารถดาวน์โหลดไฟล์ที่แปลงแล้วได้ง่ายๆ เพียงคลิกเดียว และรับผลลัพธ์ที่คุณต้องการในรูปแบบ DOCX</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง XLS ใช้เวลานานเท่าไหร่?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ความเร็วของตัวแปลงออนไลน์นี้เร็ว แต่ขึ้นอยู่กับขนาดของไฟล์ XLS เป็นหลัก หากคุณมีไฟล์ XLS ขนาดเล็ก ก็สามารถแปลงเป็น DOCX ได้ในเวลาเพียงไม่กี่วินาที นอกจากนี้ หากคุณรวมรหัสการแปลงเข้ากับแอปพลิเคชัน .NET ของคุณ ความเร็วของกระบวนการแปลงจะขึ้นอยู่กับว่าคุณได้เพิ่มประสิทธิภาพแอปพลิเคชันของคุณได้ดีเพียงใด</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง XLS เป็น DOCX ปลอดภัยหรือไม่โดยใช้ตัวแปลง Aspose.Total ฟรี</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แน่นอน! หลังจากกระบวนการแปลง XLS เป็น DOCX เสร็จสิ้น ลิงก์ดาวน์โหลดไฟล์ DOCX จะถูกสร้างขึ้นทันที เราให้ความสำคัญกับความปลอดภัยของไฟล์ของคุณ นั่นเป็นเหตุผลว่าทำไมไฟล์ที่อัปโหลดทั้งหมดจึงถูกลบหลังจากผ่านไป 24 ชั่วโมง และลิงก์ดาวน์โหลดจะหยุดทำงานหลังจากช่วงเวลาดังกล่าว คุณมั่นใจได้ว่าไฟล์ของคุณปลอดภัยในระหว่างขั้นตอนการแปลง รวมถึงไฟล์ XLS แอปฟรีด้านบนมีไว้สำหรับทดสอบ ให้คุณตรวจสอบผลลัพธ์ได้ก่อนที่จะรวมโค้ด</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ฉันควรใช้เบราว์เซอร์ใดในการแปลง XLS</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณมีความยืดหยุ่นในการใช้เว็บเบราว์เซอร์ที่ทันสมัยสำหรับการแปลง XLS เป็น DOCX ออนไลน์ เช่น Google Chrome, Firefox, Opera, Safari อย่างไรก็ตาม หากคุณกำลังสร้างแอปพลิเคชันเดสก์ท็อป คุณสามารถผสานรวม Aspose.Total XLS Conversion API ได้อย่างราบรื่น</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}