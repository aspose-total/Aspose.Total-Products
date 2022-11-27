---
title: Cập nhật tệp Excel bằng C ++ 

description: Chỉnh sửa tài liệu Microsoft Excel XLSX, XLS, CSV mà không cần cài đặt Microsoft Office với các ứng dụng dựa trên C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Cập nhật tài liệu Excel qua C++" h2="Sửa đổi các tệp Microsoft Excel XLSX, XLS trong các ứng dụng dựa trên C++ mà không cần cài đặt Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Tổ chức thường cập nhật dữ liệu của họ, được lưu trữ trong các tệp excel như dữ liệu sinh viên, hồ sơ bệnh nhân và danh sách kho hàng, v.v. thông qua phần mềm của công ty. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API cung cấp chức năng sửa đổi bảng tính bằng phần mềm. Các lập trình viên có thể cải tiến phần mềm với khả năng sửa đổi chỉ bằng cách viết vài dòng mã API. API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) là một phần của gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/) giúp quá trình sửa đổi này trở nên dễ dàng. Dưới đây là quá trình cập nhật tài liệu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Cập nhật tài liệu Excel bằng C++" %}}

Sử dụng API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), tải tài liệu nguồn bằng [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Truy cập [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) bằng GetIWorksheets()->GetObjectByIndex(0) và ô được yêu cầu bằng GetICells()->GetObjectByIndex. Bằng cách sử dụng phương pháp PutValue, hãy sửa đổi nội dung trong ô được truy cập. Cuối cùng gọi phương thức save() để lưu tài liệu.

{{% blocks/products/pf/feature-page-code h3="Mã C++ - Cập nhật tài liệu Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Cập nhật">}}