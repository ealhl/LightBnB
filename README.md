# LightBnB
Lighthouse BnB is an app that will revolutionize the travel industry. It will allow homeowners to rent out their homes to people on vacation, creating an alternative to hotels and bed and breakfasts...There’s nothing else like it! Users can view property information, book reservations, view their reservations, and write reviews. We'll be creating the first ever application to do something like this and we will call it LighthouseBnB.

## Final Product

!["Screenshot of URLs Index page"](https://github.com/ealhl/LightBnB/blob/main/docs/Screenshot%202024-02-24%20at%2011.27.28%E2%80%AFPM.png)
!["Screenshot of URLs My Reservation page"](https://github.com/ealhl/LightBnB/blob/main/docs/Screenshot%202024-02-24%20at%2011.28.00%E2%80%AFPM.png)
!["Screenshot of URLs My Listing page"](https://github.com/ealhl/LightBnB/blob/main/docs/Screenshot%202024-02-24%20at%2011.28.06%E2%80%AFPM.png)

## Getting Started

1. [Create](https://github.com/ealhl/LightBnB.git) a new repository using this repository as a template.
2. Clone your repository onto your local device.
3. Install dependencies using the `npm install` command and cd to LightBnB_WebApp folder
4. Run psql to create your own db and update database.js pool info for your own db
5. Install schema using the `\i migrations/01_schema.sql` command.
6. Install 01 seeds file using the `\i seeds/01_seeds.sql` command.
7. Install 02 seeds file using the `\i seeds/02_seeds.sql` command.
3. Start the web server using the `npm run local` command. The app will be served at <http://localhost:3000/>.
4. Go to <http://localhost:3000/> in your browser.

## Dependencies
- bcrypt
- cookie-session
- express
- nodemon

