---
title: Chuyển đổi định dạng tệp qua C# 
url: /vi/net/conversion/
description: Chuyển đổi Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, Hình ảnh 3D, Sơ đồ, Định dạng Video và nhiều tệp phổ biến khác chỉ với vài dòng mã C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng tệp qua C# .NET" h2="Chuyển đổi các tệp Microsoft <sup> & reg; </sup> Office, PDF, Hình ảnh, HTML và các định dạng khác mà không cần sử dụng bất kỳ phần mềm nào khác." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Tổng thư viện .NET](https://products.aspose.com/total/net/) tăng tốc phát triển các giải pháp quản lý tài liệu từ đầu hoặc tăng cường các ứng dụng hiện có để xử lý thao tác tài liệu một cách dễ dàng. API không chỉ quản lý các tài liệu Microsoft Office mà còn xử lý các tệp PDF, HTML, Hình ảnh TIFF, JPG, PNG, BMP và SVG, Email, định dạng Video, định dạng dữ liệu GIS và hơn thế nữa. Nó là một tập hợp hoàn chỉnh các API giải pháp quản lý tài liệu và thao tác mà không có bất kỳ phụ thuộc phần mềm nào. Lập trình viên có thể dễ dàng tạo, cập nhật, kết xuất, in và chuyển đổi giữa hầu hết các định dạng phổ biến trong bất kỳ ứng dụng dựa trên .NET nào.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển Word sang PDF" %}}
Total API không chỉ hỗ trợ chuyển đổi giữa các định dạng Microsoft Word mà còn chuyển đổi Word sang PDF, HTML, Hình ảnh, EPUB, Markdown và XPS. Quá trình chuyển đổi rất đơn giản. Tải Tài liệu qua lớp Tài liệu và chỉ cần gọi phương thức Lưu với định dạng đích. Nó rất đơn giản. Các nhà phát triển có thể kiểm tra [kết quả chuyển đổi](https://products.aspose.com/words/net/conversion/word-to-pdf/) trước khi tích hợp mã của ** Word sang PDF **


{{% blocks/products/pf/feature-page-code h3="C# - Chuyển đổi Word sang PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF sang hình ảnh" %}}
API hỗ trợ chuyển đổi PDF sang Hình ảnh, Powerpoint, Excel và các định dạng khác. Để chuyển đổi PDF sang hình ảnh, hãy coi hình ảnh JPG là tệp đích. Quá trình là, tải tệp PDF bằng cách sử dụng lớp Tài liệu và khởi tạo [lớp JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) đối tượng và hiển thị PDF thành JPEG thông qua [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) method
Tải tệp JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image) và cuối cùng gọi phương thức Save.

{{% blocks/products/pf/feature-page-code h3="C# - Chuyển đổi PDF sang hình ảnh" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Excel sang Word và PowerPoint" %}}

Để chuyển đổi các định dạng Microsoft Excel sang các tệp khác nhau bao gồm Word và PowerPoint, các API phụ có liên quan sẽ bị loại bỏ khỏi Aspose.Total chính cho API .NET. Quy trình chuyển đổi tệp Excel sang tài liệu Word, tải tệp EXCEL bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) và chuyển EXCEL sang PDF trước tiên và đặt SaveFormat thành Tự động. Sau đó, tải tệp PDF đã chuyển đổi bằng cách sử dụng lớp Tài liệu và gọi phương thức Lưu và đặt Tài liệu, Docx làm SaveFormat. Mã cũng được liệt kê để chuyển đổi Microsoft ** Excel sang Powerpoint **.

{{% blocks/products/pf/feature-page-code h3="C# - Chuyển đổi JSON sang Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Chuyển đổi Excel sang JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}