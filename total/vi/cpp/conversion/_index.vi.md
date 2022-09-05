---
title: Chuyển đổi tài liệu qua C ++ 
url: /vi/cpp/conversion/
description: Chuyển đổi các định dạng tài liệu khác nhau như Word, Excel, PowerPoint, PDF, JSON, Hình ảnh và hơn thế nữa bằng C ++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi tài liệu bằng C ++" h2="Chuyển đổi Microsoft <sup> & reg; </sup> Office Word, Excel, PowerPoint, PDF, Images và nhiều định dạng khác bằng thư viện C ++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C ++ Library](https://products.aspose.com/total/cpp/) giải quyết vấn đề chuyển đổi tài liệu và các nhà phát triển có thể tự động hóa giải pháp quản lý và thao tác tài liệu một cách trực tiếp bằng cách tích hợp API trong các ứng dụng được phát triển mới hoặc trong các ứng dụng hiện có. Lập trình viên C ++ có thể thêm các chức năng như tạo, chỉnh sửa hoặc chuyển đổi các tài liệu định dạng khác nhau trong giải pháp của họ mà không cần dựa vào bất kỳ phần mềm nào. Một số trường hợp chung chung như txt sang PDF, SVG sang PNG, XLSX sang CSV, JSON sang CSV, Word sang PDF, HTML sang PDF, người ta có thể dễ dàng chuyển đổi. Hơn nữa, rất ít trường hợp giao dịch API được liệt kê bên dưới và một số liên kết được cung cấp cho các trường hợp chuyển đổi có liên quan. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft Word sang Excel" %}}
Total C ++ API hỗ trợ chuyển đổi DOC / DOCX sang Excel của Microsoft Word.  Quy trình là, Tải tệp Word DOC / DOCX bằng cách sử dụng tham chiếu lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) và gọi [Lưu](https://tham chiếu. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) chức năng thành viên để chuyển đổi thành HTML trước tiên. Sau đó, tải tài liệu HTML bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) và gọi [Save](https://reference.aspose.com/ ô /cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) hàm thành viên để lưu tài liệu sang định dạng Excel. 

{{% blocks/products/pf/feature-page-code h3="C ++ - Chuyển đổi Word sang Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PDF sang Word" %}}
Thư viện chuyển đổi C ++ cũng hỗ trợ PDF sang word DOC, DOCX và chuyển đổi định dạng khác. Xem xét trường hợp hiển thị PDF sang RTF, Đó là một quy trình gồm hai bước, trước tiên chuyển đổi PDF sang định dạng Word DOC / DOCX và sau đó hiển thị định dạng đó sang RTF. Các bước bao gồm cho việc này, Tải tệp PDF bằng tham chiếu lớp [Tài liệu](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) và gọi [Lưu](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) chức năng thành viên để chuyển đổi PDF sang Word. Bây giờ hãy tải lại tệp Word DOC / DOCX bằng cách sử dụng tham chiếu lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) của API Aspose. AdWords và lưu nó vào định dạng RTF bằng Hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).

{{% blocks/products/pf/feature-page-code h3="C++ - Chuyển đổi PDF sang Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi JSON sang Word" %}}
Để chuyển đổi JSON, C ++ API hỗ trợ nhiều kết hợp khác nhau như JSON sang Word, Json sang PowerPoint, Word sang JSON, v.v. Xem xét trường hợp chuyển đổi Word, Quy trình là đọc dữ liệu JSON hợp lệ từ tệp bằng cách sử dụng đối tượng [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) mới và sau đó gọi Phương thức [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) để lưu JSON dưới dạng tệp PDF. Vì vậy, bây giờ hãy tải tệp đã lưu bằng cách sử dụng lớp [Tài liệu](https://reference.aspose.com/words/cpp/class/aspose.words.document) và lưu nó vào định dạng tài liệu word bằng cách sử dụng [Lưu](https://ham khảo .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) phương thức.
{{% blocks/products/pf/feature-page-code h3="C ++ - Chuyển đổi JSON sang Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}