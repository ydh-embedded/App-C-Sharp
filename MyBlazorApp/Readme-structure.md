# Blazor MAUI Projektstruktur

## Hauptordner und Dateien

```
MyBlazorApp/
├── Components/           # Blazor-Komponenten
│   ├── Layout/          # Layout-Komponenten
│   │   ├── MainLayout.razor
│   │   ├── NavMenu.razor
│   │   └── MainLayout.razor.css
│   └── Pages/           # Seiten-Komponenten
│       ├── Home.razor
│       ├── Counter.razor
│       └── Weather.razor
├── Platforms/           # Plattform-spezifische Dateien
│   ├── Android/
│   ├── iOS/
│   ├── MacCatalyst/
│   ├── Tizen/
│   └── Windows/
├── Resources/           # Ressourcen (Bilder, Fonts, etc.)
├── wwwroot/            # Statische Web-Dateien
│   ├── css/
│   │   ├── app.css
│   │   └── bootstrap/
│   └── js/
├── App.razor           # Root-Komponente
├── AppShell.xaml       # Shell-Navigation
├── MainPage.xaml       # MAUI-Wrapper für Blazor
├── MauiProgram.cs      # App-Konfiguration
└── MyBlazorApp.csproj  # Projektdatei
```

## Wichtige Konzepte

### 1. Razor-Komponenten (.razor)
- Mischen HTML, CSS und C#-Code
- Beispiel: `Counter.razor`

### 2. wwwroot Ordner
- Hier können Sie Ihre HTML/CSS/JS-Dateien platzieren
- Wird wie eine normale Web-App behandelt

### 3. CSS-Unterstützung
- Globales CSS in `wwwroot/css/app.css`
- Komponenten-spezifisches CSS mit `.razor.css`
- Bootstrap ist bereits integriert

### 4. Navigation
- Routing funktioniert wie bei Web-Apps
- `@page "/counter"` für URLs

## Wie HTML/CSS eingefügt wird

### Option A: In Razor-Komponenten
```razor
@page "/mypage"
<div class="my-custom-class">
    <h1>Meine Seite</h1>
    <p>HTML direkt in Razor!</p>
</div>

<style>
.my-custom-class {
    background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
    padding: 20px;
}
</style>
```

### Option B: In wwwroot
- Statische HTML-Dateien in `wwwroot/`
- CSS-Dateien in `wwwroot/css/`
- JavaScript in `wwwroot/js/`

### Option C: CSS-Dateien pro Komponente
- `Counter.razor` + `Counter.razor.css`
- Automatisch gekoppelt