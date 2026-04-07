---
title: Převést XPS na EML v Pythonu
description: Ukládejte XPS do EML v aplikacích Python bez použití Microsoft Word nebo Outlook

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte XPS na EML pomocí Pythonu" h2="Převod XPS na EML ve vašich aplikacích Python bez instalace Microsoft Word<sup>&reg;</sup> nebo Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pro vývojáře Pythonu, který se snaží přidat do aplikace funkci převodu XPS na EML? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API může pomoci automatizovat proces převodu. Je to úplný balík různých rozhraní API zabývajících se různými formáty, včetně formátů E-mail, Obrázky a Microsoft Word. Rozhraní API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) a [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/), která jsou součástí balíčku [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), usnadňují tento převod pomocí Pythonu. Jedná se o dvoukrokový proces, nejprve načtěte soubor XPS a vykreslete jej do HTML pomocí [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Za druhé načtěte převedený HTML pomocí [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) a uložte jej do formátu EML.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést XPS na EML v Pythonu" %}}

- Otevřete zdrojový soubor XPS pomocí třídy [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Zavolejte metodu `save`, přičemž jako parametr zadejte cestu k výstupnímu souboru HTML a příslušné možnosti uložení HTML. Váš soubor XPS je tedy převeden na HTML v zadané cestě
- Nyní načtěte uložený soubor HTML pomocí MailMessage.load
- Zavolejte metodu uložení s příslušnou cestou k souboru. Takže nakonec je XPS převeden

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

- Pro převod XPS na EML je vyžadován Python 3.5 nebo novější
- Referenční API v rámci projektu přímo z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) a [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Nebo použijte následující příkaz pip ```pip install aspose.words``` a ```pip install Aspose.Email-for-Python-via-NET``` 
- Kromě toho operační systém založený na Microsoft Windows nebo Linux (viz více [Words](https://docs.aspose.com/words/python-net/system-requirements/) a [Email](https://docs.aspose.com/email/python-net/system-requirements/)) a pro Linux zkontrolujte další požadavky pro gcc a libpython a postupujte podle pokynů krok za krokem [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Uložit XPS do EML v Pythonu" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

XPS to EML conversion with Python APIs allows fixed-layout documents to be transformed into standard email message files that are widely used for message storage, exchange, and archival. This is especially useful when document content must be preserved in a portable email format for downstream communication, review, or compliance use cases.

Z pohledu automatizace zlepšují pracovní postupy XPS na EML konzistenci v dokumentově řízeném zasílání zpráv, snižují ruční přípravu a podporují škálovatelnou integraci mezi systémy pro dokumenty, nástroji pro zpracování pošty a archivními prostředími.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové případy použití" %}}

* **Portable Email Message Creation**  
  Converts XPS documents into EML files for standardized storage and transfer across compatible systems.

* **Document Archiving in Mail Format**  
  Helps preserve document content as email messages for regulated retention and future retrieval.

* **Interoperable Message Exchange**  
  Enables easier movement of converted messages between platforms that support standard email file formats.

* **Review and Approval Flows**  
  Supports workflows where document content must be shared as message files for validation or sign-off.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénáře automatizace" %}}

* **Batch Document-to-Message Conversion**  
  Automated jobs can convert large volumes of XPS files into EML for consistent downstream handling.

* **System-Generated Record Packaging**  
  Applications can convert generated XPS outputs into EML files as part of record management workflows.

* **Mail Archive Ingestion**  
  Converted EML files can be programmatically routed into archive or indexing systems for retention.

* **Workflow-Based Message Export**  
  Dynamic pipelines can create EML outputs when documents reach a defined stage in processing.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}