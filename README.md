# NetMAPPER

## Definition

Create a web interface for the CLI tool `nmap`.

- Using the official documentation ([https://nmap.org/book/man-briefoptions.html]), **implement at least one scan option** (e.g `-sS`, `-sV`, etc.) **and at least 3 options** (e.g `--max-retries`, `--host-timeout`, etc.);
- You have to store the results of each query in a database;
- You have to use MongoDB as your database engine and Mongoose.js;
- Your interface should present at least 3 pages:
  - the query interface (a form);
  - the history page (a list of all past queries);
  - the details of a past query, showing the output of a `nmap` for a previous query’s result stored in the database, but also all the option used for that query in the query form;
- You can use any framework or source code from the lessons;
- You can either do a synchronous API, or an asynchronous one;
- But in both case, you will have to process all queries regardless of the frontend (i.e if the user leaves the query page, the query should not be aborted on the backend side, as well as all information should be store properly in the database);
- _BONUS_: handle users (sign-up/sign-in) and handle access to queries according to users (i.e a user can only access to his own queries).

## Scoring and delivery

- code quality:
  - your code **must be** linted and properly formatted using tools seen during the lessons;
  - all best practice seen during the lessons;
- you will deliver your code in a zip file uploaded on Pepal **and** on GitHub (link should be in a `README.md` file at the root of the project) **without** ignored/temporary/sensitive files;
- any missing feature or improper code will diminish your final score;
- you have until May 21st, 2023 11:59:59 PM to upload your delivery.

To help you, here is a piece of documentation from NodeJS official website: [https://nodejs.org/dist/latest-v19.x/docs/api/child\_process.html#child\_processspawncommand-args-options]
