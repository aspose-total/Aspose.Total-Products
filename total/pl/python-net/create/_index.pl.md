---
title: Utwórz plik za pomocą Pythona 

description: Twórz dokumenty tekstowe i Microsoft Word bez instalowania pakietu Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Twórz dokumenty za pomocą Pythona" h2="Twórz pliki tekstowe i Microsoft Word DOCX, DOC w aplikacjach Pythona bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Przechowywanie danych jest podstawą każdej aplikacji w zależności od charakteru aplikacji. Miejscem przechowywania może być baza danych, XML, JSON, pliki tekstowe, raporty Excela lub dokumenty Microsoft Word. Plik I/O jest częścią dowolnego języka, a głównie języki, w tym Python, obsługują zapisywanie danych do plików tekstowych. Rozważmy język Python. Pisząc istniejące pliki tekstowe za pomocą Pythona, zapewnia metodę otwierania, pisania i zamykania dla tych zadań. Najpierw otwórz plik z odpowiednią ścieżką pliku i dodaj lub zapisz funkcję jako argumenty. Następnie wpisz wymagany tekst do pliku i na koniec zamknij plik za pomocą metody close(). 

Do tworzenia dokumentów Microsoft Word przy użyciu Pythona używamy pakietu [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) APIs, którego częścią jest API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Ten interfejs API zapewnia pełną automatyzację dokumentów dla faktur, raportów i artykułów technicznych. Poniżej wymieniono procedurę tworzenia dokumentu tekstowego.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Jak utworzyć plik tekstowy za pomocą Pythona" %}}

Tworzenie i zapisywanie do plików tekstowych jest proste. Python dostarcza metodę open() z trzema parametrami i musi używać jednego z parametrów wraz ze ścieżką do pliku. Trzy parametry to „x”, „a” i „w”. Podając "x", zostanie utworzony nowy plik, ale zgłosi błąd w przypadku, gdy plik już istnieje. Po podaniu "a" zostanie utworzony nowy plik tekstowy, jeśli nie istnieje, aw przypadku, gdy istnieje, zawartość zostanie dołączona na końcu. I na koniec po podaniu "w", nowy dokument tekstowy zostanie utworzony i nadpisany nową treścią, jeśli już istnieje.

{{% blocks/products/pf/feature-page-code h3="Python - Utwórz plik tekstowy" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Twórz dokumenty Microsoft Word" %}}

Total Python Word API ma wiele funkcji, w tym tworzenie plików Microsoft Word, wstawianie obrazów i tekstu w dokumentach, dodawanie tabel i list w plikach, a także łatwe modyfikowanie istniejących dokumentów. Aby utworzyć proces dokumentu Microsoft Word, utwórz obiekt klas [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) i [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Dodaj wymagany tekst, akapit, listy i tabele w dokumencie, a na koniec zapisz go.

{{% blocks/products/pf/feature-page-code h3="Python - Twórz dokumenty Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Tworzyć">}}