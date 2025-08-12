---
title: API Java để xuất CGM sang PS
description: Chuyển đổi CGM sang PS bằng cách sử dụng API Java tiền đề
url_ignore: /vi/java/conversion/cgm-to-ps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PS
otherformats: MHTML MARKDOWN ODT DOT WORDML OTT RTF PS FLATOPC DOTM DOTX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi CGM sang PS qua Java" h2="Trên API Premise Java để kết xuất CGM thành PS mà không sử dụng bất kỳ ứng dụng bên thứ ba nào" >}}
{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi CGM sang PS bằng hai bước đơn giản. Trước tiên, bạn cần kết xuất tệp CGM thành DOC bằng [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Sau đó, bằng cách sử dụng API xử lý tài liệu mạnh mẽ [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể chuyển đổi DOC thành PS. Cả hai API đều nằm trong gói [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API để chuyển đổi CGM sang PS" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi CGM sang DOC bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng PS bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt PS dưới dạng SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) và [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trong khi chuyển đổi CGM thành PS, ngay cả khi tài liệu của bạn được bảo vệ bằng mật khẩu, bạn vẫn có thể mở nó bằng API thao tác PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Để mở tệp được mã hóa, bạn cần tạo đối tượng [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và mở CGM bằng mật khẩu của chủ sở hữu.  
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
Trong khi lưu tài liệu đầu vào của bạn ở định dạng tệp PS, bạn cũng có thể lưu tài liệu của mình vào cơ sở dữ liệu thay vì hệ thống tệp. Bạn có thể cần triển khai việc lưu trữ và truy xuất các đối tượng Tài liệu đến và từ cơ sở dữ liệu. Điều này sẽ cần thiết nếu bạn đang triển khai bất kỳ loại hệ thống quản lý nội dung nào. Để lưu PS của bạn vào cơ sở dữ liệu, thông thường cần phải tuần tự hóa tài liệu để có được một mảng byte. Điều này có thể được thực hiện bằng cách sử dụng API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Sau khi nhận được mảng byte của bạn, bạn có thể lưu trữ nó trong cơ sở dữ liệu bằng cách sử dụng câu lệnh SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
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
{{% blocks/products/pf/feature-page-summary %}}
```
Chuyển đổi CGM (Computer Graphics Metafile) sang PS (PostScript) là một bước quan trọng để đạt được kết quả in chính xác, chất lượng cao và chuyên nghiệp. Định dạng độc lập với thiết bị của PostScript đảm bảo rằng đồ họa vector phức tạp, sơ đồ kỹ thuật và minh họa kỹ thuật giữ nguyên độ chính xác và trung thực khi chuyển sang máy in hoặc hệ thống xuất bản. Điều này khiến việc chuyển đổi CGM sang PS trở nên không thể thiếu đối với các ngành đòi hỏi đầu ra nhất quán, có thể mở rộng và sẵn sàng in.

## ✅ Các Trường Hợp Sử Dụng Chính
- **In Vector Cấp Công Nghiệp** – Tạo ra sơ đồ kỹ thuật sắc nét, có thể mở rộng cho sản xuất, kỹ thuật và tài liệu kiến trúc.
- **Lưu Trữ Minh Họa Kỹ Thuật trong Hệ Thống Dựa Trên PostScript** – Lưu trữ tài sản vector dưới dạng tối ưu hóa cho khả năng truy cập lâu dài và tương thích in ấn.
- **Chuẩn Bị Sơ Đồ CGM cho Dàn Trang** – Đảm bảo tích hợp mượt mà vào quy trình dàn trang và thiết lập trang chuyên nghiệp.
- **Sản Xuất Tài Liệu Vật Lý** – Tạo ra các tệp sẵn sàng in cho sách hướng dẫn, danh mục và biểu đồ kỹ thuật định dạng lớn.

## ⚙️ Kịch Bản Tự Động Hóa
- **Công Cụ Tạo Luồng In Dựa Trên Java** – Chuyển đổi tập tin CGM thành đầu ra PS độ phân giải cao theo cách lập trình cho quy trình in doanh nghiệp.
- **Công Cụ Chuyển Đổi Batch Từ Vector Sang PostScript** – Tự động hóa quy trình chuyển đổi quy mô lớn để xử lý hiệu quả các bộ sưu tập đồ họa lớn.
- **Tích Hợp Đường Ốc Xuất Bản** – Nhúng việc chuyển đổi CGM sang PS vào quy trình tự động hóa kết xuất tài liệu và hệ thống xuất bản chuyên nghiệp để có kết quả chất lượng cao và nhất quán.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}