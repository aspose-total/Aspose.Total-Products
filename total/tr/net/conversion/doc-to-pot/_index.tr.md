---
title: DOC'yi C# .NET aracılığıyla POT'ye dönüştürün veya ücretsiz Çevrimiçi Dönüştürücü ile
description: C# ile Word doc belgelerini PowerPoint pot dosyalarına dönüştürün. ASP.NET veya diğer .NET uygulamaları içinde birden çok dosyayı dönüştürün.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C# kullanarak DOC'yi POT'ye dönüştürün veya çevrimiçi" h2=".NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında Microsoft Word DOC'den PowerPoint POT'ye dönüştürme uygulamaları oluşturun." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="C# Kullanarak DOC'u POT'ye Dönüştürme" %}}

Herhangi bir Word belgesi dosyasını PowerPoint pot sunum toplu dönüştürme işlemini otomatikleştirmek için [Aspose.Words for .NET](https://products.aspose.com/words/net) ve [Aspose.Slides] kullanacağız .NET için](https://products.aspose.com/slides/net) API'leri. İlki, Microsoft Word belgelerini işlemek veya işlemek için bir kelime işlem API'sidir. İkincisi, Microsoft PowerPoint slaytları oluşturmanıza veya değiştirmenize izin veren bir sunum işleme API'sidir. Her iki API de [Aspose.Total for .NET](https://products.aspose.com/total/net) paketinin bir parçasıdır. Nuget'ten doğrudan [indirebilir](https://releases.aspose.com/) veya Paket Yöneticisi Konsolundan aşağıdaki komutları kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="DOC'yi C# ile POT'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Total for .NET referansını ekleyin
1. DOC dosyasını [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
1. DOC belgesini HTML'ye kaydedin
1. [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) Nesnesi oluşturun
1. HTML içeriğini sunum içindeki herhangi bir slayt şeklinin metin çerçevesinde içe aktarın
1. Belgeyi [Aspose.Slides.Presentation.Save("output.pot", SaveFormat.Pot)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods) kullanarak kaydedin /5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi.
- Microsoft Visual Studio gibi geliştirme ortamı.
- Aspose.Words for .NET &amp; Projenizde referans verilen Aspose.Slides for .NET DLL'leri veya Aspose.Total for .NET DLL.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu kod örneği, C# kullanarak bir DOC'nin POT'ye nasıl dönüştürüleceğini gösterir." offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word DOC file
Aspose.Words.Document doc = new Aspose.Words.Document("sourceWordFile.doc");

// Save DOC file to HTML 
doc.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages DOC documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POT.

using (Presentation pot = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the POT Presentation
	pot.Save("filepath\\pres.pot", Aspose.Slides.Export.SaveFormat.Pot);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>DOC'den POT'e Çevrimiçi Dönüştürücü</h3>

<iframe title="doc'dan pot'ye Çevrimiçi Dönüştürme Aracı" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pot&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DOC'yi POT'ye Dönüştürmek için Ücretsiz Uygulama" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

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
                          <span itemprop="name"><b>DOC'yi Çevrimiçi POT'e nasıl dönüştürebilirim?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">DOC dönüştürme için Çevrimiçi Uygulama yukarıda entegre edilmiştir. Bu uygulamayı kullanmak için, DOC dosyanızı belirlenen beyaz alana sürükleyip bırakarak veya belgeyi içe aktarmak için alanın içine tıklayarak ekleyebilirsiniz. Ardından, dönüştürme işlemini başlatmak için Dönüştür düğmesine basın. DOC'den POT'e dönüştürme işlemi tamamlandıktan sonra, yeni dönüştürülen dosyanızı tek bir tıklamayla indirebilir ve bir POT dosyası biçiminde kullanımınıza sunulur.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>DOC'yi dönüştürmek ne kadar sürer?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bu çevrimiçi dönüştürücü hızlı çalışır ancak öncelikle dönüştürülmekte olan DOC dosyasının boyutuna bağlıdır. Küçük DOC dosyaları için POT'e dönüştürme birkaç saniye içinde tamamlanabilir. Ancak dönüştürme kodunu bir .NET uygulamasına entegre ettiyseniz dönüştürme hızı, uygulamanızın dönüştürme işlemi için ne kadar iyi optimize edildiğine bağlı olacaktır.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ücretsiz Aspose.Total dönüştürücü kullanarak DOC'yi POT'e dönüştürmek güvenli midir?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Elbette! DOC'den POT'e dönüştürme işlemi tamamlandıktan sonra, yeni dönüştürülen POT dosyasının indirme bağlantısı anında kullanılabilir olacaktır. DOC dosyaları da dahil olmak üzere yüklenen tüm dosyalar tamamen güvenli olduğundan ve 24 saat sonra sistemden silineceğinden, dönüştürme işleminin güvenliğini de sağlar. Ayrıca, indirme bağlantıları bu süreden sonra çalışmayı durdurarak dosyalarınızın gizliliğini ve korunmasını sağlar. Entegre uygulamanın kullanımı ücretsizdir ve kullanıcıların kodu projelerine entegre etmeden önce sonuçları değerlendirebilmesi için test amacıyla tasarlanmıştır.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>DOC'yi dönüştürmek için hangi tarayıcıyı kullanmalıyım?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Çevrimiçi DOC'den POT'e dönüştürme için Google Chrome, Firefox, Opera veya Safari gibi herhangi bir modern web tarayıcısını kullanabilirsiniz. Ancak bir masaüstü uygulaması geliştiriyorsanız sorunsuz ve verimli işleme için Aspose.Total DOC Conversion API önerilir.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}