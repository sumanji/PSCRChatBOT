PSCR-ChatBot

Objectives:
The goal of this POC (Proof of Concept) is to assist users in searching information  related to public sector compliance and regulation strategy or any functional area in PSCR domain. 


Challenges faced During this Project
1. Some of the information which is not available in the dataset,llm tries to give random answer with it. Needs to figure out if somehow we can restrict user only information related with trained dataset.
2.Tried implementing with custom query search engine but its simple openai chat completion call,it can format the response in customized way,but sometime it starts behaving weired.Hence consistency is not guaranteed with response.
3. OpenAI function call mechanism was not able to do work accurately, it was fetching the inaccurate data for the data value.
4. custom training of the model can be done in order to avoid point 1 issue.

Lesson Learned
1.	Learnt llamaindex several packages like vectorstore index,retriever and query engine.
2.	Overall Architecture design.
3.Tried implementing custom query engine to frame result in our own way.

