IRS-MR-2019-01-19-IS1PT-GRP-THOR-PSR
---

## SECTION 1 : PROJECT TITLE
SANA Chatbot: Smart Academic Network Assistant

---
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
In this project, the team developed a proof of concept (PoC) for a chatbot assistant to communicate with potential students of courses offered by the NUS Institute of Systems Science (NUS-ISS) via the Google Assistant platform.
Why does NUS-ISS need chatbots? User experience is of critical importance in today’s society. Hence, it is essential to create superior customer experience for potential students in finding the right course at a faster speed. Also, awareness of chatbots and interest in the capabilities of this technology is growing among consumers today. One study [Brandtzaeg and Følstad 2017] identified the main factors motivating people to interact with chatbots:
•	Productivity. Chatbots provide the assistance or access to information quickly and efficiently.
•	Entertainment. Chatbots amuse people by giving them funny tips, they also help killing time when users have nothing to do.
•	Social and relational factors. Chatbots fuel conversions and enhance social experiences. Chatting with bots also helps to avoid loneliness, gives a chance to talk without being judged and improves conversational skills.
•	Curiosity. The novelty of chatbots sparks curiosity. People want to explore their abilities and to try something new.

ISS offers a large range of courses under different programmes. For this PoC, the scope of the chatbot is limited to answering questions about courses offered under the Executive Education programme. This scope covers over 100 course, organized under the following disciplines:
1)	Artificial Intelligence	2)	Cybersecurity
3)	Data Science	4)	Digital Agility
5)	Digital Innovation & Design	6)	Digital Products & Platforms
7)	Digital Strategy and Leadership	8)	Software Systems
9)	Stackup – Startup Tech Talent Development	
 
Primarily, this chatbot is designed to answer queries on the following topics about individual courses:
1)	Course overview	2)	Upcoming classes
3)	Key takeaways	4)	Who should attend
5)	What will be covered	6)	Course fees
7)	Funding schemes	8)	Course instructors
9)	Certification	10)	Course preparation

This PoC will provide a good opportunity for NUS-ISS to explore the benefits of having a chatbot while identifying gaps to be addressed and future enhancements to potentially expand on the path towards a fully-developed chatbot in the future.


---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | Work Items (Who Did What) | Email (Optional) |
| :------------ |:---------------:| :-----| :-----|
| IAN TAN ENG KIONG | A0120534W | Dialogflow Documentation|  |
| RANA BHATTACHARJEE | A0195178N | Dialogflow Webhook Video Documentation|  |
| YEO WHYE CHUNG NELSON | A0195405A | Dialogflow Webhook Webscraping Google Assistant|  |

---
## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

[![Power Supplier Recommender](https://www.youtube.com/watch?v=lsLjX5LYQyo)]

---
## SECTION 5 : USER GUIDE

`<Github File Link>` : <https://github.com/dion797/IRS-MR-2019-01-19-IS1PT-GRP-THOR-PSR/blob/master/UserGuide/User%20Guide.pdf>

### [ 1 ] To run the system using iss-vm

> download pre-built virtual machine from http://bit.ly/iss-vm

> start iss-vm

> open terminal in iss-vm

> $ git clone https://github.com/dion797/IRS-MR-2019-01-19-IS1PT-GRP-THOR-PSR.git

> $ sudo apt-get install python-django

> $ cd IRS-MR-2019-01-19-IS1PT-GRP-THOR-PSR/SystemCode/psr

> $ python2 manage.py runserver

> **Go to URL using web browser** http://localhost:8000

### [ 2 ] To run the system in other/local machine:
### Install additional necessary libraries. This application works in python 2 only.

> $ sudo apt-get install python-clips clips build-essential python-dev python-pip python-django

> $ pip install pyclips 

---
## SECTION 6 : PROJECT REPORT / PAPER

Power_Supplier_Recommender.pdf
`<Github File Link>` : <https://github.com/dion797/IRS-MR-2019-01-19-IS1PT-GRP-THOR-PSR/blob/master/ProjectReport/Power_Supplier_Recommender.pdf>

---
## SECTION 7 : MISCELLANEOUS

Power Supplier Recommender.xlsx
`<Github File Link>` : <https://github.com/dion797/IRS-MR-2019-01-19-IS1PT-GRP-THOR-PSR/blob/master/Miscellaneous/Power%20Supplier%20Recommender.xlsx>

---
