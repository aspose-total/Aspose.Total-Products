---
title: C# kullanarak Web Sayfalarını HTML'den Görüntülere Dönüştürün
description: Web sitesi web sayfalarını kazıyın ve HTML'yi Görüntülere aktarın. Web sitesi verilerini JPEG, PNG, GIF, BMP vb. biçimlere kazımak için .NET uygulamaları geliştirin. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Web Sayfalarını C# ile Görüntülere Dönüştürün" h2="Web sitesi verilerini HTML web sayfalarından çıkarın. .NET uygulamaları içinde HTML'yi JPG, GIF, PNG, BMP resimlerine dönüştürün." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Neden Web Sayfalarını Görsellere Dönüştürmelisiniz?</h2>
<p>Web sayfalarını resimlere dönüştürmek, çeşitli durumlarda yararlı olabilir. Birçok uygulama için ortak bir gerekliliktir. Bazı senaryolarda, ekranda görünmeyen kısımlar da dahil olmak üzere tüm web sayfasının görüntü olarak alınması gerekir. Bu, web sitesi önizlemeleri oluşturmak, makbuzları ve faturaları almak veya yasal amaçlarla web sayfalarını arşivlemek için yararlı olabilir. Dokümantasyon veya test amacıyla web sayfalarının ekran görüntülerini oluşturmak için kullanılabilir. Arama sonuçlarında veya resim galerilerinde kullanılmak üzere web sayfalarının küçük resimlerini veya önizlemelerini oluşturmak için de kullanılabilir. İster bir masaüstü uygulaması ister bir web uygulaması oluşturuyor olun, C# kullanarak web sayfalarını görüntülere dönüştürmek için birçok seçenek vardır.</p><br />

<p>Web sayfalarını C# kullanarak resimlere dönüştürmek, aşağıdakiler de dahil olmak üzere çeşitli avantajlar sağlayabilir:</p><br />
<ul>
<li>Geliştirilmiş erişilebilirlik: Resimlerin okunması ve anlaşılması, görme engelli veya diğer engelleri olan kişiler için daha kolay olabilir.</li>
<li>Arttırılmış taşınabilirlik: Görüntüler kolayca paylaşılabilir veya diğer belgelere veya uygulamalara gömülebilir.</li>
</ul>
<p>Web sayfalarını C# kullanarak resimlere dönüştürmek, aşağıdakiler de dahil olmak üzere bazı zorluklar ortaya çıkarabilir:</p><br />
<ul>
<li>Sınırlı biçim desteği: Bazı API'ler veya araçlar, tüm görüntü biçimlerini desteklemeyebilir veya çıktı görüntülerinin boyutu veya çözünürlüğü konusunda sınırlamalara sahip olabilir.</li>
<li>Uyumluluk sorunları: Bazı web sayfaları tüm tarayıcılarda doğru şekilde oluşturulmayabilir veya düzgün görüntülenmesi için belirli ayarlar veya eklentiler gerektirebilir.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Web Sayfalarını C# Kullanarak Görüntülere Nasıl Dönüştürürüz?" %}}
Web sayfalarını C# kullanarak görüntülere dönüştürmek için, HTML sayfalarını JPEG, PNG ve TIFF dahil olmak üzere görüntü biçimlerine dönüştürmek için bu işlevi sağlayan bir Aspose.HTML for .NET API kullanabilirsiniz.</p>

1. içinde bulunan oluşturuculardan birini kullanarak bir HTML belgesi yükleyin. [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). HTML'yi bir dosyadan, HTML kodundan, akıştan veya URL'den yükleyebilirsiniz.
2. Yeni bir örneğini oluştur [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) ve ImageFormat özelliğini JPEG olarak ayarlayın. Format özelliği varsayılan olarak PNG olarak ayarlanmıştır.
3. kullanmak [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) HTML belgesini bir JPEG dosyası olarak kaydetmek için Converter sınıfından bir yöntem. HTMLDocument, ImageSaveOptions ve çıktı dosyası yolunu ConvertHTML() yöntemine parametre olarak sağlamanız gerekir.
4. Ortaya çıkan JPEG dosyası, belirtilen dosya yoluna kaydedilecektir.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Web Hurdaya Çıkarma ve Görüntü Dönüştürme Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` olarak kurun veya doğrudan Visual Studio'nun Paket Yöneticisi Konsolundan kurun.

İki [Aspose.Total for .NET](https://products.aspose.com/total/net/) alt API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) entegre olacak.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri bir ZIP dosyasında şu adresten edinin: [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}