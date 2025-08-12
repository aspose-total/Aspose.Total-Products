---
title: Java API เพื่อแสดงผล CGM เป็น DIF
description: ส่งออก CGM เป็น DIF ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: XLT XLSB XLAM DIF XLTX XLTM SXC TXT EXCEL ODS MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก CGM เป็น DIF ผ่าน Java" h2="แปลงไฟล์ CGM เป็น DIF โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง CGM เป็น DIF ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง CGM เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น DIF ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ CGM เป็น DIF ผ่าน Java" %}}
1. เปิดไฟล์ CGM โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง CGM เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ DIF โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
หากเอกสาร CGM ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น DIF ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง CGM ที่ได้รับการป้องกันเป็น DIF ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ CGM เป็น DIF คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ DIF เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น DIF ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
## ✅ การใช้งานหลัก

- **การย้ายระบบสเปรดชีตเก่า**  
  แปลงข้อมูล CGM เป็น DIF เพื่อนำเข้าโปรแกรมสเปรดชีตเก่าที่ยังใช้งานในสภาพแวดล้อมองค์กรได้อย่างราบรื่น

- **แพลตฟอร์มการคำนวณทางวิทยาศาสตร์**  
  แปลงข้อมูลกราฟิก CGM เป็น DIF เพื่อความเข้ากันได้กับเครื่องมือวิเคราะห์ตัวเลขในฟิสิกส์ เคมี และการจำลองสภาพแวดล้อม

- **การจำแนกข้อมูลโครงสร้างในแอปพลิเคชันวิศวกรรม**  
  ใช้ DIF เพื่อแทนแผนภาพที่ใช้ CGM ในรูปแบบตารางโครงสร้างสำหรับการจำลองวิศวกรรมและการผสมข้อมูล CAD


## ⚙️ สถานการณ์การอัตโนมัติ

- **ไลบรารี Java สำหรับการแปลงสเปรดชีต**  
  นำเข้าการแปลง CGM เป็น DIF โดยอัตโนมัติโดยใช้ Java APIs ที่จัดการกับรูปแบบที่เข้ากันได้กับสเปรดชีต

- **การประมวลผลแบบกลุ่มในเครื่องมือ ETL**  
  รวมขั้นตอนการแปลงเข้ากับท่อการทำงาน Extract-Transform-Load ที่ใช้ Java เพื่อประมวลผลปริมาณข้อมูลวิศวกรรมหรือวิจัยที่มาก

- **การผสมรวมกับท่อการคำนวณทางสถิติ**  
  ส่งไฟล์ DIF ที่แปลงมาให้กับโมดูลวิเคราะห์สถิติใน R, MATLAB หรือ Python อัตโนมัติผ่านการจัดการกระบวนการทำงานใน Java
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}