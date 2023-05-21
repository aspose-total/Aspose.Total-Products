---
title: WORD'yi C++ ile JSON formatına dönüştürün
description: Microsoft Excel veya Word kullanmadan WORD'yi C++'da JSON'a aktarın

family: total
platformtag: cpp
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORD'yi C++ ile JSON Formatına Dönüştür" h2="Microsoft<sup>&reg;</sup> Word veya Excel kullanmadan WORD'yi C++ aracılığıyla JSON'a aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) kullanarak, C++ uygulamalarınızda WORD'yi JSON formatına dönüştürebilirsiniz. İlk olarak, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak WORD'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak HTML'yi JSON formatına dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORD'yi C++ ile JSON Formatına Dönüştür" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordument) sınıf referansını kullanarak WORD dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string_saveformat) üye işlevini kullanarak WORD'u HTML'ye dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak HTML belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) üye işlevini kullanarak belgeyi JSON biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Total.Cpp``` ile yükleyin.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Korumalı WORD'yi C++ ile JSON Formatına Dönüştür" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Girdiğiniz WORD belgeniz parola korumalıysa, parolayı kullanmadan JSON biçimine dönüştüremezsiniz. Bunu yapmak için, bir LoadOptions nesnesini kabul eden özel bir yapıcı aşırı yüklemesi kullanın. Bu nesne, parola dizesini belirten Parola özelliğini içerir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}