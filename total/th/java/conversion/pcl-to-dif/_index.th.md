---
title: Java API เพื่อแสดงผล PCL เป็น DIF
description: ส่งออก PCL เป็น DIF ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/pcl-to-dif/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: DIF
otherformats: XLSB ODS XLT TSV SXC FODS TXT XLTX XLSM MD EXCEL XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก PCL เป็น DIF ผ่าน Java" h2="แปลงไฟล์ PCL เป็น DIF โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง PCL เป็น DIF ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง PCL เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น DIF ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ PCL เป็น DIF ผ่าน Java" %}}
1. เปิดไฟล์ PCL โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง PCL เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
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
หากเอกสาร PCL ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น DIF ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง PCL ที่ได้รับการป้องกันเป็น DIF ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ PCL เป็น DIF คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ DIF เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น DIF ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

## การแปลง **PCL เป็น DIF** จะแปลงไฟล์ **Printer Command Language** เป็นไฟล์ **Data Interchange Format (DIF)** ซึ่งช่วยให้มีการแลกเปลี่ยนข้อมูลโครงสร้างและสามารถใช้งานร่วมกันในสเปรดชีตระหว่างแอปพลิเคชัน

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

* การสกัดข้อมูลตารางจากรายงานที่พิมพ์เป็นรูปแบบ DIF
* การอำนวยความสะดวกในการนำเข้าข้อมูลการพิมพ์เข้าสู่ระบบสเปรดชีตรุ่นเก่า
* การทำให้การย้ายข้อมูลระหว่างเครื่องมือวิเคราะห์เป็นไปอย่างราบรื่น
* การสร้างชุดข้อมูลที่ใช้ซ้ำจากการพิมพ์ PCL ที่ถูกเก็บถาวร

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

* การแปลงรายงาน PCL เป็น DIF โดยอัตโนมัติสำหรับการแลกเปลี่ยนข้อมูล
* การรวมเข้ากับท่อ ETL สำหรับการแลกเปลี่ยนข้อมูลโครงสร้าง
* การแปลงข้อมูลจำนวนมากจากการเก็บถาวรพิมพ์ให้เป็นแหล่งข้อมูลวิเคราะห์ที่เข้ากันได้กับ DIF

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}