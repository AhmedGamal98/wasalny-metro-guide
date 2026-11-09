# Wasalny: Cairo Metro Guide

> **Wasalny** (وصلني, "get me there") is a Windows desktop app that helps Cairo Metro riders plan a trip between stations on Line 1 (Helwan to Maadi). Built with C# WinForms.

![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)
![.NET Framework](https://img.shields.io/badge/.NET%20Framework%204.5-WinForms-512BD4?logo=dotnet&logoColor=white)

## Features

- **Accounts:** sign up, log in, edit or delete your account. Accounts are stored as local files in `data/`.
- **Trip planner:** enter your current station and your destination to get the trip details.
- **Station map buttons:** pick stations directly from the line map (Helwan, Ain Helwan, Helwan University, Wadi Hof, Hadayek Helwan, El-Maasara, Tora El-Asmant, Kozzika, Tora El-Balad, Thakanat El-Maadi, Hadayek El-Maadi, Maadi).

## Project structure

```
Wasalny/
├── Wasalny.sln
└── Wasalny/
    ├── start_frm.cs, Form1.cs        Start and login screens
    ├── sign_up_frm.cs, acc_frm.cs    Sign up and account screens
    ├── edit_frm.cs                   Edit account
    ├── main_frm.cs                   Trip planner
    ├── stations/                     One file per station (copied next to the app on build)
    └── data/                         Created at build time; stores user accounts
```

## Run it

1. Open `Wasalny/Wasalny.sln` in Visual Studio (any version with .NET Framework 4.5 support).
2. Build and run (F5). The `stations` and `data` folders are copied to the output folder automatically.

## Author

**Ahmed Gamal Saber**, Full-Stack Web Developer & AI Engineer
[LinkedIn](https://linkedin.com/in/ahmed-gamal-saber-382081169) · [GitHub](https://github.com/AhmedGamal98)
