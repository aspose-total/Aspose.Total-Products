---
title: Usuń adnotację PDF online lub zarządzaj adnotacjami za pomocą aplikacji mobilnych na Androida
description: usuwaj komentarze z pliku PDF za pośrednictwem aplikacji online za darmo.Kod API Androida do zarządzania komentarzami do plików PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Usuń komentarze z dokumentu PDF online lub zarządzaj za pomocą aplikacji na Androida" h2="Opracuj potężną aplikację do adnotacji dokumentów PDF opartą na systemie Android.Kod do zarządzania komentarzami do pliku PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Usuń adnotacje PDF online" %}}

1. Zaimportuj plik PDF, aby usunąć komentarze, przesyłając go
1. Zrób to, klikając wewnątrz obszaru upuszczania, przeciągając i upuszczając aplikację do adnotacji
1. W zależności od rozmiaru pliku PDF i szybkości Internetu poczekaj kilka sekund
1. Kliknij przycisk „Usuń”, aby usunąć komentarze
1. Pobierz plik natychmiast

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Usuń komentarze do dokumentu PDF za pośrednictwem interfejsu API aplikacji na Androida" %}}

1. Dodaj odwołanie do biblioteki do projektu Android
1. Załaduj dokument poprzez obiekt klasy Dokument
1. Wybierz konkretną stronę za pomocą getPages().get_Item(Index)
1. Użyj AnnotationSelector i uzyskaj wszystkie adnotacje tekstowe za pośrednictwem annotationSelector.getSelected()
1. Iteruj po każdej adnotacji i wywołaj metodę usuwania, aby ją usunąć.
1. Wywołaj metodę save, aby zapisać plik.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod: Usuń komentarze z pliku PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Dodaj adnotację za pośrednictwem interfejsu API aplikacji na Androida" %}}

1. Dodaj odwołanie do biblioteki do projektu Android
1. Utwórz obiekt klasy Dokument
1. Dodaj nową stronę i zawartość za pomocą getPages().add()
1. Użyj metody getPages().get_Item(Index) klasy TextAnnotation
1. Ustaw odpowiednie adnotacje, takie jak tytuł, temat, treść itp
1. Aby dodać adnotacje, użyj getAnnotations().add
1. Wywołaj metodę save, aby zapisać plik z dodanymi komentarzami
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kod: Dodaj adnotację PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Opracuj aplikację do adnotacji w dokumentach PDF na Androida</h2>

Chcesz opracować aplikację mobilną lub narzędzie z adnotacjami PDF, aby przekazywać opinie, zgłaszać sugestie lub współpracować z innymi osobami nad dokumentem?Dzięki [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/pl/android-java/), podrzędnemu interfejsowi API [Aspose.Total for Android via Java](https://products.aspose.com/total/pl/android-java/), każdy programista Androida może zintegrować powyższy kod API ze swoją aplikacją do adnotacji w dokumentach.Potężna biblioteka Android umożliwia programowanie dowolnego rozwiązania do adnotacji w dokumentach.Ponadto może obsługiwać wiele popularnych formatów, w tym format PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteka Androida do dodawania adnotacji do plików PDF" %}}

- Nasze pakiety Java hostujemy w formacie [Repozytoria Mavena](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java to popularny plik JAR zawierający kod bajtowy.
- Postępuj zgodnie z [instrukcje krok po kroku](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository), jak zainstalować Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

- Interfejsy API Androida 31 i 32
- Android 4.0 i nowsze
- Narzędzia Android Studio i SDK

<br />
Więcej szczegółów na temat opcjonalnych zależności pakietów, takich jak JogAmp JOGL, silnik czcionek Harfbuzz, Java Advanced Imaging JAI, można znaleźć w [Dokumentacja produktu](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}