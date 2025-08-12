---
title: API Java para renderizar CGM para TSV
description: Exporte CGM para TSV via API Java sem usar o Microsoft Excel ou Adobe Reader
url_ignore: /pt/java/conversion/cgm-to-tsv/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TSV
otherformats: XLT ODS XLSB XLTM XLAM TXT SXC MD DIF FODS XLSM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar CGM para TSV via Java" h2="Converta o arquivo CGM para TSV usando a API Java local em qualquer aplicativo Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ao usar o [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode integrar o recurso de conversão CGM para TSV em seus aplicativos Java em um processo de duas etapas. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) você pode renderizar CGM para XLSX. Na segunda etapa, você pode converter XLSX para TSV usando a API de programação de planilha [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter arquivo CGM para TSV via Java" %}}
1. Abra o arquivo CGM usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta CGM para XLSX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o documento XLSX usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o documento no formato TSV usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) em seu pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Se o seu documento CGM estiver protegido por senha, você não poderá convertê-lo em TSV sem a senha. Usando a API, você pode primeiro abrir o documento protegido usando uma senha válida e convertê-lo depois. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter CGM Protegido para TSV via Java" %}}
Ao converter o arquivo CGM para TSV, você também pode adicionar marca d'água ao formato de arquivo TSV de saída. Para adicionar uma marca d'água, crie uma nova pasta de trabalho para abrir o arquivo XLSX convertido. Selecione a Planilha por meio de seu índice, crie uma Forma e use sua função addTextEffect, defina cores, transparência e muito mais. Depois disso, você pode salvar seu documento XLSX como TSV com marca d'água. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Transformar arquivos CGM (Computer Graphics Metafile) em formato TSV (Valores Separados por Tabulação) usando utilitários Java garante um alinhamento preciso das colunas e manipulação de dados amigável ao Unix. Isso é particularmente valioso em fluxos de trabalho de engenharia, onde as saídas de simulação e conjuntos de dados de medição precisam ser processados em ambientes de plataforma cruzada. As APIs de E/S do Java e as bibliotecas TSV permitem pipelines de conversão robustos e escaláveis de CGM para TSV que se encaixam perfeitamente nos processos ETL.

## ✅ Casos de Uso Principais
- Criar tabelas com colunas alinhadas a partir de dados de medição baseados em CGM.
- Exportar resultados de simulação para TSV para pesquisa e análise.
- Garantir compatibilidade com ferramentas de processamento de linha de comando Unix/Linux.
- Apoiar a troca de dados em aplicações de engenharia de código aberto.

## ⚙️ Cenários de Automação
- APIs de E/S do Java e bibliotecas TSV para transformações automatizadas de CGM para TSV.
- Conversão em lote sem interface de arquivos CGM técnicos para fluxos de trabalho de relatórios.
- Pipelines ETL de plataforma cruzada usando motores de processamento de dados baseados em Java.
- Integração com ambientes de computação científica e clusters de HPC.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}