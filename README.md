## Aditya Palit

High school developer working at the intersection of physics, machine learning, and software. I learn by building.

I'm a rising senior at Mission San Jose High School in Fremont, CA, headed toward physics and AI/ML. I build full-stack and machine-learning projects, compete at the Gold level of the USA Computing Olympiad, and run independent research applying ML to astrophysics. Recent highlights: 3rd place nationally in the Modeling the Future Challenge, a USA Physics Olympiad Honorable Mention, and an AIME qualification.

I build in public to turn ideas into working tools and to learn each technology end to end. These repos show how I approach problems across ML, web, and scientific computing:

**What I'm building:**

**Galaxy Spectra ML** -- Classifying galaxies by hand does not scale to modern sky surveys. This analyzes ~4,000 galaxy spectra from the Sloan Digital Sky Survey, using PCA, ICA, and NMF for dimensionality reduction and a 1D CNN to classify galaxies into four types at 88.2% accuracy, with 25x data compression at ~4% accuracy loss. Research paper under revision at the Journal of Emerging Investigators.

**Modeling the Future Challenge** -- Can self-driving cars offset the rising road-safety risk from climate change? This predicts US traffic-collision severity from 500K records (XGBoost plus a graph-neural-net hybrid, ROC-AUC 0.86) and projects how AV adoption and warming interact across five future scenarios. Placed 3rd nationally and earned a $10,000 team scholarship.

**Nutrition Tracker** -- Logging food by hand is tedious and easy to skip. This full-stack web app lets users photograph a meal for automatic recognition (CNN, ~89% accuracy), search 350,000+ foods from the USDA database, and track daily calories and macros. FastAPI backend, JavaScript frontend, REST API serving live ML predictions.

**Sign Language Translator** -- ASL has few real-time, low-cost translation tools. This converts hand gestures to text and speech in real time using MediaPipe hand tracking and a MobileNetV2 transfer-learning model (95% accuracy), with a CPU-friendly Random Forest fallback. Built as an accessibility tool.

**Recap Bot** -- Meeting notes get lost and slides go unread. This Discord bot uses the Claude API to turn uploaded presentation slides (images or PDF) into structured summaries: main topics, key takeaways, and action items. Built on Node.js and discord.js.

**Calculus Library** -- Pure-Python numerical methods are slow and scattered across packages. This is a single calculus library with a C++ backend for differentiation, integration, limits, Taylor series, and multivariable operators (gradient, Jacobian, Hessian), running 10 to 100x faster than pure Python.

**Get in touch:** adityapalit16@gmail.com
