---
title: .NET ile ODS'yi POWERPOINT'ye dönüştürün veya ücretsiz Çevrimiçi Dönüştürücü ile
description: .NET Framework, .NET Core, Mono veya Xamarin Platformlarında ODS'yi POWERPOINT'ye dönüştürün veya çevrimiçi. Kodu entegre etmeden önce ücretsiz CSV'den DOC'e çevrimiçi dönüştürücüyü hızlı bir şekilde test edin.

family: total
platformtag: net
feature: conversion
informat: ODS
outformat: PPTX
otherformats: DOC PPTX WORD DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="C# ile ODS'yi POWERPOINT'ye dönüştürün veya Çevrimiçi Uygulama" h2="Excel'i Dışa Aktar&reg; .NET Framework, .NET Core, Mono veya Xamarin Platformlarında ODS'den POWERPOINT'ye">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET'te ODS'den POWERPOINT'ye Dönüştürme" %}}
1. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) sınıfını kullanarak ODS dosyasını açın
2. ODS'yi PDF'ye dönüştürün ve SaveFormat'ı Otomatik olarak ayarlayın
3. Dönüştürülen PDF dosyasını [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument) sınıfını kullanarak yükleyin
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) yöntemini kullanarak dokümanı POWERPOINT formatına kaydedin ve Dokümanı SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="ODS'den POWERPOINT'ye Dönüştürme için .NET C# Kodu" gistPath="" %}}
```cs
// load the ODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.ods");
// save ODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ODS'den POWERPOINT'e Ücretsiz Çevrimiçi Dönüştürücü</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=ods" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

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
                          <span itemprop="name"><b>ODS'yi Çevrimiçi POWERPOINT'e nasıl dönüştürebilirim?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ODS dönüştürme için Çevrimiçi Uygulama yukarıda entegre edilmiştir. Dönüştürme işlemini başlatmak için ODS dosyanızı sürükleyip bırakabilir veya belgeyi içe aktarmak için belirlenen alanın içine tıklayabilirsiniz. Ardından, ODS'den POWERPOINT'e dönüştürmeyi başlatmak için "Dönüştür" düğmesine tıklayın. İşlem tamamlandıktan sonra, dönüştürülen dosyanızı tek bir tıklamayla kolayca indirebilir ve istediğiniz çıktıyı POWERPOINT formatında elde edebilirsiniz.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ODS'yi dönüştürmek ne kadar sürer?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bu çevrimiçi dönüştürücünün hızı hızlıdır, ancak öncelikle ODS dosyasının boyutuna bağlıdır. Küçük bir ODS dosyanız varsa, birkaç saniye içinde POWERPOINT'e dönüştürülebilir. Ayrıca, dönüştürme kodunu .NET uygulamanıza entegre ettiyseniz, dönüştürme işleminin hızı, uygulamanızı ne kadar iyi optimize ettiğinize bağlıdır.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ücretsiz Aspose.Total dönüştürücü kullanarak ODS'yi POWERPOINT'e dönüştürmek güvenli midir?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Elbette! ODS'den POWERPOINT'e dönüştürme işlemi tamamlandıktan sonra, POWERPOINT dosyaları için indirme bağlantısı hemen oluşturulur. Dosyalarınızın güvenliğini ön planda tutuyoruz, bu nedenle yüklenen tüm dosyalar 24 saat sonra silinir ve indirme linkleri bu süre sonunda çalışmayı durdurur. ODS dosyaları da dahil olmak üzere dönüştürme işlemi sırasında dosyalarınızın güvende olduğundan emin olabilirsiniz. Yukarıdaki ücretsiz uygulama test amaçlıdır ve kodu entegre etmeden önce sonucu kontrol etmenizi sağlar.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ODS'yi dönüştürmek için hangi tarayıcıyı kullanmalıyım?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Çevrimiçi ODS'den POWERPOINT'e dönüştürme için Google Chrome, Firefox, Opera, Safari gibi herhangi bir güncel web tarayıcısını kullanma esnekliğine sahipsiniz. Ancak bir masaüstü uygulaması oluşturuyorsanız Aspose.Total ODS Conversion API'yi sorunsuz bir şekilde entegre edebilirsiniz.</span>
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