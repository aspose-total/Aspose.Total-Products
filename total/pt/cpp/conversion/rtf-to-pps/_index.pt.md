---
title: Converter RTF para PPS via C++ ou com o conversor online grátis
description: Exporte RTF para PPS em seus aplicativos C++ sem usar o Microsoft Word do PowerPoint ou on-line. Teste o conversor online gratuito de POT para CSV rapidamente antes de integrar o código.

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: PPS
otherformats: PPT PPSM POTM POTX ODP PPSX POT POWERPOINT PPTM PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para converter RTF em PPS ou aplicativo on-line" h2="Exporte RTF para PPS em seus aplicativos C++ sem usar o Microsoft Word&reg; ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consiste em poderosas APIs de automação de arquivos que permitem automatizar a conversão de RTF para PPS usando duas de suas APIs. Carregue seu RTF usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) e converta-o em HTML, depois carregue o HTML via API C++ de manipulação do PowerPoint [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para criar uma nova apresentação e salvá-la como PPS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversão de RTF para PPS em C++" %}}
1. Abra o arquivo RTF usando a referência de classe [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)
2. Converta RTF para HTML usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_stdbasicostream_saveoptions)
3. Inicialize um novo objeto [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Adicione uma AutoForma em seu slide e adicione AddTextFrame nele
5. Carregue o conteúdo HTML e escreva-o em seu arquivo de apresentação
6. Salve o rtfumento no formato PPS usando o método [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina Pps como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load RTF file with an instance of Rtfument
Rtfument rtfument = new Rtfument("template.rtf");
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"sourceFile.rtf");
// save the rtfument in HTML file format
rtf->Save(u"HtmlOutput.HTML");
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Conversor Online Gratuito de RTF para PPS</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pps&from=rtf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Carregar rtfumento RTF protegido por senha via C++" %}}
Além da conversão de rtfumentos, a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite vários recursos de manipulação de rtfumentos para desenvolvedores de C++. Caso seu formato de arquivo RTF do Microsoft Word seja protegido por senha, você ainda pode abri-lo usando a API. Para carregar o rtfumento criptografado, você pode usar uma sobrecarga de construtor especial, que aceita um objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contém a propriedade Password, que especifica a string de senha.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected rtfument, the password is passed to the rtfument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"rtfPassword");
// load the rtfument from the local file system by filename:
SharedPtr<Rtfument> rtf = MakeObject<Rtfument>(u"Encrypted.rtf", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adicionar comentários no rtfumento PPS via C++" %}}
Ao salvar o RTF como PPS, você também pode usar o [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para adicionar mais recursos ao seu rtfumento PPS. Por exemplo, você pode adicionar comentários em sua apresentação. O comentário do slide da apresentação está associado a um autor específico. A classe Presentation contém a coleção de autores em ICommentAuthorCollection que são responsáveis por adicionar comentários ao slide. Para cada autor, há uma coleção de comentários em ICommentCollection.
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);  
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
              <h2>perguntas frequentes</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Como posso converter RTF para PPS Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Você pode encontrar o aplicativo online para conversão RTF acima. Para iniciar o processo de conversão, você pode adicionar o arquivo RTF arrastando e soltando ou clicando dentro da área branca para importar o documento. Depois de adicionar o arquivo, basta clicar no botão "Converter". Após a conclusão da conversão de RTF para PPS, você pode baixar o arquivo convertido com apenas um clique.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo leva para converter RTF?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">A velocidade deste conversor online depende muito do tamanho do arquivo RTF que está sendo convertido. Pequenos arquivos RTF podem ser convertidos em PPS em apenas alguns segundos. Se você estiver usando o código de conversão em um aplicativo C++, a velocidade de conversão dependerá de quão bem você otimizou seu aplicativo.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>É seguro converter RTF para PPS usando o conversor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Claro! Depois que seu arquivo RTF for convertido em PPS usando nosso conversor online, o link para download do arquivo PPS estará imediatamente disponível. Levamos a sério a segurança e a privacidade de seus arquivos enviados e os excluímos 24 horas após a conclusão do processo de conversão. Fique tranquilo, ninguém terá acesso aos seus arquivos. Nosso processo de conversão, incluindo conversão RTF, é totalmente seguro. Fornecemos um aplicativo gratuito para fins de teste para que você possa verificar os resultados antes de integrar o código.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Qual navegador devo usar para converter RTF?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Para conversão RTF online, você pode usar qualquer navegador moderno, como Google Chrome, Firefox, Opera ou Safari. No entanto, se você estiver desenvolvendo um aplicativo de desktop, a API de conversão Aspose.Total RTF é recomendada para um desempenho suave.</span>
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