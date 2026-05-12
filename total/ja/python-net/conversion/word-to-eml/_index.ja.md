---
title: Python で WORD を EML に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で WORD を EML に保存します。

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して WORD を EML に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで WORD から EML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に WORD から EML への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に WORD ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EML 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で WORD を EML に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORD ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、WORD ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にWORDが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORD から EML への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでWORDをEMLに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API を使用した Word から EML への変換は、ワードプロセッシング文書を標準的なメールメッセージファイルに変換し、保存、共有、または互換性のあるメールクライアントにインポートできるようにします。これは、コミュニケーションやアーカイブ目的で、メッセージ指向の形式で文書内容を保持する必要がある組織にとって重要です。

自動化および統合のために、Word から EML への変換は、承認ワークフロー、バルク処理ルーチン、そして自動メッセージアーカイブで使用できる、ポータブルなメールファイルの繰り返し生成をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* **ポータブルメールファイル作成**
  文書内容を EML ファイルに変換し、対応するメールツールで開いたりインポートしたりできるようにします。

* **メッセージアーカイブ**
  通信や文書ベースの通知を認識されたメールファイル構造で保存します。

* **テンプレート変換**
  再利用可能な Word テンプレートを、運用で使用できる標準化されたメッセージファイルに変換します。

* **クライアントインポートサポート**
  作成済みのメッセージ内容をメール環境へ移行しやすくします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* **バルクメッセージファイル生成**
  バッチワークフローで複数の Word 文書から自動的に EML ファイルを作成します。

* **承認からアーカイブへのパイプライン**
  最終化された文書を保存および監査目的のメールファイルに変換します。

* **自動メッセージパッケージング**
  下流のメールシステムや配布ツール向けに EML 出力を生成します。

* **コンテンツ再利用ワークフロー**
  文書内容を再利用可能なメールアーティファクトにプログラム的に変換できるようにします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}