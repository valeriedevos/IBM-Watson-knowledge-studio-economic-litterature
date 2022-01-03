# IBM-Watson-knowledge-studio-economic-litterature
This repository include the ressources used to train a supervised machine learning model in Watson Knowledge Studio.
Those ressources were created in link with the thesis: Automated extraction of causal diagrams from scientific literature in economics.
The thesis (which will be added soon to the repository) contains all the explaination in link with the creation of the model.
Watson Knowledge Studio (WKS) makes it possible to upload ressources from one workspace to another (see documentation: https://cloud.ibm.com/docs/watson-knowledge-studio?topic=watson-knowledge-studio-exportimport)

Firstly, create a WKS account an open an new workspace. 

Secondly, upload the type system (type-system.json).
This type system contains entity types: variables, relations, evidence and relation types: causal, correlation and no relation.

Thirdly, upload the different dictionnaries (dictionary1, dictionary2, dictionary3).
The dictionary contain names of economic variables, names of relations and evidence words.

Fouth, upload the annotated documents (corpus).
Those contain a corpus of 102 annotated abstracts in the domain of "income inequality".
The references of those abstract can be found in Sources of annotated abstracts.

This enables to replicate the results of the thesis or to use the annotated document set for other purpose.
Do not hesitate to send me an email: valeriedevos97@gmail.com if you have any question.
