---
title: .NET API เพื่อแปลง DOCM เป็น FODS หรือด้วยตัวแปลงออนไลน์ฟรี
description: C# API เพื่อแปลง DOCM เป็น FODS หรือแอพออนไลน์ โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader หรือทางออนไลน์ ทดสอบตัวแปลง CSV เป็น DOC ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด 
url_ignore: /th/net/conversion/docm-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: FODS
otherformats: XLSM XLTX XLAM XLT ODS FODS EXCEL XLS SXC XLSX XLSB XLTM TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API เพื่อแปลง DOCM เป็น FODS หรือแอพออนไลน์" h2="ส่งออก DOCM เป็น FODS ผ่าน C# โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถรวมคุณลักษณะการแปลง DOCM เป็น FODS ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ใดก็ได้ สองขั้นตอนง่ายๆ ประการแรก ด้วยการใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถส่งออก DOCM เป็น HTML หลังจากนั้น การใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API จะช่วยให้คุณแปลง HTML เป็น FODS ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง DOCM เป็น FODS" %}}
1. เปิดไฟล์ DOCM โดยใช้คลาส [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. แปลง DOCM เป็น HTML โดยใช้วิธีการ [Save](https://reference.aspose.com/words/net/aspose.words.documentsave/methods/4)
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. บันทึกเอกสารในรูปแบบ FODS โดยใช้วิธี [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) และตั้งค่า `FODS' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ DOCM เป็น FODS</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=fods&from=docm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="โหลดเอกสาร DOCM จากสตรีมผ่าน C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ยังอนุญาตให้คุณโหลดเอกสาร DOCM ผ่านสตรีม หากต้องการเปิดเอกสารจากสตรีม เพียงส่งออบเจ็กต์สตรีมที่มีเอกสารไปยังตัวสร้าง [Document](https://reference.aspose.com/words/net/aspose.words/document ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเปิดเอกสารจากสตรีม:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เพิ่มคุณสมบัติที่กำหนดเองในไฟล์ FODS ผ่าน C#" %}}
ขณะแปลง DOCM เป็น FODS [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ช่วยให้คุณเพิ่มคุณสมบัติที่กำหนดเองในเอกสาร FODS ได้ ในการเพิ่มคุณสมบัติที่กำหนดเอง คุณสามารถใช้ [เพิ่ม](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentropertycollection/methods/add/index)เมธอดสำหรับ [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/CustomDocumentPropertyCollection) คลาส วิธีการเพิ่มจะเพิ่มคุณสมบัติลงในไฟล์ Excel และส่งคืนข้อมูลอ้างอิงสำหรับคุณสมบัติเอกสารใหม่เป็น [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/DocumentProperty) วัตถุ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
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
                          <span itemprop="name"><b>ฉันจะแปลง DOCM เป็น FODS ออนไลน์ได้อย่างไร</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แอพออนไลน์สำหรับการแปลง DOCM ถูกรวมไว้ด้านบน ประการแรก คุณต้องเพิ่มไฟล์ DOCM สำหรับการแปลงโดยการลาก &amp; วางหรือคลิกภายในพื้นที่สีขาวเพื่อนำเข้าเอกสาร จากนั้นคลิกปุ่มแปลง เมื่อการแปลง DOCM เป็น FODS เสร็จสิ้น คุณสามารถดาวน์โหลดไฟล์ที่แปลงแล้วได้ ดังนั้นคุณจะได้ไฟล์ FODS ที่ส่งออกด้วยการคลิกเพียงครั้งเดียว</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง DOCM ใช้เวลานานเท่าไหร่?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ตัวแปลงออนไลน์นี้ทำงานได้อย่างรวดเร็ว แต่ขึ้นอยู่กับขนาดของไฟล์ DOCM เป็นหลัก คุณสามารถเรนเดอร์ไฟล์ DOCM ขนาดเล็กเป็น FODS ได้ในไม่กี่วินาที ยิ่งไปกว่านั้น หากคุณได้รวมรหัสการแปลงภายในแอปพลิเคชัน .NET ขึ้นอยู่กับว่าคุณได้เพิ่มประสิทธิภาพแอปพลิเคชันของคุณสำหรับกระบวนการแปลงอย่างไร</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง DOCM เป็น FODS ปลอดภัยหรือไม่โดยใช้ตัวแปลง Aspose.Total ฟรี</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แน่นอน! ลิงค์ดาวน์โหลดไฟล์ FODS จะใช้งานได้ทันทีหลังจากการแปลง เราลบไฟล์ที่อัปโหลดหลังจาก 24 ชั่วโมง และลิงก์ดาวน์โหลดจะหยุดทำงานหลังจากช่วงเวลานี้ ไม่มีใครสามารถเข้าถึงไฟล์ของคุณได้ การแปลงไฟล์ (รวมถึง DOCM) นั้นปลอดภัยอย่างยิ่ง แอพฟรีส่วนใหญ่ถูกรวมเข้าด้วยกันเพื่อจุดประสงค์ในการทดสอบเพื่อให้สามารถตรวจสอบผลลัพธ์ก่อนที่จะรวมรหัส</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ฉันควรใช้เบราว์เซอร์ใดในการแปลง DOCM</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณสามารถใช้เบราว์เซอร์สมัยใหม่ใดก็ได้สำหรับการแปลงออนไลน์นี้ เช่น Google Chrome, Firefox, Opera, Safari แต่ในกรณีที่คุณกำลังพัฒนาแอปพลิเคชันบนเดสก์ท็อป Aspose.Total DOCM Conversion API จะทำงานได้อย่างราบรื่น</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}