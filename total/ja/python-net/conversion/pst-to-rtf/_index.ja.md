---
title: Python で PST を RTF に変換する
description: Microsoft Outlook や Word を使用せずに、Python アプリケーションで PST を RTF に保存します。 

family: total
platformtag: Python
feature: conversion
informat: PST
outformat: RTF
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して PST を RTF に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで PST から RTF への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に PST から RTF への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。まず、E メールをロードし、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用して変換された HTML を読み込み、RTF 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で PST を RTF に変換する方法" %}}

- MailMessage.load クラスを使用してソース PST ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、PST ファイルは指定されたパスで HTML に変換されます。
- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にPSTが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- PST から RTF への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでPSTをRTFに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API における PST から RTF への変換は、メールボックスのコンテンツをリッチテキスト形式に変換し、編集可能でポータブルな文書ワークフローを実現します。メール由来のテキストが基本的な書式を保持しつつ、多くのワードプロセッシング環境と広く互換性を保つ必要がある場合に有用です。

自動化環境において、PST から RTF への変換は軽量な文書交換と、メールボックスアーカイブを効率的に編集可能な出力へ変換することを支援します。これにより、さまざまなシステム間でフォーマットされたコミュニケーションコンテンツをスケーラブルに再利用できるようになります。

{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}

* **フォーマットされたテキストのエクスポート**
  PST のコンテンツを RTF に変換し、基本的な文書スタイルを保持します。

* **広範な互換性ワークフロー**
  メールボックス由来のファイルをさまざまな編集環境で利用できるようにします。

* **編集可能なアーカイブの準備**
  コミュニケーション記録を再編集可能な文書形式に変換することをサポートします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動テキスト変換パイプライン**
  システムは PST コンテンツを RTF にエクスポートし、下流の編集や再利用に利用できます。

* **ポータブル文書ワークフロー**
  変換されたファイルはオフィスアプリケーションとアーカイブシステム間で簡単に移動できます。

* **スケーラブルなコンテンツ再フォーマット**
  プログラムによる変換は、メールボックステキストを大量に編集可能なファイルへ変換する作業を簡素化します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}