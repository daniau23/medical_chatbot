## **Medical ChatBot**

This project shows the use of Langchain's RetrievalQAWithSourcesChain and a safety prompt for the retrieval of relevant information from sourced documents.

If a harmful question is asked, it is caught and notifies the user that such a prompt is not allowed.

### **Why use article_parser?**
For better RAG results

### **Using an Agent**
With the use of an agent, the use of a `saftey_prompt_checker` was not needed because the agent is smart enough to determine if the query is harmful or not.