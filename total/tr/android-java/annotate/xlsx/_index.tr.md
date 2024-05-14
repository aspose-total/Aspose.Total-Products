---
title: XLSX Annotation Online'ı kaldırın veya Android Mobil Uygulamalarını kullanarak Ek Açıklamaları Yönetin
description: XLSX dosyasındaki yorumları çevrimiçi uygulama aracılığıyla ücretsiz olarak silin.XLSX dosyalarının yorumlarını yönetmek için Android API kodu.

family: total
platformtag: Android
feature: Annotate
informat: XLSX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="XLSX Document Online'dan Yorumları Temizle veya Android Uygulamaları aracılığıyla Yönetin" h2="Güçlü Android tabanlı XLSX belge açıklama yardımcı programı uygulaması geliştirin.XLSX dosyasının yorumlarını yönetmek için listelenen kod." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSX Ek Açıklamalarını Çevrimiçi Kaldırma" %}}

1. Yorumları silmek için XLSX dosyasını yükleyerek içe aktarın
1. Ek açıklama uygulamasının sürükle ve bırak yöntemiyle bırakma alanının içine tıklayarak bunu yapın
1. XLSX dosyasının boyutuna ve internet hızına bağlı olarak birkaç saniye bekleyin
1. Yorumları temizlemek için 'Kaldır' düğmesini tıklayın
1. Dosyayı anında indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="XLSX Belge Yorumlarını Android Uygulama API'si aracılığıyla kaldırın" %}}

1. Android projesine kitaplık referansı ekleme
1. Belgeyi Çalışma Kitabı sınıfı nesnesi aracılığıyla yükleyin
1. Belirli bir Çalışma Sayfasını seçin
1. [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--) kullananların tüm yorumlarını alın
1. Tüm Konulu yorumları getThreadedComments aracılığıyla alın
1. Sırasıyla yorumları ve yazarları kaldırmak için RemoveAt'ı kullanın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod : XLSX Belgesinden Yorumları Kaldır" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Dizili XLSX Yorumlarını Güncelle" %}}

1. Belgeyi Çalışma Kitabı sınıfı nesnesi aracılığıyla yükleyin
1. Özel Çalışma Sayfasını edinin
1. getComments().getThreadedComments(Index).get(Index)'ü kullanarak zincir halindeki yorumu alın
1. Yorumu güncellemek için setNotes yöntemini kullanın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android Uygulama API'si aracılığıyla Yorum Ekle" %}}

1. Çalışma Kitabı sınıfı nesnesi aracılığıyla Belge Oluştur
1. Özel Çalışma Sayfasını edinin
1. getComments().add aracılığıyla yorum dizini ekleyin
1. Yorum eklemek için setNotes yöntemini kullanın
1. Dosyayı kaydetmek için kaydetme yöntemini çağırın with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod: XLSX Dosyasının Zincirli Yorumunu Güncelle" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kod: Yorum Ekleme" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>XLSX Belge Açıklaması Android Uygulamasını Geliştirin</h2>

Geri bildirim sağlamak, önerilerde bulunmak veya belge üzerinde başkalarıyla işbirliği yapmak için android tabanlı bir XLSX açıklama uygulaması veya yardımcı programı geliştirmeniz mi gerekiyor?[Aspose.Cells for Android via Java](https://products.aspose.com/cells/tr/android-java/), [Aspose.Total for Android via Java](https://products.aspose.com/total/tr/android-java/)'nin alt API'si olduğundan, herhangi bir android geliştiricisi yukarıdaki API kodunu kendi belge açıklama uygulamasına entegre edebilir.Güçlü Android kitaplığı, herhangi bir belge açıklama çözümünün programlanmasına olanak tanır.Üstelik XLSX formatı da dahil olmak üzere birçok popüler formatı destekleyebilir.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSX Dosyalarına Açıklama Eklemek için Android API'si" %}}

- Java paketlerimizi [Maven depoları](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/)'de barındırıyoruz. 
- Aspose.Cells for Java, bayt kodunu içeren yaygın bir JAR dosyasıdır.
- Aspose.Cells for Android via Java'in nasıl kurulacağını öğrenmek için [adım adım talimatlar](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository)'yi takip edin.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

- Android işletim sistemi 2.0 veya üzeri.
- Java paketi çapraz platformdur ve JVM uygulamasına sahip tüm işletim sistemlerinde çalışır.

<br />
Daha fazla ayrıntı için lütfen [Ürün Dokümantasyonu](https://docs.aspose.com/cells/java/system-requirements/)'e bakın.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}