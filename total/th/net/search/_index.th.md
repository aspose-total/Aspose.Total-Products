---
title: ค้นหาเอกสารผ่าน C# .NET 

description: ค้นหาเอกสารรวมถึง PDF, Microsoft Office Excel, Word, PowerPoint และอื่นๆ ผ่านทางแอปพลิเคชัน .NET ของคุณ ค้นหาเอกสารออนไลน์ผ่านแอพ
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ค้นหาเอกสารโดยใช้ .NET API" h2="ค้นหาและดึงข้อมูลจากเอกสารที่หลากหลายได้อย่างง่ายดาย ครอบคลุมไฟล์ Microsoft Office Word, Excel, PowerPoint และ PDF ในลักษณะที่มีประสิทธิภาพสูงด้วย Aspose.Total สำหรับ .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}

การเปิดใช้งานการค้นหาข้อความและการจัดทำดัชนีเนื้อหาสำหรับรูปแบบไฟล์เอกสารที่หลากหลายทำให้ผู้ใช้สามารถเพิ่มประสิทธิภาพการทำงาน ปรับปรุงการดึงข้อมูล และปรับปรุงการจัดการข้อมูลทั่วทั้งองค์กรและแอปพลิเคชัน ปรับปรุงฟังก์ชันการทำงานของซอฟต์แวร์หรือระบบที่ใช้ .NET ของคุณโดยเปิดใช้งานการค้นหาด้วยข้อความภายในเอกสารและสร้างดัชนีเพื่อการดึงข้อมูลจากรูปแบบไฟล์เอกสารที่หลากหลายอย่างมีประสิทธิภาพ

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="เหตุผลสำคัญในการค้นหาในเอกสาร" %}}

1. การจัดระเบียบเอกสาร
1. การสืบค้นข้อมูล
1. การตรวจสอบเนื้อหา 
1. การสรุปเนื้อหา 
1. การวิเคราะห์ข้อความ
1. การสกัดข้อมูล 
1. การจัดทำดัชนีเอกสาร 


{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ค้นหาเอกสาร PDF" %}}

เราใช้ [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ซึ่งเป็น API ลูกของ [Aspose.Total for .NET](https://products.aspose.com/total/net/) ที่ออกแบบมาสำหรับคุณสมบัติการจัดการเอกสารโดยเฉพาะ รวมถึงงานที่เกี่ยวข้องกับการดึงและค้นหาเนื้อหาเอกสาร ข้อมูลโค้ดด้านล่างเขียนด้วยภาษา C# เพื่อโต้ตอบกับเอกสาร PDF ขั้นแรกจะตั้งค่ารูปแบบนิพจน์ทั่วไปเพื่อค้นหาลำดับของอักขระที่ไม่ใช่ช่องว่างภายในเอกสาร จากนั้นจะเข้าถึงหน้าแรกของ PDF และใช้ TextFragmentAbsorber เพื่อค้นหาข้อความบนหน้านั้นโดยใช้นิพจน์ทั่วไปที่ระบุ จากนั้นโค้ดจะรวบรวมส่วนของข้อความที่ค้นพบไว้ในคอลเลกชัน สุดท้ายจะวนซ้ำผ่านคอลเลกชันนี้และส่งออกส่วนข้อความที่ระบุแต่ละส่วนไปยังคอนโซล โดยพื้นฐานแล้ว ข้อมูลโค้ดนี้ทำหน้าที่เป็นกลไกในการแยกและแสดงรูปแบบข้อความเฉพาะจากเอกสาร PDF นอกจากนี้ .NET Search API ยังรองรับ Microsoft [ค้นหาเอกสารคำ](https://products.aspose.com/total/net/search/word/) และรูปแบบอื่นๆ อีกด้วย

{{% blocks/products/pf/feature-page-code h3="รหัส C# สำหรับการค้นหาเอกสาร PDF" %}}

{{< gist "aspose-com-gists" "3c806eb023f399cd402ab922a247f2d0" "pdf-document-search.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}