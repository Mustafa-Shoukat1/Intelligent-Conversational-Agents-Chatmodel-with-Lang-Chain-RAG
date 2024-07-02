<div style="position: relative; text-align: center; background-image: url('https://th.bing.com/th/id/OIP.FhY2jL9E3OtyWAmmT_fFaAHaDt?w=341&h=175&c=7&r=0&o=5&dpr=1.5&pid=1.7'); background-size: cover; background-position: center; border-radius: 20px; border: 2px solid #64B5F6; padding: 15px; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19); transform: perspective(1000px) rotateX(5deg) rotateY(-5deg); transition: transform 0.5s ease-in-out;">
    <div style="position: relative; z-index: 1; background-color: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); border-radius: 20px; padding: 20px;">
        <h1 style="color: red; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4); font-weight: bold; margin-bottom: 10px; font-size: 32px;">Welcome!</h1>
        <p style="color: #1976D2; font-size: 18px; margin: 10px 0;">
            I'm Mustafa Shoukat, a Generative Expert. I'm in the world of LLMs and exploring various concepts of Langchain and techniques to enhance my skills. In this notebook, I'll unlock the potential of Langchain, Langchain Prompting Techniques, and ChatModels.
        </p>
        <p style="color: #000000; font-size: 16px; font-style: italic; margin: 10px 0;">
            "I am just a humble data practitioner. I make mistakes and I have blind spots. If you notice things I can improve or if you just want to chat, please feel free to DM me or connect :)"
        </p>
        <p style="color: #2980B9; font-size: 16px; font-style: italic; margin: 10px 0;">
            <strong>About Notebook:</strong> 🧠 Integrating LangChain with HuggingFace and FAISS for Advanced NLP Applications
        </p>
        <p style="color: #27AE60; font-size: 16px; font-style: italic; margin: 10px 0;">
            This notebook explores building intelligent conversational agents with LangChain. It covers prompt engineering, chat model creation, document retrieval with FAISS, and text summarization using transformer models. Through practical examples, you'll learn to integrate these components into a context-aware chatbot system, providing a streamlined guide to developing advanced NLP applications.
        </p>
        <h2 style="color: red; margin-top: 15px; font-size: 28px;">Contact Information</h2>
        <table style="width: 100%; margin-top: 15px; border-collapse: collapse;">
            <tr style="background-color: #64B5F6; color: #ffffff;">
                <th style="padding: 8px; border-bottom: 2px solid #000000;">Name</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">Email</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">LinkedIn</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">GitHub</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">Kaggle</th>
            </tr>
            <tr style="background-color: #FFFFFF; color: #000000;">
                <td style="padding: 8px;">Mustafa Shoukat</td>
                <td style="padding: 8px;">mustafashoukat.ai@gmail.com</td>
                <td style="padding: 8px;">
                    <a href="https://www.linkedin.com/in/mustafashoukat/" target="_blank">
                        <img src="https://img.shields.io/badge/LinkedIn-0e76a8.svg?style=for-the-badge&logo=LinkedIn&logoColor=white" alt="LinkedIn Badge" style="border-radius: 5px; width: 100px;">
                    </a>
                </td>
                <td style="padding: 8px;">
                    <a href="https://github.com/Mustafa-Shoukat1" target="_blank">
                        <img src="https://img.shields.io/badge/GitHub-171515.svg?style=for-the-badge&logo=GitHub&logoColor=white" alt="GitHub Badge" style="border-radius: 5px; width: 100px;">
                    </a>
                </td>
                <td style="padding: 8px;">
                    <a href="https://www.kaggle.com/mustafashoukat" target="_blank">
                        <img src="https://img.shields.io/badge/Kaggle-20beff.svg?style=for-the-badge&logo=Kaggle&logoColor=white" alt="Kaggle Badge" style="border-radius: 5px; width: 100px;">
                    </a>
                </td>
            </tr>
        </table>
    </div>
</div>

<!-- Optional image below the main content -->
<img src="https://ralabs.org/wp-content/uploads/2024/04/Rectangle-2431.jpg" alt="Optional Image" style="width: 100%; height: auto; margin-top: 20px; border-radius: 10px;">
 
<div style="position: relative; text-align: center; background-image: url('https://th.bing.com/th/id/OIP.FhY2jL9E3OtyWAmmT_fFaAHaDt?w=341&h=175&c=7&r=0&o=5&dpr=1.5&pid=1.7'); background-size: cover; background-position: center; border-radius: 20px; border: 2px solid #64B5F6; padding: 15px; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19); transform: perspective(1000px) rotateX(5deg) rotateY(-5deg); transition: transform 0.5s ease-in-out;">
    <div style="position: relative; z-index: 1; background-color: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); border-radius: 20px; padding: 20px;">
        <p style="font-size: 16px; color: #000000;">
            Note: Include your API key in the sections where it is required. For instance, you might include your OpenAI API key or LangChain Hugging Face API key in the necessary code cells.
        </p>
    </div>
</div>


<div style="position: relative; text-align: center; background-image: url('https://th.bing.com/th/id/OIP.FhY2jL9E3OtyWAmmT_fFaAHaDt?w=341&h=175&c=7&r=0&o=5&dpr=1.5&pid=1.7'); background-size: 50%; background-position: center; border-radius: 20px; border: 2px solid #64B5F6; padding: 15px; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19); transform: perspective(1000px) rotateX(5deg) rotateY(-5deg); transition: transform 0.5s ease-in-out;">
    <div style="position: relative; z-index: 1; background-color: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); border-radius: 20px; padding: 20px;">
       🔗 LangChain | RAG 
    </div>
