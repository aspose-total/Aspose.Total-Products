---
title: Python で WORD を EMAIL に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で WORD を EMAIL に保存します。

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: EMAIL
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して WORD を EMAIL に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで WORD から EMAIL への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に WORD から EMAIL への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に WORD ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EMAIL 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で WORD を EMAIL に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORD ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、WORD ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にWORDが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORD から EMAIL への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでWORDをEMAILに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API を使用した Word から Email への変換は、文書コンテンツをメール用の出力に変換し、メッセージ生成、コンテンツ再利用、コミュニケーションワークフローに利用できます。これは、レポート、通知、またはテンプレートがワードプロセッシングファイルで作成され、直接配布のために再利用する必要がある場合に便利です。

最新の自動化パイプラインでは、この変換により文書作成とコミュニケーション実行を橋渡しし、アラート、アウトリーチ、取引メッセージングプロセス向けにスケーラブルにメール対応コンテンツを生成できるようになります。

{{% blocks/products/pf/agp/feature-section-col title="主なユースケース" %}}

* **テンプレートベースのメッセージング**
  文書コンテンツを再利用して、アウトバウンドメールコミュニケーションの基礎とします。

* **レポート配布**
  作成された文書をメール対応形式に変換し、チームやクライアントと共有します。

* **通知コンテンツの準備**
  正式なワード文書を構造化されたメッセージに変換し、自動配信を支援します。

* **コミュニケーションワークフローの簡素化**
  文書コンテンツをメールシステムに手動でコピー・適応する必要性を減らします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動メール生成**
  承認されたワード文書をメールコンテンツに変換し、スケジュールまたはイベント駆動の送信に使用します。

* **キャンペーンコンテンツの再利用**
  文書テンプレートを定期的な情報提供または運用メールのソースとして使用します。

* **ワークフローベースのアラート**
  ビジネスルールやシステムトリガーが満たされたときに、文書からメールメッセージを生成します。

* **集中型コンテンツ公開**
  1つのソース文書が複数のコミュニケーションチャネルにプログラム的に供給できるようにします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}