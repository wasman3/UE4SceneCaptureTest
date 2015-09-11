# UE4SceneCaptureTest
UnrealEngine4でのSceneCapture2D Testプロジェクト
# 概要
TopDownテンプレートを使用してます。Versionは4.9

下記のキャラクターブループリント内にSceneCapture2Dをキャラクターにつけています。
` \SceneCaptureTest\Content\TopDownBP\Blueprints\TopDownCharacter.uasset`

下記フォルダにSceneCaptureしたものをマテリアル化し、UMGで表示するブループリントが入っています
` \SceneCaptureTest\Content\TopDownBP\SceneCapture`

下記のレベルブループリント内で、上記で作成したUMGを画面内に表示しています
` \SceneCaptureTest\Content\TopDownBP\TopDownOverview.uasset`

上記の箇所以外はテンプレートをそのまま使用しています。

下記機能を追加

* SceneCapture2D
* UMG
* マテリアル
* RenderTarget

*動作画面*
![画面](/SceneCaptureTest.png)
