# optimus-tech-assessment

## Summary
We need to build a poll system for a one-time marketing campaign for English and French users.
User can input their email and select their favourite colours.
And then the result of everyone's poll will be presented.

### Requirement 1
Given a user open the link in the marketing campaign email, a page of campaign is shown.
Including:
 - a banner
 - a form
 - text input of user email
 - multi-select input of colours 

### Requirement 2
Given a user submitted the poll, the form is replaced by the poll result.
Each email can only submit poll once.
The result should show the number of total votes for each colour

### Instructions for Running the Code

#### Backend:

1. Open a new terminal and run the following commands from the root directory:
    ```bash
    yarn install
    yarn run start:api
    ```

#### Frontend:

1. Open a new terminal and run the following commands in root directory:
    ```bash
    cd frontend
    yarn install
    yarn proxy
    ```

2. Open another terminal and run following commands in root directory:
    ```bash
    cd frontend
    yarn start
    ```
