---
title: XLSB Dosyasını C++ kullanarak güncelleyin
description: Microsoft Excel kullanmadan C++ uygulamalarında XLSB belgesini değiştirin.
family: total
platformtag: C++
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XLSB Dosyasını C++ ile Güncelleyin" h2="XLSB elektronik tablolarını Microsoft Office'i yüklemeden C++ tabanlı uygulamalarınız aracılığıyla değiştirin<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

C++ uygulamasında XLSB dosyalarını güncellemeye çalışan bir programcı için, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API, güncelleme işleminin otomatikleştirilmesine yardımcı olabilir. Microsoft Excel belgeleri de dahil olmak üzere birden çok formatla ilgilenen farklı C++ kitaplıklarının eksiksiz bir paketidir. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketinin bir parçası olan [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, bu değiştirme işlemini kolaylaştırır. XLSB belgesini güncelleme işlemi, önce sayfaya erişerek ve ardından C++ kullanarak excel'deki hücre değerini güncelleyerek basittir.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++'da XLSB Dosyası Nasıl Güncellenir?" %}}

- XLSB dosyasını [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) kullanarak yükleyin
- GetIWorksheets()->GetObjectByIndex(0) kullanarak ilgili [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet)'ye ve GetICells()->GetObjectByIndex kullanarak ilgili hücreye erişim
- PutValue yöntemini kullanarak erişilen hücreye yeni veri ekleyin
- Dosyayı parametre olarak yol ile geçirerek Save yöntemini kullanarak dosyayı .xlsb dosyası olarak kaydedin.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Değişiklik Gereksinimleri" %}}

- XLSB modifikasyonu için, Windows ve Linux sistemleri için [sistem gereksinimleri](https://docs.aspose.com/cells/cpp/system-requirements/)'yı takiben 
- Komut satırından ```nuget install Aspose.Total.Cpp`` olarak kurun
- Veya ``Install-Package Aspose.Total.Cpp`` ile Visual Studio'nun Paket Yönetici Konsolu aracılığıyla
- Alternatif olarak, [İndirilenler](https://releases.aspose.com/cells/cpp)'den bir ZIP dosyasında çevrimdışı MSI yükleyicisini veya DLL'leri edinin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod - XLSB Dosyasını C++ ile Güncelleyin" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}