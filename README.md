# 📊 Social Blade Dashboard — C# WPF

A **Material Design** inspired Social Blade dashboard UI built with **C# WPF** and the **Material Design in XAML Toolkit**. A clean, modern desktop application that replicates the Social Blade analytics dashboard experience.

> 🎬 Built as part of a YouTube tutorial by [CCode Academy](https://www.youtube.com/c/CCodeAcademy)

---

## ✨ Features

- **Material Design UI** — built with the Material Design XAML Toolkit for a modern, clean look
- **Social Blade–style Dashboard** — channel stats, subscriber growth, and analytics layout
- **Multi-window navigation** — `MainWindow` for entry, `Dashboard` for the analytics view
- **WPF + XAML** — fully designed using XAML with code-behind in C#
- **Clean layout** — structured with WPF Grid and StackPanel for proper alignment

---

## 🛠️ Tech Stack

| Technology | Details |
|---|---|
| Language | C# (.NET) |
| UI Framework | WPF (Windows Presentation Foundation) |
| Design Toolkit | [Material Design in XAML](http://materialdesigninxaml.net/) |
| IDE | Visual Studio |

---

## 📁 Project Structure

```
Social-Blade-Dashboard-C-WPF-/
├── Images/                        # Image assets used in the UI
├── App.xaml                       # Application entry point & resource dictionaries
├── App.xaml.cs                    # App startup logic
├── MainWindow.xaml                # Main landing window
├── MainWindow.xaml.cs             # Main window logic
├── Dashboard.xaml                 # Dashboard UI layout (XAML)
├── Dashboard.xaml.cs              # Dashboard logic & data binding
├── AssemblyInfo.cs                # Assembly metadata
├── Social Blade Dashboard.csproj  # Project file
├── Social Blade Dashboard.sln     # Visual Studio solution file
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [Visual Studio 2019 or later](https://visualstudio.microsoft.com/)
- .NET Framework / .NET 6+
- [Material Design in XAML Toolkit](http://materialdesigninxaml.net/) — installed via NuGet

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/LukeshPawar/Social-Blade-Dashboard-C-WPF-.git
   ```

2. **Open the solution in Visual Studio**
   ```
   Social Blade Dashboard.sln
   ```

3. **Restore NuGet packages**
   - Go to `Tools` → `NuGet Package Manager` → `Restore NuGet Packages`
   - Or run in the Package Manager Console:
     ```
     Install-Package MaterialDesignThemes
     Install-Package MaterialDesignColors
     ```

4. **Build and Run**
   - Press `Ctrl + Shift + B` to build
   - Press `F5` to run

---

## 📦 Dependencies

Install via NuGet Package Manager:

```
Install-Package MaterialDesignThemes
Install-Package MaterialDesignColors
```

---

## 🎬 Tutorial Reference

This project was built following a YouTube tutorial:

- **Video:** [Social Blade Dashboard in WPF](https://youtu.be/qSP8v8Gi3XU)
- **Channel:** [CCode Academy](https://www.youtube.com/c/CCodeAcademy)
- **Toolkit Docs:** [materialdesigninxaml.net](http://materialdesigninxaml.net/)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 👤 Author

**Lukesh Pawar**  
[GitHub](https://github.com/LukeshPawar)
