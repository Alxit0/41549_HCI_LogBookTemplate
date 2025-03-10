[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| [Kabaz.pt]        |[Online platform comparing supermaket prices]| [[Competitor Analysis AmazonShoes]] |
| ...               |                                             |                                     |




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution
Kabaz.pt

### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]
We made each an heuristic evaluation of the kabaz.pt system, using the default severity scale. Then we talked about each issue found on the evaluation and came to a consensus of wich ones were usefull.

#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**           | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             					|
| --------------------| ------------ | -------- | -------- | ---------------------------------------------------------------|
| Search Indicator    | 2            | 3        |          | Indicate to user when a search is being made					|
| Adding to list      | 3            |          |          | Haver uma confirmação imediata de adição de um produto 		|
| Product descriptions| 3            |          |          | Usar linguagem mais simples do dia a dia						|
| Undo remove         | 3            |          | 1        | Adiconar uma feature para desfazer remoção						|
| Exit search		      | 3            |          | 2        | Adicionar um botão para voltar para trás						|
| Missing Itens		    | 3            |          | 3        | Avisar o utilizador que o produto não está disponivel			|
| Recent Searchs	    | 2            |          |          | Mostrar pesquisas recentes ao pesquisar						|
| Recomendations	    | 2            |          |          | Implementar recomendações de produtos baseados no histórico	|
| Tutorial/Tooltips	  | 3            |          |          | Add an page for begginers to learn how to use the system   	|
| Mobile Format	      |              | 4        | 1        | Fazer o sistema mais adequado para dispositivos mais pequenos	|
| Remove item	        |              | 3        | 2        | Add button on list to remove item				        		|
| Supermarket item	  |              | 2        |          | Make supermarket where item is available visible right away    |
| Discount Search	    |              | 3        |          | Make it available to search on the specific discount			|
| Frequent Lists	    |              | 2        |          | Have the most used lists stored for speed						|
| FAQ	                |              | 3        |          | Make a FAQ available for users to solve their problems quickly |
| Scroll animation	  |              |          |          | Make it available to search on the specific discount			|
| Discount Search	    |              |          | 1        | Add an spring animation when pages comes to end while scrolling|
| Troca e poupa		    |              |          | 2        | Make button disappear when going to menu						|
| GPS	  			        |              |          | 2        | Explain to user what it does and how it works for them			|



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

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

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

Fizemos um guião de entrevista para perceber quais os costumes dos nossos utilizadores, os seus problemas, as suas frustações e as funcionalidades que eles mais precisam num sistema.
Os utilizadores considerados são todos, já que o sistema é direcionado para toda a gente de qualquer idade e profissão.
As questões usadas foram [Questões](interviews/questions.md)
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
