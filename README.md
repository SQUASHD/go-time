# go-time - a simple time-keeping application

> [!WARNING]  
> This is very much a work in progress I have no clue what I'm doing.

## Goals
* Automatic time-keeping based on user's (my) schedule
* Simple start and stop of new records outside of regular hours
    * Click the button, do the thing.
* Conflict handling
    * If a manually made record overlaps with regular hours, it should be flagged
    * Perhaps an option to automatically resolve overlaps
* Nice UI with HTMX
    * Keep everything on the server (for once)

### Optional
* Integrate with various APIs
    * Email - templates / sending
    * Geo tracking - get on location and start tracking automatically?
    * Document generation - maybe I'd like a CSV or spreadshet
* Dashboard with stats
* User registration
    * Right now I just want the app to work for me

### Learning Outcomes
* HTMX - so long js, and thanks for all the fish
* Go web server architecture - let's do some high-level stuff
* Integration testing - I don't want to mock 3 services and a repository
