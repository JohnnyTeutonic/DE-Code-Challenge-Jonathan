# Data-Engineering-Challenge
Take home assignment based on Demyst Python libraries and building a model

## Description
In this challenge you will have to use our Analytics Python package using the documentation to show your understanding of APIs and knowledge of Python. The API documentation is available on https://docs.demyst.com/apis/python/analytics/api/. You can also login to our platform through the [website](https://demyst.com/) where you will find input file for this challenge that you need to append with external data using the Python API. 

Once you are done with the data enrichment, you will have to predict the target variable (safety_flag). The input file is available through the [Transfer Files section](https://console.demystdata.com/discovery/file_transfers) of the platform or from this repo.

## Requirement

Perform three sub-tasks for submission:

1) Analyze and clean the input file using Python/Pandas in a Jupyter Notebook. 
2) Enrich the cleaned input with external data from the providers available on the platform.
3) Use the enriched file to predict the target variable (safety_flag). You can use any model building packages/tools. Make sure the model can be re-trained. 

A Jupyter Notebook displaying the steps you took to clean the input and enrich it through our Analytics Python package along with the model must be pushed to the Github Repo with any supporting files. Please be reminded to cache the enriched data in order to save some cost as there is an upper limit for the data enrichment. A smart tip is to try to run a few records first to test what the input and output should look like. For sub-task 1) and 3), please also create some unit test cases using Python standard unit testing framework.

If you use any third party libraries / non-standard build tools, document the build instructions clearly in a readme file.

## Evaluation

- Coding style: 30% Ease of maintenance; terseness; use of best practices; leverage latest technologies / libraries / clever coding techniques; etc. Appropriate choice of 3rd party libraries or frameworks is encouraged.
- Data wrangling: 20% Steps taken to clean data and possibility of automating the cleansing step through scripts.
- Documentation: 20% Is the Jupyter Notebook self-explanatory?
- Modelling: 20% Understanding of models and analytics and implementation on the dataset to predict the outcome. 
- Unit test: 10% Can the test cases isolate each part of the Jupyter Notebook and show that the individual parts work correctly?

Feel free to ask any questions as you tackle challenge! Have Fun!