</div>

LangChain is a framework for creating applications powered by large language models (LLMs). It simplifies the LLM application lifecycle with three main stages:

## 1. Development
- **Components**: 🛠️ Use open-source building blocks and integrations.
- **LangGraph**: 🌐 Build stateful agents with streaming and human-in-the-loop features.

## 2. Productionization
- **LangSmith**: 🕵️‍♂️ Inspect, monitor, and evaluate your chains to optimize and ensure quality.

## 3. Deployment
- **LangGraph Cloud**: ☁️ Turn your applications into production-ready APIs and Assistants.

## RAG 📚

## Understanding RAG (Retrieval-Augmented Generation)

### 1. **Basic RAG** 📄🔄📝
- **What it does**: Combines retrieval of documents with generation of responses.
- **How it works**: Uses a retriever to fetch relevant documents and a generator to produce text based on the retrieved information.

### 2. **Advanced RAG**
- **RAG-Token** 📝🔄
  - **What it does**: Retrieves documents and generates responses token-by-token.
  - **How it helps**: Allows for more refined and contextually accurate generation.
- **RAG-Sequence** 📄➡️📝
  - **What it does**: Retrieves documents first and then generates a full response in one go.
  - **How it helps**: Focuses on generating longer, more coherent text.

### 3. **RAFT (Retrieval-Augmented Fine-Tuning)** 🎯📈
- **What it does**: A variant of RAG that fine-tunes a model by incorporating retrieval results directly into the training process.
- **How it helps**: Enhances the model's ability to generate contextually relevant text.

### 4. **Rafter** 🛠️✨
- **What it means**: Often a term used to describe advanced or customized versions of RAG models.
- **How it helps**: Provides additional features or optimizations for specific use cases.

These variations and extensions aim to improve the effectiveness and efficiency of retrieval and generation in natural language processing tasks.




<div style="position: relative; text-align: center; background-image: url('https://th.bing.com/th/id/OIP.FhY2jL9E3OtyWAmmT_fFaAHaDt?w=341&h=175&c=7&r=0&o=5&dpr=1.5&pid=1.7'); background-size: 50%; background-position: center; border-radius: 20px; border: 2px solid #64B5F6; padding: 15px; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19); transform: perspective(1000px) rotateX(5deg) rotateY(-5deg); transition: transform 0.5s ease-in-out;">
    <div style="position: relative; z-index: 1; background-color: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); border-radius: 20px; padding: 20px;">
       Difference between LLMs and Chat Models 🤖💬
 
</div>



## **Large Language Models (LLMs):**<br><br>

LLMs are like super-smart text generators. They're great at understanding language and can write coherent and relevant text for a wide range of tasks. For example, they can summarize articles, translate languages, or even write stories.

**Focus:**

They focus on generating text.<br><br>
**How They Work:**<br><br>
LLMs learn from huge amounts of text data to understand language patterns.<br><br>
**Strengths:**<br><br>
They're flexible and powerful at understanding and creating text.<br><br>
Examples: GPT-4 is a famous example of a large language model.<br><br>


## **Chat Models:**

Chat Models are like conversational partners. <br><br>

They're specifically designed to have interactive conversations with people. They aim to understand what you're saying and respond in a way that makes sense in a conversation.

**Focus:** <br><br>

They're all about interactive conversations.<br><br>
**How They Work:**<br><br>

Chat Models pay attention to both what's said before and after in a conversation to understand context better.<br><br>
**Strengths:**<br><br>

They're good at keeping track of what's been said before and making conversation feel natural.<br><br>
Examples: OpenAI's ChatGPT is a well-known chat model.

**system_fingerprint:**<br><br>

This is a unique identifier or fingerprint associated with the specific system or environment where the request was processed. It helps OpenAI track and monitor the usage of their API across different systems. It's essentially a way to identify the system that generated the response.



<div style="position: relative; text-align: center; background-image: url('https://th.bing.com/th/id/OIF.OQvVLEvcQ1B5sJYkwxlRcQ?w=218&h=183&c=7&r=0&o=5&dpr=1.5&pid=1.7'); background-size: cover; background-position: center; border-radius: 20px; border: 2px solid #64B5F6; padding: 15px; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19);">
    <div style="position: relative; z-index: 1; background-color: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); border-radius: 20px; padding: 20px;">
        <div style="border-radius: 20px; border: 2px solid #336699; padding: 20px; background-color: #e0f7fa; text-align: center; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19);">
            <h1 style="color: #003366; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4); font-weight: bold; margin-bottom: 10px; font-size: 32px;">
                Thank You!
            </h1>
            <p style="color: #003366; font-size: 18px; margin: 15px 0;">
                Thank you so much for joining me on this journey through the world of Lgain chain Advance Project! Your support and enthusiasm have been incredibly motivating. 🌟
            </p>
            <blockquote style="border-left: 4px solid #336699; padding-left: 10px; color: #003366; font-size: 18px; margin: 20px 0; background-color: #f0f8ff; padding: 10px;">
                As I delve deeper into the realm of <strong>Generative AI</strong>, I am grateful for your continued encouragement and guidance. Together, we are pushing the boundaries of what's possible in data science and beyond. 🚀💡
            </blockquote>
          
</div>


