---
title: JSON Formatını C++ ile POTM'ye Dönüştür
description: Microsoft PowerPoint kullanmadan JSON'u C++'da POTM'ye ayrıştırın

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTM
otherformats: POTX OTP ODP PPT PPTM PPSM PPSX POWERPOINT POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="JSON Formatını C++ ile POTM'ye Dönüştür" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan JSON'u POTM'ye ayrıştırmak için C++ API'si" >}}

{{% blocks/products/pf/feature-page-summary %}}
JSON'u herhangi bir C++ uygulamasında iki basit adımda POTM'ye dönüştürebilirsiniz. İlk olarak, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) kullanarak JSON'u PPTX'e ayrıştırabilirsiniz. Bundan sonra, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanarak PPTX'i POTM'ye dönüştürebilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON Formatını C++ ile POTM'ye Dönüştür" %}}
1. Yeni bir [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) nesnesi oluşturun ve dosyadan geçerli JSON verilerini okuyun
2. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) yöntemini kullanarak JSON'u PPTX olarak kaydedin
3. [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) yöntemini kullanarak belgeyi POTM biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Total.Cpp``` ile yükleyin.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarlayın ve JSON Formatını C++ ile POTM'ye Dönüştürün" %}}
JSON'u POTM'ye ayrıştırırken, JSON'u [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıfıyla yükleyerek satır ve sütunların boyutunu da ayarlayabilirsiniz. Çalışma sayfasındaki tüm satırlar için aynı satır yüksekliğini ayarlamanız gerekiyorsa, bunu [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f) kullanarak yapabilirsiniz. ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) koleksiyonunun yöntemi. Benzer şekilde, çalışma sayfasındaki tüm sütunlar için aynı sütun genişliğini ayarlamak için ICells koleksiyonunun [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) yöntemini kullanın.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++'da Filigran ile JSON Formatını POTM'ye Dönüştürün" %}}
API'yi kullanarak JSON'u filigranlı POTM'ye de dönüştürebilirsiniz. POTM belgenize filigran eklemek için önce JSON'u PPTX'e ayrıştırıp ona bir filigran ekleyebilirsiniz. Filigran eklemek için yeni oluşturulan PPTX dosyasını [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) sınıfını kullanarak yükleyin, ilk slaydı alın, AutoShape of Rectangle tipi, Rectangle'a TextFrame ekleyin, metin çerçevesi için Paragraph nesnesi oluşturun, paragraf için Portion nesnesi oluşturun, set_Text() kullanarak filigran ekleyin ve belgeyi POTM'ye kaydedebilir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}