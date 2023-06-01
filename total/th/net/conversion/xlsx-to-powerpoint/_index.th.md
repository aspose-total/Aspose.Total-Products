---
title: แปลง XLSX เป็น POWERPOINT ด้วย .NET หรือด้วยตัวแปลงออนไลน์ฟรี
description: แปลง XLSX เป็น POWERPOINT บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms หรือทางออนไลน์ ทดสอบตัวแปลง XLSX เป็น POWERPOINT ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด

family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: POWERPOINT
otherformats: PPTX DOC WORD DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="แปลง XLSX เป็น POWERPOINT ผ่าน C# หรือแอพออนไลน์" h2="ส่งออก Excel&reg; XLSX เป็น POWERPOINT บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="การแปลง XLSX เป็น POWERPOINT บน .NET" %}}
1. เปิดไฟล์ XLSX โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. แปลง XLSX เป็น PDF และตั้งค่า SaveFormat เป็น Auto
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. บันทึกเอกสารในรูปแบบ POWERPOINT โดยใช้วิธี [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) และตั้งค่า Powerpoint เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code สำหรับการแปลง XLSX เป็น POWERPOINT" gistPath="" %}}
```cs
// load the XLSX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsx");
// save XLSX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ XLSX เป็น POWERPOINT</h3>

<iframe title="เครื่องมือออนไลน์สำหรับการแปลง xlsx เป็น pptx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>

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
                          <span itemprop="name"><b>ฉันจะแปลง XLSX เป็น POWERPOINT ออนไลน์ได้อย่างไร</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แอพออนไลน์สำหรับการแปลง XLSX ถูกรวมไว้ด้านบน ในการเริ่มกระบวนการแปลง คุณสามารถลากและวางไฟล์ XLSX ของคุณหรือคลิกภายในพื้นที่ที่กำหนดเพื่อนำเข้าเอกสาร จากนั้นคลิกที่ปุ่ม "แปลง" เพื่อเริ่มการแปลง XLSX เป็น POWERPOINT เมื่อกระบวนการเสร็จสิ้น คุณสามารถดาวน์โหลดไฟล์ที่แปลงแล้วได้ง่ายๆ เพียงคลิกเดียว และรับผลลัพธ์ที่คุณต้องการในรูปแบบ POWERPOINT</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง XLSX ใช้เวลานานเท่าไหร่?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ความเร็วของตัวแปลงออนไลน์นี้เร็ว แต่ขึ้นอยู่กับขนาดของไฟล์ XLSX เป็นหลัก หากคุณมีไฟล์ XLSX ขนาดเล็ก ก็สามารถแปลงเป็น POWERPOINT ได้ในเวลาเพียงไม่กี่วินาที นอกจากนี้ หากคุณรวมรหัสการแปลงเข้ากับแอปพลิเคชัน .NET ของคุณ ความเร็วของกระบวนการแปลงจะขึ้นอยู่กับว่าคุณได้เพิ่มประสิทธิภาพแอปพลิเคชันของคุณได้ดีเพียงใด</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง XLSX เป็น POWERPOINT ปลอดภัยหรือไม่โดยใช้ตัวแปลง Aspose.Total ฟรี</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แน่นอน! หลังจากกระบวนการแปลง XLSX เป็น POWERPOINT เสร็จสิ้น ลิงก์ดาวน์โหลดไฟล์ POWERPOINT จะถูกสร้างขึ้นทันที เราให้ความสำคัญกับความปลอดภัยของไฟล์ของคุณ นั่นเป็นเหตุผลว่าทำไมไฟล์ที่อัปโหลดทั้งหมดจึงถูกลบหลังจากผ่านไป 24 ชั่วโมง และลิงก์ดาวน์โหลดจะหยุดทำงานหลังจากช่วงเวลาดังกล่าว คุณมั่นใจได้ว่าไฟล์ของคุณปลอดภัยในระหว่างขั้นตอนการแปลง รวมถึงไฟล์ XLSX แอปฟรีด้านบนมีไว้สำหรับทดสอบ ให้คุณตรวจสอบผลลัพธ์ได้ก่อนที่จะรวมโค้ด</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ฉันควรใช้เบราว์เซอร์ใดในการแปลง XLSX</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณมีความยืดหยุ่นในการใช้เว็บเบราว์เซอร์ที่ทันสมัยสำหรับการแปลง XLSX เป็น POWERPOINT ออนไลน์ เช่น Google Chrome, Firefox, Opera, Safari อย่างไรก็ตาม หากคุณกำลังสร้างแอปพลิเคชันเดสก์ท็อป คุณสามารถผสานรวม Aspose.Total XLSX Conversion API ได้อย่างราบรื่น</span>
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