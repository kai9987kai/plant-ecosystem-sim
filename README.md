
# 🌱 Frontier Plant Ecosystem Simulation

An experimental, browser-based plant ecosystem simulator built with vanilla HTML, CSS, and JavaScript.  
It models a small “digital twin” greenhouse where plants grow, react to changing environmental conditions, pass genetic traits into future generations, and generate live ecosystem telemetry.

The project is designed as an interactive learning lab for plant growth, genetics, environmental stress, resource management, and simulation design.

---

## ✨ Overview

**Frontier Plant Ecosystem Simulation** turns a simple plant-growing game into a living systems sandbox.

You can plant seeds, adjust greenhouse conditions, scan phenotypes, tune plant behaviour, mutate the seed bank, and harvest mature plants. The simulation focuses on the relationship between:

- **G — Genetics**
- **E — Environment**
- **M — Management**

This makes it useful as a creative prototype for ecosystem simulations, digital agriculture interfaces, artificial-life experiments, and educational science tools.

---

## 🚀 Features

### 🌿 Plant Growth Simulation
- Grow plants from seed to maturity.
- Watch height, health, and visual state change over time.
- Harvest mature fruiting plants to build the yield bank.

### 🧬 Genetic Traits
Each plant can carry different trait values that influence behaviour such as:

- Growth potential
- Stress tolerance
- Nutrient efficiency
- Environmental resilience
- Yield performance

Strong plants can pass lightly mutated genes into the seed bank, creating a simple evolutionary loop.

### 🌦️ Dynamic Weather & Climate Stress
The simulation includes changing weather and greenhouse conditions that affect plant performance.

Current greenhouse/environment controls include:

- Nutrients
- Water
- Light
- Temperature
- Soil pH
- Weather state
- Forecast/event feedback

### 🧪 Phenotype Scan
Use the phenotype scan feature to inspect plant performance and identify useful traits.

The telemetry panel tracks:

- Plant count
- Average height
- Average health
- Current generation
- Selected plant
- Best gene
- Yield bank
- Eco score

### 🤖 AI Tune Concept
The AI tuning feature is a simulation-facing control designed to support smarter balancing of plant traits, environment, and management decisions.

It can be expanded into future adaptive systems such as:

- Auto-balancing greenhouse controls
- Trait recommendation
- Growth prediction
- Stress warnings
- Yield optimization

### 🧫 Mutate Seeds
Mutate the available seed bank to explore genetic variation and encourage different plant outcomes across generations.

### ⚡ Adjustable Simulation Speed
Run the ecosystem at different speeds:

- `1x`
- `2x`
- `10x`

Useful for slow observation, fast testing, and rapid generation experiments.

### 📱 Responsive Single-Page App
The project runs directly in the browser with no build step required.

---

## 🖥️ Live / Local Use

You can run the project by opening `index.html` directly in a modern browser.

For the most reliable local testing, you can also serve it with a simple local server:

```bash
git clone https://github.com/kai9987kai/plant-ecosystem-sim.git
cd plant-ecosystem-sim
python -m http.server 8000
````

Then open:

```text
http://localhost:8000
```

---

## 📁 Project Structure

```text
plant-ecosystem-sim/
├── index.html              # Main simulation app
├── README.md               # Project documentation
├── LICENSE                 # MIT license
├── CODE_OF_CONDUCT.md      # Contributor Covenant code of conduct
└── SECURITY.md             # Security policy
```

---

## 🎮 How to Use

1. Open the simulation in your browser.
2. Click a soil bay or use the **Plant** button to add a seed.
3. Adjust the greenhouse sliders:

   * Nutrients
   * Water
   * Light
   * Temperature
   * Soil pH
4. Watch plant height, health, and ecosystem score change.
5. Use **Phenotype Scan** to inspect traits and plant state.
6. Use **AI Tune** to experiment with adaptive balancing.
7. Use **Mutate Seeds** to introduce variation into future plants.
8. Harvest mature plants to collect yield and continue the growth loop.
9. Change the speed to observe the simulation slowly or accelerate testing.

---

## 🧠 Simulation Concepts

### Genetics

Plants can carry trait values that affect how they respond to the greenhouse environment. These traits influence growth, health, and survival.

### Environment

Weather, light, water, nutrients, pH, and temperature all shape plant outcomes. A strong plant in one environment may struggle in another.

### Management

The player acts as the greenhouse manager, changing resources and conditions to improve growth, yield, and resilience.

### Evolution Loop

Harvesting and mutation create a basic generational feedback system. Over time, the seed bank can shift toward stronger or more interesting traits.

---

## 📊 Telemetry

The simulator includes a live dashboard for understanding the ecosystem state.

| Metric         | Meaning                                |
| -------------- | -------------------------------------- |
| Plants         | Current number of active plants        |
| Average Height | Mean plant height across the ecosystem |
| Average Health | Overall ecosystem health               |
| Generation     | Current genetic generation             |
| Selected       | Currently inspected plant              |
| Best Gene      | Strongest observed genetic trait       |
| Yield Bank     | Harvested output                       |
| Eco Score      | Overall ecosystem performance          |

---

## 🔬 Research-Inspired Direction

This project is inspired by modern ideas in:

* Plant digital twins
* Functional plant modelling
* High-throughput phenotyping
* Genotype × environment × management analysis
* Controlled-environment agriculture
* AI-assisted plant monitoring
* Artificial life and evolutionary simulation

The goal is not to be a scientifically exact crop model yet, but to act as an approachable creative prototype for exploring those ideas interactively.

---

## 🛣️ Roadmap Ideas

Future versions could add:

### 🌱 More Plant Types

* Different species
* Species-specific genetics
* Unique growth curves
* Flowering and fruiting stages

### 🐛 Pests & Disease

* Pest outbreaks
* Disease spread
* Resistance genes
* Treatment choices

### 🌗 Day/Night Cycle

* Light changes over time
* Circadian-style growth effects
* Night recovery periods

### 🧬 Deeper Genetics

* Dominant/recessive traits
* Heritable stress tolerance
* Seed lineage tracking
* Trait history charts

### 📈 Data & Charts

* Growth graphs
* Health history
* Yield trends
* Weather impact charts
* Gene performance comparison

### 🤖 Smarter AI Tuning

* Rule-based greenhouse assistant
* Predictive yield hints
* Auto-adjusted water/light/nutrients
* Explainable recommendations

### 💾 Save / Load

* Save ecosystem state
* Export seed banks
* Import experiments
* Share simulation presets

### 🧪 Experiment Presets

* Drought stress test
* Low nutrient challenge
* High temperature trial
* Mutation lab mode
* Maximum yield mode

---

## 🧰 Tech Stack

* HTML
* CSS
* Vanilla JavaScript
* Browser-based simulation logic
* No required build step

---

## 🤝 Contributing

Contributions are welcome.

Ideas for useful contributions:

* Improve simulation realism
* Add better plant visuals
* Add charts and analytics
* Expand genetics
* Improve mobile layout
* Add accessibility improvements
* Refine the UI/UX
* Add save/load support
* Improve documentation

Suggested workflow:

```bash
git clone https://github.com/kai9987kai/plant-ecosystem-sim.git
cd plant-ecosystem-sim
git checkout -b feature/my-improvement
```

After making changes:

```bash
git add .
git commit -m "Add my improvement"
git push origin feature/my-improvement
```

Then open a pull request.

---

## 🔐 Security

If you find a vulnerability or unsafe behaviour, please report it through the repository’s security process rather than opening a public issue.

---

## 📜 License

This project is licensed under the MIT License.

See [`LICENSE`](LICENSE) for details.

---

## 🙌 Acknowledgements

Inspired by ecosystem simulations, farming games, digital twin research, artificial-life systems, and controlled-environment agriculture tools.

---

## 🌱 Project Status

Active experimental prototype.

The current version focuses on interactive plant growth, greenhouse controls, simple genetics, mutation, harvesting, telemetry, and research-inspired simulation design.

```
::contentReference[oaicite:1]{index=1}
```

[1]: https://github.com/kai9987kai/plant-ecosystem-sim/tree/main "GitHub - kai9987kai/plant-ecosystem-sim: An interactive plant growth simulation built with vanilla JavaScript. Features genetic traits, weather effects, and adjustable speed controls. Grow and harvest plants in a dynamic ecosystem! · GitHub"
