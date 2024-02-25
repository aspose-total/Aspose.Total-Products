---
title: Chuyển đổi DOCX sang MHTML bằng Python
description: DOCX sang mhtml Định dạng lưu trữ web và chuyển đổi tệp HtmlFixed trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DOCX sang MHTML bằng Python" h2="Chuyển đổi DOCX sang MHTML, HtmlFixed và HTML trong Ứng dụng Python của bạn mà không cần cài đặt Microsoft Word <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển Python, những người đang cố gắng thêm tính năng chuyển đổi DOCX sang MHTML (Định dạng lưu trữ web) hoặc HtmlFixed có nghĩa là muốn lưu tài liệu ở định dạng HTML bằng cách sử dụng các phần tử được định vị hoàn toàn trong ứng dụng. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau. 

Chúng tôi sử dụng API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) nằm trong Gói [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) để thêm tính năng chuyển đổi DOCX sang MHTML. Trong trường hợp tệp DOCX đơn giản thì nó chỉ có hai dòng mã. Tải tệp DOCX và gọi phương thức lưu với đường dẫn tệp thích hợp cùng với kiểu liệt kê SaveFormat dưới dạng MHTML hoặc HTML_FIXED. Nhưng trong trường hợp cần khôi phục mô hình tài liệu gần giống với mô hình ban đầu thì cần phải lưu thêm một số thông tin trong tài liệu kết quả được gọi là thông tin khứ hồi.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Làm thế nào để Chuyển đổi DOCX sang MHTML bằng Python" %}}
- Tải tệp DOCX nguồn bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Tạo phiên bản của [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Đặt export_roundtrip_information là True
- Chỉ định [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) dưới dạng MHTML
- Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat làm tham số. Vì vậy, tệp DOCX của bạn được chuyển đổi thành MHTML theo đường dẫn được chỉ định.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi định dạng DOCX sang MHTML hoặc HtmlFixed, Python 3.5 trở lên là bắt buộc
- Tham khảo các API trong dự án trực tiếp từ PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Hoặc sử dụng các lệnh pip sau `` pip install aspose.words ''.
- Hơn nữa, hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem thêm cho [Words](https://docs.aspose.com/words/python-net/system-requirements/)) và cho Linux, hãy kiểm tra các yêu cầu bổ sung cho gcc và libpython và làm theo hướng dẫn từng bước [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu DOCX thành MHTML bằng Python - Đơn giản" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Chuyển đổi DOCX sang MHTML bằng Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}