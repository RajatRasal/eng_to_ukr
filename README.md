# English to East-Slavic translations

### Setup instructions
This assumes you have Docker installed.

1. Ensure the docker deamon is running.
2. Download the `models.zip` from [here](https://www.dropbox.com/sh/fksr6o34lhfhl9q/AAA0oOBEZR03jLtLdFrw2Tf2a?dl=0) and copy the zip into the `translation` folder. Unzip the file. Now there should be a `models` folder, with `en-ukr`, `en-rus`, `rus-en` and `ukr-en` subfolders,` inside the `translation` folder.
3. Open a command prompt / terminal, and then open up the `translation` sub-directory.
4. Run `docker-compose up` in this directory.
5. Navigate to `localhost:8889` to view the UI.
