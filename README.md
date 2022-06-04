# Translation Service from English to East-Slavic and Russian, and back.

### Setup instructions
This assumes you have Docker installed.

1. Ensure the docker deamon is running.
2. Download the `models.zip` from [here](https://www.dropbox.com/s/jmiwnwzp242z3qt/models.zip?dl=0) and copy the zip into the `translation` folder. Unzip the file. Now there should be a `models` folder, with `en-ukr`, `en-rus`, `rus-en` and `ukr-en` subfolders, inside the `translation` folder.
3. Open a command prompt / terminal, and then open up the `translation` sub-directory.
4. Run `docker-compose up --build` in this directory.
5. Navigate to `localhost:8889` to view the UI.

### Verifying `models.zip`
These will need to be run in a command prompt / terminal.

On a Mac, you can calculate the SHA256 checksum of the `models.zip` by running `shasum -a 256 translation/models.zip`. On Windows, `certutil -hashfile translation/models.zip sha256`.

You would expect the following SHA256 checksum: `bf963b5221803a011411258fb63abd145cb6c41cb36c27df218ec90f3d9ca86f`.

### Getting started
Entire the source text on the left and visualise the translations on the right.

<img width="872" alt="Screenshot 2022-06-04 at 14 43 12" src="https://user-images.githubusercontent.com/20817781/172003388-622b1d28-f7b4-4f82-8efb-670c0402dd07.png">

Empty lines cannot be translated, and no result will be returned.

<img width="877" alt="image" src="https://user-images.githubusercontent.com/20817781/172003437-8653d24e-f9fc-48d4-9fb7-c9a488a7e3ac.png">

