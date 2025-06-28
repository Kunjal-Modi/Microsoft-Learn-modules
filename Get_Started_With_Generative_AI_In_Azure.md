<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<div class="container">
    <h1>100 Questions on Generative AI on Azure</h1>
    <p>Based on Microsoft Learn Modules: Get started with generative AI on Azure</p>
    <div class="question-section">
        <div class="question">
            <div class="question-text">1. What is the primary function of a generative AI model?</div>
            <ul class="options-list">
                a) To classify data.
                <li>b) To analyze existing data for patterns.</li>
                <li>c) To create new, original content.</li>
                <li>d) To predict future trends.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) To create new, original content.</div>
        </div>
        <div class="question">
            <div class="question-text">2. What is a "prompt" in the context of generative AI?</div>
            <ul class="options-list">
                <li>a) The output from the model.</li>
                <li>b) A type of generative model.</li>
                <li>c) The input a user provides to guide the model's generation.</li>
                <li>d) The training dataset.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) The input a user provides to guide the model's generation.</div>
        </div>
        <div class="question">
            <div class="question-text">3. Which of the following is a common application of generative AI?</div>
            <ul class="options-list">
                <li>a) Running a transactional database.</li>
                <li>b) Generating realistic images from text descriptions.</li>
                <li>c) Managing network traffic.</li>
                <li>d) Performing financial audits.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Generating realistic images from text descriptions.</div>
        </div>
        <div class="question">
            <div class="question-text">4. What does the term "hallucination" mean in the context of generative AI?</div>
            <ul class="options-list">
                <li>a) The model is dreaming.</li>
                <li>b) The model generates incorrect, fabricated, or nonsensical information.</li>
                <li>c) The model is used for virtual reality.</li>
                <li>d) The model is creating highly imaginative content.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) The model generates incorrect, fabricated, or nonsensical information.</div>
        </div>
        <div class="question">
            <div class="question-text">5. What is a "foundation model"?</div>
            <ul class="options-list">
                <li>a) A small model trained for a very specific task.</li>
                <li>b) A large model trained on vast amounts of data that can be adapted for various tasks.</li>
                <li>c) A model used to build foundations of buildings.</li>
                <li>d) The first version of a model.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) A large model trained on vast amounts of data that can be adapted for various tasks.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">6. Generative AI models are always 100% accurate and do not require human review.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">7. A key ethical concern with generative AI is the potential to create deepfakes and misinformation.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">8. Discriminative AI is used to create new data, while generative AI classifies existing data.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">9. Generative AI is limited to creating only text content.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">10. The output from a generative AI model is deterministic and will be the same every time for the same prompt.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">11. Match the generative AI model type to its characteristic: <br><br>
                    A) GAN <br>
                    B) VAE <br>
                    C) Transformer <br><br>
                    1) Uses an encoder-decoder architecture to learn latent representations. <br>
                    2) Employs a Generator and a Discriminator that compete with each other. <br>
                    3) Uses a self-attention mechanism to understand context in sequences.
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-1, C-3</div>
            </div>
            <div class="question">
                <div class="question-text">12. Match the generative AI application to its industry: <br><br>
                    A) Healthcare <br>
                    B) Software Development <br>
                    C) Marketing <br><br>
                    1) Generating synthetic medical images for training. <br>
                    2) Creating personalized ad copy and creative assets. <br>
                    3) Generating code snippets and documentation.
                </div>
                <div class="answer"><strong>Answer:</strong> A-1, B-3, C-2</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 2: Large Language Models (LLMs) & Prompting</h2>
        <h3>Multiple Choice Questions</h3>
        <div class="question">
            <div class="question-text">13. What does "LLM" stand for?</div>
            <ul class="options-list">
                <li>a) Lightweight Learning Module</li>
                <li>b) Large Language Model</li>
                <li>c) Long-form Learning Machine</li>
                <li>d) Low-level Logic Model</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Large Language Model</div>
        </div>
        <div class="question">
            <div class="question-text">14. What is a "token" in the context of LLMs?</div>
            <ul class="options-list">
                <li>a) A complete sentence.</li>
                <li>b) A unit of text, such as a word or part of a word.</li>
                <li>c) A character in a string.</li>
                <li>d) A punctuation mark.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) A unit of text, such as a word or part of a word.</div>
        </div>
        <div class="question">
            <div class="question-text">15. What is "in-context learning"?</div>
            <ul class="options-list">
                <li>a) Training the model from scratch.</li>
                <li>b) The model's ability to learn from examples provided in the prompt.</li>
                <li>c) The model's ability to learn from a database.</li>
                <li>d) The model's ability to learn by itself without any examples.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) The model's ability to learn from examples provided in the prompt.</div>
        </div>
        <div class="question">
            <div class="question-text">16. What parameter controls the randomness of an LLM's output?</div>
            <ul class="options-list">
                <li>a) Max tokens</li>
                <li>b) Temperature</li>
                <li>c) Frequency penalty</li>
                <li>d) Top P</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Temperature</div>
        </div>
        <div class="question">
            <div class="question-text">17. What is "prompt engineering"?</div>
            <ul class="options-list">
                <li>a) Designing a computer chip.</li>
                <li>b) The process of training a new LLM.</li>
                <li>c) The art and science of crafting effective prompts to guide an LLM's output.</li>
                <li>d) Building a prompt flow.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) The art and science of crafting effective prompts to guide an LLM's output.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">18. A "system message" in a prompt is used to define the model's persona and instructions.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">19. A lower temperature setting will result in a more creative and random response.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">20. "Zero-shot learning" means the LLM can perform a task it has never seen before, with no examples in the prompt.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">21. The token limit for an LLM applies only to the input, not the output.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">22. "Chain-of-thought" prompting helps the model arrive at a better answer by guiding it to think step-by-step.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">23. Match the prompt engineering technique to its description: <br><br>
                    A) Zero-shot prompting <br>
                    B) Few-shot prompting <br>
                    C) Chain-of-thought prompting <br><br>
                    1) Providing a few examples in the prompt to teach the model a new task. <br>
                    2) Giving the model no examples, just the task. <br>
                    3) Instructing the model to reason through a problem step-by-step.
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-1, C-3</div>
            </div>
            <div class="question">
                <div class="question-text">24. Match the LLM parameter to its effect on output: <br><br>
                    A) Temperature <br>
                    B) Max tokens <br>
                    C) Top P <br><br>
                    1) Controls the maximum length of the response. <br>
                    2) Controls the randomness of the output. <br>
                    3) Limits the AI to consider only a certain percentage of probability mass.
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-1, C-3</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 3: Tools to Develop Generative AI Solutions</h2>
        <h3>Multiple Choice Questions</h3>
        <div class="question">
            <div class="question-text">25. What Azure service provides access to OpenAI's powerful language models with enterprise-grade security?</div>
            <ul class="options-list">
                <li>a) Azure Machine Learning</li>
                <li>b) Azure AI Services</li>
                <li>c) Azure OpenAI Service</li>
                <li>d) Azure App Service</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) Azure OpenAI Service</div>
        </div>
        <div class="question">
            <div class="question-text">26. What is "fine-tuning" a generative AI model?</div>
            <ul class="options-list">
                <li>a) Adjusting the model's physical size.</li>
                <li>b) Further training a pre-trained model on a smaller, specific dataset.</li>
                <li>c) Making the model's output more random.</li>
                <li>d) Changing the model's architecture.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Further training a pre-trained model on a smaller, specific dataset.</div>
        </div>
        <div class="question">
            <div class="question-text">27. Which Azure tool is a unified platform for building, training, and deploying AI solutions?</div>
            <ul class="options-list">
                <li>a) Azure Portal</li>
                <li>b) Azure Blob Storage</li>
                <li>c) Azure AI Studio (formerly Azure AI Foundry)</li>
                <li>d) Azure DevOps</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) Azure AI Studio (formerly Azure AI Foundry)</div>
        </div>
        <div class="question">
            <div class="question-text">28. What is "Retrieval-Augmented Generation (RAG)"?</div>
            <ul class="options-list">
                <li>a) The model retrieves information from its own training data.</li>
                <li>b) The model retrieves information from an external knowledge base to inform its generation.</li>
                <li>c) The model hallucinates information.</li>
                <li>d) The model is angry.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) The model retrieves information from an external knowledge base to inform its generation.</div>
        </div>
        <div class="question">
            <div class="question-text">29. What is "Prompt Flow" in Azure AI Studio?</div>
            <ul class="options-list">
                <li>a) A tool for managing your prompts.</li>
                <li>b) A visual tool for orchestrating and evaluating LLM-based applications.</li>
                <li>c) A method for running code.</li>
                <li>d) A type of database.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) A visual tool for orchestrating and evaluating LLM-based applications.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">30. Azure AI Studio's playground is intended for production-level deployments.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">31. "Parameter-efficient fine-tuning (PEFT)" is a technique for training a model on a very large dataset.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">32. RAG helps ground a generative AI model's responses in verifiable, external data.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
           <div class="question">
                <div class="question-text">33. Azure AI services include built-in tools for content filtering and moderation to promote responsible AI.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">34. A real-time endpoint is a hosted version of a model that can be called via an API for inference.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">35. Match the Azure tool to its function: <br><br>
                    A) Azure OpenAI Service <br>
                    B) Azure AI Studio <br>
                    C) Prompt Flow <br><br>
                    1) A visual orchestration tool for building LLM applications. <br>
                    2) Provides secure access to OpenAI models. <br>
                    3) A unified platform for the end-to-end AI lifecycle.
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-3, C-1</div>
            </div>
            <div class="question">
                <div class="question-text">36. Match the term to its definition: <br><br>
                    A) Fine-tuning <br>
                    B) RAG <br>
                    C) Embeddings <br><br>
                    1) Adapting a pre-trained model with a smaller dataset. <br>
                    2) Converting data into numerical vectors for semantic search. <br>
                    3) Using external data sources to enhance model generation.
                </div>
                <div class="answer"><strong>Answer:</strong> A-1, B-3, C-2</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 4: Azure AI Studio Model Catalog</h2>
        <h3>Multiple Choice Questions</h3>
        <div class="question">
            <div class="question-text">37. What is the primary purpose of the Model Catalog in Azure AI Studio?</div>
            <ul class="options-list">
                <li>a) To sell AI models.</li>
                <li>b) To provide a centralized hub for discovering and deploying foundation models.</li>
                <li>c) To store user data.</li>
                <li>d) To manage compute resources.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) To provide a centralized hub for discovering and deploying foundation models.</div>
        </div>
        <div class="question">
            <div class="question-text">38. The models available in the catalog include:</div>
            <ul class="options-list">
                <li>a) Only models from Microsoft.</li>
                <li>b) Only open-source models.</li>
                <li>c) Both Microsoft-developed models and curated open-source models.</li>
                <li>d) Only models you have trained yourself.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) Both Microsoft-developed models and curated open-source models.</div>
        </div>
        <div class="question">
            <div class="question-text">39. What is a key benefit of using a model from the catalog?</div>
            <ul class="options-list">
                <li>a) You have to train it from scratch.</li>
                <li>b) They are pre-trained and ready to be used or fine-tuned.</li>
                <li>c) They are not compatible with other Azure services.</li>
                <li>d) They are free of charge for all usage.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) They are pre-trained and ready to be used or fine-tuned.</div>
        </div>
       <div class="question">
            <div class="question-text">40. What action does the "deploy" button next to a model in the catalog typically perform?</div>
            <ul class="options-list">
                <li>a) Deletes the model from the catalog.</li>
                <li>b) Downloads the model to your local machine.</li>
                <li>c) Deploys the model as a real-time endpoint for inference.</li>
                <li>d) Starts the training process for the model.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) Deploys the model as a real-time endpoint for inference.</div>
        </div>
        <div class="question">
            <div class="question-text">41. What is the "Model as a Service (MaaS)" approach?</div>
            <ul class="options-list">
                <li>a) You manage all the infrastructure for the model.</li>
                <li>b) The model is provided as a hosted API, simplifying deployment and scaling.</li>
                <li>c) The model is only available for offline use.</li>
                <li>d) The model is a physical machine.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) The model is provided as a hosted API, simplifying deployment and scaling.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">42. Every model in the Azure AI Studio Model Catalog is open source.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">43. The model catalog provides information about a model's capabilities, limitations, and responsible AI considerations.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">44. You cannot fine-tune a model from the catalog; you must use it as-is.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">45. The Model Catalog is only for discovering text-based models.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">46. Match the model type to its provider in the Azure AI Model Catalog: <br><br>
                    A) GPT-4 <br>
                    B) Llama 2 <br>
                    C) Phi <br><br>
                    1) Meta <br>
                    2) OpenAI <br>
                    3) Microsoft
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-1, C-3</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 5: Azure AI Studio Capabilities</h2>
        <h3>Multiple Choice Questions</h3>
        <div class="question">
            <div class="question-text">47. Besides prompt engineering, what key capability does Azure AI Studio offer for building generative AI applications?</div>
            <ul class="options-list">
                <li>a) Video editing</li>
                <li>b) Data visualization</li>
                <li>c) Prompt Flow for orchestration</li>
                <li>d) Hardware management</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) Prompt Flow for orchestration.</div>
        </div>
        <div class="question">
            <div class="question-text">48. What is the purpose of "evaluations" within Azure AI Studio?</div>
            <ul class="options-list">
                <li>a) To assess the quality and performance of your AI solution.</li>
                <li>b) To calculate the cost of a model.</li>
                <li>c) To grade user prompts.</li>
                <li>d) To measure the server's temperature.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> a) To assess the quality and performance of your AI solution.</div>
        </div>
        <div class="question">
            <div class="question-text">49. What is a "vector database" designed to do?</div>
            <ul class="options-list">
                <li>a) Store images.</li>
                <li>b) Store and search numerical vector embeddings efficiently.</li>
                <li>c) Store traditional relational data.</li>
                <li>d) Store audio files.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Store and search numerical vector embeddings efficiently.</div>
        </div>
        <div class="question">
            <div class="question-text">50. What is a "grounding data source" in the context of RAG applications?</div>
            <ul class="options-list">
                <li>a) The model's original training data.</li>
                <li>b) The external knowledge base from which the model retrieves information.</li>
                <li>c) The user's input.</li>
                <li>d) A source of electrical power.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) The external knowledge base from which the model retrieves information.</div>
        </div>
       <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">51. Azure AI Studio supports only Python for development.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">52. Prompt Flow allows you to chain together multiple components, such as models and code, into a single workflow.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">53. The collaborative features in Azure AI Studio are limited to a single user.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">54. Embeddings are used to convert text into a numerical format for semantic search.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">55. Match the Azure AI Studio capability to its use: <br><br>
                    A) Playground <br>
                    B) Prompt Flow <br>
                    C) Evaluations <br><br>
                    1) Interacting with and testing a model in a UI. <br>
                    2) Orchestrating complex LLM workflows. <br>
                    3) Assessing the quality and performance of a solution.
                </div>
                <div class="answer"><strong>Answer:</strong> A-1, B-2, C-3</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 6: Observability in Generative AI</h2>
        <h3>Multiple Choice Questions</h3>
        <div class="question">
            <div class="question-text">56. What is the main goal of "observability" for a deployed generative AI application?</div>
            <ul class="options-list">
                <li>a) To monitor and ensure the application is performant, safe, and produces high-quality results.</li>
                <li>b) To make the application invisible to users.</li>
                <li>c) To reduce the application's cost to zero.</li>
                <li>d) To make the application run faster.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> a) To monitor and ensure the application is performant, safe, and produces high-quality results.</div>
        </div>
        <div class="question">
            <div class="question-text">57. Which Azure service is integrated with Azure AI Studio for monitoring deployed applications?</div>
            <ul class="options-list">
                <li>a) Azure Blob Storage</li>
                <li>b) Azure Monitor Application Insights</li>
                <li>c) Azure DevOps</li>
                <li>d) Azure Virtual Machines</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Azure Monitor Application Insights</div>
        </div>
        <div class="question">
            <div class="question-text">58. What does "continuous evaluation" in observability help monitor for agent-based applications?</div>
            <ul class="options-list">
                <li>a) The number of users.</li>
                <li>b) Quality and safety metrics.</li>
                <li>c) The time of day.</li>
                <li>d) The amount of storage used.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Quality and safety metrics.</div>
        </div>
        <div class="question">
            <div class="question-text">59. What is "AI red teaming"?</div>
            <ul class="options-list">
                <li>a) A team that trains the model.</li>
                <li>b) A security exercise where a team tries to find vulnerabilities and weaknesses in an AI system.</li>
                <li>c) A team that develops the UI.</li>
                <li>d) A team that writes documentation.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) A security exercise where a team tries to find vulnerabilities and weaknesses in an AI system.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">60. The observability dashboard in Azure AI Studio can provide insights into token consumption and latency.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">61. Observability is only important before an application is deployed to production.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">62. You can use Kusto Query Language (KQL) to explore and analyze telemetry data from your AI application.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">63. The purpose of observability is to hide any issues with the application.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">64. Automated scans using an AI red teaming agent can help identify potential safety issues before deployment.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
        </div>
       <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">65. Match the observability metric to its purpose: <br><br>
                    A) Groundedness <br>
                    B) Coherence <br>
                    C) Fluency <br><br>
                    1) Measures how understandable and human-like a model's response is. <br>
                    2) Measures the linguistic and grammatical correctness of a response. <br>
                    3) Measures whether a response is based on the provided external data source.
                </div>
                <div class="answer"><strong>Answer:</strong> A-3, B-1, C-2</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 7: Responsible Generative AI</h2>
        <h3>Multiple Choice Questions</h3>
       <div class="question">
            <div class="question-text">66. Which of the following is a core principle of responsible AI?</div>
            <ul class="options-list">
                <li>a) Cost-effectiveness</li>
                <li>b) Scalability</li>
                <li>c) Fairness</li>
                <li>d) Speed</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> c) Fairness</div>
        </div>
        <div class="question">
            <div class="question-text">67. What does "Fairness" in responsible AI aim to prevent?</div>
            <ul class="options-list">
                <li>a) Bias and discrimination in the model's output.</li>
                <li>b) The model from making mistakes.</li>
                <li>c) The model from being too fast.</li>
                <li>d) The model from using too much energy.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> a) Bias and discrimination in the model's output.</div>
        </div>
        <div class="question">
            <div class="question-text">68. What is "Transparency" in the context of responsible AI?</div>
            <ul class="options-list">
                <li>a) The model is easy to see through.</li>
                <li>b) The model's behavior and decisions are explainable and understandable.</li>
                <li>c) The model's code is open source.</li>
                <li>d) The model's training data is public.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) The model's behavior and decisions are explainable and understandable.</div>
        </div>
        <div class="question">
            <div class="question-text">69. What does "Inclusiveness" in responsible AI refer to?</div>
            <ul class="options-list">
                <li>a) The model is available in every country.</li>
                <li>b) The model is easy to use for everyone, including people with disabilities.</li>
                <li>c) The model includes many different types of data.</li>
                <li>d) The model is always accurate.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) The model is easy to use for everyone, including people with disabilities.</div>
        </div>
        <div class="question">
            <div class="question-text">70. Which of the following is a responsible AI feature in Azure OpenAI Service?</div>
            <ul class="options-list">
                <li>a) Automatic data deletion.</li>
                <li>b) Content filtering.</li>
                <li>c) Unlimited token usage.</li>
                <li>d) Guaranteed perfect accuracy.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Content filtering.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">71. Responsible AI is only a concern for developers, not business leaders.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">72. "Accountability" in responsible AI means there are clear lines of responsibility for an AI system's actions.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">73. Generative AI models are inherently unbiased because they are trained on vast amounts of data.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">74. "Reliability and Safety" means an AI system should perform consistently and predictably.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">75. Red teaming is a process used to test a model's security and safety.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">76. Match the responsible AI principle to its goal: <br><br>
                    A) Fairness <br>
                    B) Accountability <br>
                    C) Transparency <br><br>
                    1) Prevent biased outcomes. <br>
                    2) Ensure explainable behavior. <br>
                    3) Establish clear responsibility for system outcomes.
                </div>
                <div class="answer"><strong>Answer:</strong> A-1, B-3, C-2</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 8: Mixed Concepts & Applications</h2>
        <h3>Multiple Choice Questions</h3>
        <div class="question">
            <div class="question-text">77. How can generative AI be used in education?</div>
            <ul class="options-list">
                <li>a) To replace all teachers.</li>
                <li>b) To create personalized learning materials and interactive tutors.</li>
                <li>c) To manage school finances.</li>
                <li>d) To track student attendance.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) To create personalized learning materials and interactive tutors.</div>
        </div>
        <div class="question">
            <div class="question-text">78. What is the benefit of "iterative prompting" with a generative AI model?</div>
            <ul class="options-list">
                <li>a) It makes the model slower.</li>
                <li>b) It allows you to refine your prompt to get a better output.</li>
                <li>c) It costs more money.</li>
                <li>d) It makes the model repeat itself.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) It allows you to refine your prompt to get a better output.</div>
        </div>
        <div class="question">
            <div class="question-text">79. What is a key limitation of using generative AI for content creation?</div>
            <ul class="options-list">
                <li>a) It cannot generate creative content.</li>
                <li>b) It may generate inaccurate information that requires verification.</li>
                <li>c) It is always more expensive than human labor.</li>
                <li>d) It can only create short texts.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) It may generate inaccurate information that requires verification.</div>
        </div>
        <div class="question">
            <div class="question-text">80. How can Microsoft Copilot assist with creating training content?</div>
            <ul class="options-list">
                <li>a) By writing the entire training course automatically.</li>
                <li>b) By generating outlines, scripts, and practice questions.</li>
                <li>c) By taking the training for you.</li>
                <li>d) By grading the students.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) By generating outlines, scripts, and practice questions.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">81. Critical thinking is not necessary when using generative AI because the outputs are always correct.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">82. You should always verify the information generated by a generative AI model with external sources.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">83. "Source bias" refers to bias present in the training data of a model.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">84. Generative AI can be used to create realistic characters and environments in video games.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">85. Microsoft Copilot is a type of hardware device.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">86. Match the term to its application: <br><br>
                    A) Code Generation <br>
                    B) Personalized Tutoring <br>
                    C) Synthetic Data Generation <br><br>
                    1) Education <br>
                    2) Software Development <br>
                    3) Healthcare
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-1, C-3</div>
            </div>
        </div>
    </div>
    <div class="question-section">
        <h2>Part 9: Final Mixed Concepts</h2>
        <h3>Multiple Choice Questions</h3>
        <div class="question">
            <div class="question-text">87. What is a "cognitive bias" to be aware of when using AI?</div>
            <ul class="options-list">
                <li>a) Confirmation bias</li>
                <li>b) Technological bias</li>
                <li>c) Hardware bias</li>
                <li>d) Software bias</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> a) Confirmation bias</div>
        </div>
        <div class="question">
            <div class="question-text">88. When using generative AI for product design, what is a common use case?</div>
            <ul class="options-list">
                <li>a) Tracking inventory</li>
                <li>b) Generating new design concepts and prototypes</li>
                <li>c) Managing supply chains</li>
                <li>d) Automating billing</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) Generating new design concepts and prototypes</div>
        </div>
        <div class="question">
            <div class="question-text">89. What is the purpose of a "stop sequence" in prompt parameters?</div>
            <ul class="options-list">
                <li>a) To make the model stop working.</li>
                <li>b) To instruct the model to stop generating tokens at a certain sequence.</li>
                <li>c) To restart the model.</li>
                <li>d) To prevent the model from generating.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) To instruct the model to stop generating tokens at a certain sequence.</div>
        </div>
        <div class="question">
            <div class="question-text">90. How can a generative AI tool help a student improve their writing?</div>
            <ul class="options-list">
                <li>a) By writing the entire paper for them.</li>
                <li>b) By providing feedback on grammar, style, and structure.</li>
                <li>c) By summarizing content.</li>
                <li>d) By finding errors in code.</li>
            </ul>
            <div class="answer"><strong>Answer:</strong> b) By providing feedback on grammar, style, and structure.</div>
        </div>
        <h3>True or False</h3>
        <div class="true-false">
            <div class="question">
                <div class="question-text">91. Generative AI can accelerate the content creation process.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">92. The "playground" in Azure AI Studio is a place for running production deployments.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">93. A real-time endpoint is a hosted version of a model accessible via an API.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
            <div class="question">
                <div class="question-text">94. Observability is about hiding issues from users.</div>
                <div class="answer"><strong>Answer:</strong> False</div>
            </div>
            <div class="question">
                <div class="question-text">95. In-context learning involves providing examples within the prompt itself.</div>
                <div class="answer"><strong>Answer:</strong> True</div>
            </div>
        </div>
        <h3>Matching</h3>
        <div class="matching">
            <div class="question">
                <div class="question-text">96. Match the concept to its definition: <br><br>
                    A) Token <br>
                    B) Prompt <br>
                    C) Hallucination <br><br>
                    1) A fabricated output from a model. <br>
                    2) A unit of text. <br>
                    3) User input to guide a model.
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-3, C-1</div>
            </div>
            <div class="question">
                <div class="question-text">99. Match the responsible AI principle to its characteristic: <br><br>
                    A) Transparency <br>
                    B) Inclusiveness <br>
                    C) Reliability and Safety <br><br>
                    1) The system is understandable and explainable. <br>
                    2) The system performs consistently and safely. <br>
                    3) The system is easy to use for all users.
                </div>
                <div class="answer"><strong>Answer:</strong> A-1, B-3, C-2</div>
            </div>
            <div class="question">
                <div class="question-text">97. Match the Azure tool to its capability: <br><br>
                    A) Azure AI Studio Model Catalog <br>
                    B) Prompt Flow <br>
                    C) Azure OpenAI Service <br><br>
                    1) Access to curated foundation models. <br>
                    2) Orchestration of LLM-based applications. <br>
                    3) Enterprise-grade access to GPT models.
                </div>
                <div class="answer"><strong>Answer:</strong> A-1, B-2, C-3</div>
            </div>
            <div class="question">
                <div class="question-text">98. Match the parameter to its influence on output: <br><br>
                    A) Temperature <br>
                    B) Top P <br>
                    C) Frequency Penalty <br><br>
                    1) Reduces the likelihood of repetition. <br>
                    2) Controls the randomness. <br>
                    3) Limits token selection to a probability mass.
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-3, C-1</div>
            </div>
            <div class="question">
                <div class="question-text">100. Match the generative AI application to its output type: <br><br>
                    A) Text-to-Image <br>
                    B) Language Model <br>
                    C) Code Generation <br><br>
                    1) Python script <br>
                    2) A photograph from a description <br>
                    3) A paragraph of text
                </div>
                <div class="answer"><strong>Answer:</strong> A-2, B-3, C-1</div>
            </div>
        </div>
    </div>
</div>
</body>
</html>
