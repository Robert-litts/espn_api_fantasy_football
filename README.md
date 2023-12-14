# Accessing Historical ESPN Fantasy Football League Data via V3 API
I'm part of a fantasy football league that began in 2013 using ESPN's Fantasy Football system. In 2021, we transitioned the league to Sleeper but wanted to keep the historical data.
ESPN provides no ability to export historical data, and Sleeper provides no ability to import historical data either. An [ESPN API](https://github.com/cwendt94/espn-api) Python module was developed to interact with ESPN's very poorly documented API. In 2019, ESPN upgraded the API without much public notice. Discussion such as [this](https://www.reddit.com/r/fantasyfootball/comments/56u8bc/espn_fantasy_football_api_wrapper_for_python_3/) have been insightful in writing several Python modules which allow for interaction with the JSON formatted data. 

This repository is used to document my utilization of the [ESPN API](https://github.com/cwendt94/espn-api) python library to format almost 10 years of historical fantasy football data in case it is ever deleted by ESPN. 

# Important Data I'm Looking to Extract
- Final Rankings
- Weekly Matchup Results
- Draft results
- Metrics on points scored (for/against)
