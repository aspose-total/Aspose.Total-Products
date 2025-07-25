---
title: ลบคำอธิบายประกอบ DOCX ออนไลน์หรือจัดการคำอธิบายประกอบผ่าน .NET
description: ลบความคิดเห็นออกจากไฟล์ DOCX ผ่านแอปออนไลน์ฟรีรหัส .NET API เพื่อจัดการความคิดเห็นของไฟล์ DOCX

family: total
platformtag: net
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากเอกสาร DOCX ออนไลน์หรือจัดการผ่าน .NET" h2="พัฒนาแอพพลิเคชั่นยูทิลิตีคำอธิบายประกอบเอกสาร DOCX ที่ใช้ .NET อันทรงพลังรหัสที่แสดงสำหรับจัดการความคิดเห็นของไฟล์ DOCX ผ่าน. NET" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ DOCX ออนไลน์" %}}

1. นำเข้าไฟล์ DOCX เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ DOCX และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นเกี่ยวกับเอกสาร DOCX ของผู้แต่งเฉพาะเจาะจงผ่าน .NET" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ .NET
1. โหลดเอกสารผ่านวัตถุคลาสเอกสาร
1. รับความคิดเห็นของโหนดทั้งหมดโดยใช้ GetChildNodes ที่มี NodeType.Comment
1. ย้ำความคิดเห็นทั้งหมดและจับคู่ชื่อผู้แต่ง
1. เรียกใช้เมธอด Remove เพื่อลบความคิดเห็นของผู้เขียนโดยเฉพาะ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส C#: ลบความคิดเห็นของผู้เขียนเฉพาะจากไฟล์ DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มความคิดเห็นผ่านทาง .NET" %}}

1. สร้างวัตถุคลาสเอกสาร
1. ใช้คลาสความคิดเห็น
1. เพิ่มย่อหน้าใหม่โดยใช้ Paragraphs.Add
1. ใช้ FirstParagraph.Runs เพิ่มความคิดเห็น
1. หรืออีกวิธีหนึ่งคือใช้คลาส CommentRangeStart และ CommentRangeEnd
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์พร้อมความคิดเห็นเพิ่มเติม

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="แยกความคิดเห็นทั้งหมด" %}}

1. โหลดเอกสารผ่านวัตถุคลาสเอกสาร
1. สร้างวัตถุ ArrayList
1. รับ GetChildNodes ทั้งหมดใน NodeCollection
1. วนซ้ำแต่ละคอลเลกชันและเพิ่มความคิดเห็นใน ArrayList

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET Code : เพิ่มความคิดเห็นจากไฟล์ DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: แยกความคิดเห็นทั้งหมด" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอปพลิเคชันคำอธิบายประกอบเอกสาร DOCX ผ่าน .NET</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ DOCX เพื่อให้คำติชม ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.Words for .NET](https://products.aspose.com/words/net/) ซึ่งเป็น API ลูกของ [Aspose.Total for .NET](https://products.aspose.com/total/net/) นักพัฒนา .NET ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี .NET อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ DOCX<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET Library เพื่อใส่คำอธิบายประกอบไฟล์ DOCX" %}}

มีทางเลือกสามทางในการติดตั้ง "Aspose.Words for .NET" หรือ "Aspose.Total for .NET" ลงบนระบบของคุณโปรดเลือกรายการที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:<br /><br />

