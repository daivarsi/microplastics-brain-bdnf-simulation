# Microplastics & Brain BDNF Suppression Simulation

This project simulates the potential long-term impact of microplastic exposure on brain-derived neurotrophic factor (BDNF) levels in the human brain — focusing on daily intake from bottled vs. tap water. It models suppression over the age range 60–80 using biologically grounded parameters drawn from recent scientific literature.

## 🔬 Project Motivation

Microplastics are now found in human organs, including the brain. Studies suggest that chronic exposure may reduce BDNF, a key molecule for memory and neuroplasticity. This simulation explores how daily intake over time could affect brain function.

## 🧠 What the Code Does

- Simulates BDNF decline due **only to plastic exposure** (no aging)
- Uses sigmoid suppression curve based on cumulative plastic retention
- Compares:
  - Bottled Water (~883 microplastics/day)
  - Tap Water (~110 microplastics/day)
- Includes biological clearance (0.01% per day)
- Graphs BDNF over ages 60–80, normalized to 1.0 at age 60

## 📈 Results Summary

- **Tap Water** leads to ~0.25% BDNF reduction over 20 years  
- **Bottled Water** leads to ~2.8% BDNF reduction under same conditions  
- Effects are additive to natural aging-related BDNF decline

## 📚 Scientific Sources Used

- **Mohamed Nor et al., 2021**: Lifetime plastic ingestion estimates  
- **Nature Medicine, 2024**: Human brain plastic loads (5,000–26,000 μg/g)  
- **Kang et al., 2023 / Hou et al., 2023**: Rodent studies linking microplastic exposure to 30–50% BDNF suppression  
- **Erickson et al., 2010**: Aging-related BDNF changes (used for reference only)

Full APA citations included in the Instagram post and documentation.

## 📁 File Contents

- `bdnf_simulation.ipynb` — Main Colab notebook with graph output
- `README.md` — This file
- (Optional) `figures/` — Exported plots for Instagram or slide deck

## 📸 Instagram Post

This simulation was featured in a science communication post on [@thecognitiveengineer](https://www.instagram.com/thecognitiveengineer).

## 🤝 License

MIT License — share, remix, or adapt with credit.

## 💡 Future Work

- Add recovery curves after switching to filtered water
- Layer on BDNF aging decline + disease models (e.g., dementia)
- Extend to include inflammation and oxidative stress pathways

## 🚀 Author
Daivarsi Malik  
[Instagram: @cognitive.engineer](https://instagram.com/cognitive.engineer)  
PhD-track Biomedical Engineer | Applied AI | Cognitive Neuroscience Modeling  
