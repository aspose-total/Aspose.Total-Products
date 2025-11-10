---
title: API Java para renderizar XSLFO para XLAM
description: Exporte XSLFO para XLAM via API Java sem usar o Microsoft Excel ou Adobe Reader
url_ignore: /pt/java/conversion/xslfo-to-xlam/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: XLAM
otherformats: XLSM XLTM XLTX FODS EXCEL XLAM SXC TXT TSV XLSB MD XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar XSLFO para XLAM via Java" h2="Converta o arquivo XSLFO para XLAM usando a API Java local em qualquer aplicativo Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ao usar o [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode integrar o recurso de conversão XSLFO para XLAM em seus aplicativos Java em um processo de duas etapas. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) você pode renderizar XSLFO para XLSX. Na segunda etapa, você pode converter XLSX para XLAM usando a API de programação de planilha [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter arquivo XSLFO para XLAM via Java" %}}
1. Abra o arquivo XSLFO usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta XSLFO para XLSX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o documento XLSX usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o documento no formato XLAM usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) em seu pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Se o seu documento XSLFO estiver protegido por senha, você não poderá convertê-lo em XLAM sem a senha. Usando a API, você pode primeiro abrir o documento protegido usando uma senha válida e convertê-lo depois. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter XSLFO Protegido para XLAM via Java" %}}
Ao converter o arquivo XSLFO para XLAM, você também pode adicionar marca d'água ao formato de arquivo XLAM de saída. Para adicionar uma marca d'água, crie uma nova pasta de trabalho para abrir o arquivo XLSX convertido. Selecione a Planilha por meio de seu índice, crie uma Forma e use sua função addTextEffect, defina cores, transparência e muito mais. Depois disso, você pode salvar seu documento XLSX como XLAM com marca d'água. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Converter XSLFO para **XLAM (Excel Add-In)** permite incorporar dados gerados por XSLFO e macros em add-ins do Excel reutilizáveis. XLAM suporta automação, relatórios personalizados e aplicativos de planilhas interativos.



{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}



* Empacotar modelos de relatórios XSLFO como add-ins do Excel para uso em equipe.

* Distribuir ferramentas de cálculo automatizadas derivadas de dados XSLFO.

* Integrar análises XSLFO em painéis personalizados do Excel.

* Possibilitar fluxos de trabalho de relatórios repetíveis com add-ins XLAM.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}



* Automatizar a geração de XLAM a partir de XSLFO para tarefas recorrentes.

* Implantação agendada de add-ins com dados XSLFO atualizados.

* Integração com automação de fluxo de trabalho baseada em VBA.

* Geração acionada de add-ins XLAM para ferramentas de relatórios corporativos.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}