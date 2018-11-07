# cse591chatbot
Human Aware AI Project - Persuasive Chatbot

## 6 Principles of Persuasion + end state (function maps to each)
• Reciprocity -  
offer, free, sample, introduction, discount
thank you, you're welcome, discount
Ex: "Free" ebooks, free webinars, free podcasts, free samples, free trial

• Commitment & Consistency -  
safe, action, commitment, investment, choice
Ex: input personal info, leave good review, post before-after photos, contest

• Social Proof -  
expert, recommendation, friends, credible, endorsement, popular
Ex: star ratings, popularity, testimonials, friends liked this

• Liking -  
friendly, sexy, teamwork, compliment, relatable

• Authority -  
title, clothes
Ex: Dr., Companies worked for, "apple geniuses", "shopify experts", suit,

• Scarcity -  
limited, temporary, demand, special event, hurry, only x left, invite only, exclusivity, oout-of-stock, clearance, 

• Close -  
Trust, purchase, satisfaction, buy, yes

## Obstacles
• Gatekeeper -  
keep a strong relationship with the gatekeeper

• Budget/price -  
justify cost, get customer to explain why cost

• No Need -  
create pain, get customer to explain how cost benefits, problem magnitude

• Proof of Product/Quality of Product -  
show reccomendations, friends, premptively

• Too much push -  
emotional, get leads where they fall, offer free stuff

## Information
•General
- Product Name
- Example past product names
- Prices
- Limited Promotions
- Free Samples
- Reccomendations
 
•Personal
- email
- name


#Conversational Flow

1. Hello, how are you? What is your name? #intro

2. What brought you to this site? #solidifies intention

if (tryingtoBuy)

	continue
	
elif (noResponse)

	elicitAttention
	
else (notsure)

	persuade()
	
3. Would you like to be redirected to the purchase page?

4. Who would you recommend this purchase for?


def persuade:


 *Reciprocity 
 
 trigger: Budget
 
 Would you like a [free sample]?

 *Commitment (unneeded?)
 
 trigger: used product, happy
 
 If [free sample | product] helps, want to leave a review?
 
 Would any of your friend's like to try [free sample | product]


 *Authority
 
 trigger: No Need
 
 [recommendations]
 
 How would you use our product?


 *Commitment
 
 trigger: gatekeeper
 
 Where could we reach {you | gatekeeper} at?

 *Social Proof
 
 Trigger: roof of Product/Quality of Product
 
 [recommendations]
 
  use them
  
  You get what you pay for
  

def elicitAttention:

 Limited Time Offer
 
 Gifs
 
 Who knows
 

