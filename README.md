# SafePick: Guard-Constrained Robot Escort Policy Evaluation

SafePick implements a **guard-constrained evaluation framework** for warehouse 
human-robot collaboration that:

- Replays **8,535 production warehouse picking waves** under alternative robot 
  escort policies
- Enforces **dual safety contracts**:
  - **Iso-time tolerance (ε)**: Limits schedule drift (0.5-2.0%)
  - **Protective Separation Distance (PSD)**: Conservative human-robot spacing
- Compares three policies: **P0** (human-only baseline), **P1** (escort-trail), 
  **P2** (lead-ahead)
- Decouples **policy quality** from **deployment eligibility** for transparent, 
  auditable evaluation

**Dataset:** 8,535 waves (87.9% retention) from footwear warehouse (58×90m, 
2,292 bins, 3 levels)

## Quick Start
```bash
git clone https://github.com/Sjtu-Fuxilab/Guard-Constrained-HRC.git
cd Guard-Constrained-HRC
pip install -r requirements.txt
export SAFEPICK_DATA="/path/to/data"
jupyter notebook SafePick_Analysis_Pipeline.ipynb
```

## Key Results
- Ergonomic improvement: 5.4-5.8% ΔEHB reduction
- Median time impact: ≤0.34%
- Adoption rate (ε=1.0%): 62.2%
- Digital twin MAPE: 2.96%

## Data
Download from: https://doi.org/10.17632/pf2w725pw3.1

## Citation
```bibtex
@article{safepick2025,
  title={Guard-Constrained Robot Escort Policies for Warehouse Intralogistics},
  author={Zafar, Sanwal Ahmad and Qin, Wei and Chengliang, Liu and Chen, Tiger and Tan, Runzhi},
  year={2025}
}
```

## Contact
- PI: Wei Qin (wqin@sjtu.edu.cn)
- Institution: Shanghai Jiao Tong University, China


