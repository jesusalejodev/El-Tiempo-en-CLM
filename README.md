# El Tiempo en CLM

## Descripción
Aplicación sencilla para Windows llamada **El Tiempo CLM** que desarrollamos en clase de Desarrollo de Interfaces, utilizando C# y WPF (Windows Presentation Foundation) para crear la interfaz gráfica. Esta aplicación tiene como objetivo proporcionar información meteorológica sobre diferentes municipios.


### API y datos
Se utiliza la API de OpenWeatherMap junto con un archivo JSON donde se encuentran todos los municipios de CLM.

## Funcionamiento
- **Interfaz de usuario**: La aplicación utiliza WPF con XAML para crear una ventana principal interactiva donde se mostrarán los datos meteorológicos.
- **Patrón MVVM**: La estructura de la aplicación se divide en la carpetas de model, view y viewModel, según el patrón MVVM, lo cual permite una clara separación entre la lógica de la aplicación y la interfaz de usuario.

## Requisitos
- .NET Framework versión 6.0
- Windows OS

## Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/jesusalejodev/El-Tiempo-en-CLM.git
