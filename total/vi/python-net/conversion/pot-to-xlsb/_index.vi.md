---
title: Chuyển đổi POT sang XLSB bằng Python
description: Chuyển đổi POT sang XLSB trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: POT
outformat: XLSB
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi POT sang XLSB qua Python" h2="Chuyển đổi POT sang XLSB trong các ứng dụng Python của bạn mà không cần cài đặt Microsoft PowerPoint<sup>&reg;</sup> hoặc Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với nhà phát triển Python, người đang cố gắng thêm tính năng chuyển đổi POT sang XLSB trong ứng dụng. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm các tệp POT và XLSB.

Nó chủ yếu trong hai bước. Đầu tiên sử dụng API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) để chuyển đổi tệp POT sang HTML. Sau đó, bằng cách sử dụng Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), hãy lưu HTML đã tạo thành định dạng Microsoft Excel mong muốn. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi POT sang XLSB bằng Python" %}}
- **Bước 1** Sử dụng phiên bản lớp [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) để mở tệp POT nguồn 
- Lưu tệp POT sang HTML bằng cách sử dụng phương pháp [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) bằng cách cung cấp tên tệp và đường dẫn thư mục mong muốn
-  **Bước 2** Tải tệp HTML với một phiên bản của lớp Workbook
-  Gọi phương thức `save` trong khi chỉ định đường dẫn tệp XLSB đầu ra. Vì vậy, tệp POT của bạn được chuyển đổi thành XLSB theo đường dẫn đã chỉ định

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi POT sang XLSB, cần có Python 3.5 trở lên
- API tham chiếu trong dự án trực tiếp từ PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) và [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Hoặc sử dụng các lệnh pip sau ```pip install aspose.slides``` và ```pip install aspose-cells-python```
-  Hơn nữa, HĐH dựa trên Microsoft Windows hoặc Linux (xem thêm về [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) và [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu POT vào HTML trong Python - Bước 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lưu HTML vào XLSB bằng Python - Bước 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}