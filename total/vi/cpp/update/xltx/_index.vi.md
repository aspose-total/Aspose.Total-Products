---
title: Cập nhật tệp XLTX bằng C++
description: Sửa đổi tài liệu XLTX trong ứng dụng C++ mà không cần sử dụng Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Cập nhật tệp XLTX qua C++" h2="Sửa đổi bảng tính XLTX thông qua các ứng dụng dựa trên C++ của bạn mà không cần cài đặt Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một lập trình viên đang cố cập nhật các tệp XLTX trong ứng dụng C++, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API có thể giúp tự động hóa quá trình cập nhật. Đó là một gói đầy đủ các thư viện C++ khác nhau xử lý nhiều định dạng bao gồm các tài liệu Microsoft Excel. API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) là một phần của gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/) giúp quá trình sửa đổi này trở nên dễ dàng. Quá trình cập nhật tài liệu XLTX rất đơn giản bằng cách trước tiên truy cập trang tính và sau đó cập nhật giá trị ô trong excel bằng C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách cập nhật tệp XLTX trong C++" %}}

- Tải tệp XLTX bằng [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Truy cập [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) có liên quan bằng GetIWorksheets()->GetObjectByIndex(0) và ô có liên quan bằng GetICells()->GetObjectByIndex
- Chèn dữ liệu mới vào ô đã truy cập bằng phương pháp PutValue
- Lưu tệp dưới dạng tệp .xltx bằng phương thức Lưu bằng cách chuyển tệp có đường dẫn làm tham số

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu sửa đổi" %}}

- Để sửa đổi XLTX, hãy làm theo [yêu cầu hệ thống](https://docs.aspose.com/cells/cpp/system-requirements/) cho các hệ thống Windows và Linux 
- Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total.Cpp```
- Hoặc qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total.Cpp```
- Ngoài ra, hãy tải trình cài đặt MSI ngoại tuyến hoặc tệp DLL trong tệp ZIP từ [Tải xuống](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã - Cập nhật tệp XLTX trong C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}