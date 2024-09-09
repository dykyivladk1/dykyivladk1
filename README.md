# Saving the user's README content as a markdown file

readme_content = """
# Hey There 👋  
I'm **Vladyslav Dykyi**, a passionate AI/ML Developer specializing in:

- Development of AI models
- Deep Learning
- Audio Deep Learning
- Natural Language Processing (NLP)
- Computer Vision

## C O N T A C T A B O U T M E
- **Email**: vladdikiy17@gmail.com  
- **Website**: [https://portcode.at/](https://portcode.at/)  
- **Location**: Linz, Upper Austria  
- **Phone Number**: +43-688-640-595-08  

## W O R K E X P E R I E N C E

### **FREELANCER | TECH INNOVATIONS ODESSA**  
**UpWork | 2021-2023**  
**Private Company | 2022-2023**

- Developed and deployed AI/ML models that increased processing efficiency by 35% and reduced manual intervention by 50%.
- Led a team of 3 developers to create advanced computer vision models, achieving a 92% precision rate in object detection tasks, which directly improved customer support automation.

### **WIZA TELEGRAM BOT**  
Founder of the WIZA Telegram bot, a comprehensive travel assistant supporting 39 countries and 462 cities.  
- Features: Top-rated restaurants and hotels, currency conversion, local taxi services, nearby hospitals, shopping centers, apartment rental options, emergency contacts, and upcoming events.  
- The bot utilizes a proprietary WIZA search engine and supports multiple languages for seamless travel experiences.

## P R O J E C T S

### **POLIP**  
Founder of the POLIP library, a comprehensive toolkit designed for Machine Learning developers.  
- POLIP includes essential functions and classes that significantly enhance model performance, offering custom implementations to improve the efficiency and accuracy of machine learning models.

### **GPT-X**  
Developed a custom version of the Generative Pretrained Transformer (GPT), named GPT-X, consisting of 56 transformer blocks.  
- This model integrates causal self-attention mechanisms and byte-pair encoding for efficient tokenization, optimized for various NLP tasks.

### **TEXT-TO-SPEECH WEBSITE**  
Developed a website featuring trained Tacotron models for high-performance text-to-speech conversions.  
- The project involved both model training and full-stack development to ensure a seamless user experience.

## E D U C A T I O N

### **Johannes Kepler University Linz**  
- Bachelor in AI (2023-Present)

### **IT School Odessa**  
- Python Developer (2021-2022)

## S K I L L S
- Web-Scraping
- Data analysis
- Data gathering
- Chatbot development
"""

# Saving the content to a README.md file
with open("/mnt/data/README.md", "w") as file:
    file.write(readme_content)

"/mnt/data/README.md"
