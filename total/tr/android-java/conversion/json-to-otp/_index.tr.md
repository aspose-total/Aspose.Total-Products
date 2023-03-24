---
title: Java ile Android'de JSON Formatını OTP'ye Dönüştür
description: Microsoft PowerPoint kullanmadan Android Uygulamalarında JSON'u OTP'ye ayrıştırma

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: OTP
otherformats: PPT POTM POTX PPTM PPS PPSX POT PPSM POWERPOINT ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android'de JSON Formatını OTP'ye Dönüştür" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan JSON biçimini Android Uygulamalarında OTP'ye ayrıştırın" >}}

{{% blocks/products/pf/feature-page-summary %}}
Android uygulamalarınızda JSON formatını iki aşamalı bir işlemle OTP'ye dönüştürebilirsiniz. İlk olarak, [Java üzerinden Android için Aspose.Cells](https://products.aspose.com/cells/android-java/) kullanarak JSON'u PPTX'e ayrıştırabilirsiniz. Bundan sonra, [Java üzerinden Android için Aspose.Slides](https://products.aspose.com/slides/android-java/) kullanarak PPTX'i OTP'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android'de JSON Formatını OTP'ye Dönüştür" %}}
1. Yeni bir [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) nesnesi oluşturun ve JSON dosyasını açın
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) kullanarak JSON'u PPTX olarak kaydedin ) yöntem
3. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) yöntemini kullanarak belgeyi OTP biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://releases.aspose.com/total/java/) üzerinden kolayca kullanabilirsiniz ve uygulamanıza kitaplıkları yükleyin.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Android Uygulamalarında Düzeni Ayarlayın ve JSON Formatını OTP'ye Dönüştürün" %}}
Ayrıca API, belirtilen düzen seçenekleriyle JSON'u OTP'ye ayrıştırmanıza olanak tanır. Düzen seçeneklerini belirlemek için [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) sınıfını kullanabilirsiniz. Bir diziyi tablo olarak işlemenize, boş değerleri yok saymanıza, dizi başlığını yoksaymanıza, nesne başlığını yoksaymanıza, dizeyi sayıya veya tarihe dönüştürmenize, tarih ve sayı biçimini ayarlamanıza ve başlık stilini ayarlamanıza olanak tanır. Bu seçeneklerin tümü, verilerinizi ihtiyaçlarınıza göre sunmanıza olanak tanır. Aşağıdaki kod parçacığı, düzen seçeneklerini nasıl ayarlayacağınızı gösterir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de Filigran ile JSON Formatını OTP'ye Dönüştürün" %}}
API'yi kullanarak JSON'u filigranlı OTP'ye de dönüştürebilirsiniz. OTP belgenize filigran eklemek için önce JSON'u PPTX'e ayrıştırıp ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan PPTX dosyasını [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak yükleyin, tüm slaytlar arasında dolaşın, metin ekleyin addTextFrame kullanarak color, fillType ve daha fazlası gibi ilgili tüm seçenekleri ayarlayın ve belgeyi OTP'ye kaydedebilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}