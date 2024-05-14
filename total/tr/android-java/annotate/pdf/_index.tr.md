---
title: PDF Annotation Online'ı kaldırın veya Android Mobil Uygulamalarını kullanarak Ek Açıklamaları Yönetin
description: PDF dosyasındaki yorumları çevrimiçi uygulama aracılığıyla ücretsiz olarak silin.PDF dosyalarının yorumlarını yönetmek için Android API kodu.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="PDF Document Online'dan Yorumları Temizle veya Android Uygulamaları aracılığıyla Yönetin" h2="Güçlü Android tabanlı PDF belge açıklama yardımcı programı uygulaması geliştirin.PDF dosyasının yorumlarını yönetmek için listelenen kod." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF Ek Açıklamalarını Çevrimiçi Kaldırma" %}}

1. Yorumları silmek için PDF dosyasını yükleyerek içe aktarın
1. Ek açıklama uygulamasının sürükle ve bırak yöntemiyle bırakma alanının içine tıklayarak bunu yapın
1. PDF dosyasının boyutuna ve internet hızına bağlı olarak birkaç saniye bekleyin
1. Yorumları temizlemek için 'Kaldır' düğmesini tıklayın
1. Dosyayı anında indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="PDF Belge Yorumlarını Android Uygulama API'si aracılığıyla kaldırın" %}}

1. Android projesine kütüphane referansı ekleyin
1. Belge sınıfı nesnesi aracılığıyla Belgeyi Yükle
1. getPages().get_Item(Index) aracılığıyla belirli sayfayı seçin
1. AnnotationSelector'ı kullanın ve tüm metin açıklamalarını annotationSelector.getSelected() aracılığıyla alın
1. Her ek açıklamayı yineleyin ve kaldırmak için silme yöntemini çağırın.
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : PDF Dosyasından Yorumları Sil" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Android Uygulama API'si aracılığıyla Ek Açıklama Ekleme" %}}

1. Android projesine kütüphane referansı ekleyin
1. Belge sınıfı nesnesi oluştur
1. getPages().add() işlevini kullanarak yeni sayfayı ve içeriği ekleyin
1. TextAnnotation sınıfının getPages().get_Item(Index) işlevini kullanın
1. Başlık, konu, içerik vb. gibi ilgili ek açıklamaları ayarlayın
1. Ek açıklamaları eklemek için getAnnotations().add'ü kullanın
1. Dosyayı eklenen yorumlarla kaydetmek için kaydetme yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : PDF Ek Açıklaması Ekle" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PDF Belge Açıklaması Android Uygulamasını Geliştirin</h2>

Geri bildirim sağlamak, önerilerde bulunmak veya belge üzerinde başkalarıyla işbirliği yapmak için bir PDF açıklama mobil uygulaması veya yardımcı programı geliştirmeniz mi gerekiyor?[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/tr/android-java/), [Aspose.Total for Android via Java](https://products.aspose.com/total/tr/android-java/)'nin alt API'si olduğundan, herhangi bir android geliştiricisi yukarıdaki API kodunu kendi belge açıklama uygulamasına entegre edebilir.Güçlü Android kitaplığı, herhangi bir belge açıklama çözümünün programlanmasına olanak tanır.Üstelik PDF formatı da dahil olmak üzere birçok popüler formatı destekleyebilir.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF Dosyalarına Açıklama Eklemek için Android Kitaplığı" %}}

- Java paketlerimizi [Maven depoları](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/)'de barındırıyoruz. 
- Aspose.PDF for Java, bayt kodunu içeren yaygın bir JAR dosyasıdır.
- Aspose.PDF for Android via Java'in nasıl kurulacağını öğrenmek için [adım adım talimatlar](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository)'yi takip edin.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

- Android API 31 ve 32
- Android4.0 ve üzeri
- Android Studio ve SDK araçları

<br />
JogAmp JOGL, Harfbuzz yazı tipi motoru, Java Gelişmiş Görüntüleme JAI gibi isteğe bağlı paket bağımlılıkları hakkında daha fazla ayrıntı için lütfen [Ürün Dokümantasyonu](https://docs.aspose.com/pdf/java/system-requirements/)'e bakın.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}