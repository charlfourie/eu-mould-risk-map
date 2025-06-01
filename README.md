# 🌍 Mould Risk Map – Europe Edition

An expanded version of the original [NL Mould Risk Map](https://github.com/charlfourie/nl-mould-risk-map), this project visualises mould risk levels across multiple European countries using weather data from open APIs.

It highlights potential risk areas based on humidity, dew point, temperature, and other factors known to encourage mould growth.

---

## 🚀 What’s New in the EU Version

- ✅ Multi-country support: Netherlands, Germany, France, Belgium (more coming)
- ✅ Scalable API data model (Open-Meteo or similar)
- ✅ Modular logic for risk calculation across regions
- ✅ Country filters and improved map view
- ✅ New folder structure for expansion and collaboration

---

## 🌐 Supported Countries (Initial)

- 🇳🇱 Netherlands
- 🇩🇪 Germany
- 🇫🇷 France
- 🇧🇪 Belgium

More countries will be added over time.

---

## 🧪 Risk Model (Overview)

Risk levels are determined by:
- Consecutive days of high relative humidity (> 70%)
- Dew point proximity to ambient temperature
- Lack of wind and low solar exposure (optional extensions)

This logic is adjustable per country based on local climate norms.

---

## 🧱 Repo Structure

```
/data-sources/         → API queries & regional configs
/public/               → Map assets, JS/CSS
/scripts/              → Main logic for data fetching & risk scoring
/components/           → UI widgets and map overlays
/utils/                → Shared functions (e.g., date conversion, normalisation)
/config/               → Country-specific parameters, thresholds
```

---

## 🛠 How to Run

Coming soon — cloned repo will match setup instructions from the original NL version.

---

## 🤝 Credits

Original idea by [charlfourie](https://github.com/charlfourie)  
Forked from: [github.com/charlfourie/nl-mould-risk-map](https://github.com/charlfourie/nl-mould-risk-map)

---

## 📜 Licence

MIT Licence
