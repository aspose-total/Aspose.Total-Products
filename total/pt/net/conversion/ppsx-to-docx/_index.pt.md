---
title: Converter PPSX para DOCX via C# .NET ou com o conversor online gratuito
description: Converta documentos ppsx do PowerPoint em arquivos docx do Word com C#. Converta vários arquivos no ASP.NET ou em outros aplicativos .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter PPSX para DOCX usando C# ou online" h2="Crie aplicativos de conversão de documentos do Microsoft PowerPoint PPSX Presentation para Word DOCX nas plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Como converter PPSX para DOCX usando C#" %}}

Para automatizar o processo de qualquer apresentação do PowerPoint ppsx para conversão em lote de arquivos docx do Word, usaremos [Aspose.Slides for .NET](https://products.aspose.com/slides/net) e [Aspose.Words para .NET](https://products.aspose.com/words/net) APIs. O primeiro é uma API de manipulação de apresentações do PowerPoint que permite criar ou modificar slides do Microsoft PowerPoint. Considerando que, o último é uma API de processamento de texto para processar ou manipular documentos do Microsoft Word. Ambas as APIs fazem parte do pacote [Aspose.Total for .NET](https://products.aspose.com/total/net). Você pode [baixar] diretamente (https://releases.aspose.com/) do Nuget ou pode usar os seguintes comandos do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do console do gerenciador de pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter PPSX em DOCX via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Adicione referência de Aspose.Slides para .NET e Aspose.Words para .NET
1. Carregue a apresentação do PowerPoint PPSX usando a classe [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Salve o documento no objeto [MemoryStream](https://docxs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0)
1. Crie [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) e inicialize-o com o objeto MemoryStream
1. Salve o documento usando [Aspose.Words.Document.Save("output.docx", SaveFormat.Docx)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou SO compatível com plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Ambiente de desenvolvimento como Microsoft Visual Studio.
- Aspose.Slides para .NET e Aspose.Words para .NET DLL referenciados em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este exemplo de código mostra como converter um PPSX em DOCX usando C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPSX file
Aspose.Slides.Presentation ppsx = new Aspose.Slides.Presentation("source.ppsx");

var stream = new MemoryStream();

ppsx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var docx = new Aspose.Words.Document(stream);
      
// Save the Word DOCX document
docx.Save("output.docx", Aspose.Words.SaveFormat.Docx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Conversor Online de PPSX para DOCX</h3>

<iframe title="Ferramenta on-line de conversão de docx para ppsx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=ppsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicativo gratuito para converter PPSX para DOCX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSX file." >}}

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
                          <span itemprop="name"><b>Como posso converter PPSX para DOCX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">O aplicativo online para conversão PPSX está integrado acima. Para usar o aplicativo, você pode adicionar seu arquivo PPSX arrastando e soltando-o na área designada ou clicando dentro da área para importar o arquivo. Depois que o arquivo for adicionado, clique no botão Converter para iniciar o processo de conversão. Após a conclusão da conversão de PPSX para DOCX, você pode baixar o arquivo recém-convertido com apenas um clique e ele estará disponível no formato DOCX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo leva para converter PPSX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">este conversor online é rápido, mas a velocidade da conversão de PPSX para DOCX depende principalmente do tamanho do arquivo PPSX que está sendo convertido. Arquivos PPSX menores podem ser renderizados no formato DOCX em segundos. Além disso, se você integrou o código de conversão PPSX para DOCX em um aplicativo .NET, a velocidade de conversão dependerá de quão bem você otimizou seu aplicativo para o processo de conversão.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>É seguro converter PPSX para DOCX usando o conversor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Claro! Assim que o processo de conversão de PPSX para DOCX estiver concluído, o link de download do arquivo DOCX convertido estará disponível instantaneamente. Todos os arquivos carregados, incluindo arquivos PPSX, são excluídos do sistema após 24 horas e os links de download deixam de funcionar após esse período. O conversor online garante a segurança e a privacidade de seus arquivos, e o aplicativo integrado está disponível gratuitamente para fins de teste. Isso permite que os usuários verifiquem o resultado antes de integrar o código em seus projetos.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Qual navegador devo usar para converter PPSX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Você pode utilizar qualquer navegador da web contemporâneo, como Google Chrome, Firefox, Opera ou Safari para converter arquivos PPSX em DOCX online. No entanto, se você estiver criando um aplicativo de desktop, a API de conversão Aspose.Total PPSX é recomendada para um processo de conversão suave e contínuo.</span>
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