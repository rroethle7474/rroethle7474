# Ryan Roethle

## About Me
Full Stack Dev who uses both tabs and spaces (can't ever watch Silicon Valley enough). Love/hate relationship with vibe coding but understand that with expert knowledge the sky's the limit to where AI will take us. I think having solid fundamentals, proper structure, and repeatable processes that evolve over time (is that considered clean code practices, probably not), a code base made with the help of AI doesn't have to be a giant mess. (you'll see some of them currently in my repos...)

After a year long break, I decided to jump back into the developing wolrd and can't wait to do this for the rest of my life (or for as long as our AI overlords will let us). No real preference on what language I like best but I prefer to develop using .NET, Javascript, and Python.

I use Visual Studio, Visual Studio Code, Cursor, and Windfurf for creating a project (normally based on the size and language I'm using) and have a very good friend in Claude helping me along the way.

I feel that as long as a person has enthusiasm and a willingness to learn that life will never not give you an opportunity and I can't wait to use this wherever my programming journey takes me.

Feel free to browse some of the repo's I've been working on below for more details or review the readme docs associated with them. I've deployed some of them to Azure to refamiiarize myself again with the DevOps portion of the cloud world. None of them are currently production ready, but I do use them in my own daily life.


## What I'm working on Next (starting 3/25/25)
I'm starting a project to scrape mlb player prop bets from various sites and then allow me to "paper" bet along so I can track different betting strategies over the course of the baseball season. This fun project will allow me to test out different strategies and do real time back testing which will hopefully prepare me for my adventures in doing my own stock market trading.

The project will feature two seperate front ends.

1) React (to apply my knowledge that I'm gaining while going through Maximilian Schwarzmüller's wonderful book: https://www.amazon.com/React-Key-Concepts-depth-features/dp/183620227X/ref=tmm_pap_swatch_0)
The front end will be primarily used for displaying my progress and allowing the user to place fake bets.

2) .NET Front End allowing the user to create prop betting strategies and allowing for data uploads to backtest strategies. The purpose of making a seperate front end is to test how current .net 9 (whether razor pages or mvc) compares to front end frameworks like react and angular as I'm more familiar with creating API's with .NET. (I'm current using https://www.udemy.com/course/complete-aspnet-core-21-course/  from my favorite .NET teacher: Bhrugen Patel)

2 seperate back ends

1) Python Flask API: Used for web scraping and machine learning capabilities.

2) .NET API to retrieve results since I prefer using SQL and entity framework.


## Links: Live Demo Sites all full stack applications hosted in Azure
*Please note: For cost saving purposes all sites are run on Basic Tiers, performance may be slow especially on first page load. Full repo's can be found on my github page+

*Front End Demo for Landing Page (with links to below sites)*

https://mandry.software/

*Full Stack Web Applications (Front End, Backend, Database)*

https://www.dopaminedetoxtoday.com/

https://www.sillymonkeygifts.com/

https://www.jclleague.com/


## Skills & Technologies
- **Languages**: C#, Python, JavaScript, etc.
- **Frontend**: Angular, React, HTML/CSS, Razor Pages & MVC (professional work)
- **Backend**: .NET, Node.js, Flask, FastApi
- **Databases**: SQL, PostgreSQL, SQLite, ChromaDb
- **DevOps**: Azure DevOps, CI/CD, etc.
- **CMS**: Optimizely, ContentStack (Professional work)

## Featured Projects
Here are some highlighted projects that demonstrate my capabilities:

## C#, .NET Projects
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| SocialMediaDetoxAPI | API to support retrieving content from SQL db for the Social Media Detox app and sending email notifications through SendGrid | C#, .NET 8, Entity Framework/Identity, Auto Mapper, SendGrid Email |  [Link](https://github.com/rroethle7474/DopamineDetoxAPI) | |
| GiftAPI | A restful API to interact with GiftWeb | C#, .NET 8, Entity Framnework | [Link](https://github.com/rroethle7474/gift-api) | |
| StoryTimeComicBookApi | Brief description of what this project does | C#, .NET 7, PostgreSQL, Replicate, Entity Framnework | [Link](https://github.com/rroethle7474/StoryTimeComicBookApi) | |
| NewsFeedAPI | Very basic API to support retrieving articles from Yahoo, Google, and YouTube | C#, .NET 7, Swagger Rest API  | [Link](https://github.com/rroethle7474/JCLNewsFeedAPI) | |

## Azure Functions
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| SocialMediaDetox Function | Trigger and Timer functions available for populating data daily/weekly for Social Media Detox App with SignalR hub functions for notifications. | C#, .NET 8, SignalR |  [Link](https://github.com/rroethle7474/DopamineDetoxFunction) | |

