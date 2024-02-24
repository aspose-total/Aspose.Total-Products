---
title: แปลง HTML ของหน้าเว็บเป็นภาพโดยใช้ C #
description: ขูดหน้าเว็บเว็บไซต์และส่งออก HTML เป็นรูปภาพ พัฒนาแอปพลิเคชัน .NET เพื่อขูดข้อมูลเว็บไซต์เป็น JPEG, PNG, GIF, BMP เป็นต้น 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลงหน้าเว็บเป็นภาพผ่าน C#" h2="แยกข้อมูลเว็บไซต์ออกจากหน้าเว็บ HTML แปลง HTML เป็นภาพ JPG, GIF, PNG, BMP ภายในแอปพลิเคชัน .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">ทำไมต้องแปลงหน้าเว็บเป็นรูปภาพ</h2>
<p>การแปลงหน้าเว็บเป็นรูปภาพอาจมีประโยชน์ในหลายสถานการณ์ เป็นข้อกำหนดทั่วไปสำหรับแอปพลิเคชันจำนวนมาก ในบางสถานการณ์ จำเป็นต้องจับภาพหน้าเว็บทั้งหน้าเป็นรูปภาพ รวมถึงส่วนที่มองไม่เห็นบนหน้าจอ สิ่งนี้มีประโยชน์ในการสร้างตัวอย่างเว็บไซต์ บันทึกใบเสร็จรับเงินและใบแจ้งหนี้ หรือเก็บถาวรหน้าเว็บเพื่อวัตถุประสงค์ทางกฎหมาย สามารถใช้สร้างภาพหน้าจอของหน้าเว็บเพื่อวัตถุประสงค์ในการจัดทำเอกสารหรือการทดสอบ นอกจากนี้ยังสามารถใช้เพื่อสร้างภาพขนาดย่อหรือตัวอย่างหน้าเว็บเพื่อใช้ในผลการค้นหาหรือแกลเลอรีรูปภาพ ไม่ว่าคุณกำลังสร้างเดสก์ท็อปแอปพลิเคชันหรือเว็บแอปพลิเคชัน มีตัวเลือกมากมายสำหรับการแปลงหน้าเว็บเป็นรูปภาพโดยใช้ C#</p><br />

<p>การแปลงหน้าเว็บเป็นรูปภาพโดยใช้ C# สามารถให้ประโยชน์หลายประการ ได้แก่:</p><br />
<ul>
<li>การเข้าถึงที่ดีขึ้น: รูปภาพสามารถอ่านและเข้าใจได้ง่ายขึ้นสำหรับผู้ที่มีความบกพร่องทางสายตาหรือความพิการอื่นๆ</li>
<li>เพิ่มความสะดวกในการพกพา: รูปภาพสามารถแชร์หรือฝังในเอกสารหรือแอปพลิเคชันอื่นๆ ได้อย่างง่ายดาย</li>
</ul>
<p>การแปลงหน้าเว็บเป็นรูปภาพโดยใช้ C# อาจทำให้เกิดความท้าทายบางอย่าง เช่น:</p><br />
<ul>
<li>รองรับรูปแบบจำกัด: API หรือเครื่องมือบางอย่างอาจไม่รองรับรูปแบบรูปภาพทั้งหมด หรืออาจมีข้อจำกัดเกี่ยวกับขนาดหรือความละเอียดของรูปภาพที่ส่งออก</li>
<li>ปัญหาความเข้ากันได้: หน้าเว็บบางหน้าอาจแสดงไม่ถูกต้องในทุกเบราว์เซอร์ หรืออาจต้องการการตั้งค่าหรือปลั๊กอินเฉพาะเพื่อให้แสดงได้อย่างถูกต้อง</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลงหน้าเว็บเป็นรูปภาพโดยใช้ C #" %}}
หากต้องการแปลงหน้าเว็บเป็นรูปภาพโดยใช้ C# คุณสามารถใช้ Aspose.HTML สำหรับ .NET API ที่มีฟังก์ชันนี้เพื่อแปลงหน้า HTML เป็นรูปแบบรูปภาพ รวมถึง JPEG, PNG และ TIFF</p>

1. โหลดเอกสาร HTML โดยใช้ตัวสร้างที่มีอยู่ใน [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). คุณสามารถโหลด HTML จากไฟล์ โค้ด HTML สตรีม หรือ URL
2. สร้างอินสแตนซ์ใหม่ของ [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) และตั้งค่าคุณสมบัติ ImageFormat เป็น JPEG ตามค่าเริ่มต้น คุณสมบัติ รูปแบบ จะถูกตั้งค่าเป็น PNG
3. ใช้ [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) เมธอดจากคลาส Converter เพื่อบันทึกเอกสาร HTML เป็นไฟล์ JPEG คุณจะต้องระบุ HTMLDocument, ImageSaveOptions และเส้นทางไฟล์เอาต์พุตเป็นพารามิเตอร์ให้กับเมธอด ConvertHTML()
4. ไฟล์ JPEG ที่ได้จะถูกบันทึกไปยังเส้นทางไฟล์ที่ระบุ
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดเรื่องเศษซากเว็บและการแปลงรูปภาพ" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` nuget install Aspose.Total``` หรือติดตั้งโดยตรงจาก Package Manager Console ของ Visual Studio

สอง [Aspose.Total for .NET](https://products.aspose.com/total/net/) API ลูก [Aspose.HTML for .NET](https://products.aspose.com/html/net/) จะถูกบูรณาการ

หรืออีกทางหนึ่ง ให้ดาวน์โหลดตัวติดตั้ง MSI หรือ DLL แบบออฟไลน์ในไฟล์ ZIP จาก [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}