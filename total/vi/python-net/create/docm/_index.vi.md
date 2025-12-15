---
title: Tạo DOCM bằng Python
description: Tạo tệp DOCM bằng các ứng dụng Python mà không cần sử dụng Microsoft Word. 

family: total
platformtag: Python
feature: create
informat: DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Tạo DOCM bằng Python" h2="Tạo DOCM thông qua Ứng dụng Python của bạn mà không cần cài đặt Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển, ai đang cố gắng tạo tệp DOCM thông qua ứng dụng Python? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình tạo. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm các tệp Microsoft Office và Hình ảnh. API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) là một phần của gói [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) giúp quá trình tạo này trở nên dễ dàng. Hơn nữa, các nhà phát triển có thể dễ dàng nâng cao ứng dụng sửa đổi tệp DOCM. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách tạo tệp DOCM bằng Python" %}}

- Tạo đối tượng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/).
- Tạo đối tượng lớp [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/).
- Thêm văn bản vào tệp bằng phương pháp [DocumentBuilder.write()](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/write/).
- Lưu bằng phương pháp [save()](https://reference.aspose.com/words/python-net/aspose.words/document/save/) bằng cách chuyển đường dẫn tài liệu DOCM có liên quan.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Creation Requirements" %}}

- Để tạo tài liệu DOCM, cần có Python 3.5 trở lên
- Các API tham chiếu trong dự án trực tiếp từ PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) 
- Hoặc Sử dụng các lệnh pip sau đây `` pip install aspose.words ''. 
- Hơn nữa, Microsoft Windows hoặc Hệ điều hành dựa trên Linux (xem thêm cho [Words](https://docs.aspose.com/words/python-net/system-requirements/)) và cho Linux, hãy kiểm tra các yêu cầu bổ sung đối với gcc và libpython và làm theo [INSTALL](https://docs.aspose.com/words/python-net/installation/) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tạo DOCM bằng Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



DOCM — Tệp `.docm` hỗ trợ macro nhúng và lý tưởng khi tài liệu phải bao gồm hành vi có thể lập trình; Python APIs có thể tạo tài liệu hỗ trợ macro bằng cách lắp ráp nội dung OOXML và đính kèm dự án VBA đã ký hoặc chưa ký thông qua tự động hóa. Việc tạo ra theo cách lập trình đảm bảo rằng các macro được đóng gói một cách nhất quán và có thể được xác thực hoặc ký như một phần của quá trình xây dựng.



Sử dụng DOCM là phù hợp khi logic kinh doanh (các trường tùy chỉnh, nút xuất, hoặc macro thu thập dữ liệu) phải tồn tại bên trong tài liệu; tự động hóa cho phép chèn, kiểm tra và kiểm soát nội dung macro để đáp ứng các kiểm tra bảo mật và tuân thủ.



Các bài kiểm tra tự động và quy trình CI có thể đảm bảo tính toàn vẹn mã macro và ký mã macro trước khi phân phối.



{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}



* **Tự động hóa được nhúng trong Tài Liệu**

&nbsp; Phân phối các tệp DOCM chạy các macro đã được phê duyệt để thu thập dữ liệu cấu trúc hoặc biến đổi cục bộ.



* **Triển Khai Macro Được Kiểm Soát**

&nbsp; Chèn các mô-đun VBA đã được duyệt vào tài liệu trong quá trình xây dựng để thực hiện hành vi macro được quy định.



* **Mẫu Hỗ Trợ Macro**

&nbsp; Sử dụng các mẫu DOTM làm nguồn để tạo ra tài liệu DOCM với tự động hóa đã được nướng sẵn.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}



* **CI Xác Thực Macro**

&nbsp; Tự động chạy phân tích tĩnh trên mã VBA và chặn quá trình xây dựng khi vi phạm chính sách.



* **Ký và Đóng Gói**

&nbsp; Tự động ký số cho các macro và đóng gói các tệp DOCM để phân phối an toàn.



* **Chèn Macro từ Kho Lưu Trữ An Toàn**

&nbsp; Rút các đoạn mã VBA đã được phê duyệt từ một kho lưu trữ an toàn và nhúng chúng vào các tệp DOCM được tạo ra.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}