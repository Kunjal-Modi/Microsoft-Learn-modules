<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<body>
    <header>
        <h1>100 Questions on Generative AI on Azure</h1>
        <p>Based on Microsoft Learn Modules: Get started with generative AI on Azure</p>
    </header>
    <hr class="section-divider">
    <main>
        <section id="multiple-choice-questions">
            <h2>Multiple Choice Questions</h2>
            <section class="question-group">
                <h3>Part 1: Generative AI Fundamentals</h3>
                <h4>1. What is the primary function of a generative AI model?</h4>
                <ol type="a">
                    <li>To classify data.</li>
                    <li>To analyze existing data for patterns.</li>
                    <li>To create new, original content.</li>
                    <li>To predict future trends.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
                <h4>2. What is a "prompt" in the context of generative AI?</h4>
                <ol type="a">
                    <li>The output from the model.</li>
                    <li>A type of generative model.</li>
                    <li>The input a user provides to guide the model's generation.</li>
                    <li>The training dataset.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
                <h4>3. Which of the following is a common application of generative AI?</h4>
                <ol type="a">
                    <li>Running a transactional database.</li>
                    <li>Generating realistic images from text descriptions.</li>
                    <li>Managing network traffic.</li>
                    <li>Performing financial audits.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>4. What does the term "hallucination" mean in the context of generative AI?</h4>
                <ol type="a">
                    <li>The model is dreaming.</li>
                    <li>The model generates incorrect, fabricated, or nonsensical information.</li>
                    <li>The model is used for virtual reality.</li>
                    <li>The model is creating highly imaginative content.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>5. What is a "foundation model"?</h4>
                <ol type="a">
                    <li>A small model trained for a very specific task.</li>
                    <li>A large model trained on vast amounts of data that can be adapted for various tasks.</li>
                    <li>A model used to build foundations of buildings.</li>
                    <li>The first version of a model.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
            </section>
            <section class="question-group">
                <h3>True or False</h3>
                <h4>6. Generative AI models are always 100% accurate and do not require human review.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>7. A key ethical concern with generative AI is the potential to create deepfakes and misinformation.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>8. Discriminative AI is used to create new data, while generative AI classifies existing data.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>9. Generative AI is limited to creating only text content.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>10. The output from a generative AI model is deterministic and will be the same every time for the same prompt.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
            </section>
            <section class="question-group">
                <h3>Matching</h3>
                <h4>11. Match the generative AI model type to its characteristic: <br><br>
                    A) GAN <br>
                    B) VAE <br>
                    C) Transformer <br><br>
                    1) Uses an encoder-decoder architecture to learn latent representations. <br>
                    2) Employs a Generator and a Discriminator that compete with each other. <br>
                    3) Uses a self-attention mechanism to understand context in sequences.
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-2, B-1, C-3</p>
                    </div>
                </details>
                <h4>12. Match the generative AI application to its industry: <br><br>
                    A) Healthcare <br>
                    B) Software Development <br>
                    C) Marketing <br><br>
                    1) Generating synthetic medical images for training. <br>
                    2) Creating personalized ad copy and creative assets. <br>
                    3) Generating code snippets and documentation.
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-1, B-3, C-2</p>
                    </div>
                </details>
            </section>
        </section>
        <section id="large-language-models">
            <h2>Part 2: Large Language Models (LLMs) & Prompting</h2>
            <section class="question-group">
                <h3>Multiple Choice Questions</h3>
                <h4>13. What does "LLM" stand for?</h4>
                <ol type="a">
                    <li>Lightweight Learning Module</li>
                    <li>Large Language Model</li>
                    <li>Long-form Learning Machine</li>
                    <li>Low-level Logic Model</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>14. What is a "token" in the context of LLMs?</h4>
                <ol type="a">
                    <li>A complete sentence.</li>
                    <li>A unit of text, such as a word or part of a word.</li>
                    <li>A character in a string.</li>
                    <li>A punctuation mark.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>15. What is "in-context learning"?</h4>
                <ol type="a">
                    <li>Training the model from scratch.</li>
                    <li>The model's ability to learn from examples provided in the prompt.</li>
                    <li>The model's ability to learn from a database.</li>
                    <li>The model's ability to learn by itself without any examples.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>16. What parameter controls the randomness of an LLM's output?</h4>
                <ol type="a">
                    <li>Max tokens</li>
                    <li>Temperature</li>
                    <li>Frequency penalty</li>
                    <li>Top P</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>17. What is "prompt engineering"?</h4>
                <ol type="a">
                    <li>Designing a computer chip.</li>
                    <li>The process of training a new LLM.</li>
                    <li>The art and science of crafting effective prompts to guide an LLM's output.</li>
                    <li>Building a prompt flow.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
            </section>
            <section class="question-group">
                <h3>True or False</h3>
                <h4>18. A "system message" in a prompt is used to define the model's persona and instructions.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>19. A lower temperature setting will result in a more creative and random response.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>20. "Zero-shot learning" means the LLM can perform a task it has never seen before, with no examples in the prompt.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>21. The token limit for an LLM applies only to the input, not the output.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>22. "Chain-of-thought" prompting helps the model arrive at a better answer by guiding it to think step-by-step.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
            </section>
            <section class="question-group">
                <h3>Matching</h3>
                <h4>23. Match the prompt engineering technique to its description: <br><br>
                    A) Zero-shot prompting <br>
                    B) Few-shot prompting <br>
                    C) Chain-of-thought prompting <br><br>
                    1) Providing a few examples in the prompt to teach the model a new task. <br>
                    2) Giving the model no examples, just the task. <br>
                    3) Instructing the model to reason through a problem step-by-step.
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-2, B-1, C-3</p>
                    </div>
                </details>
                <h4>24. Match the LLM parameter to its effect on output: <br><br>
                    A) Temperature <br>
                    B) Max tokens <br>
                    C) Top P <br><br>
                    1) Controls the maximum length of the response. <br>
                    2) Controls the randomness of the output. <br>
                    3) Limits the AI to consider only a certain percentage of probability mass.
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-2, B-1, C-3</p>
                    </div>
                </details>
            </section>
        </section>
        <section id="tools-to-develop-generative-ai-solutions">
            <h2>Part 3: Tools to Develop Generative AI Solutions</h2>
            <section class="question-group">
                <h3>Multiple Choice Questions</h3>
                <h4>25. What Azure service provides access to OpenAI's powerful language models with enterprise-grade security?</h4>
                <ol type="a">
                    <li>Azure Machine Learning</li>
                    <li>Azure AI Services</li>
                    <li>Azure OpenAI Service</li>
                    <li>Azure App Service</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
                <h4>26. What is "fine-tuning" a generative AI model?</h4>
                <ol type="a">
                    <li>Adjusting the model's physical size.</li>
                    <li>Further training a pre-trained model on a smaller, specific dataset.</li>
                    <li>Making the model's output more random.</li>
                    <li>Changing the model's architecture.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>27. Which Azure tool is a unified platform for building, training, and deploying AI solutions?</h4>
                <ol type="a">
                    <li>Azure Portal</li>
                    <li>Azure Blob Storage</li>
                    <li>Azure AI Studio (formerly Azure AI Foundry)</li>
                    <li>Azure DevOps</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
                <h4>28. What is "Retrieval-Augmented Generation (RAG)"?</h4>
                <ol type="a">
                    <li>The model retrieves information from its own training data.</li>
                    <li>The model retrieves information from an external knowledge base to inform its generation.</li>
                    <li>The model hallucinates information.</li>
                    <li>The model is angry.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>29. What is "Prompt Flow" in Azure AI Studio?</h4>
                <ol type="a">
                    <li>A tool for managing your prompts.</li>
                    <li>A visual tool for orchestrating and evaluating LLM-based applications.</li>
                    <li>A method for running code.</li>
                    <li>A type of database.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
            </section>
            <section class="question-group">
                <h3>True or False</h3>
                <h4>30. Azure AI Studio's playground is intended for production-level deployments.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>31. "Parameter-efficient fine-tuning (PEFT)" is a technique for training a model on a very large dataset.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>32. RAG helps ground a generative AI model's responses in verifiable, external data.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>33. Azure AI services include built-in tools for content filtering and moderation to promote responsible AI.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>34. A real-time endpoint is a hosted version of a model that can be called via an API for inference.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
            </section>
            <section class="question-group">
                <h3>Matching</h3>
                <h4>35. Match the Azure tool to its function: <br><br>
                    A) Azure OpenAI Service <br>
                    B) Azure AI Studio <br>
                    C) Prompt Flow <br><br>
                    1) A visual orchestration tool for building LLM applications. <br>
                    2) Provides secure access to OpenAI models. <br>
                    3) A unified platform for the end-to-end AI lifecycle.
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-2, B-3, C-1</p>
                    </div>
                </details>
                <h4>36. Match the term to its definition: <br><br>
                    A) Fine-tuning <br>
                    B) RAG <br>
                    C) Embeddings <br><br>
                    1) Adapting a pre-trained model with a smaller dataset. <br>
                    2) Converting data into numerical vectors for semantic search. <br>
                    3) Using external data sources to enhance model generation.
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-1, B-3, C-2</p>
                    </div>
                </details>
            </section>
        </section>
        <section id="azure-ai-studio-model-catalog">
            <h2>Part 4: Azure AI Studio Model Catalog</h2>
            <section class="question-group">
                <h3>Multiple Choice Questions</h3>
                <h4>37. What is the primary purpose of the Model Catalog in Azure AI Studio?</h4>
                <ol type="a">
                    <li>To sell AI models.</li>
                    <li>To provide a centralized hub for discovering and deploying foundation models.</li>
                    <li>To store user data.</li>
                    <li>To manage compute resources.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>38. The models available in the catalog include:</h4>
                <ol type="a">
                    <li>Only models from Microsoft.</li>
                    <li>Only open-source models.</li>
                    <li>Both Microsoft-developed models and curated open-source models.</li>
                    <li>Only models you have trained yourself.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
                <h4>39. What is a key benefit of using a model from the catalog?</h4>
                <ol type="a">
                    <li>You have to train it from scratch.</li>
                    <li>They are pre-trained and ready to be used or fine-tuned.</li>
                    <li>They are not compatible with other Azure services.</li>
                    <li>They are free of charge for all usage.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>40. What action does the "deploy" button next to a model in the catalog typically perform?</h4>
                <ol type="a">
                    <li>Deletes the model from the catalog.</li>
                    <li>Downloads the model to your local machine.</li>
                    <li>Deploys the model as a real-time endpoint for inference.</li>
                    <li>Starts the training process for the model.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
                <h4>41. What is the "Model as a Service (MaaS)" approach?</h4>
                <ol type="a">
                    <li>You manage all the infrastructure for the model.</li>
                    <li>The model is provided as a hosted API, simplifying deployment and scaling.</li>
                    <li>The model is only available for offline use.</li>
                    <li>The model is a physical machine.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
            </section>
            <section class="question-group">
                <h3>True or False</h3>
                <h4>42. Every model in the Azure AI Studio Model Catalog is open source.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>43. The model catalog provides information about a model's capabilities, limitations, and responsible AI considerations.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>44. You cannot fine-tune a model from the catalog; you must use it as-is.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>45. The Model Catalog is only for discovering text-based models.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
            </section>
            <section class="question-group">
                <h3>Matching</h3>
                <h4>46. Match the model type to its provider in the Azure AI Model Catalog: <br><br>
                    A) GPT-4 <br>
                    B) Llama 2 <br>
                    C) Phi <br><br>
                    1) Meta <br>
                    2) OpenAI <br>
                    3) Microsoft
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-2, B-1, C-3</p>
                    </div>
                </details>
            </section>
        </section>
        <section id="azure-ai-studio-capabilities">
            <h2>Part 5: Azure AI Studio Capabilities</h2>
            <section class="question-group">
                <h3>Multiple Choice Questions</h3>
                <h4>47. Besides prompt engineering, what key capability does Azure AI Studio offer for building generative AI applications?</h4>
                <ol type="a">
                    <li>Video editing</li>
                    <li>Data visualization</li>
                    <li>Prompt Flow for orchestration</li>
                    <li>Hardware management</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: c)</p>
                </details>
                <h4>48. What is the purpose of "evaluations" within Azure AI Studio?</h4>
                <ol type="a">
                    <li>To assess the quality and performance of your AI solution.</li>
                    <li>To calculate the cost of a model.</li>
                    <li>To grade user prompts.</li>
                    <li>To measure the server's temperature.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: a)</p>
                </details>
                <h4>49. What is a "vector database" designed to do?</h4>
                <ol type="a">
                    <li>Store images.</li>
                    <li>Store and search numerical vector embeddings efficiently.</li>
                    <li>Store traditional relational data.</li>
                    <li>Store audio files.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>50. What is a "grounding data source" in the context of RAG applications?</h4>
                <ol type="a">
                    <li>The model's original training data.</li>
                    <li>The external knowledge base from which the model retrieves information.</li>
                    <li>The user's input.</li>
                    <li>A source of electrical power.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
            </section>
            <section class="question-group">
                <h3>True or False</h3>
                <h4>51. Azure AI Studio supports only Python for development.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>52. Prompt Flow allows you to chain together multiple components, such as models and code, into a single workflow.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>53. The collaborative features in Azure AI Studio are limited to a single user.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>54. Embeddings are used to convert text into a numerical format for semantic search.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
            </section>
            <section class="question-group">
                <h3>Matching</h3>
                <h4>55. Match the Azure AI Studio capability to its use: <br><br>
                    A) Playground <br>
                    B) Prompt Flow <br>
                    C) Evaluations <br><br>
                    1) Interacting with and testing a model in a UI. <br>
                    2) Orchestrating complex LLM workflows. <br>
                    3) Assessing the quality and performance of a solution.
                </h4>
                <details>
                    <summary>Show Correct Matches</summary>
                    <div class="correct-match">
                        <p>A-1, B-2, C-3</p>
                    </div>
                </details>
            </section>
        </section>
        <section id="observability-in-generative-ai">
            <h2>Part 6: Observability in Generative AI</h2>
            <section class="question-group">
                <h3>Multiple Choice Questions</h3>
                <h4>56. What is the main goal of "observability" for a deployed generative AI application?</h4>
                <ol type="a">
                    <li>To monitor and ensure the application is performant, safe, and produces high-quality results.</li>
                    <li>To make the application invisible to users.</li>
                    <li>To reduce the application's cost to zero.</li>
                    <li>To make the application run faster.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: a)</p>
                </details>
                <h4>57. Which Azure service is integrated with Azure AI Studio for monitoring deployed applications?</h4>
                <ol type="a">
                    <li>Azure Blob Storage</li>
                    <li>Azure Monitor Application Insights</li>
                    <li>Azure DevOps</li>
                    <li>Azure Virtual Machines</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>58. What does "continuous evaluation" in observability help monitor for agent-based applications?</h4>
                <ol type="a">
                    <li>The number of users.</li>
                    <li>Quality and safety metrics.</li>
                    <li>The time of day.</li>
                    <li>The amount of storage used.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
                <h4>59. What is "AI red teaming"?</h4>
                <ol type="a">
                    <li>A team that trains the model.</li>
                    <li>A security exercise where a team tries to find vulnerabilities and weaknesses in an AI system.</li>
                    <li>A team that develops the UI.</li>
                    <li>A team that writes documentation.</li>
                </ol>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: b)</p>
                </details>
            </section>
            <section class="question-group">
                <h3>True or False</h3>
                <h4>60. The observability dashboard in Azure AI Studio can provide insights into token consumption and latency.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>61. Observability is only important before an application is deployed to production.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>62. You can use Kusto Query Language (KQL) to explore and analyze telemetry data from your AI application.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
                <h4>63. The purpose of observability is to hide any issues with the application.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: False</p>
                </details>
                <h4>64. Automated scans using an AI red teaming agent can help identify potential safety issues before deployment.</h4>
                <details>
                    <summary>Show Answer</summary>
                    <p>Correct Answer: True</p>
                </details>
            </section>
        </section>
    </main>
</body>
</html>
