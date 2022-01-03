# IBM-Watson-knowledge-studio-economic-litterature
This repository include the ressources used to train a supervised machine learning model in Watson Knowledge Studio.
Those ressources were created in link with the thesis: Automated extraction of causal diagrams from scientific literature in economics.
The thesis (...) contains all the explaination in link with the creation of the model.
Watson Knowledge Studio (WKS) makes it possible to upload ressources from one workspace to another (see documentation: https://cloud.ibm.com/docs/watson-knowledge-studio?topic=watson-knowledge-studio-exportimport)
Firsty, create a WKS account an open an new workspace. 
Secondly, upload the type system (...).
This type system contains entity types: variables, relations, evidence and relation types: causal, correlation and no relation.
Thirdly, upload the different dictionnaries: 
The dictionary contain names of economic variables, names of relations and evidence words.
Fouth, upload the annotated documents:...
Those contain a corpus of 102 annotated abstracts in the domain of "income inequality".
This enables to replicate the results of the thesis or to use the annotated document set for other purpose.
