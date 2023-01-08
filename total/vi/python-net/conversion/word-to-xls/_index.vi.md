---
title: Chuyển đổi WORD sang XLS bằng Python
description: Chuyển đổi WORD sang XLS trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Word hoặc Excel 

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: XLS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi WORD sang XLS qua Python" h2="Chuyển đổi WORD sang XLS trong các ứng dụng Python của bạn mà không cần cài đặt Microsoft Word<sup>&reg;</sup> hoặc Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với nhà phát triển Python, người đang cố gắng thêm tính năng chuyển đổi WORD sang XLS trong ứng dụng. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau.

Nó chủ yếu trong hai bước. Trước tiên, hãy sử dụng API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) để chuyển đổi tệp WORD sang HTML. Sau đó, bằng cách sử dụng Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), hãy lưu HTML đã tạo thành định dạng Microsoft Excel mong muốn. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi WORD sang XLS bằng Python" %}}
- **Bước 1** Mở tệp WORD nguồn bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Lưu tệp WORD sang HTML bằng cách sử dụng phương pháp [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) bằng cách cung cấp tên tệp và đường dẫn thư mục mong muốn
-  **Bước 2** Tải tệp HTML bằng một phiên bản của lớp Workbook với tệp và LoadOptions làm tham số
-  Gọi phương thức `save` trong khi chỉ định đường dẫn tệp XLS đầu ra. Vì vậy, tệp WORD của bạn được chuyển đổi thành XLS theo đường dẫn đã chỉ định

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi WORD sang XLS, cần có Python 3.5 trở lên
- API tham chiếu trong dự án trực tiếp từ PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) và [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Hoặc sử dụng các lệnh pip sau ```pip install aspose.words``` và ```pip install aspose-cells-python``` 
-  Ngoài ra, HĐH dựa trên Microsoft Windows hoặc Linux (xem thêm về [Words](https://docs.aspose.com/words/python-net/system-requirements/) và [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) và đối với Linux, hãy kiểm tra các yêu cầu bổ sung đối với gcc và libpython và làm theo [hướng dẫn từng bước một](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu WORD vào HTML trong Python - Bước 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lưu HTML vào XLS bằng Python - Bước 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-excel/" name="WORD Đến EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xls/" name="WORD Đến XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xlsx/" name="WORD Đến XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-csv/" name="WORD Đến CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-dif/" name="WORD Đến DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-fods/" name="WORD Đến FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-ods/" name="WORD Đến ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-sxc/" name="WORD Đến SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-tsv/" name="WORD Đến TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xlam/" name="WORD Đến XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xlsb/" name="WORD Đến XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xlt/" name="WORD Đến XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xltm/" name="WORD Đến XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xltx/" name="WORD Đến XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/word-to-xlsm/" name="WORD Đến XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}