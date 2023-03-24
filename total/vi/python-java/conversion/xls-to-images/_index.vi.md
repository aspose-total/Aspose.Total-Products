---
title: Chuyển đổi XLS sang Hình ảnh bằng Python
description: Chuyển đổi XLS sang hình ảnh TIFF BMP PNG JPEG GIF EMF SVG trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLS
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi XLS sang Image thông qua Python" h2="Chuyển đổi ảnh XLS sang JPG, TIFF, BMP, PNG, GIF trong Ứng dụng Python của bạn mà không cần cài đặt Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển Python, người đang cố gắng thêm XLS thành tính năng chuyển đổi Hình ảnh PNG, BMP, TIFF, JPEG và GIF trong ứng dụng. Đôi khi, cần phải nhúng bảng tính Excel vào các ứng dụng web hoặc máy tính để bàn. Trong những trường hợp như vậy, xuất khẩu bảng tính thành hình ảnh là một linh hồn duy nhất. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API có thể giúp xuất tệp Excel sang hình ảnh cũng như tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm các định dạng Microsoft Excel thông qua API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) con của nó. Hiện tại Python Excel to Image Converter API hỗ trợ chuyển đổi Tệp Excel sang EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM và EMF tương thích với Office hoặc kiểm tra [Định dạng](https://docs.aspose.com/cells/python-java/supported-file-formats/) được hỗ trợ. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Làm thế nào để chuyển đổi XLS sang hình ảnh trong Python" %}}

- Tạo đối tượng lớp [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) để tải tệp XLS
- Sử dụng lớp [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) và chỉ định các tùy chọn liên quan đến hình ảnh đầu ra
- Nhận quyền truy cập bảng tính để chuyển đổi bằng phương pháp [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Lưu tất cả các trang của trang tính dưới dạng hình ảnh bằng phương pháp [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Bây giờ tệp XLS được chuyển đổi thành Hình ảnh theo đường dẫn được chỉ định

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi XLS sang Hình ảnh (JPG, PNG, GIF, BMP, TIFF), các API tham chiếu trong dự án trực tiếp từ PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Hoặc sử dụng lệnh pip sau đây `` pip install aspose.cells '' 
- Hơn nữa, Tải xuống gói API từ phần [Tải xuống](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Chuyển đổi XLS sang Hình ảnh qua Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}