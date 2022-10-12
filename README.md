# Flask app basic skeleton

This is a simple flask skeleton for any app.<br>
It has a simply basic structure to support the following items:<br>
- Flask controller
- MySQL database connection
- Configuration file via .yaml
- Controlled logging
- .env file for secure passwords handling
- repository/entity structure

In order to run this app you'll need to:
- Install the requirements with `pip install -r requirements.txt`
- Create a file named `.env` which will hold your environment variables
    ```
    DB_PASSWORD=
    ```
- If you'd like to run the app in beta/prod simply run the app with a `BETA | PROD` parameter at the end of the run script
