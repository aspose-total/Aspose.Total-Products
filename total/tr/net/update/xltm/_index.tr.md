---
title: .NET Kullanarak XLTM Dosyasını Güncelleyin
description: Microsoft Excel kullanmadan C# VB.NET uygulamalarında XLTM belgelerini değiştirin. 

family: total
platformtag: .NET
feature: update
informat: XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XLTM Dosyasını .NET Üzerinden Güncelleyin" h2="Microsoft Office<sup>&reg;</sup> yüklemeden .NET tabanlı uygulamalarınız aracılığıyla XLTM elektronik tablosunu değiştirin." >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET uygulaması aracılığıyla XLTM dosyalarını güncellemeye çalışan bir geliştirici için mi? [Aspose.Total for .NET](https://products.aspose.com/total/net/) API, güncelleme sürecini otomatikleştirmeye yardımcı olabilir. Microsoft Excel dosyaları da dahil olmak üzere farklı biçimlerle ilgilenen çeşitli .NET API'lerinden oluşan eksiksiz bir pakettir. [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketinin bir parçası olan ASPOSE.CELL API, bu değiştirme işlemini kolaylaştırır. Aşağıda XLTM belgesinin güncellenmesi süreci yer almaktadır.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET'te XLTM Dosyası Nasıl Güncellenir" %}}

- Parametre olarak kaynak XLTM dosyasına sahip yeni [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) sınıfı nesnesi oluşturun
- [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) yöntemi ile ilgili Çalışma Sayfasına ve ilgili hücreye erişim
- [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) yöntemini kullanarak erişilen hücreye yeni veri ekleyin
- Dosyayı parametre olarak yol ile ileterek save() yöntemini kullanarak dosyayı .xltm dosyası olarak kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Değişiklik Gereksinimleri" %}}

- XLTM değişikliği, Microsoft Windows veya .NET, .NET Core, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi için
- Microsoft Visual Studio gibi geliştirme ortamı 
- Komut satırından ```nuget install Aspose.Cells``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Cells`` ile kurun
- Alternatif olarak, çevrimdışı MSI yükleyicisini veya tüm DLL'leri [İndirilenler](https://releases.aspose.com/cells/net)'ten bir ZIP dosyasında alın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod - .NET'te XLTM Dosyasını Güncelleyin" offSpacer="" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}