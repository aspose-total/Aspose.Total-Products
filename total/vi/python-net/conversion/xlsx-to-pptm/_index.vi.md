---
title: Chuyển đổi XLSX sang PPTM bằng Python
description: Chuyển đổi XLSX sang PPTM trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: PPTM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi XLSX sang PPTM qua Python" h2="Chuyển đổi XLSX sang PPTM trong các ứng dụng Python của bạn mà không cần cài đặt Microsoft Excel<sup>&reg;</sup> hoặc PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với nhà phát triển Python, người đang cố gắng thêm tính năng chuyển đổi XLSX sang PPTM trong ứng dụng, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm các tệp XLSX và PPTM.

Nó chủ yếu trong hai bước. Đầu tiên sử dụng API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) để chuyển đổi tệp XLSX sang PDF. Sau đó, bằng cách sử dụng PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), lưu tệp PDF đã tạo thành định dạng Microsoft PowerPoint mong muốn. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi XLSX sang PPTM bằng Python" %}}
- **Bước 1** Sử dụng phiên bản lớp Workbook để mở tệp XLSX nguồn 
- Lưu tệp XLSX thành PDF bằng phương pháp save bằng cách cung cấp tên tệp và đường dẫn thư mục mong muốn
-  **Bước 2** Tải tệp PDF bằng lớp [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Gọi phương thức [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) trong khi chỉ định đường dẫn tệp PPTM đầu ra. Vì vậy, tệp XLSX của bạn được chuyển đổi thành PPTM theo đường dẫn đã chỉ định

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi XLSX sang PPTM, cần có Python 3.5 trở lên
- API tham khảo trong dự án trực tiếp từ PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) và [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Hoặc sử dụng các lệnh pip sau ```pip install aspose-cells-python``` và ```pip install aspose.slides```
-  Hơn nữa, HĐH dựa trên Microsoft Windows hoặc Linux (xem thêm về [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) và [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu XLSX thành PDF bằng Python - Bước 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lưu PDF thành PPTM bằng Python - Bước 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}