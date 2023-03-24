---
title: Java ile Android'de JSON Formatını OTT'ye dönüştürün
description: Microsoft Word kullanmadan Java'da JSON'u OTT'ye ayrıştırın

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: OTT
otherformats: DOC RTF PS PCL CHM MOBI WORD FLATOPC DOTX ODT DOCM WORDML EPUB DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android Uygulamalarında JSON Formatını OTT'ye Dönüştür" h2="Microsoft<sup>&reg;</sup> Word kullanmadan Android uygulamalarında JSON'u OTT'ye ayrıştırın" >}}

{{% blocks/products/pf/feature-page-summary %}}
Android uygulamalarınızda JSON'u OTT'ye iki aşamalı bir işlemle dönüştürebilirsiniz. İlk olarak, Güçlü Elektronik Tablo İşleme API'sini [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) kullanarak JSON'u PDF'ye ayrıştırabilirsiniz. İkinci adımda, Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak PDF'yi OTT'ye dönüştürebilirsiniz. Her iki API de [Java üzerinden Android için Aspose.Total](https://products.aspose.com/total/android-java/) ürün ailesi kapsamındadır. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile Android'de JSON Formatını OTT'ye dönüştürün" %}}
1. Yeni bir [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) nesnesi oluşturun ve dosyadan geçerli JSON verilerini okuyun
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) sınıfını ve [Kaydet](https://reference.aspose.com/) kullanarak JSON dosyasını çalışma sayfasına aktarın cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF olarak
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak PDF belgesi yükleyin
4. [Kaydet](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) kullanarak belgeyi OTT biçiminde kaydedin )) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://releases.aspose.com/total/java/) üzerinden kolayca kullanabilirsiniz ve uygulamanıza kitaplıkları yükleyin.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarla ve JSON Formatını Java ile Android'de OTT'ye Dönüştür" %}}
Ayrıca API, [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) kullanarak JSON'u OTT'ye ayrıştırırken JSON biçiminiz için düzen seçeneklerini ayarlamanıza olanak tanır. Diziyi bir tablo olarak işlemenize, boş değerleri yok saymanıza, dizi başlığını yoksaymanıza, nesne başlığını yoksaymanıza, dizeyi sayıya veya tarihe dönüştürmenize, tarih ve sayı biçimini ayarlamanıza ve başlık stilini ayarlamanıza olanak tanır. Bu seçeneklerin tümü, verilerinizi ihtiyaçlarınıza göre sunmanıza olanak tanır. Aşağıdaki kod parçacığı, düzen seçeneklerini nasıl ayarlayacağınızı gösterir.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java ile Android'de Filigran ile JSON Formatını OTT'ye Dönüştürün" %}}
API'yi kullanarak JSON'u filigranla OTT'ye de dönüştürebilirsiniz. OTT belgenize filigran eklemek için önce JSON dosyasını PDF'ye ayrıştırıp ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan PDF dosyasını [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve ayarlayın özellikleri, Watermark.setText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin. Filigranı ekledikten sonra belgeyi OTT'ye kaydedebilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}