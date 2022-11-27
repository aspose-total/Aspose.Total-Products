---
title: Cập nhật tệp Excel bằng Java 

description: Chỉnh sửa tài liệu Microsoft Excel XLSX, XLS, CSV mà không cần cài đặt Microsoft Office trong các ứng dụng dựa trên Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Cập nhật tài liệu Excel qua Java" h2="Sửa đổi các tệp Microsoft Excel XLSX, XLS trong các ứng dụng dựa trên Java mà không cần cài đặt Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Tổ chức thường cập nhật dữ liệu của họ, được lưu trữ trong các tệp excel như dữ liệu sinh viên, hồ sơ bệnh nhân và danh sách kho hàng, v.v. thông qua phần mềm của công ty. [Aspose.Total for Java](https://products.aspose.com/total/java/) API cung cấp chức năng sửa đổi bảng tính bằng phần mềm của riêng họ. Các lập trình viên có thể cải tiến phần mềm với khả năng sửa đổi chỉ bằng cách viết vài dòng mã API. API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) là một phần của gói [Aspose.Total for Java](https://products.aspose.com/total/java/) giúp quá trình sửa đổi này trở nên dễ dàng. Dưới đây là quá trình cập nhật tài liệu Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Cập nhật tài liệu Excel bằng Java" %}}

API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) cung cấp lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) xử lý việc tải bảng tính Excel. Quy trình rất đơn giản. Tạo đối tượng lớp Workbook bằng cách cung cấp tệp nguồn làm tham số. Truy cập Bảng tính có liên quan và ô có liên quan bằng phương pháp [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). Sử dụng phương thức [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) để sửa đổi nội dung trong ô được truy cập và cuối cùng gọi phương thức save() để lưu tài liệu.

{{% blocks/products/pf/feature-page-code h3="Mã Java - Cập nhật tài liệu Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Cập nhật">}}