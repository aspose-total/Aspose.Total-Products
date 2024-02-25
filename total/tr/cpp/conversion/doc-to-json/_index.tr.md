---
title: DOC'yi C++ ile JSON formatına dönüştürün
description: Microsoft Excel veya Word kullanmadan DOC'yi C++'da JSON'a aktarın

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="DOC'yi C++ ile JSON Formatına Dönüştür" h2="Microsoft<sup>&reg;</sup> Word veya Excel kullanmadan DOC'yi C++ aracılığıyla JSON'a aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) kullanarak, C++ uygulamalarınızda DOC'yi JSON formatına dönüştürebilirsiniz. İlk olarak, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak DOC'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak HTML'yi JSON formatına dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOC'yi C++ ile JSON Formatına Dönüştür" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıf referansını kullanarak DOC dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) üye işlevini kullanarak DOC'u HTML'ye dönüştürün
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

{{% blocks/products/pf/feature-page-section  h2="Korumalı DOC'yi C++ ile JSON Formatına Dönüştür" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Girdiğiniz DOC belgeniz parola korumalıysa, parolayı kullanmadan JSON biçimine dönüştüremezsiniz. Bunu yapmak için, bir LoadOptions nesnesini kabul eden özel bir yapıcı aşırı yüklemesi kullanın. Bu nesne, parola dizesini belirten Parola özelliğini içerir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}