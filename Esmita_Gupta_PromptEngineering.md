# Prompt Engineering Portfolio
Name: Esmita Gupta
Date: 5-6-26
LLM Used: ChatGPT-4

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation
## Goal

Explain a complex technical concept to a 10-year-old.

## Selected Concept
**Neural Networks**

---

## Initial Prompt
Explain neural networks concept to a 10-year-old.

## Output
Think of a neural network as a computer learner.
Imagine you want to teach it the difference between a cat and a dog. You show it lots of pictures:
“This is a cat.”
“This is a dog.”
At first, it may guess badly. It might see a fluffy dog and say, “Cat!” But when you tell it the correct answer, it learns from its mistake.
After seeing many pictures, it begins to notice patterns:
Cats often have whiskers and pointy ears.
Dogs may have longer noses or floppy ears.
Then, when it sees a new picture, it uses what it has learned to make a guess.
A neural network is like a child learning through examples and practice. The more good examples it sees, the better it usually becomes at recognizing things.

## Expected Issue with Initial Prompt
The prompt is too broad. It does not specify the tone, examples, length, or level of detail. The answer may become too technical or too vague.

---

## Refined Prompt – Iteration 1
Explain neural networks to a 10-year-old using simple words and a fun example. Avoid technical terms.

## Output
A neural network is a way to teach a computer by showing it many examples.
Imagine teaching a computer to recognize cats and dogs. You show it a picture of a cat and say, “Cat.” Then you show it a dog and say, “Dog.”
At first, the computer may get confused. It might call a small dog a cat. But each time you correct it, it learns a little more.
After seeing many pictures, it starts noticing helpful clues, such as ears, whiskers, faces, and body shapes. Then, when it sees a new picture, it makes its best guess.
It is a bit like how you learn to identify animals, letters, or faces: by looking, trying, making mistakes, and getting better with practice.
A neural network does not think or understand like a person. It is simply very good at finding clues in many examples.

## Improvement Made
This prompt improves the first version by asking for simple language and a relatable example. However, it still does not define the structure or check whether the child understands the concept.

---

## Refined Prompt – Iteration 2
You are an expert teacher who explains difficult ideas to children. Explain neural networks to a 10-year-old in less than 200 words. Use an example of how a child learns to recognize cats and dogs. Avoid technical terms. End with one simple question to check understanding.

## Output
Imagine you are learning to tell cats and dogs apart.
At first, someone shows you many pictures and says, “This is a cat” or “This is a dog.” You begin noticing clues:
Cats may have pointy ears, small faces, and long whiskers.
Dogs may have longer noses, floppy ears, or bigger bodies.
Sometimes you make mistakes. You may call a small fluffy dog a cat! When someone corrects you, you learn from the mistake.
A neural network learns in a similar way. It looks at lots of pictures of cats and dogs. Each time it guesses, it is told whether it was right or wrong. Little by little, it gets better at noticing clues and making the correct choice.
It does not think exactly like a person. It learns by practicing with many examples, just like you improve when you practice reading, drawing, or playing a game.
Question: How does a neural network get better at telling cats and dogs apart?

## Improvement Made
This prompt is stronger because it gives clear instructions about:

- **Audience:** 10-year-old child
- **Length:** Less than 200 words
- **Example:** Recognizing cats and dogs
- **Style:** No technical terms
- **Interaction:** End with a question

---

## Final Prompt
Explain neural networks to a 10-year-old in less than 200 words. Use a simple example of how a child learns to recognize cats and dogs. Avoid technical terms like “algorithm,” “weights,” or “training data.” Use a friendly tone and end with one simple question to check understanding.

---

## Final LLM Response

A neural network is like a brain made for a computer.

Imagine you are learning to tell the difference between cats and dogs. At first, someone shows you many pictures. You notice that cats usually have pointy ears, smaller faces, and whiskers. Dogs may have bigger noses, different ears, and different body shapes.

