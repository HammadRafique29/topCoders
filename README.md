## **Scraping Develpoers Data from TopCoders using Public API & Selnium.**

This script will extract data of developers data from TopCoders, including:
- Developer Skills
- Project Completions
- Total Project Submission.
- Badges Data.
- Current Working Place
- Eduction Details


### **Flow & Working of Code:**
 - Get Challenges:
    - Active Challenges [**Block-1**]
    - Past Challenges   [**Block-2**]
    - We are going to extract developers profiles from these challenges.
 - Get Developers RAW Data:
    - Provide the path of Challenges Json File [**Block-4**].
 - Get Developers Traits & Statictics:
    - RAW Developers Data File Used As Input [**Block-5**]
 - Convert the Developers Profiles Json into CSV:
    - Developers Profiles File Used As Input [**Block-6**]


## NSTALLATION:
- `pip install -r requirements.txt`


## Sample:

```markdown
```json

"kiwams": {
            "username": "kiwams",
            "rating": 1570,
            "track": "DEVELOP",
            "DEVELOP": {
                "challenges": 166,
                "wins": 1
            },
            "DESIGN": {
                "challenges": 49,
                "wins": 0
            },
            "DATA_SCIENCE": {
                "challenges": 0,
                "wins": 0
            },
            "work": [
                {
                    "timePeriodFrom": "2017-09-20T12:00:00.000Z",
                    "cityTown": "Accra",
                    "working": true,
                    "company": "A.T Trading",
                    "industry": "Tech & technology services",
                    "position": "Fullstack developer"
                },
                {
                    "timePeriodTo": "2020-08-31T11:00:00.000Z",
                    "timePeriodFrom": "2020-05-04T11:00:00.000Z",
                    "cityTown": "Remote",
                    "working": false,
                    "company": "Global Start-up Ecosystem",
                    "industry": "Finace",
                    "position": "Web Developer"
                },
                {
                    "timePeriodTo": "2017-08-30T11:00:00.000Z",
                    "timePeriodFrom": "2016-09-07T11:00:00.000Z",
                    "cityTown": "Berekum",
                    "working": false,
                    "company": "Holy Family Nursing Training College",
                    "industry": "Education",
                    "position": "Teaching Assistant"
                },
                {
                    "timePeriodTo": "2021-04-23T11:00:00.000Z",
                    "timePeriodFrom": "2018-02-05T12:00:00.000Z",
                    "cityTown": "Remote",
                    "working": false,
                    "company": "Kanku Media",
                    "industry": "Technology",
                    "position": "Content Manager"
                }
            ],
            "eduction": [
                {
                    "timePeriodTo": "2016-10-20T12:00:00.000Z",
                    "major": "Computer Science",
                    "timePeriodFrom": "2012-10-15T11:00:00.000Z",
                    "graduated": true,
                    "schoolCollegeName": "University For Development Studies"
                }
            ]
        }

```


