---
title: Chuyển đổi ODT sang PST bằng Python
description: Lưu ODT thành PST trong các ứng dụng Python mà không cần sử dụng Microsoft Word hoặc Outlook

family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: PST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi ODT sang PST bằng Python" h2="Chuyển đổi ODT sang PST trong Ứng dụng Python của bạn mà không cần cài đặt Microsoft Word <sup>&reg;</sup> hoặc Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với một nhà phát triển Python, ai đang cố gắng thêm tính năng chuyển đổi ODT sang PST trong ứng dụng? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm cả các định dạng Email, Hình ảnh và Microsoft Word. Các API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) và [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) là một phần của gói [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) giúp việc chuyển đổi này trở nên dễ dàng bằng Python. Đó là một quy trình gồm hai bước, trước tiên hãy tải tệp ODT và hiển thị nó thành HTML thông qua [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Thứ hai, tải HTML đã chuyển đổi bằng [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) và lưu nó thành định dạng PST.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển ODT sang PST bằng Python" %}}

- Mở tệp ODT nguồn bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Gọi phương thức `save` trong khi chỉ định đường dẫn tệp HTML đầu ra và các tùy chọn Lưu HTML có liên quan dưới dạng tham số. Vì vậy, tệp ODT của bạn được chuyển đổi thành HTML theo đường dẫn được chỉ định
- Bây giờ Tải tệp HTML đã lưu bằng MailMessage.load
- Gọi phương thức lưu với đường dẫn tệp có liên quan. Vì vậy, cuối cùng ODT được chuyển đổi

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi ODT sang PST, cần có Python 3.5 trở lên
- Tham chiếu các API trong dự án trực tiếp từ PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) và [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Hoặc sử dụng lệnh pip sau `` pip install aspose.words '' và `` pip install Aspose.Email-for-Python-via-NET '' '' 
- Hơn nữa, hệ điều hành dựa trên Microsoft Windows hoặc Linux (xem thêm cho [Words](https://docs.aspose.com/words/python-net/system-requirements/) và [Email](https://docs.aspose.com/email/python-net/system-requirements/)) và cho Linux, hãy kiểm tra các yêu cầu bổ sung cho gcc và libpython và làm theo hướng dẫn từng bước [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu ODT thành PST bằng Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Việc chuyển đổi ODT sang PST biến đổi nội dung tài liệu thành định dạng lưu trữ kiểu hộp thư, được sử dụng cho các kịch bản giao tiếp và lưu trữ gộp. Điều này hữu ích khi văn bản nguồn cần được tái sử dụng trong các container liên quan đến tin nhắn cho việc di chuyển, lưu trữ hoặc quản lý hồ sơ.

Với các API Python, việc chuyển đổi ODT sang PST có thể được tích hợp vào các quy trình làm việc tự động lưu trữ và đóng gói nội dung. Nó hỗ trợ việc chuẩn bị lặp lại các tài sản xuất phát từ tài liệu cho các kho lưu trữ tập trung vào giao tiếp.

{{% blocks/products/pf/agp/feature-section-col title="Các Trường Hợp Sử Dụng Chính" %}}

* **Chuẩn Bị Container Lưu Trữ**  
  Chuyển đổi nội dung tài liệu để sử dụng trong các quy trình lưu trữ kiểu hộp thư.

* **Hỗ Trợ Di Chuyển Nội Dung**  
  Giúp di chuyển tài liệu xuất phát từ tài liệu vào các môi trường lưu trữ hướng tin nhắn.

* **Hợp Nhất Hồ Sơ**  
  Hỗ trợ kết hợp nội dung đã chuyển đổi vào các container lưu trữ có cấu trúc.

* **Kích Hoạt Quy Trình Giữ Lưu**  
  Chuẩn bị các đầu ra phù hợp cho các quy trình bảo tồn lâu dài.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kịch Bản Tự Động Hóa" %}}

* **Đóng Gói Lưu Trữ Tự Động**  
  Các công việc Python có thể chuyển đổi tệp ODT thành các đầu ra kiểu PST cho các quy trình lưu trữ.

* **Chuyển Đổi Hàng Loạt cho Việc Giữ Lưu**  
  Thư viện tài liệu lớn có thể được xử lý tự động để chuẩn bị lưu trữ.

* **Tích Hợp Đường Ống Di Chuyển**  
  Các đầu ra đã chuyển đổi có thể được tạo ra như một phần của quá trình chuyển đổi hệ thống giao tiếp rộng hơn.

* **Xử Lý Hồ Sơ Theo Chương Trình**  
  Nội dung xuất phát từ tài liệu có thể di chuyển qua các quy trình lưu trữ lặp lại ở quy mô lớn.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}