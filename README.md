# Class-Catcher
Application that allows a user to pull information about courses offered at BU and add them to their Google calendar based on distance and commute length from their address.
## Presentation Recording
[Presentation Recording](https://youtube.com)

## Tech Stack
- Front-end: TypeScript, React, NextJS
- Back-end: Python, Flask, BeautifulSoup
- Database: SQLite, SQLAlchemy ORM
- External APIs: Google Maps API, Google Calendar API


## Important Files
- [textbox.tsx](class-catcher-frontend/textbox.tsx) - 
- [login.tsx](class-catcher-frontend/login.tsx) - 
- [layout.tsx](class-catcher-frontend/layout.tsx) - 
- [server.py](class-catcher-backend/server.py) - API endpoints, database, makes calls to APIs
- [google_maps.py](class-catcher-backend/google_maps.py) - Searches class and addresses in data/ CSVs, calls Google Maps API
- [google_calendar.py](class-catcher-backend/google_calendar.py) - Handles the authentication into Google Maps, calls Google Maps API
- [class_info_scraper.py](class-catcher-backend/class_info_scraper.py) - Scrapes course information from the BU website
