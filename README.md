# RAG-QA-with-Groq-and-Gemma

Project Overview:
This project utilizes a combination of Streamlit, Groq, OpenAI, and Langchain libraries to build an interactive Q&A platform. The application is designed to process and answer user queries based on the content of research papers, ensuring precise and context-aware responses.

𝗞𝗲𝘆 𝗖𝗼𝗺𝗽𝗼𝗻𝗲𝗻𝘁𝘀 𝗮𝗻𝗱 𝗠𝗲𝘁𝗵𝗼𝗱𝗼𝗹𝗼𝗴𝗶𝗲𝘀:
𝗦𝘁𝗿𝗲𝗮𝗺𝗹𝗶𝘁 𝗳𝗼𝗿 𝗨𝘀𝗲𝗿 𝗜𝗻𝘁𝗲𝗿𝗳𝗮𝗰𝗲: Streamlit for User Interface:
Streamlit is employed to create a user-friendly interface that allows users to input queries and receive responses. This ensures that the application is accessible and easy to navigate.

𝗖𝗵𝗮𝘁𝗚𝗿𝗼𝗾 𝗠𝗼𝗱𝗲𝗹 𝗜𝗻𝘁𝗲𝗴𝗿𝗮𝘁𝗶𝗼𝗻: The core of the Q&A system is powered by the ChatGroq model, "𝗴𝗲𝗺𝗺𝗮-𝟳𝗯-𝗶𝘁." This model is adept at processing natural language queries and providing accurate answers based on the context it is given.

𝗗𝗼𝗰𝘂𝗺𝗲𝗻𝘁 𝗟𝗼𝗮𝗱𝗶𝗻𝗴 𝗮𝗻𝗱 𝗣𝗿𝗼𝗰𝗲𝘀𝘀𝗶𝗻𝗴: 
𝗣𝘆𝗣𝗗𝗙𝗗𝗶𝗿𝗲𝗰𝘁𝗼𝗿𝘆𝗟𝗼𝗮𝗱𝗲𝗿: This module is responsible for ingesting research papers stored in PDF format, enabling the application to access a wide range of document content.
𝗥𝗲𝗰𝘂𝗿𝘀𝗶𝘃𝗲𝗖𝗵𝗮𝗿𝗮𝗰𝘁𝗲𝗿𝗧𝗲𝘅𝘁𝗦𝗽𝗹𝗶𝘁𝘁𝗲𝗿: To manage document size and complexity, this tool splits text into manageable chunks, allowing for efficient processing and retrieval.

𝗘𝗺𝗯𝗲𝗱𝗱𝗶𝗻𝗴𝘀 𝗮𝗻𝗱 𝗩𝗲𝗰𝘁𝗼𝗿𝗶𝘇𝗮𝘁𝗶𝗼𝗻: 
𝗢𝗽𝗲𝗻𝗔𝗜𝗘𝗺𝗯𝗲𝗱𝗱𝗶𝗻𝗴𝘀:These are used to convert textual data into numerical vectors, a crucial step for semantic understanding and similarity search.
𝗙𝗔𝗜𝗦𝗦 𝗩𝗲𝗰𝘁𝗼𝗿 𝗦𝘁𝗼𝗿𝗲:This library is employed to store and retrieve document vectors, optimizing the speed and accuracy of the retrieval process.

𝗖𝗵𝗮𝗶𝗻 𝗼𝗳 𝗥𝗲𝘁𝗿𝗶𝗲𝘃𝗮𝗹 𝗮𝗻𝗱 𝗔𝗻𝘀𝘄𝗲𝗿 𝗚𝗲𝗻𝗲𝗿𝗮𝘁𝗶𝗼𝗻:
𝗣𝗿𝗼𝗺𝗽𝘁 𝗧𝗲𝗺𝗽𝗹𝗮𝘁𝗲: A customized prompt ensures that the ChatGroq model focuses on context-relevant data when generating answers.
𝗗𝗼𝗰𝘂𝗺𝗲𝗻𝘁 𝗮𝗻𝗱 𝗥𝗲𝘁𝗿𝗶𝗲𝘃𝗮𝗹 𝗖𝗵𝗮𝗶𝗻𝘀: The system creates a chain that combines document content and retrieval strategies, ensuring that questions are answered with contextually accurate information.
