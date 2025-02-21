PresentationResponses
================
Anirudh Singh
March 24, 2019

# presentation prompts

Complete the prompts before the start of class on the day of the
presentation.

  - These points guide the small-group discussions.
  - Much of this work will be part of your portfolio critiques.

Once you decide the type of graph to be used for a display, you may
replace the heading, for example, if you use a box plot for Display D1,
you can change the heading from

    ## D1 distributions 

to

    ## D1 box plot

## D1 distributions

State the number of observations: 7197

List the variables:

  - Potential

  - Nationality (categorical)

  - 
State the graph type: Boxplot

Explain why the graph type is suited to the data structure:

  - Easy to see quality of players with the box

Explain each design choice and cite its supporting reference

  - choice, reference
  - choice, reference
  - etc

Comments from peers

  - Does the data structure satisfy the portfolio display
    requirements?  
  - From the Doumont paper, what type of story is being told?
  - Is the graph type suited to the data structure?
  - Other suggestion
  - etc

## D2 multiway

State the number of observations:

List the variables:

  - Price ($) - This is the price of the app one has to pay to purchase
    on the appstore
  - user\_rating (1,1.5,2,2.5,3,3.5…..5) - These are the total ratings
    the app has received over time for all versions - It has 10 levels
  - primary\_genre (Travel…) - This is the type of application on the
    app store based on the function it serves. - It has 23 unique genres

State the graph type: Multiway Plot

Explain why the graph type is suited to the data structure:

  - Want to look at popular application and their prices and how they
    vary in different genres.

  - Since we are trying to show how price varies in several categories
    of application based and we also want to show how user ratings
    affect the price. This is the ideal plot.

Explain each design choice and cite its supporting reference

  - Using only apps with price less than $42 - getting rid of outliers -
    better scaling. - applications costing are unpopular.

  - using cont\_rating as colour - helps establish relationship between
    cont rating and price. (if any)

  - user\_rating - (serves as a test to see if pricing it at that level
    was successful)

Comments from peers

  - Does the data structure satisfy the portfolio display
    requirements?  
  - From the Doumont paper, what type of story is being told?
  - Is the graph type suited to the data structure?
  - Other suggestion
  - etc

## D3 correlations

This dataset is from the EA game FIFA 19. It is a yearly franchise which
covers most players in the world. It is updated weekly hence it is safe
to say it is the most accurate representation of the level of players.

Each player has a lot of characteristics but in general they can be
divided into 3 main categories: Physical Technical Mental – Positioning,
Composure, Vision (more useful for passing), Aggression, Interceptions(
more defensive)

Mental stats that apply to all are Positioning, Composure and Aggression
Question: What matters more composure or aggression (Playing styles :
Messi vs Ronaldo) – that is where the question came from.

We can see a linear relationship with composure. Higher composure
usually leads to higher overall rating.

With aggression, things are not so easily seen. If we talk about
defending, then people with high defensive work rate can benefit from
having high aggression. (So defenders need to have high aggression)

Reorder the levels Label couple players Do composure vs Aggression -
label players Making rating as colour Shape for position

Candidate for D6 Multivariate – changed to multivariate

## D4 injuries or fatalities displayed ethically

**Context**

Type of injury or fatality: Death toll

People affected: Journalists

Over what span of time: 1992-2016

**Graph the data conventionally**

  - If you are redesigning someone else’s graph, include an image of the
    original
  - If not, graph the data yourself using a graph type suited to the
    data

State the number of observations: 1782

List the variables:

  - death toll
  - time
  - type of death (cat)

State the graph type: bar graph

Explain why the graph type is suited to the data structure:

  - Since we are plotting number of deaths. A bar graph will be able to
    show clearly when comparing
  - bar graphs give us the capability of splitting the data based on
    subcategories.

Explain the visual-rhetoric features of the graph that make it
unethical:

  - point
  - point
  - etc

**Redesign the graph to display the data ethically**

State the new graph type (if any):

Explain each design choice in the redesign and cite its supporting
reference

  - choice, reference
  - choice, reference
  - etc

Comments from peers - Difference based on different wars - Line graph
with lines for the different wars - Have a different panel for the total
- find other investigative journalists who have studied this - watermark
for the image - other editorial cartoons (edit the current one) -
phillipines - death toll as a percentage of journalists in that area
(try getting that)- get the denominator - looking at foreign
journalists? - famous journalist sayings - unknown on top so blue starts
from the same line - what goes into dangerous assignment - use coverage
as category -use magik package for the image - graphdoctor.com

  - Any suggestions on improving the ethical display of injuries or
    fatalities?
  - Does the data structure satisfy the portfolio display
    requirements?  
  - From the Doumont paper, what type of story is being told?
  - Is the graph type suited to the data structure?
  - Other suggestion
  - etc

## D5 redesign a graphical lie

**The original deceptive graph**

The original image is included in the portfolio: Yes

Explain the visual-rhetoric features of the graph that make it
deceptive:

  - does not have y axis
  - x axis not even
  - mistitled

Comments from peers

  - Are there additional deceptive practices that have not been
    mentioned?
  - Other comments
  - etc

**The redesigned graph**

State the number of observations:

Identify the variables:

Unemployed pop Year Month

Category - position State the graph type:

Explain why the graph type is suited to the data structure:

  - point 1
  - point 2
  - etc

Explain each design choice and cite its supporting reference

  - choice, reference
  - choice, reference
  - etc

Comments from peers

  - Does the data structure satisfy the portfolio display
    requirements?  
  - From the Doumont paper, what type of story is being told?
  - Is the graph type suited to the data structure?
  - Other suggestion
  - etc

## D6 multivariate

State the number of observations: 9284

List the variables:

Acceleration $ SprintSpeed  
$ Agility  
$ Balance  
$ Reactions  
$ Jumping  
$ Stamina  
$ Strength

State the graph type:

Explain why the graph type is suited to the data structure:

  - point 1
  - point 2
  - etc

Explain each design choice and cite its supporting reference

  - choice, reference
  - choice, reference
  - etc

Comments from peers

  - Does the data structure satisfy the portfolio display
    requirements?  

  - From the Doumont paper, what type of story is being told?

  - Is the graph type suited to the data structure?

  - Other suggestion

  - etc

  - as a defender….(part of critique) for each variable

  - number them on the scale

  - colors too dense for gridlines

  - annotation line

  - try more ordering

  - use teams based on high and low performing teams, another dataframe
    with the team and players

  - add best players on each attribute

  - inlcude the other

## D7 self-taught

State the number of observations: 100

List the variables:

  - ATM services variables (9) -Internet banking variables (7)

State the graph type: Likert bar plot

Explain why the graph type is suited to the data structure:

  - It has survey data Explain each design choice and cite its
    supporting reference

  - choice, reference

  - choice, reference

  - etc

Comments from peers

  - Does the data structure satisfy the portfolio display
    requirements?  
  - From the Doumont paper, what type of story is being told?
  - Is the graph type suited to the data structure?
  - Other suggestion
  - etc
