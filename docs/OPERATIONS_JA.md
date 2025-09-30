# 操作・評価手順（STM32N6570-DK / μT-Kernel 3.0）

## 前提
- STM32CubeIDE 1.19+ / Arm GNU Toolchain 13.x
- μT-Kernel 3.0 BSP2 / サンプルは submodule リポジトリ参照

## 取得
git clone --recursive <このリポジトリのURL>

## ビルド
- external/STM32N6570-DK または external/stm32n6570 を IDE にインポート
- Debug/Release でビルド

## 実行
- ボードへ書き込み後、カメラ入力・パン/チルト動作を確認
- 物体検出（デモ想定）に応じて追従

## 評価観点
- 低遅延/リアルタイム応答・小フットプリント・省電力
