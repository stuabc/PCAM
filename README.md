<img width="660" height="100" alt="image" src="https://github.com/user-attachments/assets/89ed0c71-0ddf-4aac-bfb0-f9bc99c15fc7" /># PCAM: Unveiling the Uncertainty in Embodied and Operational Carbon of Large Language Models through a Probabilistic Carbon Accounting Model
PCAM is a Probabilistic Carbon Accounting Model for large AI models that enable probabilistic carbon footprint modeling, including both embodied and operational carbon. Read more in our paper [here](https://openreview.net/pdf?id=9QyNYxKeKr). 


### Data Sources for the Carbon Emissions of Electricity Energy

| Regions | Korea | China | Taiwan | USA | Japan | EU | Other | Source |
|---------|-------|-------|--------|-----|-------|----|-------|--------|
| Yearly  | ✓     | ✓     | ✓      | ✓   | ✓     | ✓  | -     | World in Data |
| Monthly | ✓     | ✓     | ✓      | ✓   | ✓     | -  | -     | EMBIR  |
| Hourly  | ✓     | -     | ✓      | ✓   | ✓     | -  | ✓     | ENTSOE , ElectricityMaps  |

### Data Sources for Hardware

| Parameter | Description | Unit | Sources |
|-----------|-------------|------|---------|
| Fabrication capacity | Global wafer fabrication capacity by regions | % | Industrial report  |
| Energy efficiency | Annual improvement of process energy efficiency across 7-28nm | % | ESG reports  |
| EPS | Electricity consumed per die Size | kWh/cm² | Research paper  |
| GPS | Carbon emission from Gas per die Size | g/cm² |  |
| MPS | Carbon emission from Material used per die Size | g/cm² | Industrial reports |
| BD | Bit density | GB/cm² | Industrial reports  |
| EPG | Electricity consumed per GB | kWh/GB | LCA reports  |
| Die size | Include popular GPUs and CPUs | mm² | Industrial reports  |
| Process nodes | Include popular GPUs and CPUs | nm | Industrial reports  |
| Defect density | Defect density trend across time | % | Industrial reports  |
