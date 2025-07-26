# 🛍️ Work Together! GS25 Sample

🎮 DataStore2를 활용해 유저 코인을 저장/불러오기 하는 샘플 & 가구 커스터마이징 기능 중 Move 부분을 구현한 샘플입니다.
Studio에서 바로 실행 가능한 '.rbxm' 파일으로 구성되어 있습니다.

## ✨ 주요 기능
- DataStore2 기반 Coin 저장 및 불러오기
- 커스터마이징 시스템 중 파트 이동 및 배치

## 📁 구조
'.rbxm' 파일을 Roblox Studio에 드래그하면 다음과 같이 불러와집니다:  

[gs25]datastore_sample  
├── ReplicatedStorage  
│ └── CoinData (ModuleScript)  
├── ServerScriptService  
│ ├── DataStore2 (ModuleScript)  
│ └── CoinUpdateTester (Script)  
├── Workspace  
│ ├── SpawnLocation  
│ ├── CoinMinusPart (Part)  
│ └── CoinPlusPart (Part)  

[gs25]furniture_custom_sample  
├── ReplicatedStorage  
│ └── FurnitureCustomizeModule (ModuleScript)  
├── StarterGui  
│ └── BillboardGui (UI)  
├── StarterPlayer  
│ └── StarterPlayerScripts  
│ │ └── FurnitureCustomizeController (Script)  
├── Workspace  
│ ├── SpawnLocation  
│ ├── PartA (Part)  
│ └── PartB (Part)  
│ └── TestPart (Part)  

## 📦 사용 방법
1. `.rbxm` 파일을 Roblox Studio에 드래그 후 의 ServerScriptService에 위치시킵니다.
2. 플레이 버튼 (`F5`) 클릭

[gs25]datastore_sample 의 경우  
4. `CoinPlusPart` 또는 `CoinMinusPart`를 클릭하면 코인이 증가/감소합니다.  
5. 게임 종료 후 다시 실행해도 이전 값이 저장되어 유지됩니다.  

[gs25]furniture_custom_sample 의 경우  
4. `Move` 버튼을 누른 상태로 움직이면 파트가 움직입니다.  
5. 파트를 배치 할 수 있는 상태일 경우 마우스 버튼을 놓으면 파트가 배치됩니다.  

## 📷 시연 이미지
[customize_sample_gif](https://github.com/user-attachments/assets/b49534bf-10d4-471b-b518-70ff7ea8efde)  
[datastore_sample_gif](https://github.com/user-attachments/assets/8220e361-4b2c-4782-9226-7f70f9e0f006)
