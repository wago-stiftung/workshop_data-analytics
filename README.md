# Workshop - `Data Analytics am Beispiel einer PV Anlage`

```
WAGO Stiftung Makeathon 2023
```

## How to use

Voraussetzungen: Docker, (VSCode, git)

1. Repo clonen
2. Repo in VSCode öffnen (Dev Container Extension herunterladen, in Dev Container öffnen)
3. Jupyter Notebook -> `Select Kernel` -> `Existing Jupyter Server` -> [localhost:8888/lab?token=makeathon](localhost:8888/lab?token=makeathon)

oder:

1. Repo clonen
2.
```bash
docker build -t makeathon2023/data-analytics ./.devcontainer/
docker run -d -p 8888:8888 -v ./examples/:/makeathon/ makeathon2023/data-analytics
```
3. [localhost:8888/lab?token=makeathon](localhost:8888/lab?token=makeathon) im Browser aufrufen

oder:

Online-Umgebung nutzen: [Try Jupyter](https://jupyter.org/try)


## Datenquellen & Inspiration

- Wetterdaten
    - [Deutscher Wetterdienst](https://opendata.dwd.de/)
    - [OpenWeatherMap](https://openweathermap.org/)
    - [VisualCrossing](https://www.visualcrossing.com/)
    - [Copernicus Climate Data Store](https://cds.climate.copernicus.eu/cdsapp#!/home)

- [Marktstammdatenregister](https://www.marktstammdatenregister.de/MaStR/) - Register Stromerzeugungsanlagen
- [Electricitymaps](https://app.electricitymaps.com/map?lang=de) - Stromerzeugung/-verbrauch und CO₂-Emissionen
- [ENTSO-E Transparency Plattform](https://transparency.entsoe.eu/dashboard/show) - Stromerzeugung/-verbrauch/-transport
- [EMBER](https://ember-climate.org/data/) - Stromerzeugung/-verbrauch, CO₂-Emissionen etc.
- [PV-Dashboard Berlin](https://pv-dashboard.berlin/) - „ Die Berliner Solarwende in Zahlen“
- [Open Power System Data](https://open-power-system-data.org/) - Wind, PV, Wärme...
- [Kaggle](https://www.kaggle.com/search?q=energy+in%3Adatasets) - verschiedenste Datensätze
- [Netzfrequenzmessung](https://www.netzfrequenzmessung.de/leistungen.htm)


## Fragen? => FRAGEN!