# Anime Big Data Analysis kuru kuru~
![](./docs/wall.jpg)
## 0. Introduction
This is a project to analyze anime data from MyAnimeList. The data is crawl from MyAnimeList using BeautifulSoup. There are 27400 anime data in the csv file, it extracts details for each anime:
- `animeID`
- `title`
- `type`
- `number of episodes`
- `Aired Start`
- `Aired End`
- `number of members`
- `score`

## 1. Setup Environment
```
python3 -m venv venv
source venv/bin/activate
```

## 2. Install Requirements
```
pip install -r requirements.txt
```

## 3. Run
```
python3 chaialime.py
```

> NOTE: I just wonder why Boku no Pico has such bad scores ?
> ``` csv
> 1639,Boku no Pico,OVA,1,Sep 2006,Sep 2006,182442,4.22
> ```
> Hmm 🤔