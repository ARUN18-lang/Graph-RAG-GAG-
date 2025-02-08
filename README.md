# Movie Recommendation with Neo4j and LangChain

This project demonstrates how to build a movie recommendation system using Neo4j as the graph database and LangChain for querying the database with natural language.

## Project Overview

This project uses a Neo4j database to store movie data, including movies, actors, directors, genres, and production companies. LangChain is used to create a question-answering chain that allows users to query the database using natural language questions. The Groq LLM is used to generate Cypher queries from the natural language questions.

## Getting Started

1. **Install Dependencies:**
   bash !pip install langchain langchain_community neo4j langchain_groq groq

2. **Setup Neo4j:**

- Create a Neo4j AuraDB Free instance.
- Store your Neo4j username and password in Google Colab userdata

3. **Load Movie Data:**

- The project uses a movie dataset loaded into Neo4j using a Cypher query.

4. **Query the Database:**

- Use LangChain's `GraphCypherQAChain` to query the database using natural language questions.

## Contributing

Contributions are welcome! Please open an issue or pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License.
