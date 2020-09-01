# Design thoughts

This design tries to follow [best practices](https://docs.microsoft.com/en-au/azure/bot-service/bot-service-design-principles?view=azure-bot-service-4.0). 

It provides a set of button choices to guide the user to a factsheet card

![](../images/chatbot-card-application.png)

Clicking on this card will open the factsheet in LeanIX. 

As well as using the buttons to navigate, you can [type a question](../help)

## Questions you can ask

The questions you can answer, at a high level are:

- what applications, business capabilities, processes, or user groups do we have?
- what are their related factsheets?
- how many applications do we have?

## Finding factsheets

You can find business capability, process, or user group factsheets via:

- name
- a list of names
- a tag
- a list of tags

From a business capability, process, or user group, you can find related applications by typing "Uses Applications".

You can find application factsheets via:

- name
- a list of names
- a tag
- a list of tags
- lifecycle status

From an Application, you can find related  business capabilities, processes, or user groups by typing "Used by *factsheet type*".

## Counting Applications

Type "**Count Applications**" to see a total count of Applications and sub-totals by Application lifecycle status.

## Building the chatbot

Thinking about using the [Bot Framework Composer](https://docs.microsoft.com/en-us/composer/introduction).



## Deploy

Planning to deploy to Teams.
