[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: [Pedro Silva] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Pedro Silva](personas/persona2.jpg)  |
| **Name**         | [Pedro Silva]                                |
| **Age**          | [34]                                 |
| **Occupation**   | [Empresário]                           |
| **Location**     | [Minho, Portugal]                               |
| **Goals**        | [Fazer uma lista reutilizável rapidamente]           |
| **Pain Points**  | [Falta de tempo]              |
| **Motivation**   | [Fazer mais com menos tempo e esforço]                |
| **Full Profile** | [📄 Read More](personas/persona2_template.md) |

---
## Persona: [António Mendes] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![António Mendes](personas/persona3.jpg)            |
| **Name**         | [António Mendes]                                |
| **Age**          | [40]                                 |
| **Occupation**   | [Carpinteiro]                           |
| **Location**     | [Aveiro, Portugal]                               |
| **Goals**        | [Fazer lista, comparar preço de lista e produtos, ver descontos]           |
| **Pain Points**  | [Muitas opções de supermercado, mas não conseguir organizar qual o mais barato para ele]              |
| **Motivation**   | [Poupar dinheiro]                |
| **Full Profile** | [📄 Read More](personas/persona3_template.md) |

---





# Scenarios


## Scenario 1: António volta para casa depois de um dia de trabalho
António está a ir para casa depois de um dia de trabalho e decide que quer levar algo especial para a sua família jantar. Uma peça de carne que António vai usar para cozinhar um delicioso jantar para a sua família.
Como ele não é rico quer saber rapidamente onde é que esse **produto está disponível, onde tem descontos e onde é mais barato**.
António então abre a nossa aplicação, **pesquisa o produto** e rapidamente consegue ver **os supermercados em que está disponível** e **comparar os diferentes preços** tendo em conta os possíveis **descontos**.

## Scenario 2: António sai com a sua família para fazer as compras de casa
É domingo e depois de uma semana de trabalho, António e a sua mulher decidem que têm que ir ao supermercado fazer as compras do que faz falta em sua casa. Cansados que ter que escrever numa lista de papel, para depois irem ao supermercado e descobrir que os produtos que querem não estão disponíveis ou estão mais caros que em outros sítios ou que há outro supermercado com descontos naquilo que eles querem, António e a sua mulher decidem então **procurar os produtos** na nossa aplicação, **criando uma lista de compras compartilhada** e **adicionando os produtos a essa lista** em **diferentes quantidades** . No fim, eles querem **comparar os preços** da lista em diferentes supermercados para saber onde devem ir **num raio pre-definido por eles**.
  
## Scenario 3: Pedro makes a list very quick

[Pedro doesn't like to lose time when's unnecessary and money no longer a problem to him so he would like to create a general list, specifying only a few products. After that he would also like to look for the closest supermarket, using price as a tiebreaker]

[He quickly opens the app and starts writing down **general products** he wants such as milk, cookies, cereals... He also **specifies some other products** because he likes them better than the others]

[As he's running out of ideas he goes to the **recomended section** and notices that he didn't put bananas into his list so he quickly adds them]

[At last he **saves the list** and looks for the **reccomended supermarket**, **priorityzing the closest**]

## Scenario 4: Pedro reuses a list

[Since he grew up, Pedro's always been a guy with no time to waste. Since he has a company to run, he's always busy and can't manage to waste time doing unimportant things. Today, as he was having lunch, he remembered he needed to go to the market and so he opened the app.]

[As he had to do it quick he went to the lists he **saved** before and **reused** one, but he noticed that the yogurt's price had gone increased so he **edited** the list, swapping the yogurt he had chosen for other from other brand, one that was cheaper.]

[Before saving the list, he remembered that this time he also needed toothpaste and 2 boxes of cereals, so he quickly **searched and added** them to the list.]

[Once he remembered that he actually needs to use this list once a month because of the 2 things he added, he **saves the list as a copy**, keeping the one he first reused.]


## Scenario 5: Pedro goes shopping

[Pedro just finished another busy day of work and is needs to go to a market using a list that he made previously]

[As soon as he enters the supermarket he opens the app an uses the list. As he grabs the things he needs he **marks its checkboxes** to know what he bougth and what he didn't.]

[He notices that by accident he added meat when doing the list so he edits the list to **remove it** and keeps buying]

[After paying, he selects the **option to finish the shopping list (unchecking all the checkboxes)** and **saves the list, overwriting** the one with the meat mistake]
---


# Requirements
List of requirements the system should do
## C.1. Functional requirements
- O sistema deve permitir que se pesquise por um produto
    - por nome genérico(ex: leite, batatas,...)
    - por nome específico (ex: leite mimosa 1L)

- O sistema deve permitir comparar preços do produto
- O sistema deve ter em conta descontos nos produtos
- O sistema deve ter em conta a disponibilidade/stock de um produto
- O sistema deve permitir ao usuário criar uma lista
- O sistema deve permitir adicionar produtos a uma lista
    - O sistema deve permitir adicionar produtos em diferentes quantidades
- O sistema deve permitir compara preços da lista em diferentes supermercados
- O sistema deve permitir mudar a localização e/ou raio da procura 
- O sistema deve permitir salvar uma lista
- O sistema deve permitir reutilizar e/ou editar uma lista salva
- O sistema deve permitir que se copie uma lista e se salve essa cópia como uma nova lista
- O sistema deve ter um sistema de checkbox na lista
- O sistema deve permitir a remoção de um produto da lista
- O sistema deve permitir que se alterem as quantidades de um produto na lista
- O sistema deve permitir que vários dispositivos alteram a mesma lista

## C.2. Non-functional requirements
- O sistema deve recomendar produtos para a lista
- O sistema deve recomendar produtos caso um esteja indisponível
- O sistema deve avisar o utilizador de possíveis erros
- O sistema deve ter uma interface intuitiva e fácil de usar
- O sistema deve estar disponível 99% dos casos
- Os dados da mesma conta devem ser iguais em todos os dispositivos
- O utilizador deve fazer login na sua conta (opcional)
- O sistema deve cumprir com as leis e regulações do país/local onde será utilizado
- O sistema deve ser capaz de aguentar grande volume de dados de utilizadores
---
[Back to main Logbook Page](hci_logbook.md)