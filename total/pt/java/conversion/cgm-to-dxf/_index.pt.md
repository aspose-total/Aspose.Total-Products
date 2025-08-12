---
title: Converter CGM para DXF via Java
description: Exporte o arquivo CGM para DXF em seus aplicativos Java sem usar nenhum aplicativo de terceiros
url_ignore: /pt/java/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter CGM para DXF via Java" h2="Exporte o arquivo CGM para DXF em qualquer aplicativo Java J2SE, J2EE, J2ME sem usar o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Você pode converter o arquivo cgm em imagem DXF em Java em duas etapas simples. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), você pode exportar CGM para JPEG. Depois disso, usando [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API de processamento de imagem, você pode renderizar JPEG para DXF. Ambas as APIs estão no pacote [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportar CGM para DXF via Java" %}}
1. Abra o arquivo CGM usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicialize o objeto de classe e renderize CGM para JPEG usando [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-)
3. Carregue o arquivo JPEG usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Salve o documento no formato DXF usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Converter CGM para DXF em um único arquivo via Java" %}}
A API também permite exportar o arquivo CGM para DXF para um único arquivo. Para converter todas as páginas, você pode primeiro renderizar seu documento CGM em um arquivo TIFF e depois exportar o arquivo TIFF para DXF. Você pode abrir o arquivo de entrada usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e criar objetos de dispositivo Resolution, TiffSettings e TIFF. Você pode obter uma única imagem TIFF usando [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) da classe [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Por fim, você pode carregar o arquivo TIFF usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) e salvá-lo no formato DXF usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter CGM para DXF com marca d'água via Java" %}}
Usando a API, você também pode exportar o arquivo CGM para DXF com marca d'água em seu documento DXF. Para adicionar uma marca d'água, você pode primeiro converter CGM para JPEG e adicionar uma marca d'água nele. Para adicionar marca d'água, carregue um arquivo de imagem usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), crie um objeto da classe [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialize-a com o objeto Image, crie uma nova [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) e defina a tradução e a transformação para o ângulo desejado e adicione marca d'água usando [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Depois de adicionar a marca d'água em sua imagem, você pode salvar o JPEG como formato DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter e girar CGM para arquivo DXF via Java" %}}
Usando a API, você também pode girar a imagem DXF de saída conforme suas necessidades. O método Image.rotateFlip pode ser usado para girar a imagem em 90/180/270 graus e virar a imagem horizontalmente ou verticalmente. A biblioteca fornece métodos simples para realizar operações complexas enquanto encapsula todos os detalhes feios. Você pode especificar o tipo de rotação e inversão para aplicar à imagem. Para girar e inverter a imagem, você pode carregar a imagem JPEG convertida usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) e chamar a classe Image. girarFlip enquanto especifica o [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) apropriado. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertendo arquivos **Computer Graphics Metafile (CGM)** para **DXF (Drawing Exchange Format)** é essencial em fluxos de trabalho de **CAD (Computer-Aided Design)** para garantir interoperabilidade perfeita entre sistemas de engenharia, arquitetura e manufatura. Em aplicações baseadas em **Java**, essa conversão permite que diagramas técnicos baseados em vetores de CGM sejam transformados em um formato CAD amplamente suportado, tornando-os editáveis, compartilháveis e compatíveis com ferramentas de design padrão da indústria. Isso é fundamental para design colaborativo, manufatura de precisão e arquivamento de desenhos técnicos.


## ✅ Principais Casos de Uso

- **Interoperabilidade de Design de Engenharia**  
  Compartilhe e edite designs baseados em CGM em ferramentas CAD que suportam DXF para colaboração entre plataformas.

- **Troca de Projetos de Manufatura**  
  Forneça equipes de produção com arquivos DXF derivados de diagramas CGM para usinagem CNC e fabricação.

- **Edição de Gráficos Vetoriais**  
  Transforme diagramas CGM em DXF para modificação direta em software CAD sem perda de fidelidade vetorial.


## ⚙️ Cenários de Automação

- **Ferramentas CAD Baseadas em Java**  
  Integre a conversão de CGM para DXF diretamente em aplicações de edição e visualização CAD baseadas em Java.

- **Conversores de Desenhos de Engenharia**  
  Use APIs Java para automatizar conversões em lote de CGM para DXF em grande escala para fluxos de trabalho multiprojeto.

- **Sistemas de Arquivamento CAD Automatizados**  
  Armazene designs CGM como arquivos DXF em arquivos de engenharia de longo prazo para reutilização futura e conformidade.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}