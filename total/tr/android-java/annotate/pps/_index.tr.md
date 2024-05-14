---
title: PPS Annotation Online'ı kaldırın veya Android Mobil Uygulamalarını kullanarak Ek Açıklamaları Yönetin
description: PPS dosyasındaki yorumları çevrimiçi uygulama aracılığıyla ücretsiz olarak silin.PPS dosyalarının yorumlarını yönetmek için Android API kodu.

family: total
platformtag: Android
feature: Annotate
informat: PPS
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="PPS Sunumundan Yorumları Temizle Çevrimiçi veya Android Uygulamaları aracılığıyla Yönetin" h2="Güçlü Android tabanlı PPS sunum açıklama yardımcı programı uygulaması geliştirin.PPS dosyasının yorumlarını yönetmek için listelenen kod." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPS Ek Açıklamalarını Çevrimiçi Kaldırma" %}}

1. Yorumları silmek için PPS dosyasını yükleyerek içe aktarın
1. Ek açıklama uygulamasının sürükle ve bırak yöntemiyle bırakma alanının içine tıklayarak bunu yapın
1. PPS dosyasının boyutuna ve internet hızına bağlı olarak birkaç saniye bekleyin
1. Yorumları temizlemek için 'Kaldır' düğmesini tıklayın
1. Dosyayı anında indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PPS Sunum Yorumlarını Android Uygulaması aracılığıyla kaldırın" %}}

1. Android projesine kütüphane referansı ekleyin
1. PPS'i Sunum sınıfı nesnesi aracılığıyla yükleyin
1. Presentation.getCommentAuthors() koleksiyonu aracılığıyla her Yazarı yineleyin
1. Yorumunu silmek için clear() yöntemini çağırın
1. Son olarak tüm yazarları kaldırmak için getCommentAuthors().clear()'ü arayın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : PPS Sunumundan Yorumları ve Yazarları Sil" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Android Uygulaması aracılığıyla PPS Sunum Yorumları Ekleme" %}}

1. Android projesine kütüphane referansı ekleyin
1. PPS'i Sunum sınıfı nesnesi aracılığıyla yükleyin
1. Yazarları eklemek için Presentation.getCommentAuthors().addAuthor(String, String)'i çağırın
1. Yorum eklemek için ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)'yı kullanın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod: Yorum Ekleme" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PPS Belge Açıklaması Android Uygulamasını Geliştirin</h2>

Geri bildirim sağlamak, önerilerde bulunmak veya belge üzerinde başkalarıyla işbirliği yapmak için bir PPS açıklama mobil uygulaması veya yardımcı programı geliştirmeniz mi gerekiyor?[Aspose.Slides for Android via Java](https://products.aspose.com/slides/tr/android-java/), [Aspose.Total for Android via Java](https://products.aspose.com/total/tr/android-java/)'nin alt API'si olduğundan, herhangi bir android geliştiricisi yukarıdaki API kodunu kendi belge açıklama uygulamasına entegre edebilir.Güçlü Android kitaplığı, herhangi bir belge açıklama çözümünün programlanmasına olanak tanır.Üstelik PPS formatı da dahil olmak üzere birçok popüler formatı destekleyebilir.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPS Dosyalarına Açıklama Eklemek için Android Kitaplığı" %}}

- Java paketlerimizi [Maven depoları](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)'de barındırıyoruz. 
- Aspose.Slides for Java, bayt kodunu içeren yaygın bir JAR dosyasıdır.
- Aspose.Slides for Android via Java'in nasıl kurulacağını öğrenmek için [adım adım talimatlar](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)'yi takip edin.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

- J2SE 6.0 (Java 1.6) ve üzeri
- Java paketi çapraz platformdur ve JVM uygulamasına sahip tüm işletim sistemlerinde çalışır.

<br />
Daha fazla ayrıntı için lütfen [Ürün Dokümantasyonu](https://docs.aspose.com/slides/java/system-requirements/)'e bakın.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}