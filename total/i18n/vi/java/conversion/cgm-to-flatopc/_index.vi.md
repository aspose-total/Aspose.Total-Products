---
title: API Java để xuất CGM sang FLATOPC
description: Chuyển đổi CGM sang FLATOPC bằng cách sử dụng API Java tiền đề
url: /vi/java/conversion/cgm-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FLAT_OPC
otherformats: PCL MARKDOWN MHTML RTF DOTM FLATOPC XAMLFLOW DOT ODT DOTX PS OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi CGM sang FLATOPC qua Java" h2="Trên API Premise Java để kết xuất CGM thành FLATOPC mà không sử dụng bất kỳ ứng dụng bên thứ ba nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi CGM sang FLATOPC bằng hai bước đơn giản. Trước tiên, bạn cần kết xuất tệp CGM thành DOC bằng [Aspose.PDF cho Java] (https://products.aspose.com/pdf/java/). Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for Java] (https://products.aspose.com/words/java/), bạn có thể chuyển đổi DOC thành FLATOPC. Cả hai API đều nằm trong gói [Aspose.Total cho Java] (https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi CGM sang FLATOPC" %}}
1. Mở tệp CGM bằng lớp [Tài liệu] (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang DOC bằng cách sử dụng [save] (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document] (https://apireference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng FLATOPC bằng phương pháp [save] (https://apireference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, int)) và đặt FLATOPC dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ dự án dựa trên [Maven] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm [Aspose.PDF dành cho Java] (https://docs.aspose.com/pdf/java/installation/) và [Aspose.Words dành cho Java] (https://docs.aspose.com/words/java/ cài đặt /) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trong khi chuyển đổi CGM thành FLATOPC, ngay cả khi tài liệu của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở nó bằng API thao tác PDF [Aspose.PDF dành cho Java] (https://docs.aspose.com/pdf/java/installation/). Để mở tệp được mã hóa, bạn cần tạo đối tượng [Tài liệu] (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) và mở CGM bằng mật khẩu của chủ sở hữu.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Mở tài liệu CGM được bảo vệ bằng mật khẩu qua Java" %}}
Trong khi lưu tài liệu đầu vào của bạn ở định dạng tệp FLATOPC, bạn cũng có thể lưu tài liệu của mình vào cơ sở dữ liệu thay vì hệ thống tệp. Bạn có thể cần triển khai việc lưu trữ và truy xuất các đối tượng Tài liệu đến và từ cơ sở dữ liệu. Điều này sẽ cần thiết nếu bạn đang triển khai bất kỳ loại hệ thống quản lý nội dung nào. Để lưu FLATOPC của bạn vào cơ sở dữ liệu, thông thường cần phải tuần tự hóa tài liệu để có được một mảng byte. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words dành cho Java] (https://products.aspose.com/words/Java/). Sau khi nhận được mảng byte của bạn, bạn có thể lưu trữ nó trong cơ sở dữ liệu bằng cách sử dụng câu lệnh SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.FLAT_OPC);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-rtf/" name="CGM Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-wordml/" name="CGM Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-odt/" name="CGM Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-flatopc/" name="CGM Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-ps/" name="CGM Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-pcl/" name="CGM Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-mhtml/" name="CGM Đến MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-dotm/" name="CGM Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-ott/" name="CGM Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-dotx/" name="CGM Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-xamlflow/" name="CGM Đến XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/cgm-to-markdown/" name="CGM Đến MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}