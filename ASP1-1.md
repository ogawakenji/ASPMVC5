# 1-1 ASP.NETの全体像

1. Webフォーム

    ASP.NETの中で一番の古参
    ASP.NET Webフォーム or Webフォームと呼ばれるサブフレームワーク

    イベントドリブンモデルを採用
    
1. ASP.NET MVC 
    
    Visual Studio 2008の拡張コンポーネント
    Visual Studio 2010で標準搭載されたサブフレームワーク
    
1. ASP.NET Web Pages
    
    以前のASP、PHPによく似た技術
    HTML埋め込みモデルを採用
    小規模サイトの利用を想定。さほど普及していない
    
1. ASP.NET Web API

1. SignalR
 
1. ASP.NET Single Page Application(SPA)

## 1-2 ASP.NET MVCとは？

これだけ魅力的なフレームワーク(Webフォーム)が存在したにも関わらず、また新しいASP.NET MVCなどという
フレームワークを持ち出さなければならなかったのか？

### 1-2-1 Webフォームの問題点

1. 単体テストを自動化しにくい

    Webフォームは、基本的にページ(Pageクラス)を中心にしたフレームワーク
    Pageクラスは直接インスタンス化することができない。
    テストにあたってもサーバー環境の準備が必要
    
    イベントハンドラーは原則として、ユーザーインターフェイスを経由して呼び出す必要がある
    トリガーはユーザーインタフェイスの状態。これもまたテストしにくくする要因
    
    アプリケーションの変更にテストが影響を受けやすい
    

## 2-2 コントローラーの基本

基点となるのはコントローラー
    
Model-View-ControllerのControllerに当たる部分
    
    



