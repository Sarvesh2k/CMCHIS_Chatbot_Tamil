# CMCHIS Chatbot (Tamil)

This is a chatbot that answers questions regarding the Tamil Nadu's Chief Minister's Comprehensive Health Insurance Scheme in Tamil. Do check this repository out after you look into [this one](https://github.com/Sarvesh2k/CMCHIS_Chatbot_English) where I implemented a similar bot in English using NLTK. Here, I use the Artificial Intelligence Markup Language (AIML).

## Introduction

Many people aren't aware of the schemes that have been launched by the Governemnt due to lack of information and infamiliarity with the English Language. As a result, people don't know how to access and apply to these schemes. How about we bring the scheme to the people, at the comfort of their homes, in their native tongue? Thus comes the CMCHIS Chatbot. People can ask their queries to the chatbot and can be informed of the details and requirements to apply for the scheme. They can figure out the important keywords, and use the facilities effectively, reducing the burden on Government workers.

A retrieval based chatbot using AIML and Python were used to code the chatbot. A generative based chatbot wouldn’t be required in this scenario as the questions are domain specific and the users will only be asking questions mostly related to the scheme. The chatbot will be trained using the AIML Interpreter that uses a pattern matching algorithm  to classify which category the user’s message belongs to and then will give a random response from the list of responses.

## Software Requirements

- Python (3.6 or higher)
- AIML 
- Flask
- Little experience in web development (as I have coded the bot to give responses in a webpage)

## How to Use the Code

In order to facilitate an in-depth understanding of how the code works and how to execute it, I have created a `Documentation.pdf` file that attempts to explain my exploration in this domain. Comments have also been provided in the codebase.

## Issues Faced during Development

1.	Named Entity Recognition (NER).
      1. Similar to the English Chatbot, AIML doesn't have an easy implementation for NER.
      2. The only possible workaround is creating a well-defined dataset that can address all scenarios. This will require a lot of trial-and-error.

2.	Training Data.
      1. Since AIML works on the pattern matching algorithm, we need a huge dataset that addresses all the ways in which the flow of dialogue can happen.
      2. Lots of testing in a practical environment is essential, so that we know which weak points to address.

## References
- [AIML Documentation](http://www.aiml.foundation/doc.html) - Has almost everything you need.
- [More AIML Documentation](https://github.com/Calysto/aiml)
- [Rosie Bot](https://github.com/pandorabots/rosie) - Quite a vast dataset for training your bot. Will surely be handy.
- [NumPy Documentation](https://numpy.org/doc/)

I also looked into some Research Papers to know more about regional language support.
- Kalaiyarasi, T. and Ranjani Parthasarathi. *“POONGKUZHALI-An Intelligent Tamil Chatterbot.”* (2003).
- Sandhini, S., R. Binu, Rajeev R, and Marri Reshma. *“A Proposal of Chatbot for Malayalam.”* International Journal of Computer Sciences and Engineering (2018).
- M.A.S.T Goonatilleke , M.W.G Jayampath and B Hettige. *“Tilly – A Tamil Learning Chatbot for Non-Native Tamil Speakers”.* Proceedings of the 16th Annual Sessions, Sri Lanka Association for Artificial Intelligence (2020).
