# Complete Google Agentic AI Course in Just 45 Minutes + Free Certificate

* - BY SOUMYA SINGH DIDI
= We are not learning theory only we are building one ai agent in this cource
- this cource is based upon interships and current job market 

= what you will learn in this cource?
* by the end of this course you will understand:

1) what is an ai agent 
2) why llms and traditional ai are not enough
3) relationship betwwen an agent and its environment
4)how ai agent think plan and make desicions
5)types of ai agents
- simple reflex agent
- model based reflex agent
- goal based agent 
- utility-based-agent
- learning agent

so lets understand ai agents 
- real life industry examples
- how ai agents are different from ai workflows
- how to create an ai agent from scratch
- career and apportunity landscape in agentic ai
- this cource assumes zero prior knowledge

1) UNDERSTANDING THE EVALUTION 
* why ai agents were needed
- before understanding the ai agents we must understand what
  was missing in earlier ai systems

  LLM : llm is stands for large language model like chat-gpt and gemini

 EXAMPLE : we assign a task to gpt like write a pragraph or create a linkedin post  description...

 LLM :
 - LLM is a chat-gpt and gemini
 - they can :
            - understand natural langauge
            - answer questions
            - write code
            - explain concepts

* but here is the most important truth :
- an llm is a very intelligent text generator , not a worker
- suppose i have a meeting
- i tell to llm to write a meeting mail llm can write the mail

llm can only do this things:
- 1) write a mail for meeting
- 2) add schedule meeting time as given

llm cannot do this things
- 1) what is the meeting time
- 2) what will the weather at the meeting time

why it dont able to do this things because 
- it dont have access of perticular thing

1) if your asking to llm tell me the meeting time and watch my callender and tell me but its dont give u output because llm dont have access to your personal callener
2) tell me the weather of the day but its dont have the access of weather api 
- so thats why llm want tell things like this so the bigggest challenge is the access

# LIMITATIONS OF LLM (WHY LLMS ALONE ARE NOT ENOUGH)
* LLM CANNOT TAKE ACTIONS
- llm can tell you how to do something but llm cannot do it

EXAMPLE:-
- CHAT-GPT CAN EXPLAIN HOW TO BOOK A FLIGHT
- IT CANNOT OPEN BROWSER COMPARE PRICES AND BOOK FLIGHT
 FOR U

 LLM = BRAIN WITHOUT HANDS

 # NO REAL WORLD ACCESS
 FOR EXAMPLE:
   YOU ASK - when is ny meeting with paul robinson?the llm cannot answer this

   WHY? BECAUSE - 
   - it does not have access to your calendar
   - it does not know paul
   - it cannot see your gmail or outlook

   * it can only generate text based on training data, it has no access to your personal information
   * basicaaly automation is not possible by llms
   * so we thing upon this and peoples create AI-WORKFLOWS

   - IN AI WORKFLOWS GIVES AN ACCESS WHILE YOU NEED SOMETHING

   FOR EX: 
     - we want to llm automate our calendar meettings schedulling gives us a alert and telling us when meeting schedule then in that time we gives a llm to our calleder app access

     - also if i want weather then i gives and acces to weather api
     - but there is also we need to use our owm brain because human being brain are being used human think about it and
     - how llm desides to gives an acces is desided by human but after this human thinks like we want ot do something where we dont need to do this by own 
     - so basically we dot want to deside which this is need to give access or which not it also can be desided by llm

     # AI WORKFLOWS
     1) GIVING AI ACCESS - AI WORKFLOWS
     2) TO SOLVE THIS DEVELOPER STARTED GIVING LLM TOOLS ACCESS
     3) FOR EX: -  calendar api
                - weather api
                - email access
                - database access
                - now the system can : - read the emails at this stage we moved from pure llm to ai workflow

   AN AI WORKFLOW IS A STRUCTURED PIPELINE WHERE:
   - LLM is connnected to tools
   - humans desided which tools are available
   - steaps are predefined

   EXAMPLE-WORKFLOW: 
   USER QUESTION--->LLM--->CALL CALLENDER API---> RETURN OUTPUT

   NOW WHEN U ASK: 
   "when is my meeting with paul robinson?"
   IF:
   * calendar access is given
   * api is configured properlly
   
  - then the system can answer correctlly, this is progress

  # LIMITATIONS OF AI WORKFLOWS 
  # IN WORKFLOWS
  
