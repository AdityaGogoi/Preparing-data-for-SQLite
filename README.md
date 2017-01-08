# Preparing-data-for-SQLite
Preparing CSV datasets and read them into SQLite.

Introduction:-

The Academy Awards, also known as the Oscars, is an annual awards ceremony hosted to recognize the achievements in the film industry. There are many different awards categories and the members of the academy vote every year to decide which artist or film should get the award. The awards categories have changed over the years, and you can learn more about when categories were added on Wikipedia.

Here are the columns in the dataset, academy_awards.csv:

1. Year - the year of the awards ceremony.
2. Category - the category of award the nominee was nominated for.
3. Nominee - the person nominated for the award.
4. Additional Info - this column contains additional info like:
  i. the movie the nominee participated in.
  ii. the character the nominee played (for acting awards).
  iii. Won? - this column contains either YES or NO depending on if the nominee won the award.
 
Filtering The Data:-

The dataset is incredibly messy and there are many inconsistencies that make it hard to work with. Most columns don't have consistent formatting, which is incredibly important when we use SQL to query the data later on. Other columns vary in the information they convey based on the type of awards category that row corresponds to.
I will filter the data with a smaller subset to make it less messy and more manageable.
