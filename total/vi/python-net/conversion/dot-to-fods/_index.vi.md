---
title: Chuyển đổi DOT sang FODS bằng Python
description: Chuyển đổi DOT sang FODS trong các ứng dụng Python của bạn mà không cần sử dụng Microsoft Word hoặc Excel 

family: total
platformtag: Python
feature: conversion
informat: DOT
outformat: FODS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DOT sang FODS qua Python" h2="Chuyển đổi DOT sang FODS trong các ứng dụng Python của bạn mà không cần cài đặt Microsoft Word<sup>&reg;</sup> hoặc Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với nhà phát triển Python, người đang cố gắng thêm tính năng chuyển đổi DOT sang FODS trong ứng dụng. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API có thể giúp tự động hóa quá trình chuyển đổi. Đó là một gói đầy đủ các API khác nhau xử lý các định dạng khác nhau.

Nó chủ yếu trong hai bước. Trước tiên, hãy sử dụng API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) để chuyển đổi tệp DOT sang HTML. Sau đó, bằng cách sử dụng Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), hãy lưu HTML đã tạo thành định dạng Microsoft Excel mong muốn. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi DOT sang FODS bằng Python" %}}
- **Bước 1** Mở tệp DOT nguồn bằng lớp [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Lưu tệp DOT sang HTML bằng cách sử dụng phương pháp [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) bằng cách cung cấp tên tệp và đường dẫn thư mục mong muốn
-  **Bước 2** Tải tệp HTML bằng một phiên bản của lớp Workbook với tệp và LoadOptions làm tham số
-  Gọi phương thức `save` trong khi chỉ định đường dẫn tệp FODS đầu ra. Vì vậy, tệp DOT của bạn được chuyển đổi thành FODS theo đường dẫn đã chỉ định

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}

- Để chuyển đổi DOT sang FODS, cần có Python 3.5 trở lên
- API tham chiếu trong dự án trực tiếp từ PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) và [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Hoặc sử dụng các lệnh pip sau ```pip install aspose.words``` và ```pip install aspose-cells-python``` 
-  Ngoài ra, HĐH dựa trên Microsoft Windows hoặc Linux (xem thêm về [Words](https://docs.aspose.com/words/python-net/system-requirements/) và [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) và đối với Linux, hãy kiểm tra các yêu cầu bổ sung đối với gcc và libpython và làm theo [hướng dẫn từng bước một](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Lưu DOT vào HTML trong Python - Bước 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Lưu HTML vào FODS bằng Python - Bước 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-excel/" name="DOT Đến EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xls/" name="DOT Đến XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xlsx/" name="DOT Đến XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-csv/" name="DOT Đến CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-dif/" name="DOT Đến DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-fods/" name="DOT Đến FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-ods/" name="DOT Đến ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-sxc/" name="DOT Đến SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-tsv/" name="DOT Đến TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xlam/" name="DOT Đến XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xlsb/" name="DOT Đến XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xlt/" name="DOT Đến XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xltm/" name="DOT Đến XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xltx/" name="DOT Đến XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/python-net/conversion/dot-to-xlsm/" name="DOT Đến XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}