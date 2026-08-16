# Charles Kariuki

Computer Science student at Mount Kenya University, based in Nairobi. I build AI systems that protect ordinary people from fraud, and I spend the rest of my time learning how to break those same systems on purpose, so someone else does not break them for free.

## The problem I am working on

Mobile money is how most Kenyans move money. It is also where most fraud happens. Fraud detection tools that exist today were built for Western banks. They understand a stolen credit card number. They do not understand a fake M-Pesa reversal message written in Swahili, or a SIM swap attack that hijacks a phone line before a single transaction even happens. That gap is not small. Kenya lost over 800 billion shillings to mobile banking fraud in 2024 alone, and the tools built to catch it were never designed for this market.

Everything below is one connected effort to close that gap, properly, and to build the skills that make it trustworthy rather than a guess.

## How the pieces fit together

**Vigilant AI** is the actual product. It reads a suspicious message and tells you, in plain language, whether it looks like fraud and why.

**AI Security Engineering** is where I learn to attack Vigilant AI on purpose, so I find its weaknesses before someone else does. Every technique I learn gets tested directly against my own fraud classifier.

**AfricaNDR** watches network traffic instead of messages. Some fraud shows up before a scam message is even sent, in patterns like SIM swap requests or unusual API activity. AfricaNDR is built to catch that layer and feed what it finds into Vigilant AI.

**Python Automation** is separate work. It is how I fund the build, and it keeps my general engineering skills sharp: fixing broken code, pulling data from websites, connecting business systems together.

If you only remember one thing: Vigilant AI is the product, AI Security Engineering makes it harder to fool, AfricaNDR gives it a second set of eyes at the network level, and Python Automation is the income that keeps the lights on while all of that gets built.

## Projects

### Vigilant AI
Fraud detection for African mobile money. Reads a suspicious SMS or message and returns a plain language explanation of why it looks like fraud or why it does not.
Currently: rule engine and machine learning classifier both live, 98.4% precision and 100% recall on test data, trained on over two thousand real pattern messages.
[Live demo](https://vigilantai-o7udfkd7swt5f2sywwemvy.streamlit.app/) · [Repository](https://github.com/CharlesKariuki-001/VigilantAI)

### AI Security Engineering
A twelve month program where I learn to attack and defend AI systems, using Vigilant AI as the real target throughout.
Currently: Block 1 of 4, building AdversarialForge, the project that proves a model can be tricked by tiny, deliberate changes to a message.
[Repository](https://github.com/CharlesKariuki-001/ai-security-engineering)

### AfricaNDR
Network level threat detection for African fintech infrastructure. Watches raw traffic for signs of SIM swap attempts, API abuse, and other attacks that happen before a fraudulent message is ever sent.
Currently: log parsing and traffic reading built, feature extraction and the anomaly detection model in progress.
[Repository](https://github.com/CharlesKariuki-001/africandr)

### Python Automation
Freelance work built around three specific, common problems: getting data out of a website, fixing broken Python code, and connecting two business tools that do not talk to each other.
[Repository](https://github.com/CharlesKariuki-001/Python-Automation)

## Tools I use

Python, PyTorch, scikit-learn, XGBoost, SHAP, Zeek, Streamlit, FastAPI, Docker, pandas, SQL.

## Open to

Remote AI security or machine learning internships and junior roles. People testing Vigilant AI, especially small merchants or fintech teams willing to give honest feedback. Anyone who knows Zeek scripting or adversarial machine learning and wants to compare notes.

## Find me

LinkedIn: [Charles Mburu](https://ke.linkedin.com/in/charles-mburu-838965382)
X: [@KariukiBuilds__](https://x.com/KariukiBuilds__)
Email: charlesmburukariuki@gmail.com

---

"Every shilling stolen from a boda boda rider is a shilling that does not go into school fees, savings, or business growth."
