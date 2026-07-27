# Hollis

Computer Science student at the University of Bath (graduating 2029), building toward a placement year in AI engineering and quantitative finance. Based in Hong Kong.

## Technical Skills

- **Languages:** Python, C, Java, SQL, Haskell, JavaScript, HTML/CSS, GDScript
- **ML / Data:** scikit-learn, NumPy, Optuna, YOLOv8
- **Web:** React, Vite, Node.js, Chart.js
- **Tools:** Git, Docker, NPM

## Experience
 
**AI Engineering Intern, RapportAI Medical** — *Ongoing*
- Building search infrastructure for a clinical transcription platform: designed and shipped a full-text accession-number search feature (FastAPI, DynamoDB, AWS ECS), including doctor- and org-scoped access control, index provisioning, and data backfill migrations
- Debugging a hill-climbing rota scheduler for A&E doctor shift assignment, now moving toward a constraint-programming (OR-Tools CP-SAT) rewrite
  
**Machine Learning Intern, AWS**
- Built a classification model on a 46,000-sample dataset, improving accuracy by 24% using logistic regression, decision trees, and neural networks
- Presented project outcomes to industry stakeholders following a 4-week build
## Research
 
- Contributing to a Cantonese/Chinese question-answering dataset accepted at EMNLP 2026

## Featured Projects

### BetaBot — Climbing Hold Detection and Route Generation
Flagship project combining computer vision and pathfinding to detect climbing holds and generate routes.
- Trained YOLOv8n on a custom-labeled climbing hold dataset, achieving 74.1% mAP
- Implemented A* pathfinding for automated route generation
- Built a FastAPI backend with a React/Vite frontend
- [Repository](https://github.com/Silloh23/betabot)

### F1 Race Strategy Optimiser
Quantitative simulation project modelling race strategy under uncertainty.
- Built a modular race simulation modelling lap-time evolution, tire degradation, pit-stop loss, and stochastic noise
- Ran Monte Carlo simulations (500 runs per strategy) to estimate probabilistic race outcomes
- Used Bayesian optimisation (Optuna) to search pit-stop timing strategies and minimise expected race time
- Quantified uncertainty with 95% confidence intervals for statistically robust strategy comparison
- [Repository](https://github.com/Silloh23/f1_race_sim)

### Damage Claim Verifier
Multi-agent LLM pipeline built for HackerRank Orchestrate.
- Orchestrated multiple models (Groq, LLaMA 4 Maverick, Claude 3.5 Sonnet) with SHA-256-based caching
- Improved verification accuracy from 15% to 30% through iterative debugging

### Bot Racers
2D side-scroller in which evolved bipedal robots race against each other.
- Built an evolutionary training pipeline (selection, crossover, mutation) via a Genetic Algorithm to optimise racing agents
- Simulated bipedal locomotion using joint-based physics constraints
- Added procedural track generation to improve agent generalisation
- Built in Godot 4 (GDScript)
- [Repository](https://github.com/Silloh23/bot-racers)

### AWS Classification Task
Classification model on a 46,000-sample dataset.
- Improved baseline accuracy by 24% using logistic regression, decision trees, and neural networks
- Used sklearn and Optuna for model selection and hyperparameter tuning
- Presented project outcomes to New Zealand Executives following a 4-week build

## Contact

- LinkedIn: https://www.linkedin.com/in/hollis-l-95a014371
- Email: apskt347656@gmail.com
