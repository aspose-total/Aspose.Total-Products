---
title: Chuyển đổi DIF sang DOCM bằng Python
description: Chuyển đổi DIF sang DOCM trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: DIF
outformat: DOCM
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DIF sang DOCM qua Python" h2="Chuyển đổi DIF sang DOCM trong các ứng dụng Python của bạn mà không cần cài đặt Microsoft Excel<sup>&reg;</sup> hoặc Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với nhà phát triển Python, người đang cố gắng thêm tính năng chuyển đổi DIF sang DOCM trong ứng dụng. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau bao gồm các tệp DIF và DOCM.

Nó chủ yếu trong hai bước. Đầu tiên sử dụng API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) để chuyển đổi tệp DIF sang HTML. Sau đó, bằng cách sử dụng Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), hãy lưu HTML đã tạo thành định dạng Microsoft Word mong muốn. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi DIF sang DOCM bằng Python" %}}
- **Bước 1** Mở tệp DIF nguồn bằng lớp Workbook
- Lưu tệp DIF sang HTML bằng cách sử dụng phương pháp save(file, SaveFormat.HTML) bằng cách cung cấp tên tệp và đường dẫn thư mục mong muốn
-  **Bước 2** Tải tệp HTML với một phiên bản của lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Gọi phương thức `save` trong khi chỉ định đường dẫn tệp DOCM đầu ra. Vì vậy, tệp DIF của bạn được chuyển đổi thành DOCM theo đường dẫn đã chỉ định

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi DIF sang DOCM, cần có Python 3.5 trở lên
- API tham chiếu trong dự án trực tiếp từ PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) và [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Hoặc sử dụng các lệnh pip sau ```pip install aspose-cells-python``` và ```pip install aspose.words```
-  Ngoài ra, HĐH dựa trên Microsoft Windows hoặc Linux (xem thêm về [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) và [Words](https://docs.aspose.com/words/python-net/system-requirements/)) và đối với Linux, hãy kiểm tra các yêu cầu bổ sung đối với gcc và libpython và làm theo [hướng dẫn từng bước một](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu DIF vào HTML trong Python - Bước 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lưu HTML vào DOCM bằng Python - Bước 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-word/" name="DIF Đến WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-doc/" name="DIF Đến DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-docx/" name="DIF Đến DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-docm/" name="DIF Đến DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-dot/" name="DIF Đến DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-dotm/" name="DIF Đến DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-dotx/" name="DIF Đến DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-mobi/" name="DIF Đến MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-odt/" name="DIF Đến ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-ott/" name="DIF Đến OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-rtf/" name="DIF Đến RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dif-to-wordml/" name="DIF Đến WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}