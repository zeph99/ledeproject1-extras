# Did films get worse after 9/11?

#I wanted to explore whether there was any factual basis to a remark I've heard tossed around offhandedly
#Which is that TV and films changed after 9/11
#So I scraped the datatable from Wikipedia's list of worst films (https://en.wikipedia.org/wiki/List_of_biggest_box-office_bombs) and identified what proportion of films were made post 9/11, and how badly they failed

#Findings: Almost 80% of the worst films in terms of gross earnings were made from 2001 onward.

#I screamed and begged pandas and stack overflow for help and ended up doing a lot of things somewhat manually. I wanted to automatically count the number of films created after 2001, and easily select the films created in 2001 to find their release date and refine the data. I struggled a lot with the nested estimated loss titles. I also wanted to see if inflation adjusted loss was higher on average post 9/11.

#If I had more time I would have put more analysis into films released after the 2008 recession and the total number of films released per year. I also would have verified they were all produced in the US.

#There were some pesky ranges in the numbers that I didn't know how to deal with. I would have loved to see how budgets changed over time but it was too frustrating and time-consuming to manually delete all the ranges the way I did with DataWrapper.

#I learned about pandas and beautifulsoup, and which error message means I'm using the wrong brackets. I did get better at some basic commands but it felt like I couldn't do anything right and was super demoralizing while I was writing the code. I'm happy with the DataWrapper charts because they were easy.

