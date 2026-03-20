# AWSI — August Wilhelm Scheer Institut

Code written during a research stay at the August Wilhelm Scheer Institut, mostly data visualizations and analysis notebooks.

## Project Structure

```
├── insect-detect/          # Object detection for Black Soldier Fly larvae
│   ├── videos/             # Raw video recordings
│   ├── example.ipynb       # Example notebook (image import, preprocessing, detection)
│   └── README.md           # Detailed notes and todos
│
├── matrix/                 # Research focus and emissions matrix analysis
│   ├── research-focus-matrix.ipynb
│   ├── emissions-by-sector.xlsx
│   └── emissions-savings-potential.xlsx
│
├── emissions/              # Substance emission analysis and visualization
│   ├── graphs.ipynb        # Plotting notebook
│   ├── emissions.csv       # Raw emissions data
│   ├── totals-sums.csv     # Aggregated totals
│   ├── graph1.png          # Output graph 1
│   ├── graph2.png          # Output graph 2
│   ├── output1.png         # Additional output
│   └── graph-descriptions.txt
│
└── trend-graphs/           # CO2 savings trend analysis
    ├── trend-graphs.ipynb
    └── co2-savings-insects.xlsx
```

## Topics

- **Insect Detection** — Computer vision pipeline for detecting and tracking Black Soldier Fly larvae using pre-trained object detection models
- **Emission Analysis** — Graphs and visualizations of substance emissions by sector and savings potentials, produced for the paper [*Strategic Returns Prevention in E-Commerce: Simulating Financial and Environmental Outcomes Through Agent-Based Modeling*](https://www.scitepress.org/Papers/2025/131806/131806.pdf) (SciTePress, 2025)
- **Trend Analysis** — CO2 savings trend graphs for insect-based approaches

## Resources

- [Miro Board](https://miro.com/app/board/uXjVM7JCyIg=/?share_link_id=817114007209)
- [ML Framework: PyTorch](https://pytorch.org/)
- [Object Detection Models](https://paperswithcode.com/task/multi-object-tracking)
