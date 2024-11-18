---
title: Exportar XLSX para POWERPOINT no Android ou com o conversor online gratuito
description: API do Android para converter XLSX para POWERPOINT sem usar o Microsoft Word ou on-line. Teste o conversor online gratuito de XLSX para POWERPOINT rapidamente antes de integrar o código.

family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: POWERPOINT
otherformats: DOC WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderize XLSX para POWERPOINT no Android via Java ou aplicativo on-line" h2="Transforme XLSX em POWERPOINT em seus aplicativos Android sem usar o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) é um pacote de poderosas APIs de automação de arquivos. Ao usar duas de suas APIs, você pode integrar o recurso de conversão de XLSX para POWERPOINT dentro de seus aplicativos Android. Na primeira etapa, você pode exportar XLSX para PDF usando [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Depois disso, usando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), você pode converter PDF para POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API do Android para exportar XLSX para POWERPOINT" %}}
1. Abra o arquivo XLSX usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Converta XLSX para PDF e defina SaveFormat para AUTO
3. Carregue o arquivo PDF convertido usando a classe [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Salve o powerpointumento no formato POWERPOINT usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total for Android via Java diretamente do [Maven](https://releases.aspose.com/total/java/) e instale [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) e [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) em seus aplicativos.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Conversor Online Gratuito de XLSX para POWERPOINT</h3>

<iframe title="Ferramenta on-line de conversão de pptx para xlsx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Remover propriedades personalizadas do arquivo XLSX no Android via Java" %}}
Além da conversão de powerpointumentos, o [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) também oferece vários outros recursos. Antes do processo de conversão, você pode remover as propriedades personalizadas do powerpointumento XLSX. Para remover propriedades personalizadas, chame o método [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) e passe o nome de a propriedade do powerpointumento a ser removida.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
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
                          <span itemprop="name"><b>Como posso converter XLSX para POWERPOINT Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">O aplicativo online para conversão XLSX está integrado acima. Para iniciar o processo de conversão de XLSX para POWERPOINT, o primeiro passo é importar seu arquivo XLSX. Isso pode ser feito de duas maneiras: você pode arrastar e soltar o arquivo XLSX na ferramenta de conversão ou clicar dentro da área branca da ferramenta para navegar em seu computador e selecionar o arquivo XLSX que deseja converter. Depois de importar o arquivo XLSX com sucesso, você precisará clicar no botão Converter para iniciar o processo de conversão. <br />
Durante o processo de conversão, o arquivo XLSX será transformado em um arquivo POWERPOINT. A ferramenta de conversão fará sua mágica e, quando o processo for concluído, você poderá baixar seu arquivo POWERPOINT recém-convertido. Isso significa que você pode facilmente obter arquivos POWERPOINT de saída com apenas um clique, sem a necessidade de nenhum software complicado ou conhecimento técnico.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo leva para converter XLSX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Uma das principais características deste conversor online de XLSX para POWERPOINT é sua rápida velocidade de conversão. No entanto, a velocidade do processo de conversão depende principalmente do tamanho do arquivo XLSX que você deseja converter. Se você estiver trabalhando com um arquivo XLSX de tamanho pequeno, pode esperar que o processo de conversão seja concluído em apenas alguns segundos.<br />

Além disso, se você integrou o código de conversão em um aplicativo Android App, a velocidade do processo de conversão dependerá de como você otimizou seu aplicativo. Se seu aplicativo for bem otimizado e tiver sido projetado para lidar com o processo de conversão com eficiência, a velocidade de conversão será mais rápida. Por outro lado, se seu aplicativo não for otimizado para essa finalidade, o processo de conversão pode demorar mais para ser concluído.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>É seguro converter XLSX para POWERPOINT usando o conversor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Claro! O link de download dos arquivos POWERPOINT estará disponível instantaneamente após a conversão. Em nosso conversor de XLSX para POWERPOINT, levamos sua privacidade e segurança a sério. Entendemos que seus arquivos contêm informações confidenciais e pessoais, e é por isso que implementamos várias medidas para garantir que seus arquivos estejam seguros e protegidos.<br />

Em primeiro lugar, excluímos automaticamente todos os arquivos enviados após 24 horas. Isso significa que, assim que o processo de conversão for concluído e você baixar o arquivo convertido, excluiremos o arquivo XLSX original e o arquivo POWERPOINT resultante de nossos servidores. Além disso, os links de download de seus arquivos deixarão de funcionar após 24 horas, garantindo que seus arquivos não sejam acessíveis a ninguém após esse período.<br />

Também tomamos medidas para garantir que seus arquivos sejam protegidos contra acesso não autorizado. Ninguém tem acesso aos seus arquivos durante ou após o processo de conversão, e toda transmissão de dados entre seu computador e nossos servidores é criptografada e segura.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Qual navegador devo usar para converter XLSX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Este conversor online de XLSX para POWERPOINT pode ser acessado através de qualquer navegador moderno, como Google Chrome, Firefox, Opera ou Safari. Isso significa que você pode facilmente usar esta ferramenta em qualquer dispositivo com conexão à internet, sem a necessidade de nenhum software especializado ou conhecimento técnico.<br />

No entanto, se você estiver desenvolvendo um aplicativo de desktop e precisar converter arquivos XLSX em arquivos POWERPOINT, recomendamos o uso da API de conversão Aspose.Total XLSX. Essa API fornece uma maneira fácil e eficiente de converter arquivos XLSX em arquivos POWERPOINT em seu aplicativo de desktop. A API de conversão Aspose.Total XLSX foi projetada para ser fácil de usar e integrar em seu aplicativo e fornece um processo de conversão rápido e confiável.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}