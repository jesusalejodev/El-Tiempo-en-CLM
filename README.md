# El Tiempo en CLM

## Descripción
Aplicación sencilla para Windows llamada **El Tiempo CLM** que desarrollamos en clase de Desarrollo de Interfaces, utilizando C# y WPF (Windows Presentation Foundation) para crear la interfaz gráfica. Esta aplicación tiene como objetivo proporcionar información meteorológica sobre diferentes municipios.


### App.xaml y App.xaml.cs
- **App.xaml**: Este archivo configura los recursos de la aplicación y gestiona el inicio de la misma.
- **App.xaml.cs**: Contiene la lógica de arranque de la aplicación, permitiendo inicializar componentes y configurar la ventana principal.

### Municipios.csproj
- Este archivo define las propiedades del proyecto, como las dependencias y las configuraciones necesarias para compilar la aplicación. Es fundamental para asegurar que el proyecto se construya correctamente.

### MainWindow.xaml y MainWindow.xaml.cs
- **MainWindow.xaml**: Diseña la ventana principal de la aplicación, donde se presentarán los datos meteorológicos de los municipios.
- **MainWindow.xaml.cs**: Contiene el código detrás para manejar eventos e interacciones de la ventana principal, asegurando que la aplicación responda a las acciones del usuario.

### ViewModel.cs
- Este archivo sigue el patrón de diseño MVVM (Model-View-ViewModel), que sugiere que la lógica de la aplicación está separada de la interfaz de usuario. `ViewModel.cs` maneja la lógica que conecta los datos con la vista, facilitando la interacción del usuario con la información.

### Modelos (MunicipioAux.cs, RootMunicipios.cs, RootTiempo.cs)
- Estos archivos definen clases que modelan los datos de los municipios y el tiempo, lo que indica que la aplicación está trabajando con información geográfica y meteorológica de diferentes localidades.

## Funcionamiento
- **Interfaz de usuario**: La aplicación utiliza WPF con XAML para crear una ventana principal interactiva donde se mostrarán los datos meteorológicos.
- **Patrón MVVM**: El uso de `ViewModel.cs` indica que la aplicación sigue el patrón MVVM, lo que es típico en aplicaciones WPF, permitiendo una clara separación entre la lógica de la aplicación y la interfaz de usuario.

## Requisitos
- .NET Framework versión 6.0
- Windows OS

## Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/jesusalejodev/El-Tiempo-en-CLM.git
