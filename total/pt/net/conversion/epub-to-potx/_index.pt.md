---
title: Exportar EPUB para POTX via API C#
description: API .NET para converter EPUB em POTX sem usar o Microsoft Word
url_ignore: /pt/net/conversion/epub-to-potx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POTX
otherformats: PPTM POTX PPT XAML POTM OTP PPSM PPS POWERPOINT PPSX SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar EPUB para POTX via .NET" h2="API .NET para exportar EPUB para POTX no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar EPUB para POTX em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo EPUB em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para POTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter EPUB em POTX" %}}
1. Abra o arquivo EPUB usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta EPUB para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato POTX usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Potx` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo EPUB via .NET" %}}
Ao converter EPUB para POTX, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo EPUB. Para obter os metadados de um arquivo EPUB, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo EPUB de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo POTX somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo POTX como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potx", SaveFormat.Potx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EPUB a POTX mediante programación: casos de uso" %}}
Arquivos EPUB (Publicação Eletrônica) são amplamente utilizados para armazenar conteúdo digital, incluindo livros eletrônicos, artigos e documentos. No entanto, quando se trata de apresentar informações em formato estruturado, o PowerPoint (.potx) se torna uma escolha ideal devido à sua natureza interativa e envolvente.

A conversão de arquivos EPUB para formatos .potx é necessária para desbloquear a potencial completa das capacidades de apresentação. Essa conversão permite que você:

*   **Apresentações Acadêmicas**: Converter arquivos EPUB para criar apresentações interativas, destacando achados-chave e compartilhando pesquisas com colegas.
*   **Comunicação Corporativa**: Usar o PowerPoint para apresentar atualizações da empresa, lançamentos de produtos e tendências do setor de forma envolvente.
*   **Materiais de Treinamento**: Converter arquivos EPUB para criar sessões de treinamento interativas, tornando informações complexas mais acessíveis e fáceis de entender.
*   **Publicação Digital**: Usar .potx para publicar conteúdo online, como blogs, artigos e tutoriais, com elementos multimídia como imagens, vídeos e animações.
*   **Recursos Educacionais**: Converter arquivos EPUB para criar materiais educacionais interativos, incluindo planos de aula, estudos de caso e guias de estudo.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}