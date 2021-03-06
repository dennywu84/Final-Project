# Final-Project Proposal
## Abstract  
In this project, we will be working with basic data about dogs living in New York City in 2015. From this dataset, we hope to answer questions that will be beneficial to future dog owners and anybody interested in the name trends of pet dogs over time, as this will provide insight on information about dogs living in a densely populated area that some may find helpful. To do this, we will be coding with the programming language R in order to effectively analyze this data to answer our questions.

## Keywords  
Dogs, New York, Name Trends, Housing Costs, Dog Breeds

## 1. Introduction  
With a population of more than 8.4 million in 2015, New York is an extremely large and diverse city, and houses dogs of many ages and breeds in all five boroughs. The city is extremely dense population-wise, and has resulted in a high cost of living. Yet despite this, people are still able to accommodate their pets into their living situation. By analyzing a dataset about dogs located in New York, we will be able to find valuable insights about the most common dog breeds living there, and be able to think critically about why that is the case.

The research questions we are aiming to answer using our dataset are:
- How does the cost of housing and type of housing available (house, apartment, etc.) in each borough affect the size of dogs that owners choose to get?
- Does the dog breed affect the name that is chosen for the dog, or are most of the names consistent throughout all the dog breeds?
- Was there a trend in any of the years where many people gave their dogs unconventional/unpopular names?

The answers to these questions may be valuable for future dog owners (especially in dense cities like New York), as they may be interested in what type of dogs are best suited for their housing situation. This is important because there are various factors that go into caring for a dog, and choosing a dog that doesn’t fit your lifestyle or home situation may result in neglect of the dog. And on a more lighthearted note, these data would give these same people inspiration for potential dog names, and they are able to look at the name trends that have taken place throughout the years.

## 2. Related Work  
In a city where the population is so dense, finding affordable housing is difficult, especially for dog owners. In [this article](https://www.nytimes.com/2013/03/31/realestate/what-pet-owners-must-do-to-get-new-york-apartments.html) by the New York Times, stories were obtained from dog owners that went through the struggle of finding a home for themselves and their dog (Rosenblum). They asked about the types of dogs they had, the pricing of their apartment, and the process of finding the right apartment for their dog. They often had to settle for rentals that were further away, smaller, and more expensive. One person mentions how the age of her dog also prevented her from buying many apartments due to the amount of stairs.  

In [this article](https://www.nytimes.com/2013/04/04/garden/the-art-of-naming-a-dog.html), the New York Times talks about what goes on in naming a dog (Hoffman). There are general rules that most experts recommend. For example, they recommend avoiding names that could sound like a command as it could confuse the dog.  

[This paper](https://www.mdpi.com/2076-2615/4/3/409/htm) by Emily Weiss and others talks about how bigger dogs in New York and Washington D.C. are surrendered more often than smaller dogs (Weiss, et al.). They surveyed people at animal shelters that were giving up dogs and asked them twenty-six questions in an attempt to find a common reason behind why people gave up their large dogs. They found that the majority of New York respondents were living in apartments while most respondents in D.C. were living in single family homes. However, when they were asked for additional reasons for giving up the dog, only 14% of New York respondents listed housing issues.

### References  
Hoffman, Jan. “You Named Me Brutus? Really?” *The New York Times*, 3 Apr. 2013, https://www.nytimes.com/2013/04/04/garden/the-art-of-naming-a-dog.html.

Rosenblum, Constance. “What Pet Owners Must Do to Get New York Apartments.” *The New York Times*, 29 Mar. 2013, https://www.nytimes.com/2013/03/31/realestate/what-pet-owners-must-do-to-get-new-york-apartments.html.  

Weiss, Emily, et al. “Large Dog Relinquishment to Two Municipal Facilities in New York City and Washington, D.C.: Identifying Targets for Intervention.” *MDPI*, Multidisciplinary Digital Publishing Institute, 8 July 2014, https://www.mdpi.com/2076-2615/4/3/409/htm.  

## 3. The Dataset  
The data were originally discovered through a visualization named “Dog Names in New York City”, and was found on the NYC government website. The csv file for the dataset that corresponds to the visualization was found in [this GitHub repository](https://github.com/Kaz-A/dog_names/).

The data were collected by the NYC Department of Health, and it was based on results from 2015.

It is not clear what methods the author used when collecting data. But we can infer that the data were collected through questionnaires.

With the increased number of pet dogs, people are interested in the names of dogs. We think that the names may have some trends which can reflect culture or background changes. To illustrate, in some areas, there may be more dogs with one particular name than in other areas. To answer this question, we want to analyze the data of dogs’ names and what information these data could give. The purpose of collecting these data is to analyze the change and popularity in dog names.

There are 111,650 observations in total.

There are 5 features in the data, which are AnimalName, AnimalGender, AgeAsOf2015, BreedName, and Borough.

There are some possible limitations within our data. The data were collected in 2015. With 8 years passed, the popular names that owners want to give to their dogs may change. Because of this, this dataset may not be representative of the dog name trends in 2023. Additionally, it is possible that not every dog owner in New York was counted in the data, and therefore it may not be entirely accurate.

## 4. Implications  
Assuming that we answer our research questions, our findings may be able to help designers and policymakers create further changes that would benefit dog owners, specifically owners of large dogs. In densely populated areas like most of New York, many apartments don’t allow their tenants to own large dogs, and there could be many reasons for this. But as a result, a lot of new and inexperienced dog owners may adopt a large dog (or one that will get large in the future), only to realize that they won’t be allowed to keep it. The dog may end up in a shelter hoping to finding a new home, but there’s no guarantee, especially since many homes in the New York area don’t allow large dogs in the first place. Future designers may want to keep this in mind by designing housing that’s more friendly towards large dogs, which will certainly keep dogs out of the many overpopulated shelters.

Another reason why large dogs aren’t allowed in most apartments is because they’re seen as highly disruptive, yet a well-trained large dog can be less disruptive than a small dog or even a human toddler, for example. So policymakers can view this data and possibly set new rules and regulations to allow more owners of large dogs to live in apartments with their pets if the owner can prove that their dog is well-behaved enough to be there.


## 5. Challenges & Limitations  
The features of the dataset only include the animal name, gender, and age in 2015. Since we only know their age and not when the name was given to them, it will be difficult to predict the trend of dog names over the years. To combat this, we may choose to assume that most of the dogs were named the same year they were born in order to stay consistent within our data. And using this assumption, we will be able to analyze the name trends over time. Also, due to the limited features in the dataset, our topics are also limited. For example, our data do not explain the reasoning behind why the owner chose that particular name for their dog, so we are unable to analyze the reason why certain names are really popular. Additionally, data was collected only for dog names in New York, which may not be representative or applicable to other cities or states in the U.S.
