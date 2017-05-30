# Endangered Languages Project

An interactive visualization of the global nature of linguistic diversity in Queens, NY

## Introduction

New York City is one of the most linguistically diverse places in the world; estimates show anywhere from 200-800 different languages represented across the five boroughs. Nowhere is this more apparent than in Queens, where many of these languages are spoken in schools, restaurants, community centers, and homes across the area. This project takes a snapshot of this linguistic diversity and highlights the ways that language connects New York City and the rest of the world. By visualizing the languages that are represented and casting them against stories of migration, language, and identity, we come to see the ways that language ties us together, and give life to the many languages of Queens, NY.

### Research Questions
	
* In what ways does language make New York City a truly global city? 
* How are the languages spoken in Queens representative of the world as a whole?
* To what extent can language symbolize diversity in Queens?

## Take-away

The linguistic diversity of Queens is awe-inspiring, and the linguistic diversity of the world is humbling

## Project Plan

### Basic Idea

* landing page is a map of Queens with lines connecting to every country/region where the languages are spoken.
* clicking on a line sends you to a page with a map of Queens and a box on the side with information about the language (similar to Colombia)
* hovering on a line shows a popup with the name of the language

### Design

* What should this look like?
* Interaction/colors/fonts/feel
* Images? 
* What is the experience of the user?

### Raw Materials

* Maps of each country with the language of that country
* Maps of Queens for each country (possibly programmatic for all but a few)

### Pages

* Site page for each language with information about the language
* Main page with links to each language page

### Database

* Establish PostGIS relational database
* Table 1
	* LID/Language/nta
	* LID/wikilinks/story
	* LID/lang_pages

### Backend

* Layouts page
* Input Method
* PostgreSQL/Flask/Node/HTML


## Next Steps

1. Landing map where Queens connects via a line to each country in the dataset
	1. Figure out how to make those lines "hot" - does this need to be in D3?
	2. Create a search function for the languages
	3. What will users see when they leave? How can they get back?
	
2. Create geojsons for each of the languages for their home regions
3. Pages for each language that extend the template. 
4. Figure out how to connect the database through Flask


