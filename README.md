# EEOI Calculator 2.0

Windows desktop application that calculates the IMO **Energy Efficiency Operational
Indicator (EEOI)** for a fleet of vessels and their voyages.

---

## At a glance

| | |
| --- | --- |
| **Type** | Windows desktop app (WPF) |
| **Built with** | C# · .NET Framework 4.6.1 |
| **Status** | Stable: no recent changes (published May 2022) |

---

## Features

- **Fleet hierarchy:** companies, vessels and voyages.
- **Consumption entry** per voyage with fuel types and their carbon factors.
- **EEOI calculation** using the fuel carbon factors.
- **Charts** of the results (OxyPlot).
- **Excel export** of the results.
- **User manual** included (PDF and Word).

---

## Requirements

| | |
| --- | --- |
| Operating system | Windows 10 or 11 |
| Runtime | .NET Framework **4.6.1** or newer |
| Build | Visual Studio 2019 or 2022 with the **.NET desktop development** workload |
| Other | Microsoft Excel, for Excel export (Office Interop) |

---

## Building and running

1. Open `WPF_EEOI_Calculator_v2.sln` in Visual Studio.
2. NuGet packages restore automatically on the first build.
3. Build and run with **F5**.

---

## Project structure

```
WPF_EEOI_Calculator_v2.sln
WPF_EEOI_Calculator_v2/
├─ Model/                   Company, Vessel, Voyage, Consumption,
│                           FuelTypes, VesselTypes, VoyageTypes
├─ Helpers/                 converters and helpers
├─ Resources/               user manual (DOC / PDF), icons
├─ About.xaml(.cs)          about window
└─ MainWindow.xaml(.cs)     main window
```

---

## Dependencies

| Package | Used for |
| --- | --- |
| OxyPlot.Wpf | Charts |
| MathNet.Numerics | Calculations |
| Microsoft.Office.Interop.Excel | Excel export |

---

## Documentation

`Resources/EEOI Calculator 2.0_Manual.pdf` explains the calculation method and how
to use the application.

---

## Related projects

- [EEXI Calculator](https://github.com/JRouss1975/EEXI_Calculator): the design-index counterpart for existing ships.

---

## License

Copyright © JRouss1975. All rights reserved.

No license is granted to use, copy, modify or distribute this code without written permission.
