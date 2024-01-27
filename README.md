# Census-Project-Report
Analysis on a mock census of an imaginary modest town using Python.
![luke-michael-ZKZyYIR9hUA-unsplash](https://github.com/Abisola-Raji/Census-Project-Report-/assets/157732949/675cfcd4-f318-4bf8-8e82-04aab150fa9c)

# Project Background Information. 
Every ten years, the United Kingdom undertakes a census of the population, with the most recent one having 
been conducted in 2021. The purpose of such a census is to compare different people across the nation and to 
provide the government with accurate statistics of the population to enable better planning, to develop policies, 
and to allocate certain funding. 
In this project, a mock census data of an imaginary modest town was utilzed, where I was considered to be part of a local government team who would be making decisions on what to do with an 
unoccupied plot of land and what to invest in.

# About this Mock Census. 
The mock census contains randomly generate data using the Faker package in Python. It has 
been generated in a similar manner to (and designed to directly emulate the format of) the 1881 census of the 
UK wherein only a few questions were asked of the population. The fields recorded are as follows: 
1. Street Number; 
2. Street Name; 
3. First Name of occupant; 
4. Surname of occupant; 
5. Age of occupant; 
6. Relationship to the “Head” of the household (anyone aged over 18 can be a “Head” – they are simply 
the person who had the responsibility to fill in the census details); 
7. Marital status (one of: Single, Married, Divorced, Widowed, or “NA” in the case of minors); 
8. Gender (one of: Male, Female; note that other responses were not implemented in 1881); 
9. Occupation (this field was implemented in a modern style, rather than typical 1881 occupations); 
10. Infirmity (we have implemented a limited set of infirmities following the style of 1881); 
11. Religion (we have implemented a set of real-world religions).

# The Task. The town from the census is a modestly sized one sandwiched between two much larger cities that it 
is connected to by motorways. The town does not have a university, but students do live in the town and 
commute to the nearby cities. The task is to decide the following: 
(a) What should be built on an unoccupied plot of land that the local government wishes to 
develop? Choices are:
- High-density housing. This should be built if the population is significantly expanding.
- Low-density housing. This should be built if the population is “affluent” and there is 
demand for large family housing.
- Train station. There are potentially a lot of commuters in the town and building a train 
station could take pressure off the roads. But how will the commuters be identified?
- Religious building. There is already one place of worship for Catholics in the town. Is 
there demand for a second Church (if so, which denomination?), or for a different religious building?
- Emergency medical building. Not a full hospital, but a minor injuries centre. This should 
be built if there are many injuries or future pregnancies likely in the population. 
- Something else? 
Justify your answer from the data provided and argue if it is a priority against other choices.

(b) Which one of the following options should be invested in?
- Employment and training. If there is evidence for a lot of unemployment, we should re_train people for new skills. 
- Old age care. If there is evidence for increasing numbers of retired people in future years, 
the town will need to allocate more funding for end of life care. 
- Increase spending for schooling. If there is evidence of a growing population of school_aged children (new births, or families moving in to the town), then schooling spend should increase. 
- General infrastructure. If the town is expanding, then services (waste collection; road maintenance, etc.) will require more investment. 

