---
title: Cập nhật tệp XLSX bằng Python
description: Sửa đổi tài liệu XLSX trong các ứng dụng Python mà không cần sử dụng Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Cập nhật tệp XLSX qua Python" h2="Sửa đổi bảng tính XLSX thông qua Ứng dụng Python của bạn mà không cần cài đặt Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển, ai đang cố gắng cập nhật tệp XLSX thông qua ứng dụng Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API có thể giúp tự động hóa quá trình cập nhật. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm các tệp Microsoft Excel. ASPOSE.CELL API là một phần của gói [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) giúp quá trình sửa đổi này trở nên dễ dàng. Dưới đây là quá trình cập nhật tài liệu XLSX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách cập nhật tệp XLSX bằng Python" %}}

- Tạo đối tượng lớp [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) mới có tệp XLSX nguồn làm tham số
- Truy cập Bảng tính có liên quan bằng phương pháp [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Chèn dữ liệu mới vào ô đã truy cập bằng phương pháp [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Lưu tệp dưới dạng tệp .xlsx bằng cách sử dụng phương thức save () bằng cách chuyển tệp với đường dẫn là tham số

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu sửa đổi" %}}

- Để sửa đổi XLSX, tham chiếu các API trong dự án trực tiếp từ PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Hoặc sử dụng lệnh pip sau đây `` pip install aspose.cells '' 
- Hơn nữa, Tải xuống gói API từ phần [Tải xuống](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã - Cập nhật tệp XLSX bằng Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}