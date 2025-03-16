---
title: API C# para exportar EMAIL para JPEG
description: Converta EMAIL para JPEG sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/email-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: PNG DOC DOT EMF FLATOPC ODT MD TIFF XPS DOCM EPUB TEXT WORDML JPEG DOTM OTT PDF SVG DOCX GIF RTF PCL PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL para JPEG via .NET" h2="API .NET para renderizar EMAIL para JPEG no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EMAIL para JPEG dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EMAIL para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EMAIL em JPEG" %}}
1. Abra o arquivo EMAIL usando a classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converta EMAIL para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato JPEG usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Jpeg como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EMAIL via .NET" %}}
Antes de converter EMAIL para JPEG, se você quiser ter certeza de que está convertendo o email correto, você pode carregar o documento EMAIL, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos JPEG via .NET" %}}
Ao salvar o documento de EMAIL para JPEG, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a JPEG mediante programación: casos de uso" %}}
Conversão de Arquivos de E-mail em Imagens em JPEG é uma Necessidade para Desbloquear o Potencial Visual

Arquivos de e-mail, que contêm dados de comunicação cruciais, podem ser convertidos eficientemente em imagens em JPEG, tornando-os ideais para representação visual estática e compartilhamento. No entanto, ao trabalhar com conteúdo dinâmico, as plataformas de mídia social como o Instagram se tornam essenciais para a narrativa visual e engajamento.

A conversão de arquivos de e-mail em formatos JPEG é necessária para desbloquear a plena capacidade do seu conteúdo visual e potencial de compartilhamento. Essa conversão permite:

**Usos Cases:**

*   **Partilha de Redes Sociais**: Converter arquivos de e-mail em imagens em JPEG criativas que podem ser compartilhadas em várias plataformas de mídia social, permitindo uma abordagem mais ampla.
*   **Visualização de Produtos com E-commerce**: Utilizar imagens em JPEG para mostrar detalhes, especificações e características dos produtos, melhorando a experiência de compra online.
*   **Promoção de Eventos e Anúncios**: Converter arquivos de e-mail em imagens em JPEG para promover eventos, produtos ou serviços, capturando atenção e gerando interesse.
*   **Visualização de Dados e Infográficos**: Utilizar imagens em JPEG para visualizar dados, estatísticas e informações, criando conteúdo informativo e envolvente para diferentes públicos.
*   **Campanhas de Marketing Digital**: Converter arquivos de e-mail em imagens em JPEG para criar visuais cativantes para campanhas de marketing, anúncios e materiais promocionais.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}