- humans decide what tools to connect 
- human deside the order of steps 
- human define the order of steps

- now humans feels like peoples are still decision maker by own we have to do kind of all things so basically we need to give access to llm for each so now also human involvement is so high
- so human thinks we want to automate everything so thats why human created a ai agents the solution 
- so now ai agent is at the top now we dont know about whats need to improve next but this the latest ai invention right now using this peoples done their work so easilly

# AI AGENT - THE SOLUTION
AI-agents solve:
- llm limitations 
- workflow initiation

SIMPLE DEFINITIONS:
- AN AI AGENT IS A SYSTEM THAT CAN UNDERSTAND A GOAL , PLAN,OBSERVE RESULTS AND IMPROVE ITS BEHAVIOUR

- AN AI AGENT IS AI THAT CAN THINK , ACT,AND ACHIEVE A GOAL ON ITS OWN 

# EXAMPLE
- travel agent, railways agent LIC Agent , Real Estate Agent

THE ASSISTANCE:
1) understands the goal
2) checks availability
3) confirms with u

* so now we are creaing a ai agent
 
PRACTICAL CLASS : MAKING AN AI AGENT


go to the ai agent platform
- agent ai/the#1professionalnetworkforaiagents

first step is signup
- login with google
- then click on blank workflow
- then next step is to giving a agent name
* so here we are creating one linkedin coach agent can scan our linkedin profile and gives us a information how to make it more professional 

AGENT NAME : LINKEDIN PROFFESSIONAL COACH
AGENT DESCRIPTION : SCAN THE LINKEDIN PROFILE AND GIVE BEST SUGGESSTION TO IMPROVE THE PROFILE

NEXT CLICK ON OPEN ACTION LIBRARY
- FIRSTLLY AGENT ASK FOR USERS A LINKEDIN PROFILE

STEP 1 : AGENT ASK FOR USERS A LINKEDIN PROFILE
STEP 2 : WE ARE COLLECTING A LINKEDIN PROFILE USERS DATA
STEP 3 : RUN THE AI MODEL AND SCAN THE LINKEDIN PROFILE THEN IT     TELLS WHAT NEED TO IMPROVE
STEP 4 : IN FOURTH STEP WE ARE GENERATING A OUTPUT FOR THE USER

# FIRSTLLY SEARCH IN SEARCH BOX GET USER INPUT

GET USER INPUT
- USER PROMPT - GIVE YOUR LINKEDING PROFILE LINK
- ENTER SOME OPTION : ----
- DEFAULT VALUE
- https://www.linkedin--
() required

output variable namr

then social media and linkedin profile preference

get linkedin profile details
- profile handle
{{user_input}}

output variable name
proffessional_info

then click search next
generate content
gpi-d-mini
- intructions: scan the linkedin profile details here {{proffessional_info}} and give neat point-wise intructionson what all should be improve to make it the best profile and attract grat apportunities in respective domain

output variable
profile_optimization_results

then output
- show user output

- heading
 output

 output formatted

 Here is Results :
 {{profile_optimization_result}}

 then run it run draft

 * done with creating a ai agents

 STEPS
 1) GET USER INPUT
 2) GET LINKEDIN PROFILE DETAILS
 3) GENERATE CONTENT
 4) SHOW USER OUTPUT

 SO WE CREATED ONE AI AGENT 

 # AI AGENT AND ITS ENVIRONMENT

 - AN environment is everything outside the agent it can interact with 

 # examples 
 - browser, apis,files,database, emails, callendar,websites,sensors(in robotics)

 - agent environment interaction loop every ai agent follows this loop

 1. preceive - observe the environment
 2. decide - take and plan
 3. act - take action using tools
 4. observe - check result
 5. learn - improve next action

 this loop continues until the goal is achieved

 EXAMPLE GOAL : "find the best phone under rs 20,000"

  * agent checks websites
  * compare specs
  * check reviews

  # Types of Ai Agent

  * simple reflec agent
  - it reacts and dont have any memory

  * model reflex agent
  - it have a memory for passed information
  - goal is desided and complete it any how 

  * goal based agent
  * learning agent

  uses of ai agent
  - email automation
  - data entry
  - call
  - price tracking
  - revieve analytics 
  - healthcare appointment schedulling
  - core summary
  - follow-up
  - flight booking


  # roles 
  - ai agent developer 
  - automation developer
  - ai consultant
  - product builder
  - startup founder