Introduction:
Its a llm which runs on Ollama, which is a family of large language models. Firstly, climate GPT is trained on the static training data. The data consists of 300B tokens, which include data from news, patents, research papers, and more. Then they cleaned the data by seeing how the data is related and how it is extracted. In simple words its a Chatbot which is based on climate data.

Evolution of GPTs:
Evolution of gpts are done in three phases. In phase one, most of the GPTs, like ChatGPT, just act on the training data obtained from large datasets. While coming to phase two, we have added a context to the data and given it access to use tools. But in phase three, we are using the Model Context Protocol (MCP). It acts as a bridge between the model and the real-world data. So, by using mcp, we can extract the right exact information from the datasets and convert information into a JSON file, and then convert it back to plain English using a natural language model. 

What are we working on:
In this project, we are working on the same method where we develop an MCP server and connect it to a dataset and build mcp tools and try to connect it to a host. Till now we are using Claude to host and connect to data and server.
