# Extract-Blogs-api
Flask code to deploy an API that pulls structured data from online Blogs and Articles.

This is a source code of an API that you can find here (free plan available): https://rapidapi.com/kotartemiy/api/extract-news




![](extract_image.png)


## Quick Start
1. Clone the repository to your local folder 


2. Create a Python virtual environment (3.6+)

`python -m venv env`

3. Activate the environment

`source env/bin/activate`

4. Run `pip install -r requirements.txt`
5. Run `python app.py` in your terminal 

If everything is OK then you should be able to check your API on `http://127.0.0.1:5000/v0/article`

Example of request: `http://127.0.0.1:5000/v0/article?url=https://forge.medium.com/dont-save-your-fun-for-the-end-of-the-day-add7c1c351f1`

## Example of Response Body
``` 
{"status":"ok","article":{"source_url":"https://forge.medium.com","published":null,"published_method_found":"Did not find anything","published_guess_accuracy":null,"title":"Don\u2019t Save Your Fun for the End of the Day","text":"Don\u2019t Save Your Fun for the End of the Day\n\nJoy is more than a reward for productivity\n\nPhoto: fizkes/Getty Images\n\nWe may be used to motivating ourselves with the promise of a reward \u2014 grind all day and relax at night, or break for a treat only after finishing a project \u2014 but in talking with my therapy clients over the past several months, I\u2019ve found that we simply can\u2019t strong-arm ourselves into productivity when we feel anxious and isolated. The promise of happiness isn\u2019t enough when we need it right this minute.\n\nWe shouldn\u2019t wait to reward ourselves with conversations with friends, a walk outside, or a mystery novel. Instead, we should pepper our days with them. We need to build them into our daily schedules and protect them like the life-sustaining measures that they are.\n\nWhen we incorporate activities into our day that foster curiosity, like exploring a new park, playing a board game, or sitting around the fire pit with a friend, then we direct our mind away from its anxious flailing. And when we can steer away from anxiety, one added benefit is that we give ourselves a chance to do better work.\n\nTo help you decide which rewards to add to your day, here are some questions you can ask:\n\nWhat low-cost or no-cost things make me feel happy?\n\nWhat am I naturally curious about right now?\n\nWhat things do I never regret doing?\n\nHow can I start or end my day on a high note?\n\nIf you\u2019ve been having a hard time lately, consider whether you\u2019ve been withholding joy because you\u2019ve decided you don\u2019t deserve it \u2014 because you feel lazy, or unproductive, or less than enough. It\u2019s time to stop thinking of the things that make us happy as expendable extras. They\u2019re the life raft that will carry us through the next few months.","authors":["Kathleen Smith"],"images":["https://miro.medium.com/max/60/1*ye-qCds4aJ11KZCPF4LjlA.jpeg?q=20","https://miro.medium.com/focal/1200/632/45/36/1*zRR1lYeYIR4FdqIzc4QQHw.jpeg","https://miro.medium.com/focal/140/140/42/15/1*wsVj1klioqzyOOB1y9RNfg.png","https://miro.medium.com/max/60/1*wsVj1klioqzyOOB1y9RNfg.png?q=20","https://miro.medium.com/focal/140/140/38/45/1*ZpMkZ6GKs5ZKK2GKd0emrw.jpeg","https://miro.medium.com/max/60/1*M6jZ_w3ZrXTha9gr9jlAtw.jpeg?q=20","https://miro.medium.com/focal/140/140/48/43/1*zqRGtMAH6VyuyuDAwHphAA.gif","https://miro.medium.com/focal/140/140/67/49/1*tf_5C7830QCTnVPM_wR-Ow.jpeg","https://miro.medium.com/max/60/1*zRR1lYeYIR4FdqIzc4QQHw.jpeg?q=20","https://miro.medium.com/focal/140/140/34/36/1*u0TIJEW0ME3oXHHithbicA.jpeg","https://miro.medium.com/fit/c/140/140/1*ye-qCds4aJ11KZCPF4LjlA.jpeg","https://miro.medium.com/max/4242/1*zRR1lYeYIR4FdqIzc4QQHw.jpeg","https://miro.medium.com/freeze/max/60/1*zqRGtMAH6VyuyuDAwHphAA.gif?q=20","https://miro.medium.com/max/60/1*tf_5C7830QCTnVPM_wR-Ow.jpeg?q=20","https://miro.medium.com/max/60/1*ZpMkZ6GKs5ZKK2GKd0emrw.jpeg?q=20","https://miro.medium.com/max/218/1*UZoo44C0QuXbxgHZS9wAZA.png","https://miro.medium.com/focal/140/140/46/48/1*M6jZ_w3ZrXTha9gr9jlAtw.jpeg","https://miro.medium.com/max/270/1*Crl55Tm6yDNMoucPo1tvDg.png","https://miro.medium.com/focal/140/140/52/32/1*njQhYAlFWssKl7U68YplHw.jpeg","https://miro.medium.com/max/60/1*njQhYAlFWssKl7U68YplHw.jpeg?q=20","https://miro.medium.com/fit/c/56/56/2*8ZwdeYYIo5E3IbdRFtyBbQ.jpeg","https://miro.medium.com/max/270/1*W_RAPQ62h0em559zluJLdQ.png","https://miro.medium.com/max/60/1*u0TIJEW0ME3oXHHithbicA.jpeg?q=20"],"top_image":"https://miro.medium.com/focal/1200/632/45/36/1*zRR1lYeYIR4FdqIzc4QQHw.jpeg","meta_image":"https://miro.medium.com/focal/1200/632/45/36/1*zRR1lYeYIR4FdqIzc4QQHw.jpeg","movies":[],"meta_keywords":[""],"tags":[],"meta_description":"Fun and relaxation are more than just rewards for productivity.","meta_lang":"en","title_lang":"en","text_lang":"en","meta_favicon":"https://miro.medium.com/fit/c/152/152/1*sHhtYhaCe2Uc3IU0IgKwIQ.png"}}
```

## Built with
[Flask](https://github.com/pallets/flask) Copyright 2010 Pallets

