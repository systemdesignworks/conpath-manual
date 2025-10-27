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
3. プロジェクト名、カラー、期間、プロジェクトメンバー / チームを選択し、[作成する]ボタンをクリックします。

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

3. プロジェクト名、カラー、期間、プロジェクトメンバー / チームを選択し、[変更する]ボタンをクリックします。

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

2. メニューから[印刷]をクリックします。またはCtrl(MacOSは Cmd) + Pキーを押します。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/9.png" width="40%">
   </td></tr></table>

3. 印刷プレビューが表示されます。

4. 必要に応じて、印刷のオプションを変更してください。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/17.png" width="100%">
   </td></tr></table>

   <table>
      <tr>
         <th>オプション名</th>
         <th>説明</th>
         <th>初期値</th>
      </tr>
      <tr>
         <td>選択範囲</td>
         <td>印刷する期間を日付で指定できます。</td>
         <td>全期間</td>
      </tr>
      <tr>
         <td>表示モード</td>
         <td>カレンダーの表示単位を日単位または週単位で選択できます。
            <br>週単位を選択すると、より広い期間を1ページに収めることができます。
         </td>
         <td>日</td>
      </tr>
      <tr>
         <td>ヘッダー</td>
         <td>印刷のヘッダーを編集できます。チェックでヘッダーの表示と非表示を切り替えられます。
            <br>編集できる内容は次項に記載しています。
         </td>
         <td>チェック</td>
      </tr>
      <tr>
         <td>用紙の向き</td>
         <td>用紙の横縦の向きを変更できます。</td>
         <td>横</td>
      </tr>
      <tr>
         <td>ページ送り</td>
         <td>1ページに収めるか、複数ページに分けて印刷するかが選択可能です。
            <br>複数ページに分ける場合は、日数でページを分割することができます。デフォルトは縦方向が用紙向きにフィットするように、日数が自動で計算されます。
         </td>
         <td>1ページに収める</td>
      </tr>
   </table>

{: .note }
週単位表示を選択すると、タスクは週ごとに集約されて表示されます。長期間のプロジェクト全体像を把握する際に便利です。

5. 必要に応じて、<img src="/assets/images/projects/manage-project/18.png" style="height: 32px">をクリックして、印刷のヘッダーを変更してください。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/19.png" width="100%">
   </td></tr></table>

   <table>
      <tr>
         <th>オプション名</th>
         <th>説明</th>
         <th>初期値</th>
      </tr>
      <tr>
         <td>タイトル・サブタイトル</td>
         <td>-</td>
         <td>タイトル: プロジェクト名<br>サブタイトル: 空白</td>
      </tr>
      <tr>
         <td>備考欄</td>
         <td>-</td>
         <td>空白</td>
      </tr>
      <tr>
         <td>組織名</td>
         <td>-</td>
         <td>設定画面で登録した組織名</td>
      </tr>
      <tr>
         <td>ロゴ</td>
         <td>印刷時のみ画像をアップロードすることが可能です。
            <br>印刷時にアップロードした画像は、設定画面には反映されません。
         </td>
         <td>設定画面で登録したロゴ画像ファイル</td>
      </tr>
      <tr>
         <td>作成日</td>
         <td>-</td>
         <td>当日の日付</td>
      </tr>
   </table>

6. 印刷プレビューが表示された後に、[印刷]ボタンをクリックします。
   <table><tr><td>
   <img src="/assets/images/projects/manage-project/20.png" width="100%">
   </td></tr></table>

7. 印刷が開始されます。

{: .warning }
工期が長い場合、プレビュー表示に時間がかかる場合があります。

## プロジェクトを複製する

1. プロジェクト一覧を開きます。
2. プロジェクト一覧の[...]のドロップダウンメニューから[プロジェクトの複製]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/10.png" width="30%">
   </td></tr></table>

3. プロジェクト名、カラー、期間、プロジェクトメンバー / チームを選択し、[複製する]ボタンをクリックします。  

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/11.png" width="100%">
   </td></tr></table>

{: .note }
期間を変更した場合、変更後の開始日に合わせてタスクの開始日が更新されます。  
また、完了済みのタスクは未完了になります。  
プロジェクトに同一のメンバーが所属するチームが複数割り当てられている場合、一番高い権限が適用されます。  
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

## プロジェクトを削除する

### プロジェクト画面から削除

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

### プロジェクト編集画面から削除

1. プロジェクト一覧を開きます。

2. プロジェクト一覧の[...]のドロップダウンメニューから[プロジェクトの設定]をクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/14.png" width="30%">
   </td></tr></table>

3. 画面下にある、[プロジェクトを削除]ボタンをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/manage-project/15.png" width="100%">
   </td></tr></table>

4. 画面の内容を確認し、チェックを入れてください。

5. [削除する]ボタンをクリックします。

{: .note }
この設定は組織の権限がオーナー、またはプロジェクトの権限が管理者のみ可能です。