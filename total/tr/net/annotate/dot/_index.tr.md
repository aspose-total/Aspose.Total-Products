---
title: DOT Annotation Online'ı kaldırın veya Ek Açıklamaları .NET aracılığıyla Yönetin
description: DOT dosyasındaki yorumları çevrimiçi uygulama aracılığıyla ücretsiz olarak silin.DOT dosyalarının yorumlarını yönetmek için .NET API kodu.

family: total
platformtag: net
feature: Annotate
informat: DOT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="DOT Document Online'dan Yorumları Temizle veya .NET aracılığıyla Yönetin" h2="Güçlü .NET tabanlı DOT belge açıklama yardımcı programı uygulaması geliştirin.DOT dosyasının yorumlarını .NET aracılığıyla yönetmek için listelenen kod." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOT Ek Açıklamalarını Çevrimiçi Kaldırma" %}}

1. Yorumları silmek için DOT dosyasını yükleyerek içe aktarın
1. Ek açıklama uygulamasının sürükle ve bırak yöntemiyle bırakma alanının içine tıklayarak bunu yapın
1. DOT dosyasının boyutuna ve internet hızına bağlı olarak birkaç saniye bekleyin
1. Yorumları temizlemek için 'Kaldır' düğmesini tıklayın
1. Dosyayı anında indirin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Belirli Yazarın DOT Belgesi Yorumlarını .NET aracılığıyla Silme" %}}

1. .NET projesine kitaplık referansı ekleme
1. Belge sınıfı nesnesi aracılığıyla Belgeyi Yükle
1. NodeType.Comment'e sahip GetChildNodes'u kullanarak tüm düğüm yorumlarını alın
1. Tüm yorumları yineleyin ve yazarın adıyla eşleştirin
1. Belirli yazar yorumunu silmek için Kaldır yöntemini çağırın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C# Kodu: DOT Dosyasından Belirli Yazar Yorumlarını Sil" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET aracılığıyla Yorum Ekle" %}}

1. Belge sınıfı nesnesi oluştur
1. Yorum sınıfını kullanma
1. Paragrafları kullanarak yeni paragrafı ekleyin.Add
1. FirstParagraph.Runs'u kullanın. Yorumu ekleyin
1. Veya diğer yol, CommentRangeStart ve CommentRangeEnd sınıflarını kullanmaktır.
1. Dosyayı eklenen yorumlarla kaydetmek için kaydetme yöntemini çağırın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Tüm Yorumları Çıkart" %}}

1. Belge sınıfı nesnesi aracılığıyla Belgeyi Yükle
1. ArrayList nesnesi oluşturma
1. NodeCollection'daki tüm GetChildNode'ları alın
1. Her koleksiyonda yineleme yapın ve ArrayList'e yorumlar ekleyin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET Kodu : DOT Dosyasından Yorum Ekle" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: Tüm Yorumları Çıkart" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>.NET Üzerinden DOT Belge Açıklama Uygulamasını Geliştirin</h2>

Geri bildirimde bulunmak, önerilerde bulunmak veya belge üzerinde başkalarıyla işbirliği yapmak için bir DOT açıklama uygulaması veya yardımcı programı geliştirmeniz mi gerekiyor?[Aspose.Total for .NET](https://products.aspose.com/total/net/)'nin alt API'si olan [Aspose.Words for .NET](https://products.aspose.com/words/net/) ile herhangi bir .NET geliştiricisi yukarıdaki API kodunu kendi belge açıklama uygulamasına entegre edebilir.Güçlü .NET kitaplığı, herhangi bir belge açıklama çözümünün programlanmasına olanak tanır.Üstelik DOT formatı da dahil olmak üzere birçok popüler formatı destekleyebilir.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOT Dosyalarına Açıklama Eklemek için .NET Kitaplığı" %}}

Sisteminize "Aspose.Words for .NET" veya "Aspose.Total for .NET" yüklemek için üç alternatif seçenek vardır.Lütfen ihtiyaçlarınıza uygun olanı seçin ve adım adım talimatları izleyin:<br /><br />

- Bir [NuGet Package](https://www.nuget.org/packages/Aspose.Words/) yükleyin. [Documentation](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)'a bakın
- Kitaplığı Visual Studio IDE'de [Package Manager Console](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) kullanarak yükleyin
- Kitaplığı [Windows Installer](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer) kullanarak elle yükleyin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

Ürünümüz tamamen platformlar arasıdır ve '.NET Standard 2.0' spesifikasyonunu takip eden tüm önemli .NET uygulamalarını destekler:<br /><br />

- Microsoft .NET Framework, en eski 2.0 sürümünden başlayıp en son '.NET Framework 4.8' ile biten
- .NET Core, en eski 2.0 sürümünden başlayıp en son '.NET 6' ile biten
- Mono >= 2.6.7
<br /><br />
.NET kodu, temel donanıma veya işletim sistemine bağlı olmadığından, yalnızca bir Sanal Makineye dayandığından, Windows, macOS, Android, iOS ve Linux için her türlü yazılımı geliştirmekte özgürsünüz.İlgili .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin sürümünü yüklediğinizden emin olun.<br /><br />
C#, F#, VB.NET uygulamaları oluşturmak için Microsoft Visual Studio, Xamarin ve MonoDevelop IDE'yi kullanmanızı öneririz.
<br /><br />
Daha fazla ayrıntı için lütfen [Product Documentation](https://docs.aspose.com/words/net/system-requirements/)'e bakın.

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
                          <span itemprop="name"><b>Yukarıdaki .NET kodunu uygulamamda kullanabilir miyim?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Evet, bu kodu indirebilir ve .NET tabanlı belge açıklama uygulaması geliştirmek amacıyla kullanabilirsiniz.Bu kod, arka uç belge işleme ve işleme alanındaki projelerinizin işlevselliğini ve yeteneklerini geliştirmek için değerli bir kaynak görevi görebilir.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Bu çevrimiçi belge açıklaması uygulaması yalnızca Windows'ta mı çalışır?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Windows, Linux, Mac OS veya Android olsun, üzerinde çalıştığı işletim sisteminden bağımsız olarak herhangi bir cihazda yorumların kaldırılması için belge ek açıklaması başlatma esnekliğine sahipsiniz.Tek gereken çağdaş bir web tarayıcısı ve aktif bir internet bağlantısıdır.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>DOT belgesine açıklama eklemek için çevrimiçi uygulamayı kullanmak güvenli midir?</b></span>
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
                          <span itemprop="text">Çevrimiçi DOT belgesine açıklama eklemek için Google Chrome, Firefox, Opera veya Safari gibi herhangi bir modern web tarayıcısını kullanabilirsiniz.Ancak bir masaüstü uygulaması geliştiriyorsanız verimli yönetim için Aspose.Total belge işleme API'sini kullanmanızı öneririz.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}