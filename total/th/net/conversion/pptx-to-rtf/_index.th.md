---
title: แปลง PPTX เป็น RTF ผ่าน C# .NET หรือด้วยตัวแปลงออนไลน์ฟรี
description: แปลงเอกสาร PowerPoint pptx เป็นไฟล์เอกสาร Word ด้วย C# แปลงไฟล์หลายไฟล์ภายใน ASP.NET หรือแอปพลิเคชัน .NET อื่นๆ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง PPTX เป็น RTF โดยใช้ C# หรือทางออนไลน์" h2="สร้าง Microsoft PowerPoint PPTX Presentation เป็นแอปแปลงเอกสาร Word RTF บน .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="วิธีแปลง PPTX เป็น RTF โดยใช้ C# หรือทางออนไลน์" %}}

เพื่อให้กระบวนการสำหรับการนำเสนอ PowerPoint pptx เป็นไปโดยอัตโนมัติในการแปลงไฟล์เอกสาร Word แบบกลุ่ม เราจะใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/net) และ [Aspose.Words สำหรับ .NET](https://products.aspose.com/words/net) API อดีตคือ API การจัดการงานนำเสนอ PowerPoint ที่ช่วยให้คุณสร้างหรือแก้ไขสไลด์ Microsoft PowerPoint ในขณะที่อย่างหลังคือ API การประมวลผลคำสำหรับการประมวลผลหรือจัดการเอกสาร Microsoft Word API ทั้งสองเป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for .NET](https://products.aspose.com/total/net) คุณสามารถ [ดาวน์โหลด](https://releases.aspose.com) ได้โดยตรงจาก Nuget หรืออาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง PPTX เป็น RTF ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. เพิ่มการอ้างอิงของ Aspose.Slides สำหรับ .NET และ Aspose.Words สำหรับ .NET
1. โหลดงานนำเสนอ PowerPoint PPTX โดยใช้คลาส [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. บันทึกเอกสารลงใน [MemoryStream](https://rtfs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) วัตถุ
1. สร้าง [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) และกำหนดค่าเริ่มต้นด้วย MemoryStream Object
1. บันทึกเอกสารโดยใช้ [Aspose.Words.Document.Save("output.rtf", SaveFormat.Rtf)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Slides สำหรับ .NET และ Aspose.Words สำหรับ .NET DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ตัวอย่างโค้ดนี้แสดงวิธีการแปลง PPTX เป็น RTF โดยใช้ C# หรือทางออนไลน์" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPTX file
Aspose.Slides.Presentation pptx = new Aspose.Slides.Presentation("source.pptx");

var stream = new MemoryStream();

pptx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var rtf = new Aspose.Words.Document(stream);
      
// Save the Word RTF document
rtf.Save("output.rtf", Aspose.Words.SaveFormat.Rtf);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์สำหรับ PPTX เป็น RTF</h3>

<iframe title="เครื่องมือออนไลน์สำหรับการแปลง pptx เป็น rtf" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=pptx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="แอพฟรีเพื่อแปลง PPTX เป็น RTF" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

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
                          <span itemprop="name"><b>ฉันจะแปลง PPTX เป็น RTF ออนไลน์ได้อย่างไร</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แอพออนไลน์สำหรับการแปลง PPTX ถูกรวมไว้ด้านบน หากต้องการใช้แอป คุณสามารถเพิ่มไฟล์ PPTX ของคุณโดยการลากและวางลงในพื้นที่ที่กำหนดหรือคลิกภายในพื้นที่เพื่อนำเข้าไฟล์ เมื่อเพิ่มไฟล์แล้ว ให้คลิกปุ่มแปลงเพื่อเริ่มกระบวนการแปลง หลังจากการแปลง PPTX เป็น RTF เสร็จสิ้น คุณสามารถดาวน์โหลดไฟล์ที่แปลงใหม่ของคุณด้วยการคลิกเพียงครั้งเดียว และไฟล์นั้นจะพร้อมใช้งานในรูปแบบ RTF</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง PPTX ใช้เวลานานเท่าไหร่?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ตัวแปลงออนไลน์นี้รวดเร็ว แต่ความเร็วของการแปลง PPTX เป็น RTF ส่วนใหญ่ขึ้นอยู่กับขนาดของไฟล์ PPTX ที่กำลังแปลง ไฟล์ PPTX ที่เล็กลงสามารถแปลงเป็นรูปแบบ RTF ได้ภายในไม่กี่วินาที นอกจากนี้ หากคุณได้รวมโค้ดการแปลง PPTX เป็น RTF ภายในแอปพลิเคชัน .NET ความเร็วในการแปลงจะขึ้นอยู่กับว่าคุณได้เพิ่มประสิทธิภาพแอปพลิเคชันของคุณสำหรับกระบวนการแปลงได้ดีเพียงใด</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง PPTX เป็น RTF ปลอดภัยหรือไม่โดยใช้ตัวแปลง Aspose.Total ฟรี</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แน่นอน! เมื่อกระบวนการแปลง PPTX เป็น RTF เสร็จสิ้น ลิงก์ดาวน์โหลดไฟล์ RTF ที่แปลงแล้วจะพร้อมใช้งานทันที ไฟล์ที่อัปโหลดทั้งหมด รวมถึงไฟล์ PPTX จะถูกลบออกจากระบบหลังจาก 24 ชั่วโมง และลิงก์ดาวน์โหลดจะหยุดทำงานหลังจากช่วงเวลานี้ ตัวแปลงไฟล์ออนไลน์รับประกันความปลอดภัยและความเป็นส่วนตัวของไฟล์ของคุณ และแอปที่ผสานรวมไว้ให้บริการฟรีสำหรับวัตถุประสงค์ในการทดสอบ สิ่งนี้ช่วยให้ผู้ใช้สามารถตรวจสอบผลลัพธ์ก่อนที่จะรวมรหัสเข้ากับโครงการของตน</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ฉันควรใช้เบราว์เซอร์ใดในการแปลง PPTX</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณสามารถใช้เว็บเบราว์เซอร์ร่วมสมัยใดก็ได้ เช่น Google Chrome, Firefox, Opera หรือ Safari เพื่อแปลงไฟล์ PPTX เป็น RTF ทางออนไลน์ อย่างไรก็ตาม หากคุณกำลังสร้างแอปพลิเคชันเดสก์ท็อป ขอแนะนำให้ใช้ Aspose.Total PPTX Conversion API เพื่อกระบวนการแปลงที่ราบรื่นและไร้รอยต่อ</span>
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