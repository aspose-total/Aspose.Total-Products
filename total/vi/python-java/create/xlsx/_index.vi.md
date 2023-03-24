---
title: Tạo XLSX bằng Python
description: Tạo tệp XLSX bằng các ứng dụng Python mà không cần sử dụng Microsoft Office. 

family: total
platformtag: Python
feature: create
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Tạo XLSX bằng Python" h2="Tạo XLSX thông qua Ứng dụng Python của bạn mà không cần cài đặt Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển, ai đang cố gắng tạo tệp XLSX thông qua ứng dụng Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API có thể giúp tự động hóa quá trình tạo. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm các tệp Microsoft Office và Hình ảnh. [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API là một phần của gói [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) giúp quá trình tạo này trở nên dễ dàng. Dưới đây là quá trình tạo. Hơn nữa, các nhà phát triển có thể dễ dàng nâng cao ứng dụng sửa đổi tệp XLSX. Để cập nhật tệp XLSX bằng cách sử dụng quy trình Python, ngoại trừ việc nó yêu cầu tệp hiện có làm tham số trong khi tạo đối tượng Workbook.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách tạo tệp XLSX bằng Python" %}}

- Tạo đối tượng lớp [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) mới có Tập tinFormatType làm tham số
- Nhận quyền truy cập của [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) được yêu cầu bằng phương pháp [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Chèn dữ liệu vào ô đã truy cập bằng phương pháp [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Lưu tài liệu dưới dạng tệp .xlsx bằng cách sử dụng [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) bằng cách chuyển tệp có đường dẫn làm tham số

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu tạo" %}}

- Để tạo XLSX, tham chiếu các API trong dự án trực tiếp từ PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Hoặc sử dụng lệnh pip sau đây `` pip install aspose.cells ''` 
- Hơn nữa, Tải xuống gói API từ phần [downloads](https://releases.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tạo XLSX bằng Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}