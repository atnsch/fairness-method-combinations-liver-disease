# Daten

Dieser Ordner enthält die beiden unveränderten Rohdatensätze, die in der Bachelorarbeit verwendet werden. Beide Datensätze werden vom UCI Machine Learning Repository unter der Lizenz Creative Commons Attribution 4.0 International (CC BY 4.0) bereitgestellt.

## Dateien und Quellen

| Datensatz | Datei im Repository | Offizielle Quelle | DOI | Lizenz |
| --- | --- | --- | --- | --- |
| ILPD (Indian Liver Patient Dataset) | `Indian Liver Patient Dataset (ILPD).csv` | [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/225/ilpd%2Bindian%2Bliver%2Bpatient%2Bdata) | [10.24432/C5D02C](https://doi.org/10.24432/C5D02C) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| HCV data | `hcvdat0.csv` | [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/571/hcv%2Bdata) | [10.24432/C5D612](https://doi.org/10.24432/C5D612) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

## Eigenschaften der Rohdateien

| Datei | Datensätze | Spalten | Kopfzeile | Fehlende Werte |
| --- | ---: | ---: | --- | --- |
| `Indian Liver Patient Dataset (ILPD).csv` | 583 | 11 | Nein | 4 in der Spalte für das Albumin-Globulin-Verhältnis |
| `hcvdat0.csv` | 615 | 14 | Ja | Insgesamt 31: ALB 1, ALP 18, ALT 1, CHOL 10, PROT 1 |

Die ILPD-Datei muss eingelesen werden, ohne ihre erste Zeile als Kopfzeile zu interpretieren. Die Spaltennamen werden während der Datenvorbereitung programmgesteuert zugewiesen. Die erste Spalte von `hcvdat0.csv` ist der ursprüngliche Datensatzidentifikator.

## Dateiintegrität

Die im Repository gespeicherten Kopien wurden mit den Dateien aus den offiziellen UCI-Downloadarchiven verglichen. Die SHA-256-Prüfsummen lauten:

```text
84feac16488de5cf89bd22bd802c77f25841fe93e9ddd32355683e94d46c3425  Indian Liver Patient Dataset (ILPD).csv
1b62c8453b7098b695c549b19cfe070458ce6b909f0e990b6cfce7ab3c44c273  hcvdat0.csv
```

Die Rohdateien dürfen nicht bearbeitet oder neu gespeichert werden. Sämtliche Vorverarbeitungs- und Zielvariablentransformationen erfolgen programmgesteuert, ohne die Quelldateien zu überschreiben.

## Zitierangaben

- Ramana, B., & Venkateswarlu, N. (2022). *ILPD (Indian Liver Patient Dataset)* [Datensatz]. UCI Machine Learning Repository. https://doi.org/10.24432/C5D02C
- Lichtinghagen, R., Klawonn, F., & Hoffmann, G. (2020). *HCV data* [Datensatz]. UCI Machine Learning Repository. https://doi.org/10.24432/C5D612

Die Lizenz CC BY 4.0 gilt ausschließlich für die in diesem Ordner enthaltenen Datensatzdateien.
