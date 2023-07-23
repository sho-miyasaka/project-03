# Japanese PM Kishida Prefers Refreshing at Chain Salons

## About this project
This is my submission as project 3 for [the Lede Program](https://ledeprogram.com) in 2023. The story webpage is here: [https://sho-miyasaka.github.io/project-03/](https://sho-miyasaka.github.io/project-03/)

In this project, I focused on how many young people are in politics. Some of European countries’ leaders, for example, have taken office in their 30s. In contrast, Japan's youngest prime minister in history is Prime Minister Shinzo Abe, who took office at the age of 52. If we look at the Japanese Diet, there is not a single member in his or her 20s now.

I thought I would compare data on how young people are in parliaments around the world. I also wanted to find out if the percentage of young parliamentarians varied by region and electoral system.

## Data collection and analysis
First, I collected data to show the situation in Japan. I scraped the list of members of the House of Representatives elected in the most recent 2021 general election. By comparing the data with UN population estimates, I show that there are few members of the House of Representatives in their 20s and 30s relative to the composition of the population.

Data from the Inter-Parliamentary Union is useful for making comparisons between countries around the world. I downloaded several datasets in csv format, two types of data: age group data and a list of electoral systems. I merged them into a single Pandas dataframe and looked at the relationship between regions and electoral systems and the proportion of young legislators.

|Data I Collected|Source|
|---|---|
|Data on age by countries|[Inter-Parliamentary Union](https://data.ipu.org/age-brackets/)|
|Parliamentary elections data|[Inter-Parliamentary Union](https://data.ipu.org/elections/)|
|Population by age group|[United Nations World Population Prospects 2022](https://population.un.org/wpp/)|
|Japan's 2021 general election results |[Ministry of Internal Affairs and Communications of Japan](https://www.soumu.go.jp/senkyo/senkyo_s/data/shugiin/index.html)|
|List of Members, House of Representatives of Japan|[House of Representatives of Japan](https://www.shugiin.go.jp/internet/itdb_annai.nsf/html/statics/syu/1giin.htm)|


I tried several new tools.
Using D3, I color-coded and visualized the age of the winners for the 2021 House of Representatives election results. It was the first time I used Flourish to create a graph. I also experimented with adding some elements as graphical annotations.

## Things I would've liked to do:
How to maintain diversity in parliaments is an important issue in many countries. Not only age groups, but also regional, ethnic, and gender perspectives are needed. This is not only a problem in Japan. Asian countries have fewer young members of parliament, and the U.S. also has fewer young members than Europe. I would like to use a larger data set for my analysis.
