---
title: Chuyển đổi DOTM sang PPT bằng Python
description: Chuyển đổi DOTM sang PPT trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Word hoặc PowerPoint 
url: /vi/python-net/conversion/dotm-to-ppt/
family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: PPT
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DOTM sang PPT bằng Python" h2="Chuyển đổi DOTM sang PPT trong Ứng dụng Python của bạn mà không cần cài đặt Microsoft Word <sup>&reg;</sup> hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển Python, ai đang cố gắng thêm tính năng chuyển đổi DOTM sang PPT trong ứng dụng? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau. Vì thế **Làm thế nào để chuyển đổi DOTM sang PPT trong Python?**

Nó chủ yếu gồm hai bước. Đầu tiên sử dụng [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API để chuyển đổi tệp DOTM sang PDF. Sau đó, bằng cách sử dụng PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), lưu tệp PDF đã tạo thành Bản trình bày dưới dạng định dạng PPT. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi DOTM sang PPT bằng Python" %}}
- **Bước 1** Mở tệp DOTM nguồn bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Lưu tệp DOTM sang PDF bằng phương pháp [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) bằng cách cung cấp tên tệp và đường dẫn thư mục mong muốn.
-  **Bước 2** Tải tệp PDF với phiên bản của lớp [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat.PPT làm tham số. Vì vậy, tệp DOTM của bạn được chuyển đổi thành PPT theo đường dẫn được chỉ định.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi DOTM sang PPT, cần có Python 3.5 trở lên
- Tham chiếu các API trong dự án trực tiếp từ PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) và [Aspose.Words](https://pypi.org/project/aspose-words/)) hoặc
- Sử dụng các lệnh pip sau `` pip install aspose.slides '' và `` pip install aspose.words ''. Hơn thế nữa,
- Hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem thêm cho [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) và [Words](https://docs.aspose.com/words/python-net/system-requirements/)) và cho Linux, hãy kiểm tra các yêu cầu bổ sung cho gcc và libpython và làm theo hướng dẫn từng bước [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu DOTM thành PDF bằng Python - Bước 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lưu PDF sang PPT bằng Python - Bước 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}