---
title: Chuyển đổi định dạng tệp qua Java 
url: /vi/java/conversion/
description: Chuyển đổi Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, Hình ảnh 3D, Sơ đồ, Định dạng Video và các định dạng khác chỉ với vài dòng mã Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng tệp qua Java" h2="Chuyển đổi Microsoft <sup> & reg; </sup> tài liệu Office, PDF, Hình ảnh, HTML và nhiều tệp khác mà không cần sử dụng bất kỳ phần mềm nào khác." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library] (https://products.aspose.com/total/java/) tăng tốc độ phát triển các giải pháp thao tác tài liệu từ đầu hoặc nâng cao các ứng dụng hiện có để xử lý tài liệu một cách dễ dàng. API không chỉ tạo, chỉnh sửa và chuyển đổi tài liệu Microsoft Office mà còn xử lý PDF, HTML, Hình ảnh TIFF, JPG, PNG, BMP và SVG, tệp Email, định dạng Video, 3D, CAD và nhiều hơn nữa. Nó là một tập hợp các API giải pháp quản lý và thao tác tài liệu mà không có bất kỳ phụ thuộc phần mềm nào trong bất kỳ ứng dụng Java J2SE, J2EE, J2ME nào. Các lập trình viên có thể dễ dàng tạo, cập nhật, kết xuất, in và chuyển đổi giữa các định dạng phổ biến nhất trong bất kỳ ứng dụng dựa trên Java nào.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Word sang Excel" %}}
Total API không chỉ hỗ trợ chuyển đổi giữa các định dạng Microsoft Word mà còn chuyển đổi Word sang Excel, PDF, HTML, Hình ảnh, EPUB, Markdown và XPS. Quá trình chuyển đổi rất đơn giản. Hãy xem xét trường hợp chuyển đổi ** Word sang Excel **. Tải tệp Microsoft Word bằng lớp [Document] (https://apireference.aspose.com/words/java/com.aspose.words/Document) và chuyển đổi ** WORD sang HTML ** bằng cách sử dụng [Phương thức lưu] (https: //apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). Tiếp theo, mở tài liệu HTML đã được chuyển đổi bằng cách sử dụng lớp [Workbook] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) và lưu tài liệu sang định dạng XLSX bằng cách sử dụng [Save] (https: / /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
 Các nhà phát triển cũng có thể chuyển đổi [Word sang PDF] (https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Chuyển đổi Word sang Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF sang hình ảnh" %}}
API hỗ trợ chuyển đổi PDF sang Hình ảnh như JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel và các định dạng khác. Để chuyển đổi PDF sang hình ảnh, hãy coi hình ảnh JPG là tệp đích. Quy trình là, tải tệp PDF bằng cách sử dụng lớp Tài liệu và khởi tạo [lớp JpegDevice] (https://apireference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) đối tượng và hiển thị PDF thành JPEG thông qua [Process] (https : //apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) method
Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh] (https://apireference.aspose.com/imaging/java/aspose.imaging/image) và cuối cùng gọi phương thức Save.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp PowerPoint sang tệp Excel" %}}

Để chuyển đổi các tệp Microsoft PowerPoint sang các tệp khác nhau bao gồm Excel Word, MHTML, API phụ có liên quan bị hủy bỏ khỏi Aspose.Total chính cho API Java. Quy trình chuyển đổi tệp PowerPoint sang tài liệu Excel, Tải tệp PowerPoint bằng lớp [Trình bày] (https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) và chuyển đổi ** PowerPoint sang HTML ** bằng cách sử dụng phương thức [save] (https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Tiếp theo, tải tài liệu HTML đã chuyển đổi bằng cách sử dụng lớp [Workbook] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) và lưu tài liệu sang định dạng EXCEL bằng cách sử dụng [save] (https: / /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)). Mã cho chuyển đổi ** PowerPoint sang Word ** cũng được liệt kê.

{{% blocks/products/pf/feature-page-code h3="Chuyển đổi Java PowerPoint sang Excel" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Chuyển đổi Java PowerPoint sang Word" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}