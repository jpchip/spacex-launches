# Space X Launches

This app shows a simple list of launches from Space X, pulled from their public API:

https://github.com/r-spacex/SpaceX-API/blob/master/docs/v4/README.md

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/spacex-launches)

## Tasks

We'd like you to fork this project and make some changes. Focus on the logic, don't worry so much about the layout/ui.

The launches component loads and displays all the launches in a table. We'd like it to:

  - Display name, flight number, and date for each launch
  - Sorted from newest to oldest (date_utc)
  - Filterable by Launchpads (ie. https://github.com/r-spacex/SpaceX-API/blob/master/docs/v4/launchpads/all.md)
 - Clicking on a launch opens a view (eg. new page, modal, you pick) that shows more about the launch. Specifically details, success, and links to presskit and webcast
