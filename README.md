# Alexa-Covid-Cases-Skill-
<div align="center">
  <h1>Alexa Covid Cases Info by Pushpi</h1>
  <p align="center"> 
    <img src="./screenshots/capture_current_state_intent.png" style="box-shadow: 0px 0px 20px 0px rgba(189,182,189,1)">
  </p>
</div>


# Technologies
- **Node.js**: Backend to create the skills
- **AWS Lambda**: Backend to host the skills

# Data Provider
- https://covid19.who.int/table

1. **Ask about a state**: "how many cases have been reported in India?"
2. **Ask about a country**: "how many cases have been reported in India?"
3. **Ask about top countries**: "which countries have most coronavirus cases?"
4. **Ask about top states in India**: "which states have most coronavirus cases?"

## How to use the features
You can either invoke the skill about saying "covid cases info by pushpi" or just directly ask Alexa a question by saying things like "how many cases have been reported in India?"


Ask about a state|She will ask to clarify if you didn't provide a state|If you have asked about a state before, she will remember it so you don't have to say it again next time
:-------------------------:|:-------------------------:|:-------------------------:
![](./screenshots/capture_state_intent1.png)|![](./screenshots/capture_state_intent2.png)|![](./screenshots/capture_current_state_intent.png)

Ask about a country   |Ask about global summary   |  Aak about top countires and top states
:-------------------------:|:-------------------------:|:-------------------------:
![](./screenshots/capture_country_intent.png)|![](./screenshots/capture_global_intent.png)|![](./screenshots/capture_top_countries_and_states_intents.png)
