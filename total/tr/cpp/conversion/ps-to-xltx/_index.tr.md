---
title: PS'yi XLTX'ye Dönüştürmek için C++ API
description: Microsoft Excel veya Adobe Reader kullanmadan PS'yi C++ API aracılığıyla XLTX'ye dönüştürün
url: /tr/cpp/conversion/ps-to-xltx/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: XLTX
otherformats: XLSB FODS SXC TSV XLTM EXCEL XLSM CSV ODS MD DIF TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ Uygulamalarında PS'yi XLTX'ye Oluşturma" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader gerektirmeden yerel C++ uygulamalarında PS'yi XLTX'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) dosya formatı otomasyon kitaplıkları aracılığıyla PS'yi C++'da XLTX'ye dönüştürmek, iki adımlı basit bir işlemdir. İlk adımda, [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) kullanarak PS'yi XLSX'e aktarabilirsiniz, Daha sonra [Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/) Elektronik Tablo Programlama API'si, XLSX'i XLTX'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS'yi XLTX'ye Dönüştürmek için C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak PS dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) üye işlevini kullanarak PS'yi XLSX'e dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak XLSX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) üye işlevini kullanarak belgeyi XLTX biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile PS Dosya Bilgilerini Alın veya Ayarlayın" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ayrıca PS belgeniz hakkında bilgi edinmenize ve dönüştürme işleminizden önce bilinçli kararlar vermenize olanak tanır. Bir PS dosyasının dosyaya özel bilgilerini almak için önce [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) yöntemini çağırmanız gerekir. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıfı. DocumentInfo nesnesi alındığında, tek tek özelliklerin değerlerini alabilirsiniz. Ayrıca, DocumentInfo sınıfının ilgili yöntemlerini kullanarak da özellikleri ayarlayabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XLTX Dosya Formatını C++ ile Akışa Kaydet" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/), akış için XLTX dosya formatının kaydedilmesine izin verir. Dosyaları bir akışa kaydetmek için bir MemoryStream veya FileStream nesnesi oluşturun ve [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) öğesini çağırarak dosyayı bu akış nesnesine kaydedin. nesnenin [Kaydet](https://reference.aspose.comyöntemi. Kaydet yöntemini çağırırken [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) numaralandırmasını kullanarak istediğiniz dosya biçimini belirtin.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xltx-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-xlsb/" name="PS İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-fods/" name="PS İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-sxc/" name="PS İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-tsv/" name="PS İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-xltm/" name="PS İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-excel/" name="PS İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-xlsm/" name="PS İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-xltx/" name="PS İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-ods/" name="PS İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-md/" name="PS İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-dif/" name="PS İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/ps-to-txt/" name="PS İle TXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}