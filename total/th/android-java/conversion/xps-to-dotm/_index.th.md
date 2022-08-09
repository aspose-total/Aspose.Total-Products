---
title: Android API เพื่อแสดงผล XPS เป็น DOTM
description: แปลง XPS เป็น DOTM ผ่าน Android ผ่าน Java API
url: /th/android-java/conversion/xps-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: DOTM
otherformats: WORDML DOT DOTX XAMLFLOW OTT PCL FLATOPC PS MHTML MARKDOWN ODT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล XPS เป็น DOTM บน Android ผ่าน Java" h2="แปลง XPS เป็น DOTM ในแอพมือถือโดยไม่ต้องติดตั้งซอฟต์แวร์ใดๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง XPS เป็น DOTM ในแอปบนอุปกรณ์เคลื่อนที่ได้โดยใช้ API สองชุดของ [Aspose.Total สำหรับ Android Java](https://products.aspose.com/total/android-java/) ก่อนอื่น คุณต้องแปลงไฟล์ XPS เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) ประการที่สอง โดยใช้ Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) คุณสามารถแสดง DOC เป็น DOTM 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง XPS เป็น DOTM บน Android ผ่าน Java" %}}
1. เปิดไฟล์ XPS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง XPS เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ DOTM โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า DOTM เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Android ผ่าน Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF สำหรับ Android ผ่าน Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Words สำหรับ Android ผ่าน Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลไฟล์ XPS บน Android ผ่าน Java" %}}
ก่อนที่จะแปลง XPS เป็น DOTM คุณอาจต้องการข้อมูลเกี่ยวกับเอกสาร ซึ่งรวมถึงผู้แต่ง วันที่สร้าง คำหลัก วันที่แก้ไข หัวเรื่อง และชื่อเรื่อง ข้อมูลนี้มีประโยชน์สำหรับการตัดสินใจในกระบวนการแปลง ด้วยการใช้ [Aspose.PDF สำหรับ Android ผ่าน Java](https://docs.aspose.com/pdf/androidjava/) อันทรงพลัง คุณสามารถรับมันได้ทั้งหมด หากต้องการรับข้อมูลเฉพาะไฟล์เกี่ยวกับไฟล์ XPS ก่อนอื่นให้รับวัตถุ [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) โดยใช้ [getInfo](https://) วิธีอ้างอิง.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) เมื่อดึงวัตถุ DocumentInfo แล้ว คุณจะได้รับค่าของคุณสมบัติแต่ละรายการ
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS document
Document doc = new Document("template.xps");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แทรก Endnotes ในเอกสาร DOTM ใน Android ผ่าน Java" %}}
นอกเหนือจากการแปลงเอกสาร คุณยังสามารถเพิ่มคุณสมบัติอื่นๆ มากมายภายในแอปพลิเคชัน Android ของคุณโดยใช้ [Aspose.Words สำหรับ Android ผ่าน Java](https://products.aspose.com/words/androidjava/) API หนึ่งในคุณสมบัตินั้นคือการแทรกอ้างอิงท้ายเรื่องและการกำหนดหมายเลขในเอกสาร DOTM หากคุณต้องการแทรกเชิงอรรถหรืออ้างอิงท้ายเรื่องในเอกสาร DOTM โปรดใช้วิธี DocumentBuilder.InsertFootnote วิธีนี้จะแทรกเชิงอรรถหรืออ้างอิงท้ายเรื่องลงในเอกสาร คลาส EndnoteOptions และ FootnoteOptions แสดงถึงตัวเลือกการกำหนดหมายเลขสำหรับเชิงอรรถและอ้างอิงท้ายเรื่อง
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.dotm", SaveFormat.DOTM);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-wordml/" name="XPS ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-dot/" name="XPS ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-dotx/" name="XPS ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-xamlflow/" name="XPS ถึง XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-ott/" name="XPS ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-pcl/" name="XPS ถึง PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-flatopc/" name="XPS ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-ps/" name="XPS ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-mhtml/" name="XPS ถึง MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-markdown/" name="XPS ถึง MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-odt/" name="XPS ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-dotm/" name="XPS ถึง DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}