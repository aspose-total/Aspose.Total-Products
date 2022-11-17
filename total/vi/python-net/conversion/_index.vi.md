---
title: Chuyển đổi tài liệu qua Python 

description: Chuyển đổi các định dạng Microsoft Word DOC, DOCX sang PDF, Hình ảnh và hơn thế nữa cũng như các Trang trình bày, Tin nhắn Email và Hình ảnh 3D chỉ với vài dòng mã Python.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi tài liệu bằng API Python" h2="Chuyển đổi Microsoft <sup> & reg; </sup> Office Word, PDF, Images và nhiều định dạng khác bằng cách sử dụng Aspose.Words for Python via .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python APIs](https://products.aspose.com/total/python-net/) tăng tốc độ phát triển các giải pháp tự động hóa tài liệu từ đầu hoặc nâng cao các ứng dụng hiện có để tạo, chỉnh sửa hoặc chuyển đổi tài liệu, bản trình bày, email và tệp 3D. Python API không chỉ xử lý các trang trình bày Microsoft Office Word và Presentation mà còn xử lý các tệp PDF, HTML, Hình ảnh và Email và nhiều hơn nữa. API không phụ thuộc vào bất kỳ phần mềm nào và là một bộ giải pháp quản lý và thao tác tài liệu đầy đủ.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft Word sang PDF" %}}
Total Python API hỗ trợ nhiều chuyển đổi định dạng như Microsoft Word sang PDF, Hình ảnh, Markdown và HTML. API giúp quá trình chuyển đổi tài liệu Word sang PDF trở nên đơn giản với chất lượng đầu ra gần với tài liệu như tệp DOC, DOCX. Quy trình là tải tệp DOC hoặc DOCX vào đối tượng [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) và chỉ cần gọi đối tượng [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) với định dạng PDF đích cùng với đường dẫn thư mục của nó. Nó rất đơn giản. Trong trường hợp cần chỉ định các tiêu chuẩn PDF như PDF 1.7 hoặc 1.5, API cung cấp bảng liệt kê [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/), để thiết lập [PdfSaveOptions ()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python - Chuyển đổi Word sang PDF" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft Word sang Hình ảnh" %}}
Chuyển đổi từ sang hình ảnh là tính năng anthor của API Python. Bên cạnh việc chỉ cần chuyển đổi, người ta có thể dễ dàng thiết lập các tùy chọn lưu khác nhau như độ sáng, độ tương phản, độ phân giải ngang và dọc, v.v. Quy trình là, tải tài liệu qua đối tượng Document và sau đó gọi phương thức lưu với loại trừ tệp hình ảnh mong muốn có đường dẫn được chỉ định. Để chỉ định các tùy chọn lưu khác nhau, API cung cấp [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) hoặc [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) các lớp có thể được sử dụng theo kịch bản yêu cầu. Mẫu mã dưới đây minh họa việc tạo bản xem trước của trang tài liệu đầu tiên với việc áp dụng một số cài đặt bổ sung.

{{% blocks/products/pf/feature-page-code h3="Python - Chuyển đổi từ sang hình ảnh" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Microsoft PowerPoint sang Word" %}}
Python API hỗ trợ chuyển đổi tệp Microsoft PowerPoint PPT / PPTX sang Word DOC / DOCX. Hai API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) và [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) được sử dụng để thực hiện chuyển đổi này. Tải tệp PPT / PPTX bằng [Bản trình bày](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Lấy đối tượng lớp Words Document. Lặp lại từng trang chiếu, tạo và chèn hình ảnh trang chiếu, sau đó chèn văn bản trang chiếu bằng cách lặp lại qua các hình dạng trang chiếu.

{{% blocks/products/pf/feature-page-code h3="Python - Chuyển đổi slide PowerPoint sang Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}