---
title: Konwertuj PNG na EMLX w Pythonie
description: Zapisuj PNG do EMLX w aplikacjach Pythona bez używania Microsoft Word lub Outlook

family: total
platformtag: Python
feature: conversion
informat: PNG
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj PNG na EMLX za pomocą Pythona" h2="Konwersja PNG na EMLX w aplikacjach Pythona bez instalowania Microsoft Word<sup>&reg;</sup> lub Outlooka." >}}

{{% blocks/products/pf/feature-page-summary %}}

Dla programisty Pythona, kto próbuje dodać funkcję konwersji PNG do EMLX w aplikacji? API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) może pomóc zautomatyzować proces konwersji. Jest to pełny pakiet różnych interfejsów API obsługujących różne formaty, w tym formaty e-mail, obrazy i Microsoft Word. Interfejsy API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) i [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/), które są częścią pakietu [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), ułatwiają tę konwersję za pomocą Pythona. Jest to proces dwuetapowy, najpierw załaduj plik PNG i wyrenderuj go do HTML za pomocą [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Następnie załaduj przekonwertowany kod HTML za pomocą [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) i zapisz go w formacie EMLX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować PNG na EMLX w Pythonie?" %}}

- Otwórz źródłowy plik PNG za pomocą klasy ASSOSE.WORDS.DOCUMENT
- Wywołaj metodę `save`, określając ścieżkę wyjściowego pliku HTML i odpowiednie opcje HTML Save jako parametr. Więc twój plik PNG jest konwertowany na HTML w określonej ścieżce
- Teraz załaduj zapisany plik HTML za pomocą MailMessage.load
- Wywołaj metodę save z odpowiednią ścieżką do pliku. Więc w końcu PNG jest konwertowany

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}

- Do konwersji PNG na EMLX wymagany jest Python 3.5 lub nowszy
- Odwołaj się do interfejsów API w projekcie bezpośrednio z PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) i [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Lub użyj następującego polecenia pip ```pip install aspose.words``` i ```pip install Aspose.Email-for-Python-via-NET``` 
- Co więcej, system operacyjny oparty na Microsoft Windows lub Linux (zobacz więcej dla [Words](https://docs.aspose.com/words/python-net/system-requirements/) i [Email](https://docs.aspose.com/email/python-net/system-requirements/)) oraz dla Linuxa sprawdź dodatkowe wymagania dla gcc i libpython i postępuj zgodnie z instrukcjami krok po kroku [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zapisz PNG do EMLX w Pythonie" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}