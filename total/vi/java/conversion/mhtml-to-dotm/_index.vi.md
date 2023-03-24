---
title: API Java để xuất MHTML sang DOTM
description: Chuyển đổi MHTML sang DOTM bằng cách sử dụng API Java tiền đề
url_ignore: /vi/java/conversion/mhtml-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DOTM
otherformats: DOTM OTT PCL ODT RTF FLATOPC XAMLFLOW MARKDOWN DOTX DOT WORDML PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi MHTML sang DOTM qua Java" h2="Trên API Premise Java để kết xuất MHTML thành DOTM mà không sử dụng bất kỳ ứng dụng bên thứ ba nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi MHTML sang DOTM bằng hai bước đơn giản. Trước tiên, bạn cần kết xuất tệp MHTML thành DOC bằng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể chuyển đổi DOC thành DOTM. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi MHTML sang DOTM" %}}
1. Mở tệp MHTML bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi MHTML sang DOC bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng DOTM bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt DOTM dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trong khi chuyển đổi MHTML thành DOTM, ngay cả khi tài liệu của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở nó bằng API thao tác PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Để mở tệp được mã hóa, bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và mở MHTML bằng mật khẩu của chủ sở hữu.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Mở tài liệu MHTML được bảo vệ bằng mật khẩu qua Java" %}}
Trong khi lưu tài liệu đầu vào của bạn ở định dạng tệp DOTM, bạn cũng có thể lưu tài liệu của mình vào cơ sở dữ liệu thay vì hệ thống tệp. Bạn có thể cần triển khai việc lưu trữ và truy xuất các đối tượng Tài liệu đến và từ cơ sở dữ liệu. Điều này sẽ cần thiết nếu bạn đang triển khai bất kỳ loại hệ thống quản lý nội dung nào. Để lưu DOTM của bạn vào cơ sở dữ liệu, thông thường cần phải tuần tự hóa tài liệu để có được một mảng byte. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Sau khi nhận được mảng byte của bạn, bạn có thể lưu trữ nó trong cơ sở dữ liệu bằng cách sử dụng câu lệnh SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}