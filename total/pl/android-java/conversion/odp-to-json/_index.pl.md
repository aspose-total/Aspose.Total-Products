---
title: Konwertuj ODP na format JSON w Androidzie przez Java
description: Parsowanie ODP do formatu JSON w Androidzie przez Javę bez używania Microsoft Word lub Excel

family: total
platformtag: cpp
feature: conversion
informat: ODP
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj ODP na format JSON w Androidzie przez Java" h2="Projektuj aplikacje na Androida, aby eksportować ODP do formatu JSON bez użycia Microsoft<sup>&reg;</sup> Word lub Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować ODP na format JSON w swoich aplikacjach na Androida przez [Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/). Używając interfejsu API do manipulacji i konwersji dokumentów [Aspose.Words na Androida przez Javę](https://products.aspose.com/words/android-java/), możesz wyeksportować ODP do HTML. Następnie, używając [Aspose.Cells na Androida przez Javę](https://products.aspose.com/cells/android-java/), możesz przekonwertować HTML na JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj ODP na format JSON w Androidzie" %}}
1. Otwórz plik ODP za pomocą klasy [Odpument](https://reference.aspose.com/words/java/com.aspose.words/Odpument)
2. Przekonwertuj ODP na HTML za pomocą [Save](https://reference.aspose.com/words/java/com.aspose.words/Odpument#save(java.lang.String,com.aspose.words.SaveOptions) ) metoda
3. Załaduj dokument HTML za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie JSON za pomocą [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total for Android via Java bezpośrednio z [Maven](https://releases.aspose.com/total/java/)

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony ODP na format JSON w Androidzie za pomocą Java" %}}
Korzystając z interfejsu API, możesz również otworzyć dokument chroniony hasłem. Jeśli wejściowy dokument ODP jest chroniony hasłem, nie można go przekonwertować na format JSON bez użycia hasła. API umożliwia otwarcie zaszyfrowanego dokumentu poprzez podanie prawidłowego hasła w obiekcie LoadOptions. Poniższy przykład kodu pokazuje, jak otworzyć zaszyfrowany dokument za pomocą hasła.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj ODP na JSON w zakresie w Androidzie przez Java" %}}
Podczas konwertowania ODP na JSON możesz również ustawić zakres na wyjściowy format JSON. Aby ustawić zakres, możesz otworzyć przekonwertowany kod HTML za pomocą klasy Workbook, utworzyć zakres danych do wyeksportowania za pomocą metody Cells.createRange, wywołać metodę JsonUtility.exportRangeToJson z odwołaniami do Range & ExportRangeToJsonOptions i zapisać ciąg danych JSON do pliku za pomocą Metoda BufferedWriter.write.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}