# 🪐 Planetary Positions App

Una aplicación iOS nativa construida con SwiftUI para calcular y visualizar posiciones planetarias reales y cartas astrales.

## ✨ Características

- **Selección de Fecha y Hora**: Elige cualquier fecha y hora para calcular las posiciones planetarias
- **Coordenadas Personalizables**: Ingresa coordenadas geográficas o usa Greenwich, Londres por defecto
- **Posiciones Planetarias Reales**: Cálculos astronómicos precisos
- **Carta Astral Visual**: Rueda zodiacal interactiva con posiciones planetarias
- **Cuadrado de Gann**: Herramienta de análisis astrológico
- **Información Detallada**: Longitud, latitud, distancia y movimiento retrógrado

## 📱 Requisitos

- Xcode 15.0+
- iOS 17.0+
- Swift 5.9+

## 🚀 Instrucciones para Codemagic

### 1. Subir a GitHub

```bash
git init
git add .
git commit -m "Initial commit - Planetary Positions App"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/PlanetaryPositions.git
git push -u origin main
```

### 2. Configurar Codemagic

1. Ve a [codemagic.io](https://codemagic.io)
2. Conecta tu cuenta de GitHub
3. Selecciona el repositorio `PlanetaryPositions`
4. Codemagic detectará automáticamente el archivo `codemagic.yaml`
5. Ejecuta el workflow `planetary-positions-unsigned`

### 3. Descargar el IPA

Una vez completado el build, descarga `PlanetaryPositions_unsigned.ipa` desde la sección de artifacts.

## 📁 Estructura del Proyecto

```
PlanetaryPositions/
├── PlanetaryPositions.xcodeproj/    # Proyecto Xcode
│   └── project.pbxproj
├── PlanetaryPositions/
│   ├── PlanetaryPositionsApp.swift  # Punto de entrada
│   ├── Info.plist                   # Configuración de la app
│   ├── Assets.xcassets/             # Recursos gráficos
│   ├── Views/
│   │   ├── ContentView.swift        # Vista principal
│   │   ├── ZodiacWheelView.swift    # Rueda zodiacal
│   │   ├── PlanetDetailView.swift   # Detalles de planeta
│   │   ├── DegreeFinderView.swift   # Buscador de grados
│   │   ├── GannSquareView.swift     # Cuadrado de Gann
│   │   └── LocationSettingsView.swift # Configuración de ubicación
│   ├── Engine/
│   │   └── AstronomicalEngine.swift # Motor de cálculos astronómicos
│   └── Models/
│       └── AstroViewModel.swift     # Modelo de datos
├── codemagic.yaml                   # Configuración de Codemagic
└── README.md
```

## 🔧 Tecnologías

- **SwiftUI** - Framework de UI declarativo
- **Swift** - Lenguaje de programación
- **Xcode** - IDE de desarrollo

## 📄 Licencia

MIT License
