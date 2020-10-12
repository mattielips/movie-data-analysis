![](https://bechdeltest.com/generated/tests.png)
![Windows Background](/images/Windows_background.png)

# Analysis of How to Make Microsoft a Successful Film Studio 

**Authors**: [Fennec C. Nightingale,](mailto:fenneccharles@gmail.com)[Matthew Lipman](mailto:matthew.lipman@wework.com) & [Russell Pihlstrom](mailto:rgpihlstrom@yahoo.com)

## Overview

This project analyzes the best route for Microsoft to break into the film industry. Descriptive analysis of studios show the top companies to produce your film by genre. Analyzing cast shows how many “A Players” your movie should have & analysis of reviews will show you the importance of critics including which ones to choose. This will give Microsoft the tools to make films more likely to be successful. 


## Business Problem

![Film_Crew](/images/Film_Set.png)

Messing up your introductory film could not only cost you millions, but your reputation. Microsoft will get many of the tools necessary to produce a successful film from our analysis & using them will give Microsoft an edge into the film scene. 

## Data
<ol>
    <li>Box Office Mojo: Reporting & analysis service that tracks box office receipts. Data includes         daily, weekly, weekend, monthly, yearly, seasonal, and holiday box-office grosses & is linked         by movie title and year of release. </li>
    <li>IMDB : Database with information related to films, including cast, crew, fan and critical             reviews & ratings.  Data is linked through unique movie keys (tconst) & person keys (nconst).     </li>
    <li> Rotten Tomatoes:  The leading online aggregator of movie and TV show reviews. Data linked by          rotten tomatoes ID. </li>
    <li> The Numbers:  Detailed financial analysis, from box office to Blu-ray sales. Data linked by movie name, release year, person name & birthday</li>
</ol>



## Methods

 This project uses descriptive analysis, with description of trends over time. This provides the opportunity to analyze the movie industry in a manner that shows relationships between factors including: Sales, Profitability, Costs, Genre, People, Studio, Critics, and more. Our data was collected and summarized primarily through downloading, scraping, cleaning & linking via provided or
created keys.


## Results

The most profitable genres are Adventure, Sci-Fi, and Animation.

![Movie_Genres](./images/stay_lengths_by_type.png)


The most profitable Action and Adventure movies contain between three and seven  “A Players,” thus demonstrating the strong correlation between “A Player” presence, and profitability. Many of the most profitable films in the other genres have no more than two “A Players” and therefore, do not require these figures to make a profitable film.


![A_Players](/images/A_Players.png)

Regardless of whether or not the popularity was a dislike or a like by either critics or audience, the greater the popularity, the greater the return on investment. Films that had fewer interactions had a lower return on investment.

![A_Players](/images/Critics_ROI.png)
![A_Players](/images/Critics_Popularity.png)

## Conclusions

This analysis leads to three recommendations for maximizing your next movie’s profitability:

- **Make a movie with elements of adventure, sci-fi, and animation.**  The most profitable film genres in the past 15 years are the above recommended genres. While some other films might have greater return on investment, the overall profits are highest with these three.
- **If pursuing an Adventure film, ensure your movie has at least three “A Players.”** The Bankability Index® shows that by including at least three high-profile actors, directors, producers, or screenwriters, your film is guaranteed to make a certain baseline revenue.
- **eFilmCritic.com, TimeOut, The Washington Post, The New York Times, and Entertainment Weekly are our five recommended film critic publications.**  Sending your film to them pre-release will benefit your movie’s profitability because they 1) post the largest number of reviews 2) are popular enough to be read by a wide audience 3) have a high positivity rate, making it more probable to receive a positive review.

### Next Steps

Further analyses could yield additional insights to substantiate future profit in the film industry.

- **Rightsize your budget and maximize return.** If you are working on a tighter budget, we can tailor your genre inquiry to identify the highest return on investment with your specific budget.
- **Model need for franchising.** We are able to further model the Bankability Index to parlay your next box office-busting movie into the next hit-franchise.
- **Predicting your next awards.** Given your genre choice, we can model critic success by genre and forecast your chances of winning film awards.

## For More Information

See the full analysis in the [Jupyter Notebooks](folder) or review our [presentation](insert pres pdf here).

For additional info, contact us here: [[Fennec C. Nightingale,](mailto:fenneccharles@gmail.com)[Matthew Lipman](mailto:matthew.lipman@wework.com) & [Russell Pihlstrom](mailto:rgpihlstrom@yahoo.com)


## Repository Structure

```
├── code
│   ├── notebooks??
│   ├── notebooks??
│   ├── notebooks.??
│   └── notebooks.??
├── other stuff?
├── images
├── __init__.py
├── README.md
├── Animal_Shelter_Needs_Presentation.pdf
└── animal_shelter_needs_analysis.ipynb
