---
title: Chuyển đổi tài liệu qua Android API 
url: /vi/android-java/conversion/
description: Chuyển đổi các định dạng Word, Excel, PowerPoint, HTML, PDF và Hình ảnh bằng cách sử dụng API chuyển đổi Android. Android chuyển đổi Office docx, xlsx, pptx sang PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi tài liệu bằng Android API" h2="Chuyển đổi Microsoft <sup> & reg; </sup> Office Word, Excel, PowerPoint, PDF, Images và nhiều định dạng khác bằng cách sử dụng Aspose.Total for Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) cung cấp giải pháp quản lý và chuyển đổi tài liệu cho các ứng dụng Android mà không cần dựa vào bất kỳ phần mềm nào khác. Các lập trình viên có thể tự động hóa giải pháp quản lý và thao tác tài liệu một cách trực tiếp bằng cách tích hợp API trong các ứng dụng được phát triển mới hoặc trong các ứng dụng hiện có. Bằng cách tích hợp API, Lập trình viên có thể dễ dàng thêm chức năng tạo, chỉnh sửa hoặc chuyển đổi các tài liệu định dạng khác nhau trong ứng dụng. API chuyển đổi PDF trong Android xử lý các trường hợp chuyển đổi như Office DOCX, XLSX, PPTX sang PDF hoặc ngược lại. Hơn nữa, rất ít trường hợp giao dịch API được liệt kê bên dưới và một số liên kết được cung cấp cho các trường hợp chuyển đổi có liên quan. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF sang CSV" %}}
Total Android API hỗ trợ chuyển đổi PDF sang Excel XLSX và CSV. Đó là một quá trình gồm hai bước. Hai tổng số API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) và [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) có liên quan. Quy trình là bạn có thể chuyển định dạng PDF sang Excel XLSX trước tiên và sau đó XLSX sang CSV. Chi tiết hơn, Tải tệp PDF qua lớp [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và hiển thị thành XLSX qua [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). phương thức . Tiếp theo, tải tài liệu XLSX được hiển thị bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) và gọi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) phương thức.

{{% blocks/products/pf/feature-page-code h3="Android - Chuyển đổi PDF sang Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Excel sang Word" %}}
API Android cũng xử lý chuyển đổi Excel. Quy trình là, Tải tệp EXCEL XLSX bằng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) và chuyển đổi EXCEL sang PDF bằng cách đặt SaveFormat thành AUTO trước tiên. Tiếp theo, tải tệp PDF đã lưu bằng lớp [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và gọi [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) phương thức để lưu tài liệu sang định dạng Word DOC / DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Chuyển đổi Excel sang Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi POWERPOINT sang HTML và MHTML" %}}
Android Total API xử lý các định dạng khác nhau bao gồm các tệp PowerPoint để có thể chuyển đổi bản trình bày sang HTML và MHTML. Quy trình là, Tải tệp POWERPOINT PPT / PPTX bằng cách sử dụng lớp [Bản trình bày](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) và gọi [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) Phương thức  để chuyển đổi POWERPOINT sang HTML. Hơn nữa, Bây giờ tải tài liệu HTML đã chuyển đổi bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) và gọi [save](https://reference.aspose.com/cells/java/com.aspose.cells/) Phương thức  để chuyển đổi MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint Trang trình bày sang HTML và Chuyển đổi MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}