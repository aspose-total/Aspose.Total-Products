---
title: API C# para exportar EMLX para PNG
description: Converta EMLX para PNG sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/emlx-to-png/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PNG
otherformats: PNG JPEG DOCX FLATOPC TEXT OTT XPS WORDML ODT DOTX EPUB DOC PS TIFF RTF GIF MD DOCM SVG EMF DOTM DOT PDF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMLX para PNG via .NET" h2="API .NET para renderizar EMLX para PNG no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EMLX para PNG dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EMLX para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EMLX em PNG" %}}
1. Abra o arquivo EMLX usando a classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converta EMLX para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato PNG usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Png como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EMLX via .NET" %}}
Antes de converter EMLX para PNG, se você quiser ter certeza de que está convertendo o emlx correto, você pode carregar o documento EMLX, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos PNG via .NET" %}}
Ao salvar o documento de EMLX para PNG, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMLX a PNG mediante programación: casos de uso" %}}
Arquivos EMF (Metafile Aumentado) são utilizados para armazenar informações de gráficos raster, tornando-os ideais para criar imagens estáticas e ilustrações. No entanto, ao trabalhar com dados dinâmicos, outros formatos de arquivo se tornam essenciais para a edição e manipulação de imagens.

A conversão de arquivos EMF em PNG é necessária para desbloquear o potencial máximo do seu software de edição e manipulação de imagens. Essa conversão permite que você:

**Cenários de Uso:**

*   **Edição e Manipulação de Imagens**: Converter arquivos EMF para editar e manipular imagens, adicionando texto, formas e efeitos.
*   **Design de Icones e Desenvolvimento**: Usar PNG para criar icones escaláveis, logotipos e gráficos para diferentes aplicativos.
*   **Gráficos e Ilustrações**: Converter arquivos EMF para criar ilustrações intrincadas, gráficos e animações que podem ser usadas em publicações.
*   **Otimização de Web e Móveis**: Usar PNG para otimizar imagens para dispositivos web e móveis, garantindo tempos de carga rápidos e visuals de alta qualidade.
*   **Visualização de Dados e Relatórios**: Converter arquivos EMF para criar visualizações interativas e relatórios, usando PNG para exibir visões de dados guiadas.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}