---
title: Word Annotation Online'ı kaldırın veya Android Mobil Uygulamalarını kullanarak Ek Açıklamaları Yönetin
description: Word dosyasındaki yorumları çevrimiçi uygulama aracılığıyla ücretsiz olarak silin.Word dosyalarının yorumlarını yönetmek için Android API kodu.

family: total
platformtag: Android
feature: Annotate
informat: Word
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Word Document Online'dan Yorumları Temizle veya Android Uygulamaları aracılığıyla Yönetin" h2="Güçlü Android tabanlı Word belge açıklama yardımcı programı uygulaması geliştirin.Word dosyasının yorumlarını yönetmek için listelenen kod." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word Ek Açıklamalarını Çevrimiçi Kaldırma" %}}

1. Yorumları silmek için Word dosyasını yükleyerek içe aktarın
1. Ek açıklama uygulamasının sürükle ve bırak yöntemiyle bırakma alanının içine tıklayarak bunu yapın
1. Word dosyasının boyutuna ve internet hızına bağlı olarak birkaç saniye bekleyin
1. Yorumları temizlemek için 'Kaldır' düğmesini tıklayın
1. Dosyayı anında indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Word Belge Yorumlarını Android Uygulaması aracılığıyla kaldırın" %}}

1. Android projesine kütüphane referansı ekleyin
1. Belge sınıfı nesnesi aracılığıyla Belgeyi Yükle
1. [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) ve NodeType.COMMENT kullanarak tüm düğümlerden tüm yorumları alın
1. Tüm yorumları silmek için [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) yöntemini çağırın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : Word Dosyasından Yorumları Sil" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word Yorumunu Kaldır ve Ekle Yanıtı" %}}

1. Android projesine kütüphane referansı ekleyin
1. Belge sınıfı nesnesi aracılığıyla Belgeyi Yükle
1. GetChild'i kullanarak yorum alın
1. Bu yoruma verilen belirtilen yanıtı kaldırmak için [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment)'ü kullanın
1. Bu yoruma herhangi bir yanıt eklemek için [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String)'i kullanın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android Uygulaması aracılığıyla Yorum Ekle" %}}

1. Android projesine kütüphane referansı ekleyin
1. Belge sınıfı nesnesi oluştur
1. Yorumu oluşturmak için [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/)'yı kullanın
1. getParagraphs().add ve getFirstParagraph().getRuns().add'yi kullanın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod: Word Dosyasından Yorum Yanıtını Kaldırma ve Ekleme" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kod: Yorum Ekleme" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Word Belge Açıklaması Android Uygulamasını Geliştirin</h2>

Geri bildirim sağlamak, önerilerde bulunmak veya belge üzerinde başkalarıyla işbirliği yapmak için bir Word açıklama mobil uygulaması veya yardımcı programı geliştirmeniz mi gerekiyor?[Aspose.Words for Android via Java](https://products.aspose.com/words/tr/android-java/), [Aspose.Total for Android via Java](https://products.aspose.com/total/tr/android-java/)'nin alt API'si olduğundan, herhangi bir android geliştiricisi yukarıdaki API kodunu kendi belge açıklama uygulamasına entegre edebilir.Güçlü Android kitaplığı, herhangi bir belge açıklama çözümünün programlanmasına olanak tanır.Üstelik Word formatı da dahil olmak üzere birçok popüler formatı destekleyebilir.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word Dosyalarına Açıklama Eklemek için Android Kitaplığı" %}}

- Java paketlerimizi [Maven depoları](https://releases.aspose.com/java/repo/com/aspose/aspose-words/)'de barındırıyoruz. 
- Aspose.Words for Java, bayt kodunu içeren yaygın bir JAR dosyasıdır.
- Aspose.Words for Android via Java'in nasıl kurulacağını öğrenmek için [adım adım talimatlar](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/)'yi takip edin.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

- Java SE 7 ve daha yeni Java sürümleri desteklenmektedir.
- Güncel olmayan JRE kullanmak zorunda kalmanız durumunda Java SE 6 için ayrı paket.
- Java paketi çapraz platformdur ve JVM uygulamasına sahip tüm işletim sistemlerinde çalışır.
- İşletim sistemleri Microsoft Windows, Linux, macOS, Android ve iOS'u içerir.

<br />
JogAmp JOGL, Harfbuzz yazı tipi motoru, Java Gelişmiş Görüntüleme JAI gibi isteğe bağlı paket bağımlılıkları hakkında daha fazla ayrıntı için lütfen [Ürün Dokümantasyonu](https://docs.aspose.com/words/java/system-requirements/)'e bakın.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}