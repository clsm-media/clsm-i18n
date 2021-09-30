# clsm-i18n
Coliseum i18n repository

This repository stores the i18n locales files that we are going to import in the following projects:
* clsm-app
* clsm-mobile
* clsm-admin

# Instructions

Under the *locales* folder we are going to list all the folders with different languages (like 'us').
Each of this folder should present a *translation.json* file with the localization data.

# Considerations

In development you can fetch the i18n file using the URL provided by Github.
In production we will have to host the i18n files on some S3 or provide a logic to fetch from inside the project and build.