- ติดตั้ง [แพ็คเกจ NuGet](https://www.nuget.org/packages/Aspose.Words/) ดู [เอกสารประกอบ](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- ติดตั้งไลบรารีโดยใช้ [คอนโซลตัวจัดการแพ็คเกจ](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) ภายใน Visual Studio IDE
- ติดตั้งไลบรารี่ด้วยมือโดยใช้ [ตัวติดตั้ง Windows](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

ผลิตภัณฑ์ของเราสามารถข้ามแพลตฟอร์มได้อย่างสมบูรณ์และรองรับการใช้งาน .NET หลักทั้งหมดตามข้อกำหนด '.NET Standard 2.0':<br /><br />

- Microsoft .NET Framework เริ่มต้นจากเวอร์ชัน 2.0 แรกสุด และลงท้ายด้วย '.NET Framework 4.8' ล่าสุด
- .NET Core เริ่มต้นจากเวอร์ชัน 2.0 แรกสุด และลงท้ายด้วย '.NET 6' ล่าสุด
- โมโน >= 2.6.7
<br /><br />
เนื่องจากโค้ด .NET ไม่ต้องอาศัยฮาร์ดแวร์หรือระบบปฏิบัติการพื้นฐาน แต่ต้องใช้บน Virtual Machine เท่านั้น คุณจึงมีอิสระในการพัฒนาซอฟต์แวร์ทุกประเภทสำหรับ Windows, macOS, Android, iOS และ Linuxเพียงตรวจสอบให้แน่ใจว่าคุณได้ติดตั้ง .NET Framework, .NET Core, Windows Azure, Mono หรือ Xamarin เวอร์ชันที่เกี่ยวข้อง<br /><br />
เราขอแนะนำให้ใช้ Microsoft Visual Studio, Xamarin และ MonoDevelop IDE เพื่อสร้างแอปพลิเคชัน C#, F#, VB.NET
<br /><br />
สำหรับรายละเอียดเพิ่มเติม โปรดดูที่ [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/words/net/system-requirements/)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}
ไฟล์ DOCX (เอกสารรูปแบบ Microsoft Word Open XML Document) ใช้งานอย่างแพร่หลายสำหรับการสร้าง แก้ไข และแบ่งปันเอกสารที่มีเนื้อหาเป็นข้อความ การทำเครื่องหมายบนไฟล์ DOCX เป็นสิ่งสำคัญสำหรับการเพิ่มความคิดเห็น ข้อเสนอแนะ และข้อติชม เพื่อสนับสนุนการทำงานร่วมกันของทีมได้อย่างดียิ่งขึ้น

#### การทำเครื่องหมายบนไฟล์ DOCX สำหรับการตรวจสอบเอกสารร่วมกัน:

- **การแก้ไขร่วมกัน**  
  ทำเครื่องหมายบนส่วนต่างๆของเอกสารด้วยข้อเสนอแนะ การแก้ไข และข้อติชมเพื่อปรับปรุงการทำงานร่วมกันของทีมในระหว่างกระบวนการแก้ไข

- **การตรวจสอบเอกสารทางกฎหมาย**  
  เพิ่มความคิดเห็นและการทำเครื่องหมายละเอียดบนเอกสารทางกฎหมายเพื่อเน้นบริเวณที่ต้องการความชัดเจนเพิ่มเติมหรือตรวจสอบทางกฎหมาย

- **กระบวนการอนุมัติเนื้อหา**  
  ทำเครื่องหมายบนเอกสารร่างเพื่อให้ข้อเสนอแนะเกี่ยวกับโครงสร้าง เสียงเชิง และเนื้อหา เพื่อช่วยในกระบวนการอนุมัติก่อนการเผยแพร่

- **การติดตามเอกสารโครงการ**  
  ทำเครื่องหมายบนรายงานโครงการและเอกสารด้วยเวลาที่บันทึก ประวัติเวอร์ชัน หรือความคิดเห็นเพื่อติดตามความก้าวหน้าและการแก้ไขตลอดเวลา

- **การตรวจสอบความเป็นไปตามกฎหมายและข้อบังคับ**  
  แทรกการทำเครื่องหมายเพื่อบันทึกการเปลี่ยนแปลงในเอกสารและทำเครื่องหมายส่วนที่เกี่ยวข้องกับความเป็นไปตามกฎหมาย เพื่อให้แน่ใจว่าประกอบกับข้อกำหนดข้อบังคับทั้งหมดในระหว่างการสร้างเอกสาร
{{% /blocks/products/pf/feature-page-summary %}}
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
                          <span itemprop="name"><b>ฉันสามารถใช้โค้ด .NET ข้างต้นในแอปพลิเคชันของฉันได้หรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ใช่ คุณสามารถดาวน์โหลดโค้ดนี้และใช้เพื่อวัตถุประสงค์ในการพัฒนาแอปพลิเคชันคำอธิบายประกอบเอกสารที่ใช้ .NETรหัสนี้สามารถทำหน้าที่เป็นทรัพยากรอันมีค่าในการปรับปรุงฟังก์ชันการทำงานและความสามารถของโปรเจ็กต์ของคุณในโดเมนของการประมวลผลและจัดการเอกสารแบ็กเอนด์</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>แอปคำอธิบายประกอบเอกสารออนไลน์นี้ใช้งานได้บน Windows เท่านั้นหรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณมีความยืดหยุ่นในการเริ่มต้นคำอธิบายประกอบเอกสารสำหรับการลบความคิดเห็นในอุปกรณ์ใดๆ ก็ตาม โดยไม่คำนึงถึงระบบปฏิบัติการที่ทำงาน ไม่ว่าจะเป็น Windows, Linux, Mac OS หรือ Androidสิ่งที่คุณต้องมีคือเว็บเบราว์เซอร์ร่วมสมัยและการเชื่อมต่ออินเทอร์เน็ตที่ใช้งานได้</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การใช้แอปออนไลน์เพื่อใส่คำอธิบายประกอบเอกสาร DOCX ปลอดภัยหรือไม่</b></span>
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
                          <span itemprop="text">คุณสามารถใช้เว็บเบราว์เซอร์สมัยใหม่ใดก็ได้ เช่น Google Chrome, Firefox, Opera หรือ Safari สำหรับคำอธิบายประกอบเอกสาร DOCX ออนไลน์อย่างไรก็ตาม หากคุณกำลังพัฒนาแอปพลิเคชันบนเดสก์ท็อป เราขอแนะนำให้ใช้ API การประมวลผลเอกสาร Aspose.Total เพื่อการจัดการที่มีประสิทธิภาพ</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}