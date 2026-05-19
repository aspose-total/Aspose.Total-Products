---
title: Chuyển đổi DOTM sang MHTML bằng Python
description: DOTM sang mhtml Định dạng lưu trữ web và chuyển đổi tệp HtmlFixed trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DOTM sang MHTML bằng Python" h2="Chuyển đổi DOTM sang MHTML, HtmlFixed và HTML trong Ứng dụng Python của bạn mà không cần cài đặt Microsoft Word <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển Python, những người đang cố gắng thêm tính năng chuyển đổi DOTM sang MHTML (Định dạng lưu trữ web) hoặc HtmlFixed có nghĩa là muốn lưu tài liệu ở định dạng HTML bằng cách sử dụng các phần tử được định vị hoàn toàn trong ứng dụng. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau. 

Chúng tôi sử dụng API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) nằm trong Gói [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) để thêm tính năng chuyển đổi DOTM sang MHTML. Trong trường hợp tệp DOTM đơn giản thì nó chỉ có hai dòng mã. Tải tệp DOTM và gọi phương thức lưu với đường dẫn tệp thích hợp cùng với kiểu liệt kê SaveFormat dưới dạng MHTML hoặc HTML_FIXED. Nhưng trong trường hợp cần khôi phục mô hình tài liệu gần giống với mô hình ban đầu thì cần phải lưu thêm một số thông tin trong tài liệu kết quả được gọi là thông tin khứ hồi.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Làm thế nào để Chuyển đổi DOTM sang MHTML bằng Python" %}}
- Tải tệp DOTM nguồn bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Tạo phiên bản của [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Đặt export_roundtrip_information là True
- Chỉ định [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) dưới dạng MHTML
- Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat làm tham số. Vì vậy, tệp DOTM của bạn được chuyển đổi thành MHTML theo đường dẫn được chỉ định.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi định dạng DOTM sang MHTML hoặc HtmlFixed, Python 3.5 trở lên là bắt buộc
- Tham khảo các API trong dự án trực tiếp từ PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Hoặc sử dụng các lệnh pip sau `` pip install aspose.words ''.
- Hơn nữa, hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem thêm cho [Words](https://docs.aspose.com/words/python-net/system-requirements/)) và cho Linux, hãy kiểm tra các yêu cầu bổ sung cho gcc và libpython và làm theo hướng dẫn từng bước [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu DOTM thành MHTML bằng Python - Đơn giản" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Chuyển đổi DOTM sang MHTML bằng Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Việc chuyển đổi DOTM sang MHTML biến các mẫu Word có macro thành tài liệu MIME HTML kết hợp nội dung và tài nguyên thành một tệp duy nhất thân thiện với web. Nó hữu ích cho việc chia sẻ tài liệu di động, xem trên trình duyệt và bảo tồn nội dung định dạng trong một định dạng tự chứa.

Sử dụng các API Python cho việc chuyển đổi DOTM sang MHTML hỗ trợ tự động hoá bằng cách cho phép các mẫu có thể tái sử dụng được xuất bản dưới dạng tài sản tương thích web với ít nỗ lực. Điều này cải thiện khả năng di động của nội dung, đơn giản hoá việc giao tài liệu và hỗ trợ các quy trình render mở rộng.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

* **Kết Xuất Web Di Động**
  Chuyển đổi các tệp DOTM sang MHTML để xem trên trình duyệt một cách thân thiện trong một tệp gói duy nhất.

* **Chia Sẻ Tài Liệu Tự Chứa**
  Bảo tồn văn bản, định dạng và các tài nguyên liên kết cùng nhau để phân phối đáng tin cậy.

* **Xuất Bản Mẫu**
  Tái sử dụng các mẫu tài liệu thành các đầu ra hướng web cho các cổng thông tin hoặc lưu trữ.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động" %}}

* **Xuất Web Tự Động**
  Hệ thống có thể chuyển đổi các mẫu DOTM thành tệp MHTML để cung cấp trên web mà không cần định dạng thủ công.

* **Quy Trình Đóng Gói Nội Dung**
  Quá trình chuyển đổi hỗ trợ tạo tự động các tệp tài liệu tự chứa để chia sẻ và lưu trữ.

* **Đường Dây Render Mở Rộng**
  Các công việc lập trình có thể tạo ra khối lượng lớn các đầu ra MHTML từ các tài liệu mẫu lặp lại.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}