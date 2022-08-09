---
title: API Android để kết xuất PCL thành RTF
description: Chuyển đổi PCL thành RTF qua Android thông qua Java API
url: /vi/android-java/conversion/pcl-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: RTF
otherformats: DOTM OTT DOTX FLATOPC PS DOT DOCM MHTML MARKDOWN WORDML XAMLFLOW ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất PCL thành RTF trên Android qua Java" h2="Chuyển đổi PCL sang RTF trong ứng dụng di động mà không cần cài đặt bất kỳ phần mềm nào" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể tích hợp tính năng chuyển đổi PCL sang RTF trong ứng dụng dành cho thiết bị di động của mình bằng cách sử dụng hai API của gói [Aspose.Total cho Android Java](https://products.aspose.com/total/android-java/). Trước tiên, bạn cần chuyển đổi tệp PCL sang DOC bằng [Aspose.PDF cho Android qua Java](https://products.aspose.com/pdf/android-java/). Thứ hai, bằng cách sử dụng API xử lý văn bản [Aspose.Words dành cho Android Java](https://products.aspose.com/words/android-java/), bạn có thể kết xuất DOC thành RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi PCL sang RTF trên Android qua Java" %}}
1. Mở tệp PCL bằng lớp [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi PCL sang DOC bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng RTF bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt RTF dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.PDF cho Android qua Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Words dành cho Android qua Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.RTF
outputDocument.save("output.rtf", SaveFormat.RTF);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận thông tin tệp PCL trên Android qua Java" %}}
Trước khi chuyển đổi PCL sang RTF, bạn có thể cần thông tin về tài liệu bao gồm tác giả, ngày tạo, từ khóa, ngày sửa đổi, chủ đề và tiêu đề. Thông tin này rất hữu ích cho việc đưa ra quyết định cho quá trình chuyển đổi. Bằng cách sử dụng API [Aspose.PDF dành cho Android qua Java](https://docs.aspose.com/pdf/androidjava/) mạnh mẽ, bạn có thể nhận được tất cả. Để nhận thông tin cụ thể về tệp về tệp PCL, trước tiên hãy lấy đối tượng [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) bằng cách sử dụng đối tượng [getInfo](https: // phương thức reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Khi đối tượng DocumentInfo được truy xuất, bạn có thể nhận các giá trị của các thuộc tính riêng lẻ.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL document
Document doc = new Document("template.pcl");
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

{{% blocks/products/pf/feature-page-section  h2="Chèn chú thích vào tài liệu RTF trong Android qua Java" %}}
Ngoài chuyển đổi tài liệu, bạn cũng có thể thêm một loạt các tính năng khác bên trong Ứng dụng Android của mình bằng cách sử dụng API [Aspose.Words dành cho Android qua Java](https://products.aspose.com/words/androidjava/). Một trong những tính năng đó là chèn chú thích cuối và đánh số trong tài liệu RTF. Nếu bạn muốn chèn chú thích cuối trang hoặc chú thích cuối vào tài liệu RTF, vui lòng sử dụng phương thức DocumentBuilder.InsertFootnote. Phương pháp này chèn chú thích cuối trang hoặc chú thích cuối vào tài liệu. Các lớp EndnoteOptions và FootnoteOptions đại diện cho các tùy chọn đánh số cho footnote và endnote.
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
doc.save("output.rtf", SaveFormat.RTF);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-dotm/" name="PCL Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-ott/" name="PCL Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-dotx/" name="PCL Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-flatopc/" name="PCL Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-ps/" name="PCL Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-dot/" name="PCL Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-rtf/" name="PCL Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-mhtml/" name="PCL Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-markdown/" name="PCL Đến MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-wordml/" name="PCL Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-xamlflow/" name="PCL Đến XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/pcl-to-odt/" name="PCL Đến ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}