After seeing many pictures, your brain starts learning patterns. So, when you see a new animal picture, you can guess, “That is a cat!” or “That is a dog!”

A neural network works in a similar way. It looks at many examples and slowly learns patterns. It does not understand like a human, but it becomes good at making guesses based on what it has seen before.

For example, if we show it thousands of cat and dog pictures, it can learn to recognize a new picture and say whether it looks more like a cat or a dog.

**Question:** Why do you think seeing many examples helps the computer learn better?

---

### 1.1 Scenario B: Professional Email
## Goal: 
Draft an email declining a job offer politely while expressing continued interest in the company

## Initial Prompt: 
Write an email to decline a job offer expressing continued interest

## Output
Dear [Hiring Manager’s Name],
Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time you and your team invested throughout the interview process and the opportunity to learn more about the organization.
After careful consideration, I have decided to decline the offer at this time. This was not an easy decision, as I was genuinely impressed by the company, its values, and the people I had the opportunity to meet.
I remain very interested in [Company Name] and would be grateful to stay connected for any suitable opportunities in the future.
Thank you once again for your time, consideration, and confidence in me. I wish you and the team continued success.
Sincerely,
[Your Name]

---
## Refined Prompt - Iteration 1:
Write a polite email declining a job offer in professional language, thanking the company for the opportunity.

## Output
Dear [Hiring Manager’s Name],
Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time and effort you and your team invested throughout the interview process.
After careful consideration, I have decided to decline the offer at this time. This was not an easy decision, as I am truly grateful for the opportunity and impressed by the company and its work.
Thank you once again for your time, consideration, and confidence in me. I wish you and the team continued success.
Sincerely,
[Your Name]

---
## Refined Prompt - Iteration 2:
You are a professional career coach. Draft a polite email declining a job offer because the candidate has accepted another opportunity, while expressing gratitude and interest in staying connected for future roles.

## Output
Dear [Hiring Manager’s Name],
Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time and effort you and your team invested throughout the interview process.
After careful consideration, I have decided to accept another opportunity that is more closely aligned with my current career goals. Therefore, I must respectfully decline the offer at this time.
I am truly grateful for the opportunity to learn more about [Company Name], and I was very impressed by the team and the work being done. I would be happy to stay connected and hope to be considered for suitable opportunities in the future.
Thank you once again for your time, support, and consideration.
Sincerely,
[Your Name]

---
## Final Prompt
You are a professional career coach helping a candidate write a respectful and polished email. The candidate has received a job offer but has decided to accept another opportunity that is better aligned with their current goals. Draft a concise, polite email declining the offer. The email should thank the company, show appreciation for the interview process, respectfully decline the offer, and express continued interest in the company for future opportunities.

## Output
Dear [Hiring Manager’s Name],
Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time and effort you and your team invested throughout the interview process, and I am grateful for the opportunity to learn more about the company and the role.
After careful consideration, I have decided to accept another opportunity that is more closely aligned with my current career goals. Therefore, I must respectfully decline the offer at this time.
I have great respect for [Company Name] and would be happy to stay connected for any suitable opportunities in the future.
Thank you once again for your time, consideration, and support.
Sincerely,
[Your Name]

---

### 1.1 Scenario C: Creative Content
## Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

## Initial Prompt
Create a marketing tagline for an eco-friendly water bottle.

## Output:
Here are some tagline options for an eco-friendly water bottle:
Sip Smart. Save More.
Refill Today. Respect Tomorrow.
Hydrate with Purpose.
Better Bottle. Better Planet.
Drink Clean. Live Green.
Reusable by Choice. Responsible by Nature.
Every Sip Makes a Difference.
Stay Hydrated, Stay Sustainable.
Designed to Refill. Made to Last.
Less Plastic. More Purpose.
Best option: Hydrate with Purpose.

Expected Issue with Initial Prompt
The prompt is too simple and may produce generic taglines. It does not specify brand personality, target audience, or desired style.

## Refined Prompt – Iteration 1
Create five short and catchy taglines for a new eco-friendly water bottle brand.

