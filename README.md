# 🛍️ Work Together! GS25 Sample (Roblox)

3가지 샘플을 포함한 Roblox 게임 시스템 모음입니다. 각 샘플은 `.rbxm` 파일로 제공되며, Studio에서 바로 실행 가능합니다.  

## 📚 목차

- [1. 🪙 Coin DataStore Sample](#1-coin-datastore-sample)  
- [2. 🛠️ Part Customize Sample](#2-part-customize-sample)  

---

## 1. Coin DataStore Sample (데이터 업데이트 샘플)
플레이어 코인을 저장하고 불러오는 기능을 포함한 샘플입니다.  

## 🚀 주요 기능  
> - 마우스로 Part 클릭  
> - 코인 데이터 증가 또는 감소  
> - 서버에서 업데이트 된 데이터 저장  

## 파일 구조  
ReplicatedStorage/  
└── CoinData  
ServerScriptService/  
├── DataStore2  
└── CoinUpdateTester  
Workspace/  
├── CoinPlusPart  
└── CoinMinusPart   

## 📦 실행 방법
1. `.rbxm` 파일을 Roblox Studio에 드래그 후 ServerScriptService에 위치시킵니다.
2. `CoinPlusPart` 또는 `CoinMinusPart`를 클릭하면 코인이 증가/감소합니다.  
3. 재접속 시 데이터 저장 여부 확인이 가능합니다.

## 📷 시연 이미지
[datastore_sample_gif](https://github.com/user-attachments/assets/8220e361-4b2c-4782-9226-7f70f9e0f006)

---

## 2. Part Customize Sample  (파츠 색상 변경 샘플)
파트 위치를 변경하는 기능을 포함한 샘플입니다.

## 🚀 주요 기능  
> - 마우스로 Move UI 클릭 -> 배치 시스템 발동  
> - 마우스 누른채로 움직이기 -> 실시간 파트 움직임 반영  
> - 마우스 놓기 -> 배치 시스템 종료  

## 파일 구조
ReplicatedStorage/  
└── FurnitureCustomizeModule  
StarterGui  
└── BillboardGui  
StarterPlayer  
└── StarterPlayerScripts  
│ └── FurnitureCustomizeController  
Workspace  
└── TestPart (Part)  

## 📦 사용 방법
1. `.rbxm` 파일을 Roblox Studio에 드래그 후 의 ServerScriptService에 위치시킵니다.  
2. `Move` 버튼을 누른 상태로 마우스를 움직이면 파트가 움직입니다.  
3. 파트를 배치 할 수 있는 상태일 경우 마우스 버튼을 놓으면 파트가 배치됩니다.  

## 📷 시연 이미지 
[customize_sample_gif](https://github.com/user-attachments/assets/b49534bf-10d4-471b-b518-70ff7ea8efde) 
