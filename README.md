# Hollis

Computer Science student at the University of Bath (graduating 2029), building toward a placement year in AI engineering and quantitative finance. Based in Hong Kong.

## Technical Skills

- **Languages:** Python, C, Java, SQL, Haskell, JavaScript, HTML/CSS, GDScript
- **ML / Data:** scikit-learn, NumPy, Optuna, YOLOv8
- **Web:** React, Vite, Node.js, Chart.js
- **Tools:** Git, Docker, NPM

## Experience
 
**AI Engineering Intern, RapportAI Medical** — *Ongoing*
- Shipped full-text search feature for a clinical transcription platform using FastAPI, DynamoDB, and GSI design, backfilling 813/824 records (98.7%) for org-level multi-tenancy with zero service disruption
- Built a PHI-safe ASR evaluation pipeline in Python for Cantonese/English clinical radiology dictation, benchmarking 6 STT systems using exact mixed-script alignment, OpenCC normalization, and measurement-specific F1 scoring, identifying the top performer with a 16.7% relative WER reduction and 10% higher measurement F1 compared to baseline
- Independently identified the hill-climbing scheduler as unreliable and led its re-architecture to Google OR-Tools CP-SAT. Replacing heuristic approximations with mathematically-proven optimal results, integrated via a feature-flagged async job pipeline into a live Node.js/React application
- Introduced automated testing into a GitHub Actions CI/CD pipeline as a merge-gating check and integrated support for a new clinical audio file format (DS2), improving release quality and platform interoperability

  
**Machine Learning Intern, AWS**
- Built a classification model on a 46,000-sample dataset, improving accuracy by 24% using logistic regression, decision trees, and neural networks
- Presented project outcomes to industry stakeholders following a 4-week build
## Research
 
- Authored 112 culturally grounded Hong Kong Cantonese QA pairs for an NLP research dataset accepted at EMNLP 2026 and quality-checked 13 teammate-authored entries for factual accuracy, translation quality, sourcing, and duplication

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
