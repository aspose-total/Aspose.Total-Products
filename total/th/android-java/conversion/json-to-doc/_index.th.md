---
title: แปลงรูปแบบ JSON เป็น DOC ใน Android ผ่าน Java
description: แยก JSON เป็น DOC ใน Java โดยไม่ต้องใช้ Microsoft Word
url: /th/android-java/conversion/json-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOC
otherformats: DOT RTF EPUB WORD FLATOPC DOCM ODT MOBI PS OTT DOTX WORDML CHM PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลงรูปแบบ JSON เป็น DOC ในแอปพลิเคชัน Android" h2="แยก JSON เป็น DOC ภายในแอปพลิเคชัน Android โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง JSON เป็น DOC ในแอปพลิเคชัน Android ของคุณในกระบวนการสองขั้นตอน ประการแรก ด้วยการใช้ API การประมวลผลสเปรดชีตที่มีประสิทธิภาพ [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) คุณสามารถแยก JSON เป็น PDF ได้ ในขั้นตอนที่สอง คุณสามารถแปลง PDF เป็น DOC โดยใช้ Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) API ทั้งสองอยู่ภายใต้ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ตระกูลผลิตภัณฑ์ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น DOC ใน Android ผ่าน Java" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) วัตถุใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) และ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ DOC โดยใช้ [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้งไลบรารีในแอปของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น DOC ใน Android ผ่าน Java" %}}
นอกจากนี้ API ยังให้คุณตั้งค่าตัวเลือกเลย์เอาต์สำหรับรูปแบบ JSON ของคุณในขณะที่แยกวิเคราะห์ JSON เป็น DOC โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลงรูปแบบ JSON เป็น DOC พร้อมลายน้ำใน Android ผ่าน Java" %}}
การใช้ API คุณสามารถแปลง JSON เป็น DOC ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร DOC ของคุณ ขั้นแรกให้แยกไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติ Call Watermark.setText วิธีการและส่งข้อความลายน้ำและวัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ DOC
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-dot/" name="JSON ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-rtf/" name="JSON ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-epub/" name="JSON ถึง EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-word/" name="JSON ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-flatopc/" name="JSON ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-docm/" name="JSON ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-odt/" name="JSON ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-mobi/" name="JSON ถึง MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-ps/" name="JSON ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-ott/" name="JSON ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-dotx/" name="JSON ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-wordml/" name="JSON ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-doc/" name="JSON ถึง DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/json-to-pcl/" name="JSON ถึง PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}