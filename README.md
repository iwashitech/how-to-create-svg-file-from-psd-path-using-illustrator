# Illustratorを使ってPSDのパスからSVGファイルを作成する方法

## 作業の流れ

1. ベクトルマスクを選択してコピー（Ctrl+C)
1. Illustratorへペースト（Ctrl+V)
1. Illustratorで線に色をつける
1. オブジェクト->分割・拡張
<br><span style="font-size: 12px">※「分割・拡張」が選択できない場合は、オブジェクト->「アピアランスを分割」してから再度「分割・拡張」</span>
1. オブジェクト->透明部分を分割・統合
<br><span style="font-size: 12px">※すべてのオブジェクトが塗りになるのを確認</span>
1. オブジェクト->アートボード->オブジェクト全体に合わせる
1. ファイル->別名で保存、ファイルの種類でSVGを選択

## 複数のパスの場合（例：2つのパス）

1. 必要なパスを選択してスマートオブジェクトに変更、コンテンツを書き出し、元に戻す
1. 位置調整用の画像をファイル->配置
1. PSDからそれぞれのパスをコピー、PSDのスタイルを適用する
1. 位置調整用の画像と合わせる
1. 上のパスのみコピー（Ctrl+C）、前面へペースト（Ctrl+F）、非表示にする（Ctrl+3）
1. 上のパスのみ選択して、オブジェクト->透明部分を分割・統合
1. ウインドウ->パスファインダ->合体
1. 長方形のみを選択し、オブジェクト->透明部分を分割・統合
1. ウインドウ->パスファインダ->前面オブジェクトで型抜き
1. オブジェクト->すべて表示、上のパスの線を削除する
1. 位置調整用の画像を削除する