## Angular Projects
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| Social Media Detox Web | A site used too display results from youtube and twitter/x based on desired topics and channels | Angular 17, Node.js, Bootstrap | [Link](https://github.com/rroethle7474/social-media-detox) | https://www.dopaminedetoxtoday.com/|
| Gift Application UI | A UI to use for family and friends to add what gifts they'd like for christmas or birthday | Angular 17, Node.js | [Link](https://github.com/rroethle7474/gift-web) | https://www.sillymonkeygifts.com/ |
| StoryTimeComicBook | A UI to walk a user through uploading image and audio to create their very own comic | Angular 17, Typescript, RxJS, Toastr | [Link](https://github.com/rroethle7474/comic-book-generator) | |
| Fantasy Baseball Keeper UI | UI to allow for spreadsheet uploads to send to API for proper parsing | Angular 17, Bootstrap, PapParse | [Link](https://github.com/rroethle7474/JCLKeepersUI) | |
| Prop Bet Monte Carlo UI | UI to display monte carlo simulation results for various betting scenarios | Angular 17 | [Link](https://github.com/rroethle7474/monte-carlo-simulator) | |

## React Projects
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| LearningTimeUI | A front end interface to upload urls for articles, youtube videos, and documents. | React 18, Tailwind, Vite | [Link](https://github.com/rroethle7474/MrALearningTime101/tree/main/knowledge-manager) | | 
| Landing Page | A mock landing page for what I would use if I were starting my own software company. | React 18, TailwindCSS 3, Vite | [Link](https://github.com/rroethle7474/mandry-software-landing-01) | https://mandry.software/ |
| Football Prediction UI | UI for displaying predicted NFL team stats per week as well as creating new models within Huggingface| React 18, NextJS, PapaParse | [Link](https://github.com/rroethle7474/football-prediction-model-web) | https://www.jclleague.com/ | 
| Fantasy Baseball Lineup Optimizer | UI for displaying optimized lineup results allowing for various other options with API | React 19, Tailwind CSS (v4), Vite, Axios| [Link](https://github.com/rroethle7474/fantasy-baseball-frontend) | | 
| Story Time Image Generation | A basic web app to create images based on descriptions from OpenAI. The inspiration to my comic book generation app | React 19, NodeJS, Express, Tailwind | [Link](https://github.com/rroethle7474/story-time-image-gen) | | 

### Javascript Projects
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| Base AI Chat Bot | Using OpenAI, provides a simple UI for chatting and keeping history with a LLM | Javascript, Bun, Prisma, Hono, Typescript | [Link](https://github.com/rroethle7474/ai-chat/tree/main/ai-chat) | |
| Auto Fantrax Auction Pauser | An extension for Chrome (using Tampermonkey to automatically pause our auction when we run it remotely ) | Javascript | [Link](https://github.com/rroethle7474/JCL-Auction-Pauser) | |
| Social Media Detox Site Blocker Chrome Extension| An extension for Chrome that redirects a user to my Social Media Detox Site | Javascript | [Link](https://github.com/rroethle7474/SocialMediaDetoxChromeExtension) | |


### Python Projects
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| SocialMediaRetrieverAPI | A Twitter/X scaper using Selenium and BeautifulSoup to return channels and posts based on search terms | Python, Selenium, Flask, BeautifulSoup4 | [Link](https://github.com/rroethle7474/social-media-detox-pythonapi) | |
| LearningTimeAPI | API to interact with LLM providers (via API) and parse article links, youtube videos, and uploaded documents to store in ChromaDb  | Python, ChromaDb, Playwright | [Link](https://github.com/rroethle7474/LearningTimeAPI-V1) | |
| Fantasy Baseball Lineup Optimizer API | Backend API using machine learning libraries to analyze uploaded spreadsheets and players to generate optimized lineups. | Python, Pandas, NumPy, SciPy, PuLP, Flask, SQLite Db | [Link](https://github.com/rroethle7474/fantasy-baseball-backend) | |
| Fantasy Baseball Keeper List Creator | Takes previous year's rosters and determines eligible keepers via CSV file uploads. | Python | [Link](https://github.com/rroethle7474/JCL2025-Roster) | |
| Prop Betting Monte Carlo API | API for creating monte carlo simulations based on different betting probabilities. | Python, Flask, BeautifulSoup, SQLAlchemy, NumPy | [Link](https://github.com/rroethle7474/PrizePicksMonteAPI) | |
| Football Prediction API | API for processing NFL team statistics | Python, HuggingFace, Azure Storage Containers| [Link](https://github.com/rroethle7474/football-prediction-model-api) | |
| PlayerAPI | API for retrieving MLB players statistics. | Python, FastApi, Pydantic | [Link](https://github.com/rroethle7474/football-prediction-model-api) | | | | 
| Raspberry Pi Media Player with Remote | A media player tied to a universal remote to automatically play tv shows for my Grandma. | Python, Linux, Raspberry Pi| [Link](https://github.com/rroethle7474/auto-remote-media-rasp-pi) | | 

### Database
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| ProjectDb | Combined DB for gift and ProjectDB (to save cost), hosted in Azure | SQL | [Link](https://github.com/rroethle7474/ProjectDb) | |
| ComicBookGenerator | Combined DB used for the comic book generations app using multiple schemas | PostgreSQL | [Link](https://github.com/rroethle7474/StoryTimeComicBookApi/tree/main/Data) | |

### Nuget Packages
| Project | Description | Tech Stack | GitHub Link | Site Link |
|---------|-------------|------------|-------------| ----------|
| DopamineDetox.Domain | Reusable domain model nuget package for use in Social Media Detox .NET projects | C#, .NET, Azure DevOps Nuget Feed | [Link](https://github.com/rroethle7474/DopamineDetox.Domain) | |
| DopamineDetox.ServiceAgent | Reusable Service Agent nuget package for use in Social Media Detox .NET projects | C#, .NET, Azure DevOps Nuget Feed | [Link](https://github.com/rroethle7474/DopamineDetox.ServiceAgent) |

## GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=rroethle7474&show_icons=true&theme=radical)

## Contact Me
- **Email**: rroethle@gmail.com
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/ryan-roethle-64293947/)
