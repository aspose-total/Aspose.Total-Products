---
title: Chuyển đổi POWERPOINT sang DOCM bằng Python
description: Chuyển đổi POWERPOINT sang DOCM trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Word hoặc PowerPoint 
url: /vi/python-net/conversion/powerpoint-to-docm/
family: total
platformtag: Python
feature: conversion
informat: POWERPOINT
outformat: DOCM
otherformats: Word DOC DOT DOCX DOCM DOTX DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi POWERPOINT sang DOCM bằng Python" h2="Chuyển đổi POWERPOINT sang DOCM trong Ứng dụng Python của bạn mà không cần cài đặt Microsoft Word <sup>&reg;</sup> hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển Python, ai đang cố gắng thêm tính năng chuyển đổi POWERPOINT sang DOCM trong ứng dụng? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau. Vì thế **Làm thế nào để chuyển đổi POWERPOINT sang DOCM trong Python?**

Nó chủ yếu gồm hai bước. Trước hết hãy sử dụng API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) để chuyển đổi tệp POWERPOINT sang PDF. Sau đó, bằng cách sử dụng Microsoft Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), lưu tệp PDF đã tạo vào Microsoft Word dưới dạng định dạng DOCM. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi POWERPOINT sang DOCM bằng Python" %}}
-  **Bước 1** Tải tệp PDF với phiên bản của lớp [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat.PDF làm tham số. Vì vậy, tệp POWERPOINT của bạn được chuyển đổi sang PDF theo đường dẫn được chỉ định.
- **Bước 2** Mở tệp PDF bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Lưu tệp PDF thành tệp DOCM bằng phương pháp [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) bằng cách cung cấp tên tệp và đường dẫn thư mục mong muốn.
- Đây là một đoạn mã khác cho Bản trình bày PowerPoint sang Chuyển đổi Word (Microsoft Powerpoint to Word)[https://products.aspose.com/total/python-net/conversion/].

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi POWERPOINT sang DOCM, cần có Python 3.5 trở lên
- Tham chiếu các API trong dự án trực tiếp từ PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) và [Aspose.Words](https://pypi.org/project/aspose-words/)) hoặc
- Sử dụng các lệnh pip sau `` pip install aspose.slides '' và `` pip install aspose.words ''. Hơn thế nữa,
- Hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem thêm về [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) và [Words](https://docs.aspose.com/words/python-net/system-requirements/)) và đối với Linux, hãy kiểm tra các yêu cầu bổ sung cho gcc và libpython và làm theo hướng dẫn từng bước [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu POWERPOINT thành PDF bằng Python - Bước 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-slides-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lưu PDF sang DOCM bằng Python - Bước 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-files-to-microsoft-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}