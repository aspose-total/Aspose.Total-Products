---
title: API Java để xuất MD sang PCL
description: Chuyển đổi MD sang PCL bằng cách sử dụng API Java tiền đề
url_ignore: /vi/java/conversion/md-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PCL
otherformats: PCL ODT OTT MHTML DOTM MARKDOWN RTF FLATOPC WORDML DOT PS XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi MD sang PCL qua Java" h2="Trên API Premise Java để kết xuất MD thành PCL mà không sử dụng bất kỳ ứng dụng bên thứ ba nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi MD sang PCL bằng hai bước đơn giản. Trước tiên, bạn cần kết xuất tệp MD thành DOC bằng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể chuyển đổi DOC thành PCL. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi MD sang PCL" %}}
1. Mở tệp MD bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi MD sang DOC bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng PCL bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt PCL dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-pcl.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trong khi chuyển đổi MD thành PCL, ngay cả khi tài liệu của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở nó bằng API thao tác PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Để mở tệp được mã hóa, bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và mở MD bằng mật khẩu của chủ sở hữu.  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Mở tài liệu MD được bảo vệ bằng mật khẩu qua Java" %}}
Trong khi lưu tài liệu đầu vào của bạn ở định dạng tệp PCL, bạn cũng có thể lưu tài liệu của mình vào cơ sở dữ liệu thay vì hệ thống tệp. Bạn có thể cần triển khai việc lưu trữ và truy xuất các đối tượng Tài liệu đến và từ cơ sở dữ liệu. Điều này sẽ cần thiết nếu bạn đang triển khai bất kỳ loại hệ thống quản lý nội dung nào. Để lưu PCL của bạn vào cơ sở dữ liệu, thông thường cần phải tuần tự hóa tài liệu để có được một mảng byte. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Sau khi nhận được mảng byte của bạn, bạn có thể lưu trữ nó trong cơ sở dữ liệu bằng cách sử dụng câu lệnh SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PCL);
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
```
{{< blocks/products/pf/agp/feature-section >}}



Chuyển đổi Markdown (MD) sang PCL (Ngôn ngữ Lệnh Máy In) tạo ra các tệp sẵn sàng in tương thích với máy in laser và máy in phun mực. Chuyển đổi PCL phù hợp để tạo ra tài liệu kỹ thuật, báo cáo và tự động hóa quy trình làm việc trong môi trường in ấn doanh nghiệp.



{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}



* In các báo cáo dựa trên Markdown trên các máy in hỗ trợ PCL.

* Tạo đầu ra PCL cho việc phân phối tài liệu hàng loạt.

* Chuyển đổi tài liệu Markdown thành định dạng sẵn sàng in.

* Chuẩn bị hướng dẫn kỹ thuật cho quy trình in ấn văn phòng hoặc sản xuất.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}



* Chuyển đổi hàng loạt định kỳ của các tệp Markdown sang PCL cho in ấn doanh nghiệp.

* Tích hợp với máy chủ in để tự động tạo ra PCL từ tài liệu Markdown.

* Các đường ống in tự động chuyển đổi Markdown sang PCL.

* Sản xuất tài liệu dựa trên cơ sở kích hoạt cho máy in PCL có khối lượng lớn.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}