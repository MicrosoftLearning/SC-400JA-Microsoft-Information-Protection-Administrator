﻿# 演習 1 - コンプライアンス ロールを管理する

Contoso Ltd. のコンプライアンス管理者として新規採用された ジョニ・シャーマンのロールでは、組織のコンプライアンスの要件を満たすために、組織の新しい Microsoft 365 テナントを構成する任務を負います。Contoso Ltd. は、米国に本社を置き、欧州連合にいくつかの新しい子会社を保有する会社です。組織は、新しい Microsoft 365 テナントがさまざまな国の法的要件と該当する産業部門の規制要件を満たしていることを確認する必要があります。

### 演習 1 - コンプライアンス ロールを割り当てる

この演習では、最小限の特権の原則に従い、既定のグローバル管理者を使って、コンプライアンス管理者の役割を、このラボで記述された操作を行うことが求められている Joni Sherman に割り振ります。

1.	Client 1 VM (LON-CL1) に **lon-cl1\admin** アカウントでログインします。  パスワードは、ラボ ホスティング プロバイダーから支給されます。

2.	タスクバーから **Microsoft Edge** を開き、**「新しい Microsoft Edge へようこそ」** のウインドウが表示されたら、 **「完全セットアップ」** を選択します。

3. **「確認」** を選択して、デフォルトのブラウザー設定を承認したら、**「サインインしないで続行」** します。

4. **Microsoft Edge** で、**https://admin.microsoft.com** に移動し、**MOD Administrator** admin@WWLxZZZZZZ.onmicrosoft.com として Microsoft 365 管理センター にログインします (ZZZZZZ はラボ ホスティング プロバイダーから支給された固有のテナント ID)。  管理者のパスワードは、ラボ ホスティング プロバイダーから支給されます。

5. **「サインインの状態を維持しますか?」** ダイアログボックスで、**「今後このメッセージを表示しない」** チェックボックスを選択し、**「いいえ」** を選択します。

6. 下部で表示されるパスワード保存のダイアログを「いいえ」で閉じ、ご利用のブラウザー内で既存のグローバル管理者の認証情報が保存されないようにします。

7. 「Welcome」 画面が表示される場合は閉じます。Microsoft Office 365 アプリ の通知が表示される場合も閉じてください。

8. 「Welcome」 ウィンドウが表示されたら、「開始する」を選択して、閉じてください。

9. 左側のナビゲーション ウィンドウで **「ユーザー」** を展開し、**「アクティブ ユーザー」** を選択します。

10. **「アクティブ ユーザー」** リストで **Joni Sherman** を選択し、右側の設定ウィンドウを開きます。

11.	**「アカウント」** タブの設定で、**「ロール」** までスクロールし、下の **「ロールの管理」** を選択します。

12.	**「管理者ロールの管理」** ウィンドウが開いたら、**「管理センター アクセス」** を選択し、**「すべてをカテゴリ別に表示」** を選択します。スクロールダウンし、「セキュリティ＆コンプライアンス」セクションで **「コンプライアンス管理者」** を選択します。

13.	**「変更を保存」** を選択して、ロールに適用します。**「管理者ロールが更新されました」** のメッセージがウィンドウの上部に表示されたら、左側を指している矢印を選択します。

14.	Joni Sherman のアカウントのウィンドウを右上の **X** で閉じ、**「アクティブ ユーザー」** リストに戻ります。

15. 右上の **MA** の丸を選択し、**「サインアウト」** を選択します。

16. **Microsoft Edge** のブラウザーの画面を開いたままにします。

このラボの様々な演習の実施が求められているジョニ・シャーマンに、コンプライアンス管理者ロールが割り当てられました。次のタスクに進みます。

### タスク 2 – コンプライアンス センターの探索

このタスクでは、全体管理者アカウントからサインアウトし、ジョニ・シャーマンとしてもう一度サインインします。コンプライアンス管理者の役割が割り当てられたばかりのジョニ・シャーマンのアカウントを使えば、このラボの演習のほとんどを行うことができます。

1. Client 1 VM (LON-CL1) に **lon-cl1\admin** アカウントでログインしておきます。 

2. **Microsoft Edge** で、**https://compliance.microsoft.com** に移動します。

3. **「アカウントを選択」** ウィンドウが表示されたら、**「別のアカウントを使用」** を選択します。

4. **「サインイン」** ウィンドウが表示されたら、JoniS@WWLxZZZZZZ.onmicrosoft.com (ZZZZZZ はラボ ホスティング プロバイダーから支給された固有のテナント ID) としてサインインします。  Joni のパスワードは、ラボ ホスティング プロバイダーから支給されます。

5. **「コンプライアンス体制を強化する」** メッセージがj表示されたら、書かれているものを読み、**「次へ」** を 2 回選択し、**「完了」** を選択します。

6. 下へスクロールして、「**…すべて表示***」を左下部から選択し、Microsoft 365 コンプライアンス センターのメニューアイテムを全て開きます。

7. 様々な設定をよく理解しましょう。終了したら、ブラウザーの画面を開いたままにしておきます。

ジョニ・シャーマンのアカウントへの切り替えが完了し、ラボを開始する準備ができました。

# 演習 2 に進みます。