# 📋 50 Prompt Task

## A. Basic Prompt Templates

**1. General Inquiry :**
Explain cardio in simple terms.

**2. Summarization :**
Summarize the following text in 3 bullet points:
How cardio helps in weight loss?

**3. Paraphrasing**
Rewrite this sentence in your own words:
Cardio is an effective way to support weight loss, and following a consistent daily cardio routine can lead to better results.

**4. Definition Request:**
What is the meaning of cardio exercise?

**5. Comparison:**
Compare EV vehicle and petrol vehicle based on resale value.

---

## B. Persona-Based Prompt Templates

**6. Role + Explanation**
You are a gym trainer. Explain how cardio helps in weight loss to people who are obese and want to reduce weight in a single paragraph.

**7. Style Mimicry**
Write like Jillian Michaels: Why everyone needs to focus on their health and physical activities on a daily basis.

**8. Professional Writing**
You are a fitness trainer. Write a newsletter document about the importance of physical activities in day-to-day life.

---

## C. Few-Shot Prompt Templates

**9. Classification Template**

| **Scenario**           | **Response Sentiment**     |
| ---------------------- | -------------------------- |
| When people are tired  | **Positive / Encouraging** |
| If anyone gets injured | **Supportive / Caring**    |

**10. Translation Template**
Translate the following sentences into \[target language]:
\[Why daily 30 minutes of workout help us active throughout the day] — \[Chinese]
\[How physical health boosts mental health in day-to-day life] — \[Korean]

Prompt Template:
\[New sentence] > Explain what is the importance of daily physical activity?.

**11. Question Answering Template**

Answer these questions:
Who wrote "Romeo and Juliet"? — William Shakespeare
What is the capital of France? — Paris
Who discovered gravity? > Isaac Newton

---

## D. Chain-of-Thought (CoT) Templates

**12. Step-by-Step Reasoning**
Think step by step and provide a better solution to opt for purchasing a new EV vehicle.

