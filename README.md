# Search engine technology

This is a search engine which runs for either text files or json files. We have used dataset of over 36000 json files for this project.
The search engine supports basic boolean query operations like OR, AND, AND NOT, and PHRASE queries.
The search engine operates in two modes: Boolean mode and Ranked Retrieval mode.
We also integrated unit testing and GUI in this project. 

Note: If you are running the code for the first time, build the index first before performing the queries. Indexing a large corpus might take a while.
You will also have to add GSON library. I have added .jar file with other files. 

How this Search engine works?

>First, the user is asked to locate the directory where the data is present, i.e. where all the files are present on which we will be running our queries on.
>If the index is not already built, we build the index, storing the entire vocabulary on disk.
>Next, user has an option to either go for ranked retrieval mode or boolean retrieval mode.
>If user goes with ranked retrieval option, they have four different strategies to choose from. Each strategy yields in different results.
>The later option returns only true positives for the given query search.
>For ranked retrieval, we also have precision-recall functionality which shows how accurate the strategy is.

For any other queries, feel free to email me at bhavyaspatel@gmail.com

