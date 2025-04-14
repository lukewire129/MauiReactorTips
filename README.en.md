## 🇺🇸 English

### ✅ MauiReactor Update

#### 🔧 Update HotReload Tool
```bash
dotnet tool update -g Reactor.Maui.HotReload
```

#### 📦 Update Template
```bash
dotnet new update
```
---
### 🚀 Run MauiReactor HotReload
🔹 **[Normal Mode]**
- Android
```bash
dotnet-maui-reactor -f net9.0-android
```
- iOS

```bash
dotnet-maui-reactor -f net9.0-ios
```
- Windows

```bash
dotnet-maui-reactor -f net9.0-windows10.0.19041.0
```
🔸 **[Full Mode]**
- Android

```bash
dotnet-maui-reactor -f net9.0-android --mode Full
```
- iOS
```bash
dotnet-maui-reactor -f net9.0-ios --mode Full
```
- Windows
```bash
dotnet-maui-reactor -f net9.0-windows10.0.19041.0 --mode Full
```

