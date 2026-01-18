# Visual Cluster Analyzer (Preview)

**Unsupervised Image Clustering (Machine Learning)**

Dieses Projekt gruppiert Bilder automatisch nach visueller Ähnlichkeit — ganz ohne Labels. Es nutzt unüberwachtes Lernen, um aus einem Upload von Bildern sinnvolle Cluster zu erzeugen, die anschließend visuell dargestellt und heruntergeladen werden können.

---

![Beispielbild](https://www.mguenther-build.de/static/VCA.png)

---

## Projektziel

- Automatisches Clustering von Bildern basierend auf visuellen Merkmalen
- Anwendung von Machine Learning ohne vorherige Klassifizierung (unsupervised learning)
- Interaktive Visualisierung der Cluster
- Download der geordneten Cluster zur Weiterverwendung

---

## KI-Techniken

- **KMeans** für die Clusterbildung  
- **PCA** zur Dimensionalitätsreduktion und Visualisierung

---

## Verwendete Technologien

| Backend        | Frontend           | ML & Visualisierung     |
|----------------|--------------------|--------------------------|
| Python         | HTML, CSS, Bootstrap | scikit-learn, numpy, pandas |
| Flask          | JavaScript         | Plotly.js, D3.js         |

---

## Projektstruktur (Auszug)

```
visual-cluster-analyzer/
├── main.py
├── app
    ├── static
    ├── templates
    ├── data
    ├── results
    └── routes.py
```
---

## Ablaufidee

1. **Upload** von beliebigen Bildern  
2. **Feature-Extraktion** und Reduktion der Bilddaten  
3. **Clustering** mit KMeans  
4. **Visualisierung** der Cluster in der Web-Oberfläche  
5. **Download** der geordneten Bildergruppen