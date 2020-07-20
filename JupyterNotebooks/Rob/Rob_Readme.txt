#Rob's Juptyter Notebook & Resource Files

For CovidTracking API, there is no unique key required. If you want to pull the data from the site, use code below:

    url = "https://covidtracking.com/data/v/api/v1/states/daily.json
    response = requests.get(url).json()
    
    this will update daily with new data from the site. keep in mind during analysis & takeaways

For CovidTracking API Header/Column Reference, follow link below:

    https://covidtracking.com/data/api

