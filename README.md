# Lek-Paradox-3
Third Draft after the prior 2 crashed and burned
I am losing Life force as we speak


Patch 0.1 Things that have been worked on.

Created an Agent Generate Function that contains the trait values of both males and females using a rough Genetics system. AS well as having agents assigned a sex and an ID# *Had to create 100 agents becuase the rows and columns were bugging hard.

What is being worked on/could use some guidence on. *Creating a line of code that returns the male agent with the highest trait value and their ID. (So far I can only produce the male agent with the highest TV but am struggling with ID) *Creating a reproduction function for offspring


PATCH 0.2 Things that have been worked on or changed (12/15/23-1/7/24)
FULL DISCLOSURE, A crap ton of Videos, prior Workshop code, and some help from chat gpt was involved. 
*Chat GPT was used to better understand error codes and as well as to understand what I have written. IE I would ask it "What does this line of code mean to you" and use its answer to keep myself on track. All of this stuff has helped a lot. 

-----Agent Generate Function-----
It works now. I can produce 6 agents, half male, half female, with varying trait values.
First generation can be seen via (line 126)"agents_data"

Can Identify the highest maleTraitValue from the first gen of Males AND can Identify the ID of that specific male.

Can produce isolated Data frames of each gender for clarification and future code purposes

------ WIP -------
-Reproduction Function-
It semi works
Can produce a sequence of IDs AND can create an equal number of male and female agents.
Can produce male agents with the Max trait value of the father
Can produce Female agents with randomly generated new trait values
