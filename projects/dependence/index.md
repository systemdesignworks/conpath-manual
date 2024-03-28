---
layout: default
title: ネットワーク線の作成・編集
parent: プロジェクト
nav_order: 4
has_children: false
---

# ネットワーク線の作成・編集
{: .no_toc }

## 目次
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## タスク・マイルストーンを依存関係にする

1. ツールバーの[選択]アイコンをクリックしてアクティブにします。

   <table><tr><td>
   <img src="/assets/images/activetool-selection.png" width="52px">
   </td></tr></table>

2. タスクをクリックして選択します。
3. タスク終点から出ているサークルをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/1.png" width="40%">
   </td></tr></table>
  
4. 依存対象にするタスクの始点/マイルストーンまでドラッグし、ホバーアニメーションが表示されている状態でドロップします。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/2.png" width="40%">
   </td></tr></table>

   クリティカルパス（キャンバス内で最も長い経路）に該当する場合、一連のタスクとネットワーク線が自動的に水色になります。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/3.png" width="40%">
   </td></tr></table>

   既存のタスクの右側に隣接してタスクを作成すると自動的に依存関係になります。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/4.png" width="40%">
   </td></tr></table>

   <table><tr><td>
   <img src="/assets/images/projects/dependence/5.png" width="40%">
   </td></tr></table>

   <table><tr><td>
   <img src="/assets/images/projects/dependence/6.png" width="40%">
   </td></tr></table>

{: .warning }
依存関係の作成には次の制約があります。  
・始点からネットワーク線を作成することはできません  
・終点から日付を遡る点へネットワーク線を引くことはできません  
・期間が重なるタスクを前後で依存関係にすることはできません

## タスク・マイルストーンの依存対象を変更する

1. ツールバーの[選択]アイコンをクリックしてアクティブにします。

   <table><tr><td>
   <img src="/assets/images/activetool-selection.png" width="52px">
   </td></tr></table>

2. ネットワーク線をクリックして選択します。
3. ネットワーク線両端のいずれかのサークルをクリックします。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/7.png" width="40%">
   </td></tr></table>
  
4. 変更先依存対象のタスク/マイルストーンまでドラッグし、ホバーアニメーションが表示されている状態でドロップします。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/8.png" width="40%">
   </td></tr></table>
  
{: .warning }    
タスクの依存対象を変更するには次の制約があります。  
・始点/終点同士を結ぶことはできません  
・終点から日付を遡る点へネットワーク線を引くことはできません  
・期間が重なるタスクを前後で依存関係にすることはできません

## ネットワーク線の中間線を編集する

1. ツールバーの[選択]アイコンをクリックしてアクティブにします。

   <table><tr><td>
   <img src="/assets/images/activetool-selection.png" width="52px">
   </td></tr></table>

2. ネットワーク線をクリックして選択します。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/9.png" width="60%">
   </td></tr></table>

3. ネットワーク線中央のアイコンをドラッグします。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/10.png" width="60%">
   </td></tr></table>

## 依存関係のタスクを強調表示する

画面上の要素が無いところで右クリック(iPad:タッチ&ホールド)し、コンテキストメニューから[依存関係のタスクを強調表示]、[非依存関係のタスクを透過表示]を選択します。いずれか、あるいは両方を適用することができます。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/11.png" width="50%">
   </td></tr></table>

- [依存関係のタスクを強調表示]適用

   <table><tr><td>
   <img src="/assets/images/projects/dependence/12.png" width="60%">
   </td></tr></table>

- [非依存関係のタスクを透過表示]適用

   <table><tr><td>
   <img src="/assets/images/projects/dependence/13.png" width="60%">
   </td></tr></table>

- [依存関係のタスクを強調表示]と[非依存関係のタスクを透過表示]適用

   <table><tr><td>
   <img src="/assets/images/projects/dependence/14.png" width="60%">
   </td></tr></table>

## ネットワーク線をロックする

1. ロックしたいネットワーク線の上にカーソルを移動します。
2. 右クリック(iPad:タッチ&ホールド)でコンテキストメニューを開き、[ロック]を選択します。

   <table><tr><td>
   <img src="/assets/images/projects/dependence/15.png" width="60%">
   </td></tr></table>

    ネットワーク線がロックされ、ロックアイコンが表示されます。
    
   <table><tr><td>
   <img src="/assets/images/projects/dependence/16.png" width="60%">
   </td></tr></table>

{: .note }
タスクの依存関係の中にロックされたネットワーク線がある場合、タスクの移動はロックされたネットワーク線の日数を保持したまま行われます。

## ネットワーク線のロックを解除する

1. ロックを解除したいタスクの上にカーソルを移動します。
2. 右クリック(iPad:タッチ&ホールド)でコンテキストメニューを開き、[ロック解除]を選択します。
    
   <table><tr><td>
   <img src="/assets/images/projects/dependence/17.png" width="60%">
   </td></tr></table>

タスクのロックが解除されます。