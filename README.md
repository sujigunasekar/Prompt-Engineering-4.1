# Exno.4-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222230152
### Aim:
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 2 with Comparative Analysis Prompt, Comparative Analysis Prompt and Prompt Size Limitations

### Explanation - Any one use case from Unit 5 and generate the report for that with the unit 2 Prompt type
### Procedure:
1.	Define the Scenario and Use Case:
### Scenario:
The manufacturing industry is looking to reduce manual monitoring and increase efficiency through automation. The system will utilize IoT devices and embedded controllers to automate equipment, monitor performance, and enable predictive maintenance. The goal is to streamline the production process, minimize downtime, and enhance energy efficiency.

### Target Audience:
Manufacturing companies, specifically in sectors like automotive, electronics, and food processing, where automation can significantly improve productivity.

### Main Objectives:
•	Improve production efficiency by 30%.
•	Minimize machinery downtime with predictive maintenance.
•	Enable real-time monitoring and remote control of manufacturing systems.
•	Reduce energy consumption by optimizing processes.
 
### 2.	Identify Prompt Patterns for Each Design Aspect:
Idea Generation Prompts:

•	Prompt: “What features can be incorporated into the automation system to optimize production and reduce downtime?” Generated Ideas:
•	Sensors for real-time monitoring of equipment performance.
•	Predictive maintenance alerts to anticipate equipment failures.
•	Energy usage optimization by automating the switching of machines on/off based on demand.
•	Cloud-based dashboards for remote monitoring and control of machinery.

### Persona and Context Prompts:

•	Prompt: “What should the user interface and control system convey to the operators and managers?” Generated Context:
•	The user interface should be intuitive and provide real-time data on machine performance, energy usage, and alerts.
•	The system should convey reliability and ease of use, with minimal training required for operators.

## Prompting Techniques
### 🔹 1. Straightforward Prompt
#### 📝 Prompt Input:
A 65-year-old male has high fever (38.9°C), chest pain, and persistent cough. Suggest a diagnosis and treatment.

#### 🤖 Meta’s LLaMA Response:

Likely diagnosis is pneumonia. Recommend broad-spectrum antibiotics, rest, hydration, and paracetamol for fever. Suggest chest X-ray, complete blood count, and oxygen saturation monitoring.

#### 🤖 Google Gemini Response:

Symptoms are consistent with pneumonia or COVID-19. Recommend antibiotics if bacterial pneumonia is suspected or antivirals if COVID-19 confirmed. Suggest PCR test, chest imaging, and hospital observation if condition worsens.

### ✅ Comparison:

Meta’s LLaMA is focused, accurate, and concise.

Gemini includes wider differential and modern diagnostic pathways.

Best: Gemini (more comprehensive and updated).

### 🔹 2. Tabular Format Prompt
#### 📝 Prompt Input:
"Interpret the following patient data and provide diagnosis and treatment suggestions."
| Symptom             | Value          |
| ------------------- | -------------- |
| Temperature         | 38.9°C         |
| Respiratory Rate    | 22 breaths/min |
| Heart Rate          | 105 bpm        |
| Blood Pressure      | 145/90 mmHg    |
| Cough               | Persistent     |
| Shortness of Breath | Present        |

### 🤖 Meta’s LLaMA Response:

Signs suggest a respiratory infection, likely pneumonia. Recommend antibiotics, chest X-ray, oxygen monitoring, and supportive care (fluids, rest, paracetamol).

#### 🤖 Google Gemini Response:

The elevated temperature, high respiratory rate, and cough indicate pneumonia. Immediate tests include chest X-ray and blood culture. Start empirical antibiotics and observe oxygen saturation. Consider hospitalization if elderly/comorbid.

#### ✅ Comparison:

Both tools identify the correct diagnosis.

Gemini provides more structured clinical steps and is tailored for high-risk patients.

Best: Gemini (structured output and patient risk evaluation).

### 🔹 3. Missing Word Prompt
#### 📝 Prompt Input:
"Patient is experiencing joint pain, fatigue, and swelling. Most likely diagnosis is ____. Recommended treatment is ____."

#### 🤖 Meta’s LLaMA Response:

Diagnosis is rheumatoid arthritis. Recommended treatment is NSAIDs, DMARDs like methotrexate, and physiotherapy.

#### 🤖 Google Gemini Response:

Most likely diagnosis: Rheumatoid arthritis. Treatment: Anti-inflammatory medications, physical therapy, and possible DMARDs. Recommend rheumatologist referral.

### ✅ Comparison:

Both provide accurate and appropriate completions.

Gemini includes specialist referral and slightly more layman-friendly phrasing.

Best: Tie (Gemini slightly more patient-friendly, but both are accurate).

### 🔹 4. Chain-of-Thought Prompt
#### 📝 Prompt Input:
"An elderly patient with diabetes and hypertension reports swollen ankles and breathlessness at night. What’s the diagnosis? Explain step-by-step."

#### 🤖 Meta’s LLaMA Response:

Patient is elderly with chronic conditions.

Symptoms suggest fluid overload.

Nocturnal breathlessness is typical of orthopnea.

Likely diagnosis: congestive heart failure.

Suggest echocardiogram, diuretics, and cardiology referral.

#### 🤖 Google Gemini Response:

Diabetes and hypertension increase cardiovascular risk.

Swollen ankles = fluid retention.

Breathlessness at night = orthopnea, common in heart failure.

Most likely diagnosis is congestive heart failure (CHF).

Treatment includes fluid restriction, diuretics, and monitoring BP/glucose.

#### ✅ Comparison:

Both tools demonstrate clear logical flow.

Gemini explains terms like orthopnea, includes glucose/BP management.

Best: Gemini (better patient explanation and holistic advice).

### 🔹 5. Role-Based Prompt
#### 📝 Prompt Input:
"As a friendly AI nurse, explain to a 70-year-old diabetic patient how to manage their condition at home."

### 🤖 Meta’s LLaMA Response:

"To manage diabetes, you should monitor your blood sugar, take medications as prescribed, eat a balanced diet, and exercise regularly. Don’t forget to check your feet daily. If you feel dizzy or confused, contact your doctor."

### 🤖 Google Gemini Response:

"Hi there! Managing your diabetes is really important, and I’m here to help you every step of the way 😊. Check your blood sugar daily, follow a healthy meal plan (low sugar, high fiber), stay active (light walking is great!), and take your medicine on time. Remember, you’re not alone – reach out to your doctor if anything feels off. You're doing great! 💪"

### ✅ Comparison:

Meta’s response is helpful but formal.

Gemini uses empathetic tone, emojis, and reassurance — great for elderly users.

Best: Gemini (excellent tone and human-like interaction).

### ✅ Overall Summary
| Prompt Type              | Best Tool | Reason                                           |
| ------------------------ | --------- | ------------------------------------------------ |
| Straightforward Prompt   | Gemini    | Broader differential & test suggestions          |
| Tabular Format Prompting | Gemini    | More structured and clinically aware             |
| Missing Word Prompting   | Tie       | Both accurate, Gemini slightly more approachable |
| Chain-of-Thought         | Gemini    | Clearer logical flow and explanations            |
| Role-Based Prompt        | Gemini    | Empathetic and friendly tone                     |

# Result: 
Thus the Prompts were exected succcessfully.

