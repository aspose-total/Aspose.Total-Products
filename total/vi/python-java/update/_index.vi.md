---
title: Cập nhật tệp Excel bằng Python 

description: Chỉnh sửa tài liệu Microsoft Excel XLSX, XLS, CSV mà không cần cài đặt Microsoft Office trong các ứng dụng Python
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Cập nhật tài liệu Excel qua Python" h2="Sửa đổi các tệp Microsoft Excel XLSX, XLS trong Ứng dụng Python mà không cần cài đặt Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Tổ chức thường cập nhật dữ liệu của họ, được lưu trữ trong các tệp excel như dữ liệu sinh viên, hồ sơ bệnh nhân và danh sách kho hàng, v.v. thông qua phần mềm của công ty. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API cung cấp chức năng sửa đổi bảng tính thông qua phần mềm. Các lập trình viên có thể nâng cao khả năng sửa đổi của phần mềm bằng cách tích hợp API và viết một vài dòng mã. API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) là một phần của gói [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) giúp quá trình sửa đổi này trở nên dễ dàng. Dưới đây là quá trình cập nhật tài liệu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Cập nhật tài liệu Excel bằng Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API cung cấp lớp Workbook xử lý việc tải bảng tính Excel. Quy trình rất đơn giản. Tạo đối tượng lớp [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) bằng cách cung cấp tệp nguồn làm tham số. Sử dụng phương pháp [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) để truy cập Worksheet có liên quan bằng cách cung cấp chỉ mục của nó. gọi phương thức [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) để sửa đổi nội dung trong ô được truy cập và cuối cùng gọi phương thức save() để lưu tài liệu.

{{% blocks/products/pf/feature-page-code h3="Python - Cập nhật tài liệu Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Cập nhật">}}