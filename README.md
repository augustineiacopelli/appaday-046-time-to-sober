# 046 — Time to Sober

**AppADay #046 · Category U (Utility) · 2026-06-22**

A blood alcohol content (BAC) estimator and “time until sober” calculator. Enter your body weight and sex, then add drinks from quick presets (beer, craft beer, wine, shot, cocktail) or a custom volume and ABV. The app instantly estimates your current BAC using the Widmark formula and tells you how long until you’re back to 0.00%.

## Features

- Tap-to-add drink presets with quantity steppers
- Custom drink entry by ounces and ABV%
- Real-time BAC estimate with a visual scale from sober to high risk
- Estimated time to return to 0.00% BAC based on standard metabolism rate
- Clear safety disclaimer — estimate only, never a substitute for judgment

## How It Works

BAC is calculated using the Widmark formula:

```
BAC = (alcohol grams / (body weight in grams × r)) × 100
```

where `r` is 0.68 for male and 0.55 for female, reflecting average body water distribution. Alcohol grams are derived from each drink’s volume (oz → ml) and ABV%, using ethanol’s density of 0.789 g/ml. Time to sober assumes a standard elimination rate of 0.015% BAC per hour.

## Disclaimer

This tool provides a rough mathematical estimate only. Individual metabolism, food intake, medications, and health conditions all affect actual BAC. It is not a breathalyzer, not medical advice, and not a legal measurement. Never use it to decide whether it’s safe to drive.

## Live URL

<https://augustineiacopelli.github.io/appaday-046-time-to-sober/>

-----

[← Back to AppADay Portfolio](https://augustineiacopelli.github.io/appaday/)