## Output
Sip Smart. Save More.
Refill. Reuse. Refresh.
Drink Clean. Live Green.
Hydration Without Waste.
Better Bottle, Better Tomorrow.

Improvement Made
This prompt asks for multiple options and specifies that the taglines should be short and catchy. However, it still lacks brand context and target audience.

---
## Refined Prompt – Iteration 2
You are a professional copywriter. Create five short, catchy, and memorable taglines for a premium eco-friendly water bottle brand targeted at young adults who care about sustainability and style.

## Output
Refill Your Style.
Sip Smart. Look Sharp.
Sustainable Sips, Premium Feel.
Drink Better. Waste Less.
Carry Style. Leave Less Behind.

Improvement Made
This version adds a role, brand positioning, audience, and tone. It helps the output become more focused and market-ready.

---
## Final Prompt
You are a professional brand copywriter creating marketing copy for a premium eco-friendly water bottle brand. The brand targets young adults who want a stylish, reusable, and sustainable alternative to plastic bottles. Create five short, catchy, and memorable taglines. The tone should be fresh, modern, and environmentally conscious. Avoid clichés like “save the planet” or “go green.”

## Final LLM Response
Refill Your Style.
Sip Smart. Waste Less.
Hydration with a Conscience.
Built to Reuse. Designed to Impress.
Drink Better. Live Lighter.

### 1.2 Iteration Documentation
## Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|---|---|---|---|
| V1 | Explain neural networks to a 10-year-old. | N/A | N/A |
| V2 | Explain neural networks to a 10-year-old using simple words and a fun example. Avoid technical terms. | Added simple words, fun example, and instruction to avoid jargon. | Made the response more child-friendly and easier to understand. |
| V3 | You are an expert teacher who explains technology to children in a simple and friendly way. Explain neural networks to a 10-year-old in less than 200 words. Use a simple example of how a child learns to recognize cats and dogs. Avoid technical terms like “algorithm,” “weights,” or “training data.” Use a friendly tone and end with one simple question to check understanding. | Added role assignment, word limit, specific example, banned terms, tone, and final question. | Produced a focused, age-appropriate, structured, and interactive explanation. |

## Scenario B: Professional Email
| Version | Prompt | What Changed | Why This Improved the Output |
|---|---|---|---|
| V1 | Write an email to decline a job offer expressing continued interest | N/A | N/A |
| V2 | Write a polite email in professional language declining a job offer while thanking the company for the opportunity. | Added polite tone and gratitude. | Made the email more respectful and professional. |
| V3 | You are a professional career coach helping a candidate write a respectful and polished email. The candidate has received a job offer but has decided to accept another opportunity that is better aligned with their current goals. Draft a concise, polite email declining the offer. The email should thank the company, show appreciation for the interview process, respectfully decline the offer, and express continued interest in the company for future opportunities. | Added role assignment, candidate background, reason for declining, structure, and continued interest. | Created a polished email that maintains a positive relationship with the company. |

## Scenario C: Creative Content
| Version | Prompt | What Changed | Why This Improved the Output |
|---|---|---|---|
| V1 | Create a tagline for an eco-friendly water bottle. | N/A | N/A |
| V2 | Create five short and catchy taglines for a new eco-friendly water bottle brand. | Asked for five options and specified short, catchy style. | Gave more variety and made the output better suited for selection. |
| V3 | You are a professional copywriter. Create five short, catchy, and memorable taglines for a premium eco-friendly water bottle brand targeted at young adults who care about sustainability and style. | Added role assignment, brand positioning, target audience, and desired tone. | Made the taglines more focused, stylish, memorable, and suitable for a premium eco-friendly brand. |


### 1.3 Role and Context Analysis

## Part 2: Temperature & Parameter Control
### 2.1 Temperature Experimentation
### 2.2 Analysis & Recommendations

## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting
### 3.2 Few-Shot Prompting

## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
### 4.2 Testing for Bias
### 4.3 Limitations & Responsible Use
