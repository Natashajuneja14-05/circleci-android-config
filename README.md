# Circle CI Android Config
This is a sample config file for CircleCI for the Android Lovers :) Just use the simple steps below to get started with ease.

## How to use it
* Log In to Circle CI - Using Github Preferrably :)
* Click on add projects and set up.
* Select Linux Operating System, and leave Gradle as the language selected.
* Create a `.config` folder inside your project folder
* Create a `config.yaml` file inside the `.config` folder
* Commit and push changes to Github :)
* On the Circle CI dashboard, select step 5 `Start Building`. This will launch your project on CircleCI and make our webhooks listen for updates to your work.
* Continue building!

## Docker Image
Make sure to check if you have the latest Docker Image and replacing this line with the latest version :)

```yml
 docker:
      - image: circleci/android:api-24-node8-alpha #confirm the latest docker image :)
```

## Github Badge
Badges let you show the state of your documentation to your users. They are great for embedding in your README, or putting inside your actual doc pages.

To add the badge, use the following steps:
* Log In to Circle CI - Using Github Preferrably :)
* Go to your project setttings.
* Under Notifications, select Status Badges. 
* Choose branch which should be monitored.
* Copy the Markdown code, and paste it in your ReadMe File.

## Private Repo Badge
The badge does NOT WORK in a private repo without a CircleCI Token. Add it this way :
```yml
[![CircleCI](https://circleci.com/gh/<Github Username>/<RepoName>/tree/master.svg?style=shield&circle-token=<Token Here>)](https://circleci.com/gh/<Github Username>/<RepoName>/tree/master)
```

## Future Additions
* Generate an APK
* Possibly output the APK to Slack :)



