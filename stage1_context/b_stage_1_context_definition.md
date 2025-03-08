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
In order to make a cognitive walktrough, we used the site for a while so we could understand all it's features.
After that we tried to follow Nielson Norman Group's model to create simulations of the most important features.

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]

The selected task were either the most important mechanics of the site or the things users would
do the most

The selected task were either the most important mechanics of the site or the things users would
do the most

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Compare a product's**  | Search for the product                 |
|**price in each supermarket**| Select the desired one from the list   |
|                             | Slide down to the supermarket's area (only on phone)|
|                             | Analyze prices                         |

| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **2. Compare a list's**      | Search and add all desired products to the list|
| **price in each supermarket** | Click my kabaz                          |
|                               | Compare price by supermarket            |
|                               | (Optional) Go to Comparison table in order to see unavailable products |

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
|**3. Remove product from**   | Go to my kabaz                         |
|**the list**                 | Select "all the products" bar          |
|                             | Select a product or products' checkbox |
|                             | Click remove                           |

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **4. Change localization**  | Select alter on the side or top bar    |
|**radius**                   | Change the radius by sliding the blue bar|
|                             | Click start saving                     |

#### Results

Task: [Compare a product's price in each supermarket]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Search for the product | [Yes]                                         |      | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |
| 2      | Select the desired one from the list | [Yes]                     |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |
| 3      | Slide down to the supermarket's area (only on phone) | [No]                      |       | [Yes]                                                                                 |       | 
[Yes]                       | [Suggestions]               |     |
| 4      | Analyze prices          | [Yes]                                     |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |


Task: [Compare a list's price in each supermarket]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Search and add all desired products to the list | [Yes]            |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |
| 2      | Click my kabaz          | [Yes]                                     |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |
| 3      | Compare price by supermarket | [Yes]                           |       | [Yes]                                                                                 |       | [Yes]                       | [Make indisponible warnings more visible ]               |     |
| 4      | (Optional) Go to Comparison table in order to see unavailable products | [No] |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |

Task: [Remove product from the list]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Go to my kabaz          | [Yes]                                     |       | [No]                                                                                 |       | [Yes]                       | [In my kabaz put All products as first tab]               |     |
| 2      | Select "all the products" bar | [No]                                     |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |
| 3      | Select a product or products' checkbox | [No]                    |       | [Yes]                                                                                 |       | [Yes]                       | [Having a remove button on each product]               |     |
| 4      | Click remove            | [Yes]                                     |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |

Task: [Change localization radius]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Select alter on the side or top bar | [No]                          |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |
| 2      | Change the radius by sliding the blue bar | [Yes]                      |       | [Yes]                                                                                 |       | [Yes]                       | [Suggestions]               |     |
| 3      | Click start saving      | [No]                                     |       | [Yes]                                                                                 |       | [Yes]                       | [Giving the save button a better tag]               |     |



---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...

## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]

## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
