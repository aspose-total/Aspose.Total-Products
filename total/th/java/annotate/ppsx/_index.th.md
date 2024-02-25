---
title: ลบคำอธิบายประกอบ PPSX ออนไลน์หรือจัดการคำอธิบายประกอบผ่าน Java
description: ลบความคิดเห็นออกจากไฟล์ PPSX ผ่านแอปออนไลน์ฟรีรหัส Java API เพื่อจัดการความคิดเห็นของไฟล์ PPSX

family: total
platformtag: Java
feature: Annotate
informat: PPSX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากการนำเสนอ PPSX ออนไลน์หรือจัดการผ่าน Java" h2="พัฒนาแอปพลิเคชันยูทิลิตีคำอธิบายประกอบการนำเสนอ PPSX ที่ใช้ Java ที่ทรงพลังรหัสที่แสดงสำหรับการจัดการความคิดเห็นของไฟล์ PPSX ผ่าน Java" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ PPSX ออนไลน์" %}}

1. นำเข้าไฟล์ PPSX เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ PPSX และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นการนำเสนอ PPSX ผ่าน Java" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Java
1. โหลด PPSX ผ่านวัตถุคลาสการนำเสนอ
1. วนซ้ำผู้แต่งแต่ละคนผ่านคอลเลกชัน [Presentation.getCommentAuthors()](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#getCommentAuthors--)
1. เรียกใช้วิธี [clear()](https://reference.aspose.com/slides/java/com.aspose.slides/icommentcollection/#clear--) เพื่อลบความคิดเห็น
1. ในที่สุดก็เรียก [getCommentAuthors().clear()](https://reference.aspose.com/slides/java/com.aspose.slides/commentauthorcollection/#clear--) เพื่อลบผู้เขียนทั้งหมด
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="ตัวอย่างโค้ดใน Java เพื่อลบความคิดเห็นและผู้แต่งออกจากการนำเสนอ PPSX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มความคิดเห็นการนำเสนอ PPSX ผ่าน Java" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Java
1. โหลด PPSX ผ่านวัตถุคลาสการนำเสนอ
1. เรียกใช้ [Presentation.getCommentAuthors().addAuthor(String, String)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentAuthorCollection#addAuthor-java.lang.String-java.lang.String-) เพื่อเพิ่มผู้เขียน
1. ใช้ [ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentCollection#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) เพื่อเพิ่มความคิดเห็น
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์ with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส Java: การเพิ่มความคิดเห็น" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอปพลิเคชันคำอธิบายประกอบเอกสาร PPSX ผ่าน Java</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ PPSX เพื่อให้คำติชม ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ซึ่งเป็น API ลูกของ [Aspose.Total for Java](https://products.aspose.com/total/java/) นักพัฒนา Java ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี Java อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ PPSX<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java Library เพื่อใส่คำอธิบายประกอบไฟล์ PPSX" %}}
มีตัวเลือกอื่นในการติดตั้ง "[Aspose.Slides for Java](https://products.aspose.com/slides/java/)" หรือ "[Aspose.Total for Java](https://products.aspose.com/total/java/)" ลงบนระบบของคุณ แพ็คเกจ Java ของเราได้รับการออกแบบให้เป็นแพลตฟอร์มข้ามแพลตฟอร์ม เข้ากันได้กับการใช้งาน JVM บนระบบปฏิบัติการต่างๆ เช่น Microsoft Windows, Linux, macOS, Android และ iOSโปรดเลือกรายการที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:<br />

- ติดตั้ง [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/)
- หรือจาก [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)
- ทีละขั้นตอน [คำแนะนำ](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

- J2SE 6.0 (Java 1.6) และสูงกว่า

<br />
สำหรับรายละเอียด โปรดดูที่ [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/slides/java/system-requirements/#optional-dependencies)

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
                          <span itemprop="name"><b>การใช้แอปออนไลน์เพื่อใส่คำอธิบายประกอบเอกสาร PPSX ปลอดภัยหรือไม่</b></span>
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
                          <span itemprop="text">คุณสามารถใช้เว็บเบราว์เซอร์สมัยใหม่ใดก็ได้ เช่น Google Chrome, Firefox, Opera หรือ Safari สำหรับคำอธิบายประกอบเอกสาร PPSX ออนไลน์อย่างไรก็ตาม หากคุณกำลังพัฒนาแอปพลิเคชันบนเดสก์ท็อป เราขอแนะนำให้ใช้ API การประมวลผลเอกสาร Aspose.Total เพื่อการจัดการที่มีประสิทธิภาพ</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}