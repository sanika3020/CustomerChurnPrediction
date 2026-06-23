# Customer Churn Predictor

A high-fidelity predictive analytics dashboard that identifies subscription accounts at risk, runs what-if simulations, and generates personalized customer retention plans. 

100% client-side, deterministic, and free of external API or artificial intelligence dependencies.

---

## 📸 Screenshots

To showcase the dashboard interfaces in your GitHub repository, replace the placeholder paths below with your actual screenshots:

### 1. 
![SS-1](https://github.com/sanika3020/CustomerChurnPrediction/blob/main/CCP-1.png)

### 2. 
![SS-2](https://github.com/sanika3020/CustomerChurnPrediction/blob/main/CCP-2.png)


### 3. 
![SS-3](https://github.com/sanika3020/CustomerChurnPrediction/blob/main/CCP-3.png)


---

## 🛠️ Features

* **Account Fleet Monitoring**: Beautiful dynamic metrics strip showing real-time fleet risk levels, overall active subscribers, service friction averages, and platform cooling rates.
* **Interactive What-If Mutator**: Granular range sliders allowing account managers to dynamically simulate hypothetical engagement drops, ticketing frequency surges, satisfaction adjustments, or dormancy ranges.
* **Algorithmic Churn Risk Scoring**: Clean deterministic logic calculating account vulnerability instantly based on historic lifecycles, ticketing patterns, and engagement levels.
* **Account Registry & Multi-Filters**: Filter subscription tiers (Basic, Pro, Enterprise) or risk categories (High, Medium, Low), with multi-criteria sorting options.
* **Personalized Outreach Planner**: Beautiful strategic workspace detailing precise account issues, direct client engagement email drafts, and tactical checklists.
* **Responsive Visual Charts**: Adaptive visualizations including fleet risk distribution and tier breakdown indicators.
* **Seamless Creation**: Register custom account entries instantly with customizable usage logs.

---

## 🧱 Project Structure

The codebase is highly modular, type-safe, and structured cleanly for ease of maintenance:

```text
├── src/
│   ├── components/
│   │   └── CustomerMetricsOverview.tsx  # Dynamic multi-category metrics strip
│   ├── App.tsx                        # Main workspace layout & state controller
│   ├── data.ts                         # Core subscription data & risk assessment logic
│   ├── types.ts                        # Shared strict TypeScript interfaces
│   └── index.css                       # Font imports and Tailwind configuration
├── index.html                          # Entry layout anchor
├── metadata.json                       # Service registration metadata
├── package.json                        # Project dependencies and workspace scripts
└── tsconfig.json                       # TypeScript compiler settings
