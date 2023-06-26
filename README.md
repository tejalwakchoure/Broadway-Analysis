# So You Think You Can Broadway?

Code for the data journalism project hosted [here](https://tejalwakchoure.github.io/broadway/).

## Aim

To analyze the data for Broadway stars and look for any factors or trends that lead to their success. Inspired by Vulture's [nepo baby article](https://www.vulture.com/article/hollywood-nepotism-babies-list-taxonomy.html).

## Findings

While not nearly as much as in Hollywood, having connections does help a career on Broadway. What was more interesting was the schools these stars attended - NYU especially was a clear winner. Another interesting finding was how many of these performers started off in other areas of the entertainment industry.

## Data collection process

1. Scraped cast list data for shows currently running on Broadway from [IBDB](https://www.ibdb.com/shows) using beautifulsoup. Focused on opening night cast members only.
2. Checked whether Wikipedia pages exist for each of these performers using pandas. If so, scraped those using beautifulsoup.
3. Made a dataframe of all performers, their shows and opening nights, and relevant wikipedia sections (parents, relatives, schools, screen credits).
4. Cleaned dataframe with pandas. Filled in any missing information from [Playbill](https://playbill.com/) profiles of these actors.

## Data analysis process

1. Sorted the dataframe by school frequency to see which school is most popular among stars.
2. Filtered on parents/relatives and checked what these individuals were famous for.
3. Compared all screen credits with their respective opening nights to determine which credits were before opening night.

## New skills

1. Building a story from data insights
2. Data collection/scraping using beautifulsoup
3. New ways to interact with dataframes
4. Using Flourish

## Future improvements and additions

1. A searchable table where readers can look up their favorite performers' information.
2. More in-depth explanation in the story about how the industry works, maybe compared to how Hollywood or TV works.
3. I'd originally thought of making this an interactive project where the reader walks through 'becoming a Broadway star'. There wasn't enough time for that, but might try this later on.


   
