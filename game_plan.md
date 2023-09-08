# App Design / Initial Game Plan Thoughts

Approaching the problem most simply, it must work for 1 user. Then, for users 2 - ∞. 
This entire page is grossly simplified.

A user should be able to:
- 
- follow a learning/study plan for the SAT
	- follow the default, general plan that we suggest upon sign-up
	-  create personalized learning plan targeting desired concepts from any section (reading, writing & language, math)
	- shuffle mode
- receive an explanation as to why any answer is correct or incorrect
	- human supervision offered through email support (within 24h) re: incorrect explanation (later) 
- be faced with more challenging problems when concept mastery is shown, vice versa

Once that's achieved:
- 
- build account management / payment processing infra
	- create/delete their account
	- should store their email, password, openai chatgpt API key, payment information
	- service should be restricted until payment is given
- make website mobile device friendly for on-the-go studying
- provision lambda instances specifically for study functionality (want application to be fast for all users)
	- study usage patterns and peak load over time to minimize costs
- demo product to local high schools and internet, collect interest
	- case study using a school's student body and their score changes using TruPrep
- replicate the same capabilities but for the ACT test

Then:
- 
- sell product as a subscription to individuals and as a contractual offering (schools)
- hire others, build mobile app
- grow to offer prep for other standardized tests (GRE, MCAT, LSAT, international tests, etc)
