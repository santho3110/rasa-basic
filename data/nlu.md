## intent:affirm
- yes
- yep
- yeah
- indeed
- that's right
- ok
- okay
- great
- right, thank you
- correct
- great choice
- sure
- Hallo
- Good day
- sounds really good
- thanks
- thanks
- sure, why not!

## intent:goodbye
- bye
- goodbye
- good bye
- stop
- end
- ciao
- farewell
- Bye bye
- have a good one
- see you again

## intent:greet
- hey
- howdy
- hey there
- hello
- hi
- good morning
- good evening
- dear sir
- hi
- hii
- hello

## intent:restaurant_search
- i'm looking for a place to eat
- I want to grab lunch
- find some restaurant 
- I am searching for a dinner spot
- I am looking for some restaurants in [Delhi](location).
- I am looking for some restaurants in [Bangalore](location)
- show me [chinese](cuisine) restaurants
- show me [chines](cuisine:chinese) restaurants in the [New Delhi](location:Delhi)
- show me a [mexican](cuisine) place in the [centre](location)
- i am looking for an [indian](cuisine) spot called olaolaolaolaolaola
- search for restaurants
- anywhere in the [west](location)
- I am looking for [asian fusion](cuisine) food
- I am looking a restaurant in [Chennai](location)
- in [Gurgaon](location)
- [South Indian](cuisine)
- [North Indian](cuisine)
- [Italian](cuisine)
- [Chinese](cuisine:chinese)
- [chinese](cuisine)
- [Lithuania](location)
- Oh, sorry, in [Italy](location)
- in [delhi](location)
- I am looking for some restaurants in [Mumbai](location)
- I am looking for [mexican indian fusion](cuisine)
- can you book a table in [rome](location) in a [moderate](price:mid) price range with [british](cuisine) food for [four](people:4) people
- [central](location) [indian](cuisine) restaurant
- please help me to find restaurants in [pune](location)
- Please find me a restaurantin [bangalore](location)
- [mumbai](location)
- [Chinese](cuisine:chinese)
- show me restaurants
- [mumbai](location)
- [Italian](cuisine)
- please find me [chinese](cuisine) restaurant in [delhi](location)
- can you find me a [chinese](cuisine) restaurant
- [delhi](location)
- please find me a restaurant in [ahmedabad](location)
- please show me a few [italian](cuisine) restaurants in [bangalore](location)


## intent:request_mail
  examples: |
    - My email is [example@example.com](email)
    - [random@example.com](email)
    - Please send it to [anything@example.com](email)
    - Email is [something@example.com](email)

## synonym:4
- four

## synonym:Delhi
- New Delhi
- Dilli

## synonym:bangalore
- Bengaluru

## synonym:chinese
- chines
- Chinese
- Chines

## synonym:mid
- moderate
- avg

## synonym:vegetarian
- veggie
- vegg
- veg

## regex:greet
- hey[^\s]*

## regex:pincode
- [0-9]{6}
