---
title: Chuyển đổi WORD sang MHTML bằng Python
description: WORD sang mhtml Định dạng lưu trữ web và chuyển đổi tệp HtmlFixed trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi WORD sang MHTML bằng Python" h2="Chuyển đổi WORD sang MHTML, HtmlFixed và HTML trong Ứng dụng Python của bạn mà không cần cài đặt Microsoft Word <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển Python, những người đang cố gắng thêm tính năng chuyển đổi WORD sang MHTML (Định dạng lưu trữ web) hoặc HtmlFixed có nghĩa là muốn lưu tài liệu ở định dạng HTML bằng cách sử dụng các phần tử được định vị hoàn toàn trong ứng dụng. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau. 

Chúng tôi sử dụng API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) nằm trong Gói [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) để thêm tính năng chuyển đổi WORD sang MHTML. Trong trường hợp tệp WORD đơn giản thì nó chỉ có hai dòng mã. Tải tệp WORD và gọi phương thức lưu với đường dẫn tệp thích hợp cùng với kiểu liệt kê SaveFormat dưới dạng MHTML hoặc HTML_FIXED. Nhưng trong trường hợp cần khôi phục mô hình tài liệu gần giống với mô hình ban đầu thì cần phải lưu thêm một số thông tin trong tài liệu kết quả được gọi là thông tin khứ hồi.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Làm thế nào để Chuyển đổi WORD sang MHTML bằng Python" %}}
- Tải tệp WORD nguồn bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Tạo phiên bản của [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Đặt export_roundtrip_information là True
- Chỉ định [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) dưới dạng MHTML
- Gọi phương thức `save` trong khi chỉ định đường dẫn tệp đầu ra & SaveFormat làm tham số. Vì vậy, tệp WORD của bạn được chuyển đổi thành MHTML theo đường dẫn được chỉ định.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi định dạng WORD sang MHTML hoặc HtmlFixed, Python 3.5 trở lên là bắt buộc
- Tham khảo các API trong dự án trực tiếp từ PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Hoặc sử dụng các lệnh pip sau `` pip install aspose.words ''.
- Hơn nữa, hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem thêm cho [Words](https://docs.aspose.com/words/python-net/system-requirements/)) và cho Linux, hãy kiểm tra các yêu cầu bổ sung cho gcc và libpython và làm theo hướng dẫn từng bước [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu WORD thành MHTML bằng Python - Đơn giản" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Chuyển đổi WORD sang MHTML bằng Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Việc chuyển đổi Word sang MHTML bằng các API Python biến các tài liệu xử lý văn bản thành định dạng lưu trữ web dạng tệp đơn, bảo tồn văn bản, kiểu dáng và các tài nguyên nhúng trong một gói tự chứa. Điều này có giá trị cho việc chia sẻ nội dung tài liệu ở định dạng thân thiện với trình duyệt đồng thời duy trì tính nhất quán về trình bày.

Trong các quy trình tự động, việc chuyển đổi sang MHTML hỗ trợ xuất bản di động, tạo lưu trữ và cung cấp nội dung tương thích web mà không yêu cầu người nhận phải phụ thuộc vào môi trường tạo tài liệu gốc.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

* **Lưu Trữ Web Dạng Tệp Đơn**
  Bảo tồn nội dung tài liệu và các tài nguyên liên quan trong một tệp có thể đọc được bởi trình duyệt.

* **Chia Sẻ Hình Ảnh Nhất Quán**
  Giúp duy trì bố cục và định dạng khi phân phối nội dung qua các hệ thống.

* **Xuất Bản Tài Liệu Di Động**
  Giúp dễ dàng hiển thị nội dung được tạo bằng Word trong các môi trường tương thích web.

* **Hỗ Trợ Đánh Giá Ngoại Tuyến**
  Cho phép xem nội dung tài liệu đầy đủ trên máy cục bộ mà không cần các tài nguyên riêng biệt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Các Kịch Bản Tự Động Hóa" %}}

* **Tạo Lưu Trữ Web Tự Động**
  Chuyển đổi các tệp Word lặp lại thành MHTML để phân phối, lưu trữ hoặc đánh giá.

* **Quy Trình Xuất Bản Nội Dung**
  Sử dụng các đầu ra MHTML làm tài sản trung gian trong quy trình chuyển tài liệu sang web.

* **Tự Động Hóa Giao Nhận Tự Cung Cấp**
  Đóng gói văn bản và tài nguyên lại với nhau để trao đổi đáng tin cậy giữa các hệ thống.

* **Quy Trình Nhất Quán Lưu Trữ**
  Tạo ra các phiên bản được bảo tồn, thân thiện với trình duyệt của tài liệu doanh nghiệp ở quy mô lớn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}