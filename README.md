# medical_NLP
Utilized state-of-the-art transformer architecture to create a specialized Language Model (NLP) for an NHS Q&A dataset. Incorporated transfer learning by using the GPT-2 model to initialize the NLP model's parameters. Conducted fine-tuning on the domain-specific NHS data, empowering the model to deliver accurate and contextually relevant responses to healthcare-related queries.

examples using trained model:

What is bronchiolitis? <|eos|> <|ai|> :  bronchiectasis is a condition where the airways become inflamed due to a build-up of mucus.
References:
- https://www.nhs.uk/conditions/cornea-transplant/what-happens-at-an-cromium-resection/ <|eos|>

What are the complications of a heart attack? <|eos|> <|ai|> : Heart attacks can lead to serious complications such as heart failure, stroke, and death.
References:
- https://www.nhs.uk/conditions/Heart-attack/Pages/Introduction.aspx <|eos|>

What is dehydration? <|eos|> <|ai|> :  dehydration is a condition where your body loses too much fluid.
References:
- https://www.nhs.uk/conditions/alcohol-related-liver-disease-arld/complications/ <|eos|>

What should I do if someone has inhaled poisonous fumes? <|eos|> <|ai|> : Call 999 or go to your nearest accident and emergency (A&E) department immediately if you or someone you look after is seriously ill or has breathing difficulties.
References:
- https://www.nhs.uk/conditions/poisoning/symptoms-of-illness/ <|eos|>

How long does it take for jet lag to improve? <|eos|> <|ai|> : Jet lag usually improves on its own within a few weeks, but it can take longer.
References:
- https://www.nhs.uk/conditions/jet-lag/ <|eos|>
