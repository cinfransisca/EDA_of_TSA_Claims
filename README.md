# EDA of TSA Claims
by [Cindy Fransisca](www.linkedin.com/in/cindy-fransisca-18ba81213)

## Introduction

Did you know that claims can be filed against TSA? Sometimes US Terminal Security Agency (TSA) makes mistakes. People can get hurt and property can be damaged, lost, or stolen. Claims are generally filed against TSA for personal injuries and lost or damaged property during screenings and they keep records of every claim. Our objectives are (1)exploring the incidents that are filed against TSA and (2)exploring which factors resulting in higher claim amount paid. So, hopefully we might be able to help TSA improve their services which resulting in lower expenses for claims.

## Problem Statement
We will try analyzing the data to answer these questions:
- How are the characteristic of incidents that are filed against TSA?
- How are the characteristic of claims that have higher close amount paid?

## About Dataset
We get the [TSA Claims Database](https://www.kaggle.com/datasets/terminal-security-agency/tsa-claims-database) dataset from Kaggle. The dataset includes claims filed between 2002 through 2015.
The dataset contains 24 features, each are:
1.  Claim Number
2.  Date Received
3.  Incident Date
4.  Airport Code
5.  Airport Name
6.  Airline Name
7.  Claim Type
8.  Claim Site
9.  Item
10. Claim Amount
11. Status
12. Close Amount
13. Disposition


## Exploratory Data Analysis (EDA)
![Number of Incidents by Claim Site](https://github.com/cinfransisca/EDA_of_TSA_Claims/blob/main/Images/fig4.png)

![Number of Incidents by Claim Type](https://github.com/cinfransisca/EDA_of_TSA_Claims/blob/main/Images/fig5.png)

![Average Number of Incidents by Month](https://github.com/cinfransisca/EDA_of_TSA_Claims/blob/main/Images/fig8.png)

![Number of Claims by Disposition](https://github.com/cinfransisca/EDA_of_TSA_Claims/blob/main/Images/fig9.png)

![Close Amount Distribution by Claim Type](https://github.com/cinfransisca/EDA_of_TSA_Claims/blob/main/Images/fig12.png)

![Close Amount Distribution by Claim Site](https://github.com/cinfransisca/EDA_of_TSA_Claims/blob/main/Images/fig15.png)

![Average Amount Paid by Item](https://github.com/cinfransisca/EDA_of_TSA_Claims/blob/main/Images/fig18.png)



## Conclusion
Characteristics of incidents that are filed against TSA are:
- Base on the **airport**, most incidents happen at **Los Angeles International Airport** (**8.3%**) .<br>
  Base on the **state**, most incidents happen in **California** (**15.1%**).<br>
  Base on the **region**, most incidents happen in **South** (**34.1%**).
  
- Most incidents happen at **Checked Baggage** (**79.1%**), followed by **Checkpoint** (**19.8%**) claim site.

- Most incidents categorize as **Passenger Property Loss** (**61.5%**), followed by **Property Damage** (**37.1%**).

- Most people claims for items in '**Other**'(**29.1%**) category, followed by **Electronic**(**20.2%**) .

- **Highest** number of incidents happen in **July** and **lowest** in **November**.

- Claims are mostly **denied** by TSA (**47.7%**)<br>
  The **highest** number of approved or settled claims happen in **2004** and the **lowest** in **2009**.
  
-  The **highest** total amount paid for approved or settled claims is **\$2.95M** in **2004** and the lowest is **\$0.36M** in **2010**.


Characteristics of claims that have higher amount paid are:
- Claims with higher amount paid categorize as **Personal Injury** with average amount paid of **$2.2K**.<br>
  Personal Injury incidents mostly happen in **California** state.<br>
  **Highest** number of Personal Injury Incidents happen on **August** with **10.3** average number of incidents and **lowest** in **April** with **7.2** average number of incidents

- Claims with higher amount paid happen at **Motor Vehicle** claim site with average amount paid of **$1.6K**.<br>
  Motor Vehicle incidents mostly happen at **Non TSA Airport (motor vehicle)**.<br>
  **Highest** number of  Motor Vehicle incidents happen on **August** with **5.9** average number of incidents and **lowest** in **February** and **October** with **2.1** average number of incidents

-  Claims item with highest amount paid is **Jewelry** with average amount paid of **\$383**, followed by **Elctronic** with average amount paid of **\$319**.

## Recommendation
There are two options how TSA can improve their services to lower expenses for claims:
1. by reducing the number of claims in general<br>
Since number of claims in-line with the total amount paid, if we reduce the number of claims, we might also lower expenses for claims
    - Focus more on improving services for checked baggage. Give more training about how to handle baggage.
    - Increase security for checked baggage to prevent property loss.
    - Suggest passenger to bring their electronic in carry-on bag rather than checked baggage.
    - Increase the number of security in July
    - TSA can either focus on Los Angeles International Airport, California state, or South region.  
  
  
  
2. by reducing the number of claims with higher amount paid
    - Pay more attention in handling passenger and not to cause physical injury, especially in August. Give more training how to handle troublesome passengers, escpecially in California state.
    - Increase the maintenance of motor vehicle, escpecially in August. Investigate more what's happening outside the airports that can cause any motor vehicle incidents.
    - Suggesting passengers not to keep their valuable items in checeked baggage and increasing the security to prevent property loss.
