---
title: WORD'yi C++ ile PPSM'ye dönüştürün veya ücretsiz Çevrimiçi Dönüştürücü ile
description: Microsoft Word of PowerPoint kullanmadan C++ uygulamalarınızda WORD'yi PPSM'ye aktarın veya çevrimiçi. Kodu entegre etmeden önce ücretsiz WORD'den PPSM'e çevrimiçi dönüştürücüyü hızlı bir şekilde test edin.

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: PPSM
otherformats: PPTX PPTM PPS POTX ODP PPT PPSX POWERPOINT POT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="WORD'yi PPSM'ye Dönüştürmek için C++ API veya Çevrimiçi Uygulama" h2="Microsoft Word&reg; kullanmadan C++ uygulamalarınız içinde WORD'yi PPSM'ye aktarın veya PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/), iki API'sini kullanırken WORD'den PPSM'ye dönüştürmeyi otomatikleştirmeye izin veren güçlü dosya otomasyon API'lerinden oluşur. [Aspose.Words for C++](https://products.aspose.com/words/cpp/) kullanarak WORD'nizi yükleyin ve HTML'ye dönüştürün, ardından HTML'yi PowerPoint manipülasyonu C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) yeni bir sunum oluşturun ve PPSM olarak kaydedin. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++'da WORD'den PPSM'ye Dönüştürme" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.wordument) sınıf referansını kullanarak WORD dosyasını açın
2. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_stdbasicostream_saveoptions) üye işlevini kullanarak WORD'yi HTML'ye dönüştürün
3. Yeni bir [Sunum](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) nesnesini başlatın
4. Slaytınıza bir Otomatik Şekil ekleyin ve buna AddTextFrame ekleyin
5. HTML içeriğini yükleyin ve Sunum dosyanıza yazın
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) yöntemini kullanarak belgeyi PPSM formatına kaydedin ve Ppsm'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORD file with an instance of Wordument
Wordument wordument = new Wordument("template.wordx");
System::SharedPtr<Wordument> word = System::MakeObject<Wordument>(u"sourceFile.wordx");
// save the wordument in HTML file format
word->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>WORD'den PPSM'e Ücretsiz Çevrimiçi Dönüştürücü</h3>

<iframe title="docx'dan ppsm'ye Çevrimiçi Dönüştürme Aracı" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppsm&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Parola Korumalı WORD Belgesini C++ ile Yükleyin" %}}
Belge dönüştürmenin yanı sıra, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, C++ geliştiricileri için tonlarca belge işleme özelliğine izin verir. Microsoft Word WORD dosya biçiminiz parola korumalıysa, API'yi kullanarak yine de açabilirsiniz. Şifrelenmiş belgeyi yüklemek için, bir [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) nesnesini kabul eden özel bir kurucu aşırı yüklemesi kullanabilirsiniz. Bu nesne, parola dizesini belirten Parola özelliğini içerir.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordument, the password is passed to the wordument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordPassword");
// load the wordument from the local file system by filename:
SharedPtr<Wordument> word = MakeObject<Wordument>(u"Encrypted.wordx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ ile PPSM Belgesine Yorum Ekleme" %}}
WORD'yi PPSM olarak kaydederken, PPSM belgenize daha fazla özellik eklemek için [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) kullanabilirsiniz. Örneğin, sunumunuza yorum ekleyebilirsiniz. Sunum slayt yorumu belirli bir yazarla ilişkilendirilir. Presentation sınıfı, ICommentAuthorCollection'da slayt yorumları eklemekten sorumlu yazarların koleksiyonunu tutar. Her yazar için ICommentCollection'da bir yorum koleksiyonu vardır.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Sıkça Sorulan Sorular</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>WORD'yi Çevrimiçi PPSM'e nasıl dönüştürebilirim?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">WORD dönüştürme için çevrimiçi uygulamayı yukarıda bulabilirsiniz. Dönüştürme işlemini başlatmak için WORD dosyasını sürükleyip bırakarak veya beyaz alanın içine tıklayarak belgeyi içe aktararak ekleyebilirsiniz. Dosyayı ekledikten sonra, "Dönüştür" düğmesini tıklamanız yeterlidir. WORD'den PPSM'e dönüştürme işlemi tamamlandıktan sonra, dönüştürülen dosyanızı tek bir tıklama ile indirebilirsiniz.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>WORD'yi dönüştürmek ne kadar sürer?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bu çevrimiçi dönüştürücünün hızı büyük ölçüde dönüştürülmekte olan WORD dosyasının boyutuna bağlıdır. Küçük WORD dosyaları sadece birkaç saniye içinde PPSM'e dönüştürülebilir. Dönüştürme kodunu bir C++ uygulamasında kullanıyorsanız dönüştürme hızı, uygulamanızı ne kadar iyi optimize ettiğinize bağlı olacaktır.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ücretsiz Aspose.Total dönüştürücü kullanarak WORD'yi PPSM'e dönüştürmek güvenli midir?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Elbette! WORD dosyanız çevrimiçi dönüştürücümüz kullanılarak PPSM'e dönüştürüldükten sonra, PPSM dosyasının indirme bağlantısı hemen kullanılabilir olacaktır. Yüklediğiniz dosyaların güvenliğini ve gizliliğini ciddiye alıyor ve dönüştürme işlemi tamamlandıktan 24 saat sonra siliyoruz. Hiç kimsenin dosyalarınıza erişemeyeceğinden emin olabilirsiniz. WORD dönüştürme dahil dönüştürme işlemimiz tamamen güvenlidir. Kodu entegre etmeden önce sonuçları doğrulayabilmeniz için test amacıyla ücretsiz bir uygulama sunuyoruz.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>WORD'yi dönüştürmek için hangi tarayıcıyı kullanmalıyım?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Çevrimiçi WORD dönüşümü için Google Chrome, Firefox, Opera veya Safari gibi herhangi bir modern tarayıcıyı kullanabilirsiniz. Ancak bir masaüstü uygulaması geliştiriyorsanız sorunsuz performans için Aspose.Total WORD Conversion API önerilir.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}