---
layout: default
title: プロジェクトの管理
parent: プロジェクト
nav_order: 1
has_children: false
---

# プロジェクトの管理
{: .no_toc }

## 目次
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## プロジェクトを新規作成する

1. プロジェクト一覧を開きます。
2. [+新規プロジェクト]ボタンをクリックします。
3. プロジェクト名、期間、プロジェクトメンバー / チームを選択し、[作成する]ボタンをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/1.png">
   </td></tr></table>

{: .note }
プロジェクトに同一のメンバーが所属するチームが複数割り当てられている場合、一番高い権限が適用されます。  
この設定は組織の権限がオーナー、メンバーのみ可能です。

## プロジェクトの設定を変更する

1. プロジェクト一覧を開きます。
2. プロジェクト一覧の[...]のドロップダウンメニューから[プロジェクトの設定]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/2.png" width="30%">
   </td></tr></table>

3. プロジェクト名、期間、プロジェクトメンバー / チームを選択し、[変更する]ボタンをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/3.png">
   </td></tr></table>

{: .note }
プロジェクトに同一のメンバーが所属するチームが複数割り当てられている場合、一番高い権限が適用されます。  
この設定は組織の権限がオーナー、またはプロジェクトの権限が管理者のみ可能です。

## プロジェクトの休日を設定する

1. プロジェクトを開きます。
2. 設定メニューから[休日設定]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/4.png" width="30%">
   </td></tr></table>

3. 休日にしたい日付をクリックすると色が変わり、休日になります。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/5.png" width="100%">
   </td></tr></table>

4. 下にスクロールし、[確定]ボタンをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/6.png" width="100%">
   </td></tr></table>

{: .note }
タスク個別の休日は[個別休日を設定する]({% link projects/task/holiday-settings.md %})をご参照ください。  
この設定は組織の権限がオーナー、またはプロジェクトの権限が管理者、編集者のみ可能です。

## プロジェクトの期間を変更する

1. プロジェクトを開きます。
2. 設定メニューから[プロジェクト設定]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/7.png" width="30%">
   </td></tr></table>

3. カレンダーから選択するか、工期に開始日、終了日を入力します。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/8.png" width="100%">
   </td></tr></table>

4. [確定]ボタンをクリックします。

{: .note }
この設定は組織の権限がオーナー、またはプロジェクトの権限が管理者、編集者のみ可能です。

## プロジェクトを印刷する

1. プロジェクトを開きます。
2. メニューから[印刷]をクリックします。またはCmd + Pキーを押します。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/9.png" width="40%">
   </td></tr></table>

3. 印刷プレビューが表示された後に、印刷のオプションを編集することができます。
   <table><tr><td>
      <img src="/assets/images/projects/manage-project/17.png" width="80%">
   </td></tr></table>

   - 印刷する日付の範囲をカレンダーから選択することが可能です。
   <table><tr><td>
      <img src="/assets/images/projects/manage-project/18.png" width="50%">
   </td></tr></table>

   - 印刷ヘッダーの値を編集可能です。
   > タイトル(プロジェクト名)<br>サブタイトル<br>備考欄<br>ロゴ(設定画面で設定したイメージファイル)<br>日付(作成日)
   <table><tr><td>
      <img src="/assets/images/projects/manage-project/19.png" width="60%">
   </td></tr></table>

   - 印刷時に、1ページに収めるか選択可能です。
   <table><tr><td>
      <img src="/assets/images/projects/manage-project/20.png" width="40%">
   </td></tr></table>

4. [印刷]ボタンをクリックして、印刷を開始します。

{: .warning }
工期が長い場合、プレビュー表示に時間がかかる場合があります。

## プロジェクトを複製する

1. プロジェクト一覧を開きます。
2. プロジェクト一覧の[...]のドロップダウンメニューから[プロジェクトの複製]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/10.png" width="30%">
   </td></tr></table>

3. プロジェクト名、期間、プロジェクトメンバー / チームを選択し、[複製する]ボタンをクリックします。  

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/11.png" width="100%">
   </td></tr></table>

{: .note }
期間を変更した場合、変更後の開始日に合わせてタスクの開始日が更新されます。  
また、完了済みのタスクは未完了になります。  
プロジェクトに同一のメンバーが所属するチームが複数割り当てられている場合、一番高い権限が適用されます。  
この設定は組織の権限がオーナー、またはプロジェクトの権限が管理者のみ可能です。

## プロジェクトを削除する

1. プロジェクトを開きます。
2. 設定メニューから[プロジェクトの削除]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/12.png" width="30%">
   </td></tr></table>

3. 画面の内容を確認し、チェックを入れてください。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/13.png" width="60%">
   </td></tr></table>

4. [削除する]ボタンをクリックします。

{: .note }
この設定は組織の権限がオーナー、またはプロジェクトの権限が管理者のみ可能です。

## プロジェクトをアーカイブにする

1. プロジェクト一覧を開きます。
2. プロジェクト一覧の[...]のドロップダウンメニューから[プロジェクトの設定]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/14.png" width="30%">
   </td></tr></table>

3. 画面下にある、[プロジェクトをアーカイブ]ボタンをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/15.png" width="100%">
   </td></tr></table>

4. 画面の内容を確認し、[理解しました]ボタンをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/16.png" width="50%">
   </td></tr></table>

{: .note }
プロジェクトがアーカイブ済みおよび読み取り専用になると、プロジェクトが閲覧のみに制限されます。  
この設定は組織の権限がオーナー、またはプロジェクトの権限が管理者のみ可能です。