# Japanese PM Kishida Prefers Refreshing at Chain Salons

## About this project
This is my submission as project 3 for [the Lede Program](https://ledeprogram.com) in 2023. The story webpage is here: [https://sho-miyasaka.github.io/project-03/](https://sho-miyasaka.github.io/project-03/)

In this project, I attempted to examine the personal grooming habits of three Japanese Prime Ministers using text data from Japanese news articles. Major Japanese media have diligently recorded the activity logs of successive PMs for many years, making this information a valuable "source" for uncovering insights into the realities of these leaders. Being a PM is undoubtedly one of the busiest jobs, with schedules planned down to the minute, making health management and appearance crucial aspects of their responsibilities. I looked at how each prime minister refreshes himself.

The current PM, Fumio Kishida, took office in October 2021. According to the data analysis, he has been getting a haircut at an average frequency of about once every two weeks since taking office. This is twice the frequency of his predecessors, Shinzo Abe and Yoshihide Suga. In addition, he frequently visits a salon specializing in "British-style reflexology" as well as a hair salon.

## Data collection and analysis
[The articles I used for this analysis](https://www.nikkei.com/theme/?dw=22041100) were from the Japanese newspaper Nikkei, which publishes details of the prime minister's activities on a daily basis, such as who he met, where, and at what time. I first attempted to scrape this data from the Nikkei website, then compiled and cleaned the text into a Pandas DataFrame that aggregated information for the three prime ministers over ten years.

With advice from my mentor, Simrann, I created column charts and heat maps to summarize the results.

|Data I Collected|Source|
|---|---|
|Articles on the Prime Minister's Activity Record|[Nikkei](https://www.nikkei.com/theme/?dw=22041100)|

## Things I would've liked to do:
I plan to apply the methods developed in this project to my future work. I focused on examining relatively readily available data on the personal care of prime ministers. However, I believe that this approach could be extended to study other aspects, such as the frequency of meetings with specific individuals or foreign visitation rates. 
The Japanese text's lack of word spacing and variety of characters made text analysis more difficult than in English. Nevertheless, I recognize the significance of this project for my work, and I intend to use the knowledge gained from this project to explore various text data analyses in languages such as Japanese and Chinese.
