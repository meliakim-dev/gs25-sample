# 🏪 Work Together! GS25 Sample (Roblox)

This is a collection of Roblox game systems that includes 2 samples. Each sample is provided as an .rbxm file and can be run directly in Studio.  

🔗 [Play the actual game on Roblox](https://www.roblox.com/ko/games/9966461491/Work-Together-GS25)

## 📚 Contents

- [1. 🪙 DataStore Sample](#1-datastore-sample)  
- [2. 🛠️ Furniture Custom Sample](#2-furniture-custom-sample)  

---

## 1. DataStore Sample  
This is a sample that includes the ability to save and load player coins.  

## 🚀 Key Features 
> - Data management using Datastore2
> - Centralized data setup with DataInitializer

## 🏷️ File Structure  
ReplicatedStorage/  
└── CoinData  
ServerScriptService/  
├── DataStore2  
└── CoinUpdateTester  
Workspace/  
├── CoinPlusPart  
└── CoinMinusPart   

## 🎮 How To Use
1. Drag the `.rbxm` file into Roblox Studio and place it in ServerScriptService.  
2. Clicking `CoinPlusPart` or `CoinMinusPart` will increase/decrease the number of coins.  
3. You can check whether data is saved when you reconnect.  

## 📷 Demo Image
![datastore_sample_gif](https://github.com/user-attachments/assets/8220e361-4b2c-4782-9226-7f70f9e0f006)

---

## 2. Furniture Custom Sample
This is a sample that includes a function to change the part position.  

## 🚀 Key Features
> - Customization logic managed through a centralized handler
> - UI and mouse-driven connection control
> - placement system with collision checking (non-grid based)

## 🏷️ File Structure  
ReplicatedStorage/  
└── FurnitureCustomizeModule  
StarterGui  
└── BillboardGui  
StarterPlayer  
└── StarterPlayerScripts  
│ └── FurnitureCustomizeController  
Workspace  
└── TestPart (Part)  

## 🎮 How To Use
1. Drag the `.rbxm` file into Roblox Studio and place it in ServerScriptService.  
2. Move the mouse while holding down the `Move` button to move the part.  
3. When the part is ready to be placed, release the mouse button to place the part.  

## 📷 Demo Image
![customize_sample_gif](https://github.com/user-attachments/assets/b49534bf-10d4-471b-b518-70ff7ea8efde) 
