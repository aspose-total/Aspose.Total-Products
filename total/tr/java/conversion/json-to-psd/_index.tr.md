---
title: JSON Formatını Java ile PSD'ye Dönüştür
description: Microsoft PowerPoint kullanmadan Java'da JSON'u PSD'ye ayrıştırın
url_ignore: /tr/java/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: SVGZ WMF DICOM DXF IMAGE TGA EMZ PSD WMZ JPEG2000
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="JSON Formatını Java ile PSD'ye Dönüştür" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında JSON biçimini PSD'ye ayrıştırmak için Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak herhangi bir Java uygulamasında JSON biçimini iki basit adımda PSD'ye dönüştürebilirsiniz. İlk olarak, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak JSON'u JPEG'e ayrıştırabilirsiniz. Bundan sonra, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) kullanarak JPEG'i PSD'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON Formatını Java ile PSD'ye Dönüştür" %}}
1. Yeni bir [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) nesnesi oluşturun ve JSON dosyasını açın
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) kullanarak JSON'u JPEG olarak kaydedin. ) yöntem
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak JPEG belgesi yükleyin
4. Belgeyi [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) kullanarak PSD formatına kaydedin-) yöntem
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
Ayrıca API, belirtilen düzen seçenekleriyle JSON'u PSD'ye ayrıştırmanıza olanak tanır. Düzen seçeneklerini belirtmek için [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) sınıfını kullanabilirsiniz. Bir diziyi tablo olarak işlemenize, boş değerleri yok saymanıza, dizi başlığını yoksaymanıza, nesne başlığını yoksaymanıza, dizeyi sayıya veya tarihe dönüştürmenize, tarih ve sayı biçimini ayarlamanıza ve başlık stilini ayarlamanıza olanak tanır. Tüm bu seçenekler, verilerinizi ihtiyaçlarınıza göre sunmanıza olanak tanır. Aşağıdaki kod parçacığı, düzen seçeneklerini nasıl ayarlayacağınızı gösterir.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Düzeni Ayarlayın ve JSON Formatını Java ile PSD'ye Dönüştürün" %}}
API'yi kullanarak, PSD belgenizdeki filigranlı JSON'u PSD'ye de dönüştürebilirsiniz. Filigran eklemek için önce JSON'u JPEG'e dönüştürebilir ve içine bir filigran ekleyebilirsiniz. Filigran eklemek için [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) sınıfını kullanarak bir görüntü dosyası yükleyin, [Graphics](https) nesnesini oluşturun ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) sınıfını seçin ve Image nesnesiyle başlatın, yeni bir [Matrix](https://reference.aspose.com/imaging/java/) oluşturun com.aspose.imaging/Matrix) nesnesini seçin ve çeviri ile dönüştürmeyi istediğiniz açıya ayarlayın ve [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#) kullanarak filigran ekleyin drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) yöntemi. Resminize filigranı ekledikten sonra JPEG'i PSD formatında kaydedebilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}