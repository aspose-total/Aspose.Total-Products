---
title: XML'yi XLTM'ye Dönüştürmek için C++ API
description: Microsoft Excel veya Adobe Reader kullanmadan XML'yi C++ API aracılığıyla XLTM'ye dönüştürün
url: /tr/cpp/conversion/xml-to-xltm/
family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: XLTM
otherformats: CSV XLT TXT XLSM FODS DIF TSV EXCEL XLSB ODS XLTX XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ Uygulamalarında XML'yi XLTM'ye Oluşturma" h2="Microsoft<sup>&reg;</sup> Excel veya Adobe<sup>&reg;</sup> Acrobat Reader gerektirmeden yerel C++ uygulamalarında XML'yi XLTM'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) dosya formatı otomasyon kitaplıkları aracılığıyla XML'yi C++'da XLTM'ye dönüştürmek, iki adımlı basit bir işlemdir. İlk adımda, [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) kullanarak XML'yi XLSX'e aktarabilirsiniz, Daha sonra [Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/) Elektronik Tablo Programlama API'si, XLSX'i XLTM'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XML'yi XLTM'ye Dönüştürmek için C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıf referansını kullanarak XML dosyasını açın
2. [Kaydet](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) üye işlevini kullanarak XML'yi XLSX'e dönüştürün
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) sınıf referansını kullanarak XLSX belgesini yükleyin
4. [Kaydet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) üye işlevini kullanarak belgeyi XLTM biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile XML Dosya Bilgilerini Alın veya Ayarlayın" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ayrıca XML belgeniz hakkında bilgi edinmenize ve dönüştürme işleminizden önce bilinçli kararlar vermenize olanak tanır. Bir XML dosyasının dosyaya özel bilgilerini almak için önce [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) yöntemini çağırmanız gerekir. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) sınıfı. DocumentInfo nesnesi alındığında, tek tek özelliklerin değerlerini alabilirsiniz. Ayrıca, DocumentInfo sınıfının ilgili yöntemlerini kullanarak da özellikleri ayarlayabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="XLTM Dosya Formatını C++ ile Akışa Kaydet" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/), akış için XLTM dosya formatının kaydedilmesine izin verir. Dosyaları bir akışa kaydetmek için bir MemoryStream veya FileStream nesnesi oluşturun ve [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) öğesini çağırarak dosyayı bu akış nesnesine kaydedin. nesnenin [Kaydet](https://reference.aspose.comyöntemi. Kaydet yöntemini çağırırken [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) numaralandırmasını kullanarak istediğiniz dosya biçimini belirtin.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xltm-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-xltm/" name="XML İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-xlt/" name="XML İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-txt/" name="XML İle TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-xlsm/" name="XML İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-fods/" name="XML İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-dif/" name="XML İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-tsv/" name="XML İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-excel/" name="XML İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-xlsb/" name="XML İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-ods/" name="XML İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-xltx/" name="XML İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/xml-to-xlam/" name="XML İle XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}