**13. Math Problem Solving**
Solve this math problem by showing your work:
\[If I started at 9 AM to travel in a car with 80 KM speed at what time I'll reach from Coimbatore to Chennai.]

**14. Logical Puzzle**
Solve the following logic puzzle. Show your reasoning process:
Three friends — **Amit, Brian, and Charlie** — each have a different favorite fruit: **Apple, Banana, and Cherry.**

* Amit does not like Apple.
* Brian does not like Banana.
* Charlie does not like Cherry.

**Question:** Which friend likes which fruit?

---

## E. Instruction Tuning / Format Control

**15. Output Formatting**
Summarize the article below in exactly \[10] bullet points.
Importance of Physical Activity in day-to-day life.

**16. Table Generation**
Create a table comparing Apple, Banana, and Guava based on key vitamins they contain.

**17. Email Writing**
Write a professional email to Internet Service Provider regarding frequent Internet disconnection. Use a professional tone.

---

## F. Contextual Prompts

**18. Tailored Explanation**
Explain Financial Independence to people aged 25 - 35 who know basic finance.

**19. Industry-Specific Context**
As a Cloud Architect, explain how cloud computing fastens the development & deployment of a SaaS product.

---

## G. Creative Writing Prompts

**20. Story Writing**
Write a short story about a 16-year-old boy who wants to become an IAS officer but he faces hearing loss.

**21. Poem Writing**
Write a poem in Vaali style about nature.

**22. Dialogue Writing**
Write a realistic dialogue between Naveen and Suresh discussing the future of coding in AI era.

---

## H. Code & Technical Prompts

**23. Code Generation**
Write a Python function that triggers a database batch job at 1 AM every day.

**24. Debugging Help**
Here is some code. Find and fix any errors:
Faulty Python Code

```python
def add_numbers(a, b)
    result = a + b
    print("The result is: " + result)
    return result

x = 5
y = "10"
add_numbers(x, y)
```

**25. API Documentation**
Explain how to use the GitHub API to interact programmatically with GitHub repositories, issues, pull requests, users, etc., with an example request and response.

---

## I. Marketing & Business Prompts

**26. Ad Copywriting**
Write a compelling ad for baby soap targeting pregnant & young mothers.

**27. Product Description**
Write a persuasive product description for baby soap.

**28. Social Media Post**
Create a social media post promoting baby soap in a friendly tone.

---

## J. Customer Support & Service Prompts

**29. Response to Complaint**
Respond professionally to this customer complaint:
A customer complaint about a baby soap causing an infection.

**30. FAQ Generator**
Generate 5 common FAQs and answers for a baby soap.

---

## K. Education & Tutoring Prompts

**31. Lesson Plan Creation**
Create a lesson plan for teaching Mathematics to 5th-grade students.

**32. Quiz Generation**
Generate a 5-question quiz about World Wonders.

**33. Homework Help**
Explain how to solve this: calculate the time to travel between two places when you know the distance is 100KM and the speed is 45 KMPH.

---

## L. ReAct / Tree-of-Thoughts (ToT)

**34. ReAct Framework**
**Thought:** I need to automate report generation at 9 AM and email it.
**Action:** Schedule a cron job to run the report script and trigger an email function.
**Observation:** Cron job runs successfully, email sent with the report attached.
**Answer:** Reports are now automatically generated and emailed daily at 9 AM.

**35. Tree of Thoughts (ToT)**
Generate 3 possible solutions to fix an EV car battery issue. Evaluate each and choose the best one.

**36. Self-Consistency Prompting**
Solve the following question in 3 different ways and pick the most consistent answer:
How to fix car battery issue?

---

## M. Prompt Optimization & Evaluation

**37. Prompt Refinement**
Improve this prompt: "\[How to learn swimming?]"

**38. Prompt Grading Rubric**
Rate this output based on the following criteria (1-5):

```
#Role:
You are a cloud architect  
#Task
You need to design a scalable solution to host a webserver  
#Context
We need to deploy a node application in two EC2 instances and want to have a load balancer before the EC2 to serve traffic and load balance.  
#fewshots
1. App server 1, app server 2, 1 ALB, security group, VPC, nginx server  
#Report/tone
Give me an architecture diagram and implementation guide in a PDF file  
```

* Relevance: 5
* Accuracy: 5
* Clarity: 4
* Fluency: 4
* Creativity: 3

Final Score: **4.2**

**39. Prompt Iteration Challenge**
Take this weak prompt: "What is DNS and how it works"
Rewrite 3 times to improve clarity and effectiveness:

1. Explain what DNS (Domain Name System) is, and describe how it works to translate domain names into IP addresses.
2. Provide a beginner-friendly explanation of DNS, including why it is important for the internet and how it works step-by-step when someone visits a website.
3. Describe the Domain Name System (DNS) in detail, including its components (root servers, TLD servers, authoritative servers) and the full process of DNS resolution from a user's request to receiving the IP address.

---

## N. Real-World Application Prompts

**40. Job Posting Creation**
Write a job posting for UI/UX Designer at MyCompany Pvt Ltd. Include responsibilities, requirements, and benefits.

**41. Resume Summary Builder**
Create a professional summary for a resume based on:
10+ years of experience in cloud, datacenter & automation with 50 migration projects completed.

**42. Business Proposal**
Write a proposal for Executive Report Automation to my client. Include objectives, methodology, and benefits.

```
Hi Steve, I would like to propose an Executive Report Automation which sends an email every day at 9 AM about the previous day's data processing job high-level summary, including the success, failure, in-progress data with the help of Lambda serverless functions which helps in summarization and also cost-effective solution and autonomous solutions.
```

---

## O. Miscellaneous Useful Templates

**43. Opinion Writing**
Write an opinion piece on the resale value of EV cars. Use persuasive arguments and examples.

**44. Debate Preparation**
Prepare arguments for both sides of the debate: "\[Fuel Cars vs EV Cars]"

**45. Travel Planning**
Plan a 5-day trip to Kashmir for a vacation with sightseeing, road travel, surfing, snow game activities with ₹75,000 budget for 2 people and consider planning for newly married couples.

**46. Book/Movie Review**
Write a review of *Interstellar* movie. Include plot summary, strengths, weaknesses, and recommendation.

**47. Personal Development**
Give actionable advice on how to achieve financial freedom at 35, including daily habits and mindset shifts.

---

## P. Prompt Chaining Examples

**48. Multi-step Research Task**
Step 1:
Find out the top 5 causes of climate change. Based on those causes, suggest 5 practical solutions individuals can adopt.
Step 2:

* Reduce Energy Consumption
* Use Green Transportation
* Adopt a Plant-Based or Reduced-Meat Diet
* Support Reforestation & Sustainable Living
* Practice Reduce, Reuse, Recycle, and Compost

**49. Idea to Execution**
Step 1:
Generate 5 business ideas for eco-friendly products. Pick one idea and create a marketing strategy for it.
Step 2: Marketing Strategy

* Target Audience
* Unique Selling Proposition (USP)
* Branding and Messaging
* Sales Channels (Online, Retail)
* Promotional Activities (Social Media, Influencer Marketing, Eco Fairs)
* Partnerships and Collaborations
* Pricing Strategy
* Customer Education and Engagement

---

## Q. Universal Prompt Builder

**50. Universal Prompt Template:**
\[Role] + \[Task] + \[Context] + \[Example] + \[Format]

You are a cloud architect. Create a project roadmap for migration to cloud from datacenter. The data center has 25 servers, 3 databases and 1 local storage. Prepare a roadmap like week 1 pre-assessment, week 2 requirement gathering, etc., and give a PDF document.

---

If you want this in an actual **.md file**, I can generate it for download. Just let me know.
