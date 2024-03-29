![Untitled drawing](https://github.com/Theobragstad/MySports/assets/48075045/ed35bf49-e163-46a5-8037-14189f25f8db)

MySports is a comprehensive and easy to use web app for the participation in and management of intramural/club/recreational sports, especially for intramural college teams. It provides players with a way to manage, explore, and stay up-to-date with their games, teams, other players, and more.
____
It was developed in large part by myself as a member of a small team. The project was intended to simulate a real-world project following professional methodology and practices with extensive documentation, use of Git/GitHub for version control/project management, pull requests, standup meetings, testing, and presentation/deliverables.  

____

https://github.com/Theobragstad/MySports/assets/48075045/f12d5d96-7564-482e-ba4c-069db4e78bd3

_____
### Stack: 
- Frontend: EJS, HTML, CSS, Bootstrap
- Backend: JavaScript (Node.js, Express)
- Database: PostgreSQL
- Container: Docker

____

### Primary Features:
- Login or register account, log out
- Reset password if forgotten
- View and edit profile
- Change password
- View upcoming games with three filter types
  - View date, time, location, and more for each game
 - Create and join teams for a sport
 - Explore sports and teams
 - View your teams
 - View all players and player profiles
  - Search players by multiple fields (class year, username, name, player ID, sport, team, gender)
  - Connect with players by phone number on their profile
 - Admin users can schedule new games

____

### How to run locally: 
- Download and open Docker Desktop
- Open or clone repository and navigate to `project-code` directory
- Note that the `.env` file is included in the repo so you can try it yourself, but the email credentials are fake so the password reset feature will not work.
- Run `docker compose up`
- Go to `localhost:3000` in a browser

____

### Future improvements: 
Given a four week timeline, we had to prioritize the most important features to include.   
There are many other features we could have included to make the app even better, and would implement if we decided to deploy the app officially.  

- [ ] Edit or delete teams, games, players
- [ ] Admin account mode
- [ ] Add sport button
- [ ] Export games to calendar
- [ ] Server-side hosting of user media
- [ ] Message/announcement system
- [ ] Support for photos/images of games and teams
- [ ] Option to add team photo
- [ ] Dark mode
- [ ] Manually set team captain
- [ ] Remove player options
- [ ] Scheduling algorithm
- [ ] Leagues or divisions for teams
- [ ] Team/player ranking system
- [ ] Text or email notifications for games and other information
- [ ] Player availability form for scheduling
- [ ] Advanced filtering for games, players, and more
- [ ] Search games, teams, and more
- [ ] Seasons for sports
- [ ] Mobile app
- [ ] Mobile web browser/cross-platform optimization and support
- [ ] Dynamic timezone rendering
- [ ] Automatic or improved game record keeping system
- [ ] Improved score/winner input for previous games
- [ ] Divisions by college or location
- [ ] Mark players as injured, reserve, starters, etc
- [ ] Teams: minimum, maximum number of players
- [ ] Page system when rendering a lot of data
- [ ] Better game sorting system
- [ ] Clickable team pages
- [ ] Tooltips for faster information access
- [ ] Improve server routing
- [ ] Utilize more external CSS and better design CSS structure/hierarchies
- [ ] Improve code readability and formatting
- [ ] Deploy
