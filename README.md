PCAM: Unveiling the Uncertainty in Embodied and Operational Carbon of Large Language Models through a Probabilistic Carbon Accounting Model
PCAM is a Probabilistic Carbon Accounting Model for large AI models that enable probabilistic carbon footprint modeling, including both embodied and operational carbon. Read more in our paper [here](https://openreview.net/pdf?id=9QyNYxKeKr). 


### Data Sources for the Carbon Intensity of Electricity
| Regions | Korea | China | Taiwan | USA | Japan | EU | Other | Source |
|---------|-------|-------|--------|-----|-------|----|-------|--------|
| Yearly  | ✓     | ✓     | ✓      | ✓   | ✓     | ✓  | -     | [World in Data](https://ourworldindata.org/grapher/carbon-intensity-electricity?tab=chart) |
| Monthly | ✓     | ✓     | ✓      | ✓   | ✓     | -  | -     | [EMBIR](https://ember-climate.org/countries-and-regions/)  |
| Hourly  | ✓     | -     | ✓      | ✓   | ✓     | -  | ✓     | [ENTSOE](https://transparency.entsoe.eu/dashboard/show?loggedUserIsPrivileged=false) , [ElectricityMaps](https://app.electricitymaps.com/map)  |

### Data Sources for Hardware

| Parameter | Description | Unit | Sources |
|-----------|-------------|------|---------|
| Fabrication capacity | Global wafer fabrication capacity by regions | % | [Industrial report]([https://www.semiconductors.org/wp-content/uploads/2024/05/ReportEmerging-Resilience-in-the-Semiconductor-Supply-Chain.pdf.](https://www.semiconductors.org/wp-content/uploads/2024/05/Report_Emerging-Resilience-in-the-Semiconductor-Supply-Chain.pdf))|
| Energy efficiency | Annual improvement of process energy efficiency across 7-28nm | % | [ESG reports](https://esg.tsmc.com/en-US/resources/ESG-data-hub?tab=reportbuilder)  |
| EPS | Electricity consumed per die Size | kWh/cm² | [Research paper](https://dl.acm.org/doi/10.1145/3632775.3661939)  |
| GPS | Carbon emission from Gas per die Size | g/cm² | [Research paper](https://dl.acm.org/doi/10.1145/3632775.3661939) |
| MPS | Carbon emission from Material used per die Size | g/cm² |  [Research paper](https://dl.acm.org/doi/10.1145/3632775.3661939 |
| BD | Bit density | GB/cm² | [Industrial research reports](https://www.flashmemorysummit.com/English/Collaterals/Proceedings/2017/20170808_FR12_Choe.pdf)  |
| EPG | Electricity consumed per GB | kWh/GB | [LCA reports](https://www.seagate.com/gb/en/esg/planet/product-sustainability/)   |
| Die size | Include popular GPUs and CPUs | mm² | [Industrial reports](https://www.techpowerup.com/gpu-specs/)  |
| Process nodes | Include popular GPUs and CPUs | nm | [Industrial reports](https://www.techpowerup.com/gpu-specs/) |
| Defect density | Defect density trend across time | % | [Industrial reports](https://www.anandtech.com/show/16028)  |
