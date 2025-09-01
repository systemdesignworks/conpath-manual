---
layout: default
title: タスクの期間を変更する
parent: タスクの作成・編集
grand_parent: プロジェクト
nav_order: 3
has_children: false
---

# タスクの期間を変更する

1. ツールバーの[選択]アイコンをクリックしてアクティブにします。

   <table><tr><td>
   <img src="/assets/images/activetool-selection.png" width="52px">
   </td></tr></table>

2. タスクをクリックして選択します。
3. タスク両端のいずれかのサークルをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/task/change-period-task/1.png" width="40%">
   </td></tr></table>

4. 左右方向にドラッグし、目的のポイントでドロップします。

   <table><tr><td>
   <img src="/assets/images/projects/task/change-period-task/2.png" width="40%">
   </td></tr></table>

   依存関係にあるタスクの始点、終点を越えるタスクの移動を行うとダイアログが表示され、[移動を実行]をクリックすると以降のタスクも連動して移動します。
   <table><tr><td>
   <img src="/assets/images/projects/task/change-period-task/3.png" width="60%">
   </td></tr></table>

{: .note }
この操作では稼働日数が保持されたまま移動します。 
ダイアログの表示は、右クリックのコンテキストメニューから[依存関係のタスクを移動する際に確認ダイアログを表示]を選択してOFFにすることができます。   

{: .warning }
タスクの期間変更には次の制約があります。  
・1日未満への変更はできません  
・カレンダーの日付範囲外への変更はできません  
・依存関係にあるロックされたタスク、マイルストーンを越える変更はできません