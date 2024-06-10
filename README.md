# Adapting Real Life Constitutions into the Constitutional AI approach and Improving the outputs via Debate AI .

The idea came up after i noticed that while Anthropic's Constitutional AI (https://www.anthropic.com/news/claudes-constitution) is based on the Universal Declaration of Human Rights, there may be some biases about legal and moral aspects, even between different english speaking countries. Also the english language comprises about 50% (https://w3techs.com/technologies/overview/content_language) of the text data over websites in general, so there may be many viewpoints written in different languages that aren't being considered by the current models, making them heavily biased toward the views of the english speaking society.

I imagined that some prompts may be praiseworthy for a certain group of a given country but reprehensible by other. The data models are trained and finetuned on may carry heavy biases towards a certain world view, which can be dangerous for
human society overrall if the average person blindly trusts the model's judgement.
With this in mind, i'm proposing a method in which Constitutional AIs based on different worldviews (https://www.constituteproject.org/constitution) should via debate (https://openai.com/index/debate/) try to reach consensus (https://www.ungeneva.org/en/about/topics) about .

However, due to the political divide phenomenon, many countries, specially the democratic ones are having inner struggles about what is right or wrong and where the future of society should be directed on.
Meanwhile non-democratic governments could exploit this weakness by using AI models finetuned to impose their own agenda into fragilized countries, via deception, manipulation or by force.

## Constitutional Sources
  English speaking countries:
  
  [USA](https://www.constituteproject.org/constitution/United_States_of_America_1992)
  
  [UK](https://www.constituteproject.org/constitution/United_Kingdom_2013)
  
  [Canada](https://www.constituteproject.org/constitution/Canada_2011)
  
  [Australia](https://www.constituteproject.org/constitution/Australia_1985)
  
  [New Zealand](https://www.constituteproject.org/constitution/New_Zealand_2014)
  
  [Ireland](https://www.constituteproject.org/constitution/Ireland_2019)

  Non-english speaking countries:
  
  [France](https://www.constituteproject.org/constitution/France_2008)
  
  [Germany](https://www.constituteproject.org/constitution/German_Federal_Republic_2014)
  
  [Japan](https://www.constituteproject.org/constitution/Japan_1946)
  
  [Italy](https://www.constituteproject.org/constitution/Italy_2020)
  
  [Mexico](https://www.constituteproject.org/constitution/Mexico_2015)
  
  [Spain](https://www.constituteproject.org/constitution/Spain_2011)
  
  [Indonesia](https://www.constituteproject.org/constitution/Indonesia_2002)
  
  
BRICS members:

  [Brazil](https://www.constituteproject.org/constitution/Brazil_2017)
  
  [Russia](https://www.constituteproject.org/constitution/Russia_2014)
  
  [India](https://www.constituteproject.org/constitution/India_2016)
  
  [China](https://www.constituteproject.org/constitution/China_2018)
  
  [South Africa](https://www.constituteproject.org/constitution/South_Africa_2012)
  
  [Iran](https://www.constituteproject.org/constitution/Iran_1989)
  
  [Egypt](https://www.constituteproject.org/constitution/Egypt_2019)
  
  [Ethiopia](https://www.constituteproject.org/constitution/Ethiopia_1994)
  
  [United Arab Emirates](https://www.constituteproject.org/constitution/United_Arab_Emirates_2009)


US aligned:

[Israel](https://www.constituteproject.org/constitution/Israel_2013)

[Ukraine](https://www.constituteproject.org/constitution/Ukraine_2019)

[Taiwan](https://www.constituteproject.org/constitution/Taiwan_2005)

[South Korea](https://www.constituteproject.org/constitution/Republic_of_Korea_1987)

US opposed:

[North Korea](https://www.constituteproject.org/constitution/Peoples_Republic_of_Korea_2016)

[Palestine](https://www.constituteproject.org/constitution/Palestine_2005)



LangChain Framework:
A really promising framework that gives support to many different LLMs (e.g. GPT, Claude, Gemini) while also being able to rapidly quickstart prototypes into production.

LangChain: Chains, agents, and retrieval strategies that make up an application's cognitive architecture.

LangGraph: Build robust and stateful multi-actor applications with LLMs by modeling steps as edges and nodes in a graph.

LangServe: Deploy LangChain chains as REST APIs.

LangSmith: A developer platform that lets you debug, test, evaluate, and monitor LLM applications.


Learn more about it in: https://www.langchain.com/

Using the [Constitutional Chain](https://python.langchain.com/v0.1/docs/guides/productionization/safety/constitutional_chain/), it is possible to with basically the same code access APIs from many different models.

Firstly, i plan testing the models invididually with prompts based on these sources:

https://www.hrw.org/world-report/2024

https://ground.news/

Few-shotting vs Fine-tuning
A question i had about this project is how differently a Constitutional AI model would behave if it was properly fine-tuned with real life constitutional data instead of being asked to follow certain instructions by few-shotting.

Interesting reads:

https://www.americanbar.org/groups/crsj/publications/human_rights_magazine_home/intersection-of-lgbtq-rights-and-religious-freedom/worldviews-colliding/
