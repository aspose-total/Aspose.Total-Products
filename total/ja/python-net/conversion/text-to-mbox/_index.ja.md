---
title: Python で TEXT を MBOX に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で TEXT を MBOX に保存します。

family: total
platformtag: Python
feature: conversion
informat: TEXT
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して TEXT を MBOX に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで TEXT から MBOX への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に TEXT から MBOX への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に TEXT ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、MBOX 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で TEXT を MBOX に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース TEXT ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、TEXT ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にTEXTが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- TEXT から MBOX への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでTEXTをMBOXに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API を使用したテキストから MBOX への変換により、プレーンテキストコンテンツをメールボックス形式のアーカイブにコンパイルでき、メールのグループ保存と転送が可能になります。これは、大量メッセージの生成、移行ワークフロー、メールボックスコンテナ形式で通信を整理する必要がある環境に役立ちます。

この変換は特に自動化に関連しており、テキストソースからスケーラブルにメールボックスアーカイブを作成できるため、バックアップ操作、メッセージのインポート、そして大量の通信データの効率的な処理をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主要な使用例" %}}

* **メールボックスアーカイブ作成**  
  テキストコンテンツを MBOX 互換の構造に変換し、メッセージをグループで保存します。

* **大量通信パッケージ化**  
  複数のテキスト由来メッセージを単一のメールボックスファイルに結合することをサポートします。

* **移行およびインポートサポート**  
  MBOX アーカイブを受け入れるシステムへの転送のために通信を準備するのに役立ちます。

* **長期保存**  
  レビューおよびコンプライアンスのために、メッセージのようなテキストコンテンツを構造化して保存できるようにします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動化アーカイブ構築**  
  システムは生成されたテキストレコードを MBOX コレクションに変換し、集中ストレージに保存できます。

* **バッチエクスポートワークフロー**  
  大量のメッセージセットをテキストからプログラムで組み立て、メールボックスアーカイブにすることができます。

* **データ統合プロセス**  
  自動化により、テキストベースの通信を移行やバックアップ用のポータブル MBOX ファイルにまとめることができます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}