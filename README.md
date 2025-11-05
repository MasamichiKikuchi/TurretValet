# TurretValet(タレットバレット)
  
## 概要説明
 株式会社カプコン様が主催する学生向けのゲーム開発コンペティション「CAPCOM GAMES COMPETITION」にて、社内エンジン「RE ENGINE」を用いて制作したオリジナルゲームです。  
  
宇宙のどこかにある魔法使いの世界アメイジングマジック学園(通称AMG)。  
今日は年に一度の文化祭！  
メインステージでは、生徒たちが自分の使い魔を自慢し合う「使い魔コンテスト」の決勝戦が始まろうとしていて......？  
魔法少女のシーナとその使い魔のイーギ、魔法少女のフルーラとその使い魔のアーリが力を合わせて戦う2vs2チーム協力型バトル！  
１つのコントローラーを２人で分ける独創的な操作と、ミスすると相手を手助けしちゃうシステムが特徴。２人の息を合わせるのがカギの対戦ゲーム！  
  
## 開発期間  
 2025/04/07～2025/09/26  
  
## 開発環境：開発時に使用したツールや言語など  
 言語:C#  
 開発エンジン:RE ENGINE  

## 必要動作環境  
Windows10/11  
Xinput対応コントローラー2つ  

## 起動方法  
[Releasesページ](https://github.com/MasamichiKikuchi/TurretValet/releases/tag/v1.0)より実行ファイルをダウンロード  
→TurretValet.zipフォルダをダウンロード・解凍  
→protected_runtime_il2cpp.exeを実行  
  
## 終了方法  
タイトル、ポーズメニュー、リザルトで「ゲーム終了する」を選択  
  
## 操作説明  
Aボタン:決定  
Bボタン:戻る  
STARTボタン:ポーズメニュー  
Rスティック:使い魔の移動  
Rトリガー:使い魔ラリアット  
Lスティック:魔法少女の移動  
Lトリガー:魔力玉発射/ビーム発射  
  
## 担当箇所
### 菊池雅道
<details>
<summary>クリックして展開</summary>  
  
  [ActionController_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/ActionController_Work.cs)<br>
  [AppUpdateOrder_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/AppUpdateOrder_Work.cs)<br>
  [BombExplosion_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/BombExplosion_Work.cs)<br>
  [BombSpawnManager_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/BombSpawnManager_Work.cs)<br>
  [BombSpawnUseeData_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/BombSpawnUseeData_Work.cs)<br>
  [BombUserData_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/BombUserData_Work.cs)<br>
  [Bomb_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/Bomb_Work.cs)<br>
  [CameraManager_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/CameraManager_Work.cs)<br>
  [CharacterBase_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/CharacterBase_Work.cs)<br>
  [GameFlowManager_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/GameFlowManager_Work.cs)<br>
  [HitController_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/HitController_Work.cs)<br>
  [IngameCameraUserData_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/IngameCameraUserData_Work.cs)<br>
  [IngameUserData_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/IngameUserData_Work.cs)<br>
  [MagicPowerBullet_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/MagicPowerBullet_Work.cs)<br>
  [MagicPowerSpawn_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/MagicPowerSpawn_Work.cs)<br>
  [MagicPowerManager_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/MagicPowerManager_Work.cs)<br>
  [MagicPowerSpawnPoint_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/MagicPowerManager_Work.cs)<br>
  [MagicPowerUserData_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/MagicPowerUserData_Work.cs)<br>
  [SingletonRoot_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/SingletonRoot_Work.cs)<br>
  [Startup_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/Startup_Work.cs)<br>
  [TitleUserData_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/TitleUserData_Work.cs)<br>
  [WitchUserData_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/WitchUserData_Work.cs)<br>
  [Witch_Work.cs](https://github.com/MasamichiKikuchi/TurretValet/blob/main/Script/Witch_Work.cs)<br>
</details>

### 須永ジン
<details>
<summary>クリックして展開</summary>  
Bomb_Work(色変更、シェーダー関連)<br>
InGame_GUIController.cs<br>
MonsterDamageWork<br>
Load_GUIController.cs<br>
Pause_GUIController.cs<br>
Result_GUIController.cs<br>
ResultMovieGUI_Controller.cs<br>
Select_GUIController.cs<br>
Story_GUIController.cs<br>
Title_GUIController.cs<br>
</details>

### 廣山将太郎
<details>
<summary>クリックして展開</summary>  
CharacterBase_Work（ヒットストップ部分、エフェクト部分）<br>
FrameSpeedController_Work<br>
GamePadManager_Work<br>
HitStopUserData_Work<br>
Monster_Work<br>
MonsterUserData_Work<br>
SelectCharacterManager_Work<br>
</details>
