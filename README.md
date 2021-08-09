# Multiple Components of Phylogenetic Non-stationarity in the Evolution of Brain Size in Fossil Hominins

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains codes of the [paper](https://doi.org/10.1007/s11692-019-09471-z) published in Evolutionary Biology. 


## Data 

Hominin's brain sizes (Endocranial Volume) and temporal fossil ranges were gathered from literature ([more details](https://doi.org/10.1007/s11692-019-09471-z)). Hominin's phylogenetic relationship was based on  Dembo *et al.* ([2015](https://doi.org/10.1098/rspb.2015.0943), [2016](https://doi.org/10.1016/j.jhevol.2016.04.008)).   


## How to cite

> Diniz-Filho, J.A.F., Jardim, L., Mondanaro, A. et al. Multiple Components of Phylogenetic Non-stationarity in the Evolution of Brain Size in Fossil Hominins. Evol Biol 46, 47–59 (2019). [https://doi.org/10.1007/s11692-019-09471-z](https://doi.org/10.1007/s11692-019-09471-z).

### Repository structure

```bash
Human_brain_evolution/
├── data
│ ├── hominid_phy.txt
│ ├── hominid_time.txt
│ └── hominid_traits.txt
├── Human_brain_evolution.Rproj
├── LICENSE
├── Outputs
│ ├── AICs_bs.txt
│ ├── eigvec_bs.txt
│ ├── out_pbtree_homidF_bs.txt
│ ├── phylogenies_Bapst.txt
│ ├── PSR.brw_bs.txt
│ ├── PSR.eig_bs.txt
│ ├── PSR.R2_bs.txt
│ └── wAICs_bs.txt
├── R
│ ├── Data_management_analyses.R
│ ├── graphics
│ └── Results.R
└── README.md
```

### Glossary

* hominid_phy.txt - Consensus Hominin phylogeny

* hominid_time.txt - Temporal fossil ranges

* homind_traits.txt - Brain and body size data

* AICs_bs.txt - Akaike Information Criterion of the evolutionary models

* eigvec_bs.txt - Eigenvectors of evolutionary shifts

* out_pbtree_homidF_bs.txt - Analyses outputs

* phylogenies_Bapst.txt - Phylogenetic uncertainty simulated by *paleotree*

* PSR.brw_bs.txt - PSR curve under Brownian motion evolution

* PSR.eig_bs.txt - Observed PSR curve

* PSR.R2_bs.txt - PSR coefficient of determination

* wAICs_bs.txt - Akaike Information Criterion weights of the evolutionary models

## Contributing

Contributions are welcome. Open an issue to discuss the changes. 

## Funding

* Coordenação de Aperfeiçoamento de Pessoal de Nível Superior

* Ministério da Ciência, Tecnologia e Inovações 

* Conselho Nacional de Desenvolvimento Científico e Tecnológico

* Fundação de Amparo à Pesquisa do Estado de Goiás