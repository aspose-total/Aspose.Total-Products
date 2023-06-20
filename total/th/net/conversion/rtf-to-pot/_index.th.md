---
title: แปลง RTF เป็น POT ผ่าน C# .NET หรือด้วยตัวแปลงออนไลน์ฟรี
description: แปลงเอกสาร Word rtf เป็นไฟล์ PowerPoint pot ด้วย C# แปลงไฟล์หลายไฟล์ภายใน ASP.NET หรือแอปพลิเคชัน .NET อื่นๆ
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง RTF เป็น POT โดยใช้ C# หรือทางออนไลน์" h2="สร้างแอปการแปลง Microsoft Word RTF เป็น PowerPoint POT บน .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms" logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="วิธีแปลง RTF เป็น POT โดยใช้ C# หรือทางออนไลน์" %}}

เพื่อให้กระบวนการสำหรับไฟล์เอกสาร Word เป็นการแปลงแบตช์งานนำเสนอ PowerPoint pot เป็นอัตโนมัติ เราจะใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net) และ [Aspose.Slides สำหรับ .NET](https://products.aspose.com/slides/net) API อดีตคือ API การประมวลผลคำสำหรับการประมวลผลหรือจัดการเอกสาร Microsoft Word ในขณะที่หลังคือ API การจัดการการนำเสนอที่ให้คุณสร้างหรือแก้ไขสไลด์ Microsoft PowerPoint API ทั้งสองเป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for .NET](https://products.aspose.com/total/net) คุณสามารถ [ดาวน์โหลด](https://releases.aspose.com) ได้โดยตรงจาก Nuget หรืออาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง RTF เป็น POT ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. เพิ่มการอ้างอิงของ Aspose.Total สำหรับ .NET
1. โหลดไฟล์ RTF โดยใช้คลาส [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. บันทึกเอกสาร RTF เป็น HTML
1. สร้าง [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) Object
1. นำเข้าเนื้อหา HTML ในกรอบข้อความของรูปร่างสไลด์ภายในงานนำเสนอ
1. บันทึกเอกสารโดยใช้ [Aspose.Slides.Presentation.Save("output.pot", SaveFormat.Pot)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin Platforms
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Words สำหรับ .NET &amp; Aspose.Slides สำหรับ .NET DLL หรือ Aspose.Total สำหรับ .NET DLL ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ตัวอย่างโค้ดนี้แสดงวิธีการแปลง RTF เป็น POT โดยใช้ C# หรือทางออนไลน์" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word RTF file
Aspose.Words.Document rtf = new Aspose.Words.Document("sourceWordFile.rtf");

// Save RTF file to HTML 
rtf.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages RTF documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POT.

using (Presentation pot = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the POT Presentation
	pot.Save("filepath\\pres.pot", Aspose.Slides.Export.SaveFormat.Pot);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์สำหรับ RTF เป็น POT</h3>

<iframe title="เครื่องมือออนไลน์สำหรับการแปลง rtf เป็น pot" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pot&from=rtf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="แอพฟรีเพื่อแปลง RTF เป็น POT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

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
                          <span itemprop="name"><b>ฉันจะแปลง RTF เป็น POT ออนไลน์ได้อย่างไร</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แอพออนไลน์สำหรับการแปลง RTF ถูกรวมไว้ด้านบน หากต้องการใช้แอปนี้ คุณสามารถเพิ่มไฟล์ RTF ของคุณโดยการลากและวางลงในพื้นที่สีขาวที่กำหนดหรือคลิกภายในพื้นที่เพื่อนำเข้าเอกสาร ถัดไป กดปุ่มแปลงเพื่อเริ่มกระบวนการแปลง หลังจากการแปลง RTF เป็น POT เสร็จสิ้น คุณสามารถดาวน์โหลดไฟล์ที่แปลงใหม่ได้ด้วยการคลิกเพียงครั้งเดียว และไฟล์ดังกล่าวจะพร้อมใช้งานในรูปแบบไฟล์ POT</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง RTF ใช้เวลานานเท่าไหร่?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ตัวแปลงออนไลน์นี้ทำงานได้อย่างรวดเร็ว แต่ขึ้นอยู่กับขนาดของไฟล์ RTF ที่กำลังแปลงเป็นหลัก สำหรับไฟล์ RTF ขนาดเล็ก การแปลงเป็น POT สามารถทำได้ภายในไม่กี่วินาที อย่างไรก็ตาม หากคุณรวมรหัสการแปลงภายในแอปพลิเคชัน .NET ความเร็วในการแปลงจะขึ้นอยู่กับว่าแอปพลิเคชันของคุณได้รับการปรับให้เหมาะสมสำหรับกระบวนการแปลงมากน้อยเพียงใด</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การแปลง RTF เป็น POT ปลอดภัยหรือไม่โดยใช้ตัวแปลง Aspose.Total ฟรี</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">แน่นอน! เมื่อการแปลง RTF เป็น POT เสร็จสิ้น ลิงก์ดาวน์โหลดไฟล์ POT ที่แปลงใหม่จะพร้อมใช้งานทันที นอกจากนี้ยังรับประกันความปลอดภัยของกระบวนการแปลง เนื่องจากไฟล์ที่อัปโหลดทั้งหมด รวมถึงไฟล์ RTF นั้นปลอดภัยอย่างสมบูรณ์และจะถูกลบออกจากระบบหลังจาก 24 ชั่วโมง นอกจากนี้ ลิงก์ดาวน์โหลดจะหยุดทำงานหลังจากช่วงเวลานี้ เพื่อให้มั่นใจถึงความเป็นส่วนตัวและการปกป้องไฟล์ของคุณ แอปแบบรวมใช้งานได้ฟรีและออกแบบมาเพื่อการทดสอบเพื่อให้ผู้ใช้สามารถประเมินผลลัพธ์ก่อนที่จะรวมรหัสเข้ากับโครงการของตน</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ฉันควรใช้เบราว์เซอร์ใดในการแปลง RTF</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณสามารถใช้เว็บเบราว์เซอร์สมัยใหม่ใดก็ได้ เช่น Google Chrome, Firefox, Opera หรือ Safari สำหรับการแปลงไฟล์ RTF เป็น POT แบบออนไลน์ อย่างไรก็ตาม หากคุณกำลังพัฒนาแอปพลิเคชันเดสก์ท็อป ขอแนะนำให้ใช้ Aspose.Total RTF Conversion API เพื่อการประมวลผลที่ราบรื่นและมีประสิทธิภาพ</span>
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