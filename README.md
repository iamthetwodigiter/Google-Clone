# Google Clone

## Made using Flutter

To run the app, you need to have a `Custom Search API Key` and a `Context Key`.

- `Custom Search API Key`
  - Go to [this site](https://console.cloud.google.com/) and create a project.
  - From the hamburger icon, go to API and Services and Enable API and Services.
  - You will be redirected to API Library Page. Search for Custom Search and enable it for the project.
  - Then again from the hamburger icon, go to same API and Services page and Credentials from left menu. Then Create Credentials and then create and API key.


- `Context Key`
  - Go to [this site](https://programmablesearchengine.google.com/controlpanel/create).
  - Enter any name for the search engine.
  - From *What to Search?* choose *Search the entire web* and leave all the other options be.
  - Then you will be given a html code with cx=________________. Whatever is after the *cx=* is your Context Key.

Copy both the keys and paste them in `lib/config/api_keys.dart` file.
