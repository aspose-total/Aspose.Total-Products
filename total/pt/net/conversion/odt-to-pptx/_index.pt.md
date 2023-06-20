---
title: Converter ODT para PPTX via C# .NET ou com o conversor online grátis
description: Converta documentos do Word em arquivos pptx do PowerPoint com C#. Converta vários arquivos no ASP.NET ou em outros aplicativos .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter ODT para PPTX usando C# ou online" h2="Crie aplicativos de conversão do Microsoft Word ODT para PowerPoint PPTX nas plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Como converter ODT para PPTX usando C#" %}}

Para automatizar o processo de qualquer arquivo de documento do Word para conversão em lote de apresentação do PowerPoint pptx, usaremos [Aspose.Words for .NET](https://products.aspose.com/words/net) e [Aspose.Slides para .NET](https://products.aspose.com/slides/net) APIs. O primeiro é uma API de processamento de texto para processar ou manipular documentos do Microsoft Word. Considerando que o último é uma API de manipulação de apresentação que permite criar ou modificar slides do Microsoft PowerPoint. Ambas as APIs fazem parte do pacote [Aspose.Total for .NET](https://products.aspose.com/total/net). Você pode [baixar] diretamente (https://releases.aspose.com/) do Nuget ou pode usar os seguintes comandos do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do console do gerenciador de pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter ODT em PPTX via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Adicione referência de Aspose.Total para .NET
1. Carregue o arquivo ODT usando a classe [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Salve o documento ODT em HTML
1. Crie um objeto [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importe o conteúdo HTML no quadro de texto de qualquer forma de slide dentro da apresentação
1. Salve o documento usando [Aspose.Slides.Presentation.Save("output.pptx", SaveFormat.Pptx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou SO compatível com plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Ambiente de desenvolvimento como Microsoft Visual Studio.
- Aspose.Words para .NET &amp; Aspose.Slides para .NET DLLs ou Aspose.Total para .NET DLL referenciados em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este exemplo de código mostra como converter um ODT em PPTX usando C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTX.

using (Presentation pptx = new Presentation()){

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

	// Save the PPTX Presentation
	pptx.Save("filepath\\pres.pptx", Aspose.Slides.Export.SaveFormat.Pptx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0">

<h3>Conversor Online de ODT para PPTX</h3>

<iframe title="Ferramenta on-line de conversão de pptx para odt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicativo gratuito para converter ODT para PPTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

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
              <h2>perguntas frequentes</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Como posso converter ODT para PPTX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">O aplicativo online para conversão ODT está integrado acima. Para usar este aplicativo, você pode adicionar seu arquivo ODT arrastando e soltando-o na área branca designada ou clicando dentro da área para importar o documento. Em seguida, pressione o botão Converter para iniciar o processo de conversão. Após a conclusão da conversão de ODT para PPTX, você pode baixar seu arquivo recém-convertido com apenas um clique e ele estará disponível para você na forma de um arquivo PPTX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo leva para converter ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Este conversor online opera rapidamente, mas depende principalmente do tamanho do arquivo ODT que está sendo convertido. Para pequenos arquivos ODT, a conversão para PPTX pode ser concluída em questão de segundos. No entanto, se você integrou o código de conversão em um aplicativo .NET, a velocidade de conversão dependerá de quão bem seu aplicativo foi otimizado para o processo de conversão.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>É seguro converter ODT para PPTX usando o conversor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Claro! Assim que a conversão de ODT para PPTX estiver concluída, o link de download do arquivo PPTX recém-convertido estará disponível instantaneamente. Ele também garante a segurança do processo de conversão, pois todos os arquivos enviados, incluindo arquivos ODT, são totalmente seguros e serão excluídos do sistema após 24 horas. Além disso, os links para download deixarão de funcionar após esse período, garantindo a privacidade e proteção de seus arquivos. O aplicativo integrado é gratuito e projetado para fins de teste, para que os usuários possam avaliar os resultados antes de integrar o código em seus projetos.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Qual navegador devo usar para converter ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Você pode usar qualquer navegador da Web moderno, como Google Chrome, Firefox, Opera ou Safari, para a conversão on-line de ODT para PPTX. No entanto, se você estiver desenvolvendo um aplicativo de desktop, a API Aspose.Total ODT Conversion é recomendada para um processamento suave e eficiente.</span>
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