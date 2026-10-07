# CASSIE GLOBAL - Alexa+ Loan Agent for Farmers

> Ask Alexa for a loan - Cassie finds best option in your language.

### Inspiration
In Echeno, Ibaji, Kogi State, farmers travel 5 hours to Lokoja for loan info. A 46yr rice farmer was rejected for YouthCred due to age. He didn't know BOA offers 5% for agriculture. Cassie solves this with voice.

### What It Does
User: "Alexa, ask Cassie I need 500k for my rice farm"
→ Detects: Nigeria, age 46
→ Calls MCP Server /find-loan
→ Returns: BOA 5% Rice Loan, KEDA, SMEDAN (not YouthCred)
→ Speaks in Pidgin + sends docs via WhatsApp

### How It Works
Voice -> Alexa+ Skill -> AWS Lambda -> MCP Server (Bedrock) -> DynamoDB Loan DB -> Alexa Voice + WhatsApp

### Tech Stack
Alexa+ SK, Model Context Protocol, AWS Lambda, Amazon Bedrock, DynamoDB, WhatsApp API

### Global Coverage
Nigeria: BOA, BOI, SMEDAN, KEDA, YouthCred
USA: SBA | India: Mudra | UK: Start Up Loans

### Demo
Repo: github.com/uhienebayo52-star/Cassie-global-Alexa
Test: "Alexa, ask Cassie for farm loan"

### Team
Built by Bayo - Farmer from Echeno, Kogi. Rural financial inclusion via voice AI.

### License
MIT
