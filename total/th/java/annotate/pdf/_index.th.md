---
title: ลบคำอธิบายประกอบ PDF ออนไลน์หรือจัดการคำอธิบายประกอบผ่าน Java
description: ลบความคิดเห็นออกจากไฟล์ PDF ผ่านแอปออนไลน์ฟรีรหัส Java API เพื่อจัดการความคิดเห็นของไฟล์ PDF

family: total
platformtag: Java
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากเอกสาร PDF ออนไลน์หรือจัดการผ่าน Java" h2="พัฒนาแอปพลิเคชันยูทิลิตีคำอธิบายประกอบเอกสาร PDF ที่ใช้ Java ที่ทรงพลังรหัสที่แสดงสำหรับการจัดการความคิดเห็นของไฟล์ PDF ผ่าน Java" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ PDF ออนไลน์" %}}

1. นำเข้าไฟล์ PDF เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ PDF และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นเอกสาร PDF ผ่าน Java" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Java
1. โหลดเอกสารผ่านวัตถุคลาสเอกสาร
1. เลือกหน้าเฉพาะผ่าน getPages().get_Item(Index)
1. ใช้ AnnotationSelector และรับคำอธิบายประกอบข้อความทั้งหมดผ่าน annotationSelector.getSelected()
1. วนซ้ำคำอธิบายประกอบแต่ละรายการโดยเรียกใช้เมธอด Delete เพื่อลบออก
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส Java เพื่อลบความคิดเห็นออกจากไฟล์ PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มคำอธิบายประกอบผ่าน Java" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Java
1. สร้างวัตถุคลาสเอกสาร
1. เพิ่มหน้าใหม่และเนื้อหาโดยใช้ getPages().add()
1. ใช้ getPages().get_Item(Index) ของคลาส TextAnnotation
1. กำหนดคำอธิบายประกอบที่เกี่ยวข้อง เช่น ชื่อเรื่อง หัวเรื่อง เนื้อหา ฯลฯ
1. ใช้ getAnnotations().add เพื่อเพิ่มคำอธิบายประกอบ
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์พร้อมความคิดเห็นเพิ่มเติม
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="โค้ด Java เพื่อเพิ่มคำอธิบายประกอบ PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอปพลิเคชันคำอธิบายประกอบเอกสาร PDF ผ่าน Java</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ PDF เพื่อให้คำติชม ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ซึ่งเป็น API ลูกของ [Aspose.Total for Java](https://products.aspose.com/total/java/) นักพัฒนา Java ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี Java อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้ นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ PDF<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java Library เพื่อใส่คำอธิบายประกอบไฟล์ PDF" %}}
มีตัวเลือกอื่นในการติดตั้ง "[Aspose.PDF for Java](https://products.aspose.com/pdf/java/)" หรือ "[Aspose.Total for Java](https://products.aspose.com/total/java/)" ลงบนระบบของคุณแพ็คเกจ Java ของเราได้รับการออกแบบให้เป็นแพลตฟอร์มข้ามแพลตฟอร์ม เข้ากันได้กับการใช้งาน JVM บนระบบปฏิบัติการต่างๆ เช่น Microsoft Windows, Linux, macOS, Android และ iOSโปรดเลือกรายการที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:<br />

- ติดตั้ง [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/)
- หรือจาก [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/)
- ทีละขั้นตอน [คำแนะนำ](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

- J2SE 8.0 (1.8) หรือสูงกว่า
- รองรับ Aspose.PDF สำหรับ Java บน IBM i (Iseries หรือ As/400)

<br />
สำหรับรายละเอียด โปรดดูที่ [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/pdf/java/system-requirements/#optional-dependencies)

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
                          <span itemprop="name"><b>ฉันสามารถใช้โค้ด Java ข้างต้นในแอปพลิเคชันของฉันได้หรือไม่</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ใช่ คุณสามารถดาวน์โหลดโค้ดนี้และใช้เพื่อวัตถุประสงค์ในการพัฒนาแอปพลิเคชันคำอธิบายประกอบเอกสารที่ใช้ Javaรหัสนี้สามารถทำหน้าที่เป็นทรัพยากรอันมีค่าในการปรับปรุงฟังก์ชันการทำงานและความสามารถของโปรเจ็กต์ของคุณในโดเมนของการประมวลผลและจัดการเอกสารแบ็กเอนด์</span>
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
                          <span itemprop="name"><b>การใช้แอปออนไลน์เพื่อใส่คำอธิบายประกอบเอกสาร PDF ปลอดภัยหรือไม่</b></span>
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
                          <span itemprop="text">คุณสามารถใช้เว็บเบราว์เซอร์สมัยใหม่ใดก็ได้ เช่น Google Chrome, Firefox, Opera หรือ Safari สำหรับคำอธิบายประกอบเอกสาร PDF ออนไลน์อย่างไรก็ตาม หากคุณกำลังพัฒนาแอปพลิเคชันบนเดสก์ท็อป เราขอแนะนำให้ใช้ API การประมวลผลเอกสาร Aspose.Total เพื่อการจัดการที่มีประสิทธิภาพ</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}