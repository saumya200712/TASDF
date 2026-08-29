\# TASDF



\*\*Trajectory-Adaptive Semantic Deception Framework (TASDF)\*\* is a cyber-deception framework designed to adapt a multi-layer shadow environment based on the attacker's evolving behavior and estimated world model.



The framework combines:



\* Trajectory encoding

\* Belief-state estimation

\* Multi-layer shadow-network generation

\* Commitment-driven engagement



\## Requirements



\* Python 3.10+

\* Google Colab or Jupyter Notebook



Install the required packages:



```bash

pip install -r requirements.txt

```



\## Run



Open and run:



`TASDF\_complete\_pipeline.ipynb`



The notebook contains the complete experimental implementation, including the main experiments, baselines, ablation studies, statistical analysis, and visualization.



\## Repository Structure



```text

TASDF/

├── TASDF\_complete\_pipeline.ipynb

├── requirements.txt

├── README.md

├── results/

│   ├── raw\_results.csv

│   ├── summary\_metrics.csv

│   └── wilcoxon\_stats.csv

├── figures/

│   ├── fig1\_ttd\_boxplot.png

│   ├── fig2\_tcar\_boxplot.png

│   ├── fig3\_scs\_boxplot.png

│   ├── fig4\_ablation\_radar.png

│   ├── fig5\_ttd\_violin.png

│   └── fig6\_cumulative\_absorption.png

├── data/



```



\## Results



The `results/` directory contains the experimental results, while the `figures/` directory contains the generated visualizations.



\## Reproducibility



The experiments use a fixed random seed of \*\*42\*\*. The implementation was developed and tested using Python 3.10 and Google Colab.



\## Authors



\*\*Saumya Mishra\*\*

Original implementation and experimental work.



\*\*Wejdan Ali Almutiri\*\*

Methodology, validation, review, and editing.



\*\*Shailendra Mishra\*\*

Supervision.



\## Citation



The DOI and final publication information will be added after the research is formally deposited.



