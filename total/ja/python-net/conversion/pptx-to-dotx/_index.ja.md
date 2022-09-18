---
title: Python で PPTX を DOTX に変換する
description: Microsoft Word や PowerPoint を使用せずに、Python アプリケーションで PPTX から DOTX への変換 
url: /ja/python-net/conversion/pptx-to-dotx/
family: total
platformtag: Python
feature: conversion
informat: PPTX
outformat: DOTX
otherformats: Word DOC DOT DOCX DOCM DOTX DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して PPTX を DOTX に変換する" h2="Microsoft Word<sup>&reg;</sup> または PowerPoint をインストールせずに、Python アプリケーションで PPTX から DOTX への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に PPTX から DOTX への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。これは、さまざまな形式を扱うさまざまな API の完全なパッケージです。 そう **Python で PPTX を DOTX に変換する方法**

主に2段階です。 まず [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API を使用して PPTX ファイルを PDF に変換します。 その後、Microsoft Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用して、作成した PDF を Microsoft Word に DOTX 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で PPTX を DOTX に変換する" %}}
-  **ステップ1** [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) クラスのインスタンスを含む PDF ファイルをロードします。
-  パラメータとして出力ファイルパスと SaveFormat.PDF を指定して `save` メソッドを呼び出します。 したがって、PPTX ファイルは指定されたパスで PDF に変換されます。
- **ステップ2** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用して PDF ファイルを開きます。
- [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) メソッドを使用して、ファイル名と目的のディレクトリ パスを指定し、PDF ファイルを DOTX ファイルに保存します。
- PowerPoint プレゼンテーションから Word (Microsoft Powerpoint to Word)[https://products.aspose.com/total/python-net/conversion/] への変換の別のコード スニペットを次に示します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- PPTX から DOTX への変換には、Python 3.5 以降が必要です。
- PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) および [Aspose.Words](https://pypi.org/project/aspose-words/)) から直接プロジェクト内の API を参照するか、
- 次の pip コマンド ```pip install aspose.slides``` および ```pip install aspose.words``` を使用します。 さらに、
- Microsoft Windows または Linux ベースの OS ([Slides](https://docs.aspose.com/slides/python-net/system-requirements/) および [Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、[INSTALL](https://docs.aspose.com/words/python-net/installation/) の手順に従ってください。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で PPTX を PDF に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-slides-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で PDF を DOTX に保存 - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-files-to-microsoft-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}