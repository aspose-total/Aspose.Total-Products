---
title: Chuyển đổi trực tuyến MHTML sang WORDML hoặc phát triển ứng dụng dựa trên Java để chuyển đổi tệp MHTML
description: Ứng dụng trực tuyến miễn phí để chuyển đổi tệp MHTML sang WORDML. Mã thư viện chuyển đổi Java cho tài liệu MHTML. 

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: WORDML
otherformats: DOTX DOTM PCL MARKDOWN XAMLFLOW FLATOPC RTF PS DOT ODT OTT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ứng dụng chuyển đổi trực tuyến MHTML sang WORDML và mã Java để chuyển đổi tệp MHTML" h2="Phát triển ứng dụng chuyển đổi và xuất MHTML mạnh mẽ dựa trên Java. Chuyển đổi một hoặc nhiều tệp MHTML sang WORDML và các định dạng khác thông qua Java Automation API. Chuyển đổi miễn phí các tệp MHTML trực tuyến thông qua ứng dụng với khả năng tải xuống tức thì." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Ứng dụng chuyển đổi MHTML sang WORDML trực tuyến miễn phí" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=wordml&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi tệp MHTML sang WORDML trực tuyến bằng ứng dụng" %}}

1. Tải lên các tệp MHTML để chuyển đổi
1. Chờ vài giây hoặc lâu hơn tùy thuộc vào kích thước MHTML
1. Theo dõi thanh trạng thái tải lên
1. Nhấp vào nút "Chuyển đổi"
1. MHTML sẽ được chuyển đổi thành tài liệu WORDML
1. Tải xuống tệp WORDML đã chuyển đổi

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi MHTML sang WORDML thông qua Java Automation API" %}}


1. Mở tệp MHTML bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi MHTML sang DOC bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) phương pháp
3. Tải tệp DOC bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) của Aspose.Words
4. Lưu tài liệu ở định dạng WORDML bằng phương pháp [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) và đặt WORDML dưới dạng SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}


```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.WORD_ML
outputDocument.save("output.word_ml", SaveFormat.WORD_ML);   
```



{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Một số trường hợp khác để lưu MHTML vào WORDML với các tính năng khác như Yêu cầu chuyển đổi, Mở tài liệu MHTML được bảo vệ bằng mật khẩu qua Java.

{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.WORD_ML);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Phát triển ứng dụng chuyển đổi tệp MHTML bằng Java</h2>

Bạn có cần phát triển ứng dụng phần mềm dựa trên Java để dễ dàng lưu và xuất các tệp MHTML sang tài liệu WORDML không? Với [Aspose.Total for Java](https://products.aspose.com/total/vi/java/), bất kỳ nhà phát triển Java nào cũng có thể tích hợp mã API ở trên để lập trình ứng dụng chuyển đổi trên nhiều định dạng khác nhau bao gồm Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, tệp Email, Hình ảnh (JPG, PNG, BMP, GIF) và các định dạng khác. Thư viện Java mạnh mẽ để chuyển đổi tài liệu, hỗ trợ nhiều định dạng phổ biến bao gồm định dạng MHTML. Khi xuất và kết xuất tài liệu sang các định dạng khác, lập trình viên có thể sử dụng API con Aspose.Total for Java bao gồm [Aspose.Words for Java](https://products.aspose.com/words/vi/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/vi/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/vi/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/vi/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/vi/java/), v.v.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML Thư viện chuyển đổi cho Java" %}}

Có những lựa chọn thay thế để tích hợp Aspose.Total for Java vào hệ thống của bạn. Vui lòng chọn một sản phẩm phù hợp với nhu cầu của bạn và làm theo hướng dẫn từng bước:<br /><br />

- Sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên Maven và bao gồm API con có liên quan trong pom.xml.
- Ngoài ra, bạn có thể lấy tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Lưu MHTML vào WORDML Yêu cầu ứng dụng" %}}

Bất kỳ Hệ điều hành nào có thể chạy Java Runtime Environment (JRE) đều có thể chạy Aspose.Total for Java. Sau đây là danh sách hầu hết nhưng không phải tất cả các Hệ điều hành được hỗ trợ. <br /><br />
- Hệ điều hành Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS và các hệ điều hành khác
- macOS: 10.9 (Mavericks) trở lên
- Di động: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}