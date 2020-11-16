# Demo PHP Application
This is a demo PHP web application that utilizes blockonomics.co's api to automate bitcoin payments.

## Setup
- Make sure to import the *database.sql* file into your database
- Set your blockonomics api key in *config.php* and `$secretlocal=your_secret_code`  in *app/check/index.php*
- Do [blockonomics merchant](https://www.blockonomics.co/merchants) setup and Set the *HTTP Callback URL* to `domain.com/bitcoin/check.php?secret=your_secret_code`

