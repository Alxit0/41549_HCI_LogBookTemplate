[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| [Amazon Shoes]    | [Online platform selling shoe laces]        | [[Competitor Analysis AmazonShoes]] |
| [Fnac Atacadores] | [Smartphone app to buy and sell shoe laces] |                                     |
| ...               |                                             |                                     |




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]


#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Something wrong | 3            | 1        | 0        | Something could be done to the button to... |
| Another thing   | 4            | 3        | 4        | Other thing to recommend                    |
| ...             |              |          |          |                                             |



---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Buyng a grammar book** | Search for available grammar books     |
|                             | Identify a specific book from the list |
|                             | Add the selected book to the cart      |
|                             | Proceeed to checkout                   |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Booking a train ticket** | Select departure and destination cities |
|                               | Choose travel date and time             |
|                               | Pick a seat (if applicable)             |
|                               | Confirm booking and make payment        |


#### Results

Task: [This is the task]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Step 1 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | [Step 2 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | [Step 3 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| ...    | [Further steps]        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |



---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...

## B.2a. Method

- **Approach:** interviews

- **User Types:**  
  - (1) Single male  
  - (2) Homemaker  
  - (3) Adriana (University student)  
  - (4) Gonçalo (University student)  
  - (5) Tech-savvy user (New interview)  

- **Goals of Interviews:**  
  - Identify shopping habits and frustrations  
  - Understand price comparison behaviors  
  - Explore potential solutions and features for an app  

- **Key Questions:**  
  - Do you shop with a list or spontaneously?  
  - How do you choose where to shop?  
  - Do you compare prices? If so, how?  
  - Have you used any price-comparison tools?  
  - What is the most frustrating part of shopping?  
  - What features would you like in a price-comparison app?  

---

## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Participant / Role | Key Insights | Link to Notes |  
|----------------------|------------------------------------------------|---------------|  
| Single Male | Shops spontaneously, forgets items, prefers small stores | [📄 Notes](./interviews/iterview-agregate-alex.md) |  
| House-wife | Uses 'Bring' app, shops at 3 stores for savings | [📄 Notes](./interviews/iterview-agregate-alex.md) |  
| Adriana (Student) | Goes to multiple stores for specific items, dislikes checkout lines | [📄 Notes](./interviews/iterview-agregate-alex.md) |  
| Gonçalo (Student) | Focuses on best prices, limited selection influences choices  | [📄 Notes](./interviews/iterview-agregate-alex.md) |  
| Engineering Student | Compares prices online for tech, not groceries, wants per-product price comparison | [📄 Notes](./interviews/questionsAnswer1.md) |  

---

### Common Themes & Patterns 

- **Recurring Problems:** 
  - Long checkout wait times  
  - Forgetting to buy needed items  
  - Lack of organization in stores  
  - Hard to compare prices manually  
  - Limited product availability at preferred stores  

- **Frequently Used Tools:** 
  - 'Bring' app (for shopping lists)  
  - Lidl app (for promotions)  
  - Some manually check store websites  

- **Desired Features / Solutions:** 
  - A **real-time price comparison app** (must be highly accurate)  
  - Ability to **compare prices per product and for full purchases**  
  - **Discount tracking** within the app  
  - **Integration with smaller supermarkets**  
  - Option to filter by user habits (shopping times, preferred stores)  
  - Additional product info (e.g., reviews, features for tech products)  

---
[Back to main Logbook Page](../hci_logbook.md)

---
