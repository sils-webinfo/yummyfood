HTML files for www.yummyfood.com

There are four HTML files:

1) recipes.html: the homepage of the website and also the page that lists all the recipes. This page, like all the others has a search form that allows the user to search for recipes by keywords. Keywords could be meal types, ingredients,  recipe title, etc. The homepage has a ling to the meal-type page which is meal.html. It also links to individual recipes, which are represented by the recipe.html template.

2) meal.html: the page that displays recipes by the selected meal-type. Once the meal type is selected, the GET method would be needed to retrieve the data from that category (i.e. dinner recipes, lunch recipes, snacks recipes, etc.) and then the POST method would need to be used so that the user could see the selected data.
This page also links to the homepage (recipes.html) and includes the search form. 

3) search.html: is a search results page that is navigated to after a query is entered into the search form. The URI of the page will be created from the terms in the query: www.yummyfood.com/search/q=term1+term2. This example just has two terms but the query could contain more terms. This page links back to home and meals and also contains a search form. 

4) recipe.html: is the template that represents each individual recipe. It contains the elements that each recipe will have that will be described in the class elements section of this document. recipe.html links to the homepage, the meals page, and contains the search form. 


Class Attributes - used with <span> tags

URI - the URI for the resource, present on each html page

description: a description of a page and/or its contents

recipe-title: name of the recipe

meal-type: which category the meal fits into: breakfast, lunch, dinner, dessert, snacks, or appetizer

author: author of a recipe

date: date the recipe was created

time: date/timestamp for the time recipe was posted

yields: number of portions or servings a recipe yields

ingredient: an ingredient that a recipe contains

instructions: cooking and preparation instructions for the recipe

search-results:  results from search query

search-title: the title of the search which is represented by the keywords in the search


Core Attributes - used with <span> tags

ID (recurring): the page identifier. Each recipe will be identified by a combination of letters. The homepage will have the identifier "root." Search will be identified as "search+" and then the search terms. And meal with have the id of "meal." Each meal will not have a page because the output will be display within the meal page. 

Name Attributes:

recipe-search: used between <form> tags, name of form used to search for recipes by keyword. 

mealtype: used between <form> tags, form select meals based on their meal type (i.e. breakfast, lunch, dinner, etc.).

mealdropdown: the name of the drop-down menu of the meal-type form. Used between <select> tags. Has the following controlled values: breakfast, lunch, dinner, dessert, snacks, appetizers.

search: used between the <input> tags. Is the name of the search-term input text field. 

Rel Attributes:

all-recipes: name of the link that goes to the homepage and displays all the recipes. Used between the <a> tags.

meal: name of the link that goes to the page where the user can sort recipes by meal. Used between the <a> tags. 

recipe-title: title of the recipe. Used between the <a> tags. Note that recipe-title is also used between the <span> tags. 

