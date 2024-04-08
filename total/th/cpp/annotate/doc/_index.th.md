---
title: ลบคำอธิบายประกอบ DOC ออนไลน์หรือจัดการคำอธิบายประกอบผ่าน C ++
description: ลบความคิดเห็นออกจากไฟล์ DOC ผ่านแอปออนไลน์ฟรี รหัส C++ API เพื่อจัดการความคิดเห็นของไฟล์ DOC

family: total
platformtag: cpp
feature: Annotate
informat: DOC
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากเอกสาร DOC ออนไลน์หรือจัดการผ่าน C ++" h2="พัฒนาแอปพลิเคชันยูทิลิตีคำอธิบายประกอบเอกสาร DOC ที่ใช้ C++ ที่ทรงพลัง รหัสที่แสดงสำหรับจัดการความคิดเห็นของไฟล์ DOC ผ่าน C ++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ DOC ออนไลน์" %}}

1. นำเข้าไฟล์ DOC เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ DOC และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นเอกสาร DOC ผ่าน C ++" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ C ++
1. โหลดไฟล์ DOC
1. รับโหนดทั้งหมดโดยใช้ GetChildNodes โดยมี NodeType::Comment เป็นพารามิเตอร์
1. โทร NodeCollection.Clear ในการรวบรวมความคิดเห็น

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส C ++: ลบความคิดเห็นออกจากไฟล์ DOC" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มความคิดเห็นผ่าน C ++" %}}

1. สร้างวัตถุคลาส Document และ DocumentBuilder
1. หรือโหลดเอกสาร
1. ใช้คลาสความคิดเห็นเพื่อเพิ่มความคิดเห็น
1. ใช้เมธอด AppendChild โดยมีความคิดเห็น obj เป็นพารามิเตอร์
1. ใช้วิธีการที่เกี่ยวข้องเช่น get_Paragraphs()->Add
1. หรืออีกวิธีหนึ่งคือใช้คลาส CommentRangeStart และ CommentRangeEnd
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์พร้อมความคิดเห็นเพิ่มเติม

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="แยกความคิดเห็นทั้งหมด" %}}

1. โหลดเอกสารผ่านวัตถุคลาสเอกสาร
1. รับ GetChildNodes ทั้งหมดใน NodeCollection
1. ทำซ้ำแต่ละคอลเลกชันและรวบรวมข้อมูลเกี่ยวกับคอลเลกชันเหล่านั้น

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส C++: เพิ่มความคิดเห็นในไฟล์ DOC" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: แยกความคิดเห็นทั้งหมด" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอปพลิเคชันคำอธิบายประกอบเอกสาร DOC ผ่าน C ++</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ DOC เพื่อให้คำติชม ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ซึ่งเป็น API ลูกของ [Aspose.Total for C++](https://products.aspose.com/total/th/cpp/) นักพัฒนา C++ ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี C++ อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ DOC<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ไลบรารี C ++ เพื่อใส่คำอธิบายประกอบไฟล์ DOC" %}}

มีสามตัวเลือกในการติดตั้ง Aspose.Words สำหรับ C++ ในสภาพแวดล้อมนักพัฒนาของคุณโปรดเลือกรายการที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:<br /><br />

- Install a [แพ็คเกจ NuGet](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [เอกสารประกอบ](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- ติดตั้งไลบรารีโดยใช้ [คอนโซลตัวจัดการแพ็คเกจ](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) ภายใน Visual Studio IDE
- ติดตั้งไลบรารี่ด้วยมือโดยใช้ [ตัวติดตั้ง Windows](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}
คุณสามารถใช้ไลบรารี C++ นี้เพื่อพัฒนาซอฟต์แวร์บนระบบปฏิบัติการ Microsoft Windows, Linux และ macOS:<br /><br />

- GCC >= 6.3.0 และ Clang >= 3.9.1 จำเป็นสำหรับ Linux
- Xcode >= 12.5.1, Clang และ libc++ จำเป็นสำหรับ macOS

<br /><br />
หากคุณพัฒนาซอฟต์แวร์สำหรับ Linux หรือ macOS โปรดตรวจสอบข้อมูลเกี่ยวกับการพึ่งพาไลบรารีเพิ่มเติม (แพ็คเกจฟอนต์คอนฟิกและ mesa-glu) ใน [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/words/cpp/system-requirements/)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

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
                          <span itemprop="name"><b>ฉันสามารถใช้โค้ด C++ ข้างต้นในแอปพลิเคชันของฉันได้หรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ใช่ คุณสามารถดาวน์โหลดโค้ดนี้และใช้เพื่อวัตถุประสงค์ในการพัฒนาแอปพลิเคชันคำอธิบายประกอบเอกสารที่ใช้ C++รหัสนี้สามารถทำหน้าที่เป็นทรัพยากรอันมีค่าในการปรับปรุงฟังก์ชันการทำงานและความสามารถของโปรเจ็กต์ของคุณในโดเมนของการประมวลผลและจัดการเอกสารแบ็กเอนด์</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>แอปคำอธิบายประกอบเอกสารออนไลน์นี้ใช้งานได้บน Windows เท่านั้นหรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">คุณมีความยืดหยุ่นในการเริ่มต้นคำอธิบายประกอบเอกสารสำหรับการลบความคิดเห็นในอุปกรณ์ใดๆ ก็ตาม โดยไม่คำนึงถึงระบบปฏิบัติการที่ทำงาน ไม่ว่าจะเป็น Windows, Linux, Mac OS หรือ Android สิ่งที่คุณต้องมีคือเว็บเบราว์เซอร์ร่วมสมัยและการเชื่อมต่ออินเทอร์เน็ตที่ใช้งานได้</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>การใช้แอปออนไลน์เพื่อใส่คำอธิบายประกอบเอกสาร DOC ปลอดภัยหรือไม่</b></span>
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
                          <span itemprop="text">คุณสามารถใช้เว็บเบราว์เซอร์สมัยใหม่ใดก็ได้ เช่น Google Chrome, Firefox, Opera หรือ Safari สำหรับคำอธิบายประกอบเอกสาร DOC ออนไลน์อย่างไรก็ตาม หากคุณกำลังพัฒนาแอปพลิเคชันบนเดสก์ท็อป เราขอแนะนำให้ใช้ API การประมวลผลเอกสาร Aspose.Total เพื่อการจัดการที่มีประสิทธิภาพ</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}