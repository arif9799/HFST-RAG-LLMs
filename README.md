<p align="center">
  
  ___
</p>
<br>

<h3 align="center">
  
  [_Retrieval Augmented Generation, Streamlit and LangChain_](https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation)
</h3>
<br>


<h4 align="center">
  <a href="https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation">Visit the Application</a>
</h4>
<br>

<h4 align="center">
  <a href="https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation/tree/main">Link to Code and Files</a>
</h4>
<br>


<table align="center">
  <tr align="center">
    <td><img src="https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation/resolve/main/Images/ragAI.gif" width="500" alt="RAG"></td>
    
  </tr>
</table>
<br>

_Streamlit-based LLM App_ 

The project utilizes Streamlit to create an interactive web application that interfaces with large language models (LLMs). It integrates various visual components, enabling users to input queries and receive responses from the language model, alongside displaying interactive visualizations. Additionally, the knowledge base is dynamically built from user-provided data, such as PDFs or files, and keywords for web scraping, showcasing advanced AI and Python capabilities.



##  **_Situation:_**

Large language models (LLMs) have become increasingly powerful and are used for various natural language processing tasks.
Creating an accessible, interactive interface for users to interact with LLMs can enhance user experience and broaden the application of these models.
This project aims to develop a Streamlit application that provides a user-friendly interface for interacting with LLMs, visualizing outputs, and displaying additional insights along with citations from Knowledge Base to responses generated.
A key feature is the ability to build a dynamic knowledge base from user-provided data, including documents (PDFs, text files) and keywords for scraping relevant information from the internet.

<br>

##  **_Task:_**
Develop a Streamlit-based application that allows users to interact with LLMs.
Incorporate various visual elements and animations to enhance user engagement.
Enable users to input queries, view responses from the LLM, and see associated citations and insights.
Implement functionality to build and update the knowledge base using user-provided documents and web-scraped data based on user-input keywords.

<br>

##  **_Approach:_**

- Data Retrieval and Setup:

Configure the Streamlit application environment and setup necessary dependencies.
Implement utility functions in _helper_functions.py to support visual elements and interactive components.
Create mechanisms to upload and process user-provided documents, and scrape data from the web based on user-provided keywords.
Application Development:

- User Interface:

Design the main page layout with input areas for user queries.
Implement animated cards and other visual elements to enhance engagement.
Add features for users to upload documents and input keywords for web scraping.
Model Integration:
Setup the logic to invoke LLMs using the RetrievalChainGenerator.
Handle user inputs and display model responses dynamically.
Incorporate the dynamically built knowledge base into the model's response generation.
Visualization and Interaction:
Use the utility functions to display interactive elements like animated cards.
Provide visual feedback and insights based on the model responses.
Visualize the integration of data from user-provided documents and web-scraped content.

<table align="center">
  <tr align="center">
    <td><img src="https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation/resolve/main/Images/Viz1.png" width="750" alt="RAG"></td>
  </tr>
  <tr align="center">
    <td><img src="https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation/resolve/main/Images/Viz2.png" width="750" alt="RAG"></td>
  </tr>
  <tr align="center">
    <td><img src="https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation/resolve/main/Images/Viz3.png" width="750" alt="RAG"></td>
  </tr>
</table>
<br>


- Feature Engineering and Visualization:

Implement features to split and format data for better visualization and analysis.
Create visual components to display patterns in the dynamically built knowledge base, such as common themes in user-provided documents and trends in web-scraped data.

<br>

##  **_Results:_**
Developed a user-friendly Streamlit application for interacting with LLMs, showcasing advanced AI and Python capabilities.
Enhanced user experience through interactive visual elements and animations.
Enabled dynamic knowledge base creation using user-provided data and web scraping, improving the relevance and accuracy of LLM responses.
Provided insights and visual feedback on user queries and model responses, improving user engagement and understanding.
Demonstrated skills in data integration, natural language processing, and interactive application development, highlighting proficiency in AI and Python.


- Complete Infrastructure / High Level Overview of the System:

<table align="center">
  <tr align="center">
    <td><img src="https://huggingface.co/spaces/arif97/Retrieval-Augmented-Generation/resolve/main/Images/RAGWorkflow-ezgif.com-optimize.gif" width="1000" alt="RAG"></td>
  </tr>
</table>
<br>






