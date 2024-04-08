---
title: Word Annotation Online'ı kaldırın veya C++ ile Ek Açıklamaları Yönetin
description: Word dosyasındaki yorumları çevrimiçi uygulama aracılığıyla ücretsiz olarak silin. Word dosyalarının yorumlarını yönetmek için C++ API kodu.

family: total
platformtag: cpp
feature: Annotate
informat: Word
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Word Document Online'dan Yorumları Temizle veya C++ ile Yönetin" h2="Güçlü C++ tabanlı Word belge açıklama yardımcı programı uygulaması geliştirin. Word dosyasının yorumlarını C++ aracılığıyla yönetmek için listelenen kod." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word Ek Açıklamalarını Çevrimiçi Kaldırma" %}}

1. Yorumları silmek için Word dosyasını yükleyerek içe aktarın
1. Ek açıklama uygulamasının sürükle ve bırak yöntemiyle bırakma alanının içine tıklayarak bunu yapın
1. Word dosyasının boyutuna ve internet hızına bağlı olarak birkaç saniye bekleyin
1. Yorumları temizlemek için 'Kaldır' düğmesini tıklayın
1. Dosyayı anında indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Word Belge Yorumlarını C++ ile Sil" %}}

1. C++ projesine kitaplık referansı ekleme
1. Word Dosyasını Yükle
1. Parametre olarak NodeType::Comment'e sahip GetChildNodes'u kullanarak tüm düğümleri alın
1. Yorum koleksiyonunda NodeCollection.Clear'ı arayın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ Kodu: Word Dosyasından Yorumları Sil" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ ile Yorum Ekle" %}}

1. Document ve DocumentBuilder sınıfı nesnesi oluşturun
1. Veya Belgeyi yükleyin
1. Yorumu eklemek için Comment sınıfını kullanın
1. Parametre olarak comment obj ile AppendChild yöntemini kullanın
1. get_Paragraphs()->Add gibi ilgili yöntemi kullanın
1. Veya diğer yol, CommentRangeStart ve CommentRangeEnd sınıflarını kullanmaktır.
1. Dosyayı eklenen yorumlarla kaydetmek için kaydetme yöntemini çağırın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Tüm Yorumları Çıkart" %}}

1. Belge sınıfı nesnesi aracılığıyla Belgeyi Yükle
1. NodeCollection'daki tüm GetChildNode'ları alın
1. Her koleksiyonu yineleyin ve onlar hakkında bilgi toplayın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ Kodu : Word Dosyasına Yorum Ekle" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: Tüm Yorumları Çıkart" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>C++ ile Word Belge Açıklama Uygulamasını Geliştirin</h2>

Geri bildirimde bulunmak, önerilerde bulunmak veya belge üzerinde başkalarıyla işbirliği yapmak için bir Word açıklama uygulaması veya yardımcı programı geliştirmeniz mi gerekiyor?[Aspose.Words for C++](https://products.aspose.com/words/cpp/), [Aspose.Total for C++](https://products.aspose.com/total/tr/cpp/)'nin alt API'si olduğundan, herhangi bir C++ geliştiricisi yukarıdaki API kodunu kendi belge açıklama uygulamasına entegre edebilir.Güçlü C++ kitaplığı, herhangi bir belge açıklama çözümünün programlanmasına olanak tanır.Üstelik Word formatı da dahil olmak üzere birçok popüler formatı destekleyebilir.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word Dosyalarına Açıklama Eklemek için C++ Kitaplığı" %}}

Aspose.Words for C++'ı geliştirici ortamınıza kurmanın üç seçeneği vardır.Lütfen ihtiyaçlarınıza uygun olanı seçin ve adım adım talimatları izleyin:<br /><br />

- Install a [NuGet Paketi](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [Dokümantasyon](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Kitaplığı Visual Studio IDE içinde [Paket Yönetici Konsolu](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) kullanarak yükleyin
- Kitaplığı [Windows Yükleyici](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand) kullanarak elle yükleyin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}
Microsoft Windows, Linux ve macOS işletim sistemlerinde yazılım geliştirmek için bu C++ kitaplığını kullanabilirsiniz:<br /><br />

- Linux için GCC >= 6.3.0 ve Clang >= 3.9.1 gereklidir
- Xcode >= 12.5.1, macOS için Clang ve libc++ gereklidir

<br /><br />
Linux veya macOS için yazılım geliştiriyorsanız lütfen [Ürün Dokümantasyonu](https://docs.aspose.com/words/cpp/system-requirements/)'teki ek kitaplık bağımlılıkları (fontconfig ve mesa-glu açık kaynak paketleri) hakkındaki bilgileri kontrol edin.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="SSS" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>SSS</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Yukarıdaki C++ kodunu uygulamamda kullanabilir miyim?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Evet, bu kodu indirebilir ve C++ tabanlı belge açıklama uygulaması geliştirmek amacıyla kullanabilirsiniz.Bu kod, arka uç belge işleme ve işleme alanındaki projelerinizin işlevselliğini ve yeteneklerini geliştirmek için değerli bir kaynak görevi görebilir.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Bu çevrimiçi belge açıklaması uygulaması yalnızca Windows'ta mı çalışır?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows, Linux, Mac OS veya Android olsun, üzerinde çalıştığı işletim sisteminden bağımsız olarak herhangi bir cihazda yorumların kaldırılması için belge ek açıklaması başlatma esnekliğine sahipsiniz. Tek gereken çağdaş bir web tarayıcısı ve aktif bir internet bağlantısıdır.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Word belgesine açıklama eklemek için çevrimiçi uygulamayı kullanmak güvenli midir?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Elbette! Hizmetimiz aracılığıyla oluşturulan çıktı dosyaları, 24 saatlik bir süre içinde sunucularımızdan güvenli ve otomatik olarak kaldırılacaktır.Sonuç olarak, bu dosyalarla ilişkili görüntüleme bağlantıları bu sürenin sonunda artık işlevsel olmayacaktır.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Uygulamayı hangi tarayıcı kullanmalı?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Çevrimiçi Word belgesine açıklama eklemek için Google Chrome, Firefox, Opera veya Safari gibi herhangi bir modern web tarayıcısını kullanabilirsiniz.Ancak bir masaüstü uygulaması geliştiriyorsanız verimli yönetim için Aspose.Total belge işleme API'sini kullanmanızı öneririz.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}