# EEOI Calculator 2.0

WPF application that calculates the Energy Efficiency Operational Indicator
(EEOI) for a fleet of vessels and their voyages.

## Overview

Organise work by company, vessel and voyage, enter consumption and fuel types,
and the tool computes the EEOI using the applicable fuel carbon factors, with
charts and Excel export.

## Features

- Company / vessel / voyage hierarchy
- Consumption and fuel-type model
- EEOI computation with carbon factors
- Charts (OxyPlot)
- Excel export
- Built-in user manual

## Tech stack

- WPF, .NET Framework 4.6.1
- OxyPlot, MathNet.Numerics
- Microsoft Office Interop (Excel)

## Repository layout

```
WPF_EEOI_Calculator_v2/
  Model/     Company, Vessel, Voyage, Consumption, FuelTypes, VesselTypes, VoyageTypes
  Helpers/   converters and helpers
  Resources/ EEOI Calculator 2.0 manual (doc/pdf), icons
WPF_EEOI_Calculator_v2.sln
```

## Documentation

`Resources/EEOI Calculator 2.0_Manual.pdf` describes the calculation and usage.
