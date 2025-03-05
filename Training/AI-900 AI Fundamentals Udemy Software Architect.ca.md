# NOTES



## AI 900 - Microsoft Azure AI Fundamentals
Link del curso: https://deloittedevelopment.udemy.com/course/ai900-azure/learn/lecture/24746742#overview
### Fecha Inicio: [03/03/2025]

---

## Temas Principales



1. **Section 1: [Ai 900 - Azure AI Fundamentals]**
   - **Videos:**
    -  1
     	-  **Types of artificial intelligence:**
        - Azure Ai services
        - Open AI
        - Search
        - Vision
        - Speech
        - Language
        - Translator
        - Documents
        - Bots
        - Audio and Video
        - Decisions
        - Immersive reader
      - **What is ML model?**
        - A model will identify patterns, we need to test it and there are many ways to test it for the different models
      - **NOTES Azure**
        - Azure services are not longer named "cognitive services" those are called "Azure AI Services"
        - There are 5 sections for the certification
         - Describe AI and considerations
         - Fundamental principles
         - Computer vision
         - Natural language
         - fetures of genAI
        - All of them goes from 15 to 20% except for the fundamental principles  

3. **Section 2: Artificaion intelligence worloads and considerations**
   - **Videos:**
    -  1
     	-  **Common AI workloads**
        - **Machine learning workload** for predictions
         -  Training models to make predictions based on data. This is one of the core elements of AI and often forms the backbone of many AI systems.
         - for example using the visitoirs an sales table what I can see is in the next image
         - ![image](https://github.com/user-attachments/assets/c1fcc1c4-c457-4d4c-8aa1-7e335457e5ab)
         - Using prediction models like google, netflix etc are examples of them suggesting series or searchs
         - Second thing that AI can do is Anomaly Detection
          - ![image](https://github.com/user-attachments/assets/e9022a5e-777d-4771-92be-8eab89742013)
          - it can make a prediction based on anomaly detection
         - **Computer vision workload** is another thing that can do with AI
          - Create description of image
          - Identify faces
         - **Natural Language processing workload (NLP)**
          - related to this is Knowldege mining - cognitive search
          - Ingest content from blob storagesm tablesm,sl databases
         - Content moderator
          - Find proganity, hateful, offensive, violent or phishing and image. It will support multi langague you can ser the severity of the category
          - ![image](https://github.com/user-attachments/assets/efb1bc5b-ff38-40ec-ac47-d6cb9b04be22)
         - Gen AI
          - You can train bots to understand and create answers with new content based on a dataset. In other words it will create new content based on the dataset given to it.
          - ![image](https://github.com/user-attachments/assets/f4a25056-30ab-47af-8584-a8bc4032cdaf)
  -  7
     	-  **AI principles and ethics**
        - **Identify Unintended consequences**
        - -  Decisionas are wrong
          -  Decisionas are illegal or at least against the values
          -  ETC
          -  Example: Facial recognition racial bias problem, amazon scraps secert AI recruiting toolthat showed bias against women, millos of black people affected by racial bias en healtch care industry,  Calgary police face reconn can violate you privacy?
          -  What if the traffic control installs sensires in every interesectioinb to count cars, then install cameras and record the liucense plates, sounds good but waht if someone stole de info?
          -   **Six principles** in order to avoid that unintented consequences
          -  ![image](https://github.com/user-attachments/assets/3b7005a3-0141-4dc1-9eb1-d5745a505161)
   -  8
     	-  **Fairness**
      -  **Reliability and safety**
      -  **Privacy and security**
      -  **Inclusiveness**
      -  **Transparency**
      -  **Accontability**
   -  9
     	-  **Guidelines Human-AI Interactions**
       -  Microsoft has designb principles
  -  10
     	-  **ML common learning types**
        - **Regression** you can do some predictions for ex in scale 0 10 how hoappy is someonw with the salary
        - **Clasification** use cluster analysis so it has binary clasification so results is YEs or NOT
        - **Clustering** Find groups of related thins among data Ex what traits do my best customer have in common
  -  11
     	-  **Deep learning**
        - **AI**
        - **Machine learning** 
        - **Deep learning**
        - ![image](https://github.com/user-attachments/assets/58f2765c-0843-4ef5-8cab-8baf71bd8f7c)
  -  12
     	-  **Core machine learning concepts**
        - **Features and labels**
          - Given a pile of data, you the data scientis need to determine which bits are relevant to maje decisions
          - Example
          - ![image](https://github.com/user-attachments/assets/d40694a0-42d7-4702-96d9-714eff8cc29d)
        - **Training the Model**
          - Use a part of data to train the model and use another part of data for validation, good practice is split the training and validation datasets randomly
        - **Evaluate the results using regression**
          - Use the vcalidation dataset to thest the model, mesaure how close or far the actual results are from thje [predicted results
          - ***Mean Square Error** large diufferences are much that is for regression
        - **Evaluate the results for classification**
          - ![image](https://github.com/user-attachments/assets/37f5e357-2399-45ea-9fe1-4e4457df365d)
          - In the binbary classifications there are false positives vs false negatives
          - Compare true positives with false positives and true negatives wth false negatives this is related with accuracy vs precision
          - Example
          - ![image](https://github.com/user-attachments/assets/0f15ebfe-fce0-4ed1-a631-d2c14c4b0670)
          - ![image](https://github.com/user-attachments/assets/cbe4aa47-923e-44e6-9bf4-57c4d4b63a6f)
          - ![image](https://github.com/user-attachments/assets/50413e82-7faf-4da4-8621-6cf0c52f3d40)
          - ![image](https://github.com/user-attachments/assets/37e157fb-6d48-4945-b175-20169c631b24)
          - ![image](https://github.com/user-attachments/assets/c34f1aaa-4f0b-417e-b7f1-aa480f9bed4d)
  -  16
     	-  **No code ML**
        - **Automated MAchine Learning**
        - ![image](https://github.com/user-attachments/assets/a8c70cab-c23e-441b-9690-e92f3ee0fbd6)
        - ![image](https://github.com/user-attachments/assets/4aa629a0-f2f8-43b7-a0ca-083a10ddaf78)
        - **Automated Machine Learning** - this is Drag and drop tool;
        - Always remember taht we need to split the data between the training data and the validation data
  -  17
     	-  **No code ML**
        - **Azure ML designer and Auto ML Azure** are no code tool
  -  21
     	-  **Computer Vision**
        - Used for image clasification
        - Object detection. Identify objects coordinates and attirubites
        - Semantinc segmentation. Can be used to self driving cars  anyuthing that needs to udnerstand spaces in the images
        - Optical character recognition
        - Facial detection and recognition
        - Tools for this  is Cognitive services and Computer vision serie
        - Computver vision services
          - pre trained ML model, reconginze over 10000 oibjectes , can generate automatic captions for images and tags, detect faces
        - Custom Vision service
          - A model that you can train and sahre
          -  Face Services recognice human facen in an image, return the rectangle coordinates of thise 1 or more faces
          - Identify API is part of azure face services
          - Form recognizer serivce. IOt can identift an invoice pre built model or custom model
  -  21
     	-  **Computer Vision**
        - USed for image clasification
  -  28
     -  **Describes features of gen AI workloads**
       - ![image](https://github.com/user-attachments/assets/b4252b05-c126-48c8-a3a1-d93e89e09f8b)
       - Gen AI is create newly content from given train data it will not replicate the data is going to create new conent based on that data examples could be artiust and non artius, imitating tghe style of a fgamouys artist or hsitorical painting techinic, face generation
       - we can create human like responses to questions in a natural dialogue
       - compose new music or assits muysicucians, natural sounding fakes, sound effects, video generation deep fakes realistic videos where the actor has been replaced with another, animation is able to generate an animated sequence,improving videio resolution, color correction etc
       - OTher uses
        - Drug discovery, game desing, securyt, simulation and modeling
  -  28
     -  **Natural Language Model**
      -  NLG natural language generatior willl able to generate coherent and contextually appropaiuiate responses based on input data or prompts
      -  Azure Open AI Service, these moidels can perform task thew models are "o1 and o1 mini limit access" "GPT 4o" "GPT 4o mini" this is teh cheapest option
      -  Capabilities of  OpenAI for NLG
         -  Content generation
         -  Text summarisation
         -  conversational aentes
         -  codefge generation
         -  translation
         -  creatiuve writing
        - Benefits are
         - Scalability
         - Customization
         - Security
         - Integration



 



