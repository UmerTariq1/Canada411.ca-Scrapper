# Canada411.ca-Scrapper
Scrapping a website to scrap contacts of around 3,500 people

As a side project, I tried to scrap canada411.ca . 
About canada411.ca : it is directory kind of website. In which when you enter a name of the person, a list of search result names with contact info are returned. So in short For each searched name, a list of names and contact info was scrapped. 
For this first, I found a list of random names on a website, this list had around 3.5 thousand names. Then I used beautiful soup 4 and python 3 to fetch each search result under the each name. so basically structure was like this:
Salman:
  salman dawood
  salman fari
  salman rity
david:
  david phil
  david poli
  david colomb

one page only had 15 contacts, so I had to navigate on multiple pages for even one base-name.
At the end, around 250754 people's name and contacts were scrapped.
This was a good learning exercise and I learned many practical things doing this project which will help in future projects.
