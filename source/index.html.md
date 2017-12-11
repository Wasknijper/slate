---
title: API Reference

<!-- language_tabs: # must be one of https://git.io/vQNgJ
  - javascript -->

toc_footers:
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Inleiding

Welcome to the Kittn API! You can use our API to access Kittn API endpoints, which can get information on various cats, kittens, and breeds in our database.

We have language bindings in Shell, Ruby, and Python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

This example API documentation page was created with [Slate](https://github.com/lord/slate). Feel free to edit it and use it as a base for your own API's documentation.

# Voorwoord

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

# Management samenvatting

# Orientatie

<!-- 
Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted. -->

<!-- <aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside> -->

## Probleem + onderzoeksvraag

This endpoint retrieves a specific kitten.

<!-- <aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside> -->

## Context

This endpoint deletes a specific kitten.

###Lifely + Fresh Heroes

###Data opkomst

###Veiligheid

##Stakeholders

###Fresh Heroes

####Product Owner
####Developers

###Lifely

###Gebruikers

####Studenten
####Bedrijven

##Productvisie

##Aanpak

#Onderzoek

##Behoeften van Fresh Heroes

###Interviews Barry & Pim
###Rand voorwaaren van het project
###Eisenlijst van MVP

##Huidige situatie van Fresh heroes

###Gebruikte technieken
###Wat wordt er nu bij gehouden?
###Waarom zelf gebruikersdata tracken

##Bestaande oplossingen (concurrentie analyse)

##Techniek

###Intoductie

###Events

####Wat zijn events
####Hoe gebruik je events
####Implementatie van events
####Datamodel events
####Evaluatie na eerste deploy op events

###Frontend techniek

####Ophalen van data
#####Waarom geen API
#####Combinatie met Google Analytics
#####Structuur laden + renderen

####Keuze in datavisualisatie framework
#####Concurrentieanalyse
#####D3 basis uitleg
#####Svg vs Canvas

###Veiligheid

##Datavisualisaite

###Best practices
###Moodboard/Inspiratie
###Dashboard design
###Keuzes op delen van data
###Interactie
###Grafiek keuze toelichting per data type

#Validatie
##Tussentijdse feedback
##Lunch Presentatie
##Feedback frenzy
##Gebruikerstest

#Eindproduct
##Screencast
##Schermentoelichting

#Conclusie

#Aanbevelingen

##Analytics naar backend verplaatsen
##(mogelijk) anonimiseren van user_id
##Session gebruiken om de funnels en views toe te spitsen
##Gebruikersovereenkomst aanpassen
##Implementeren van KPI’s
##Grafieken generaliseren/refactoren

#Bijlagen

#Bronnen

#Termen
