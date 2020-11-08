# Github Actions + Localazy

This project demonstrates how to fully automate software localization using [Localazy](https://localazy) and Github Actions. 

You can read [detailed blog post about how to setup automated localization for your project](https://localazy/blog/automated-localization-github-actions-localazy).

---

## Automated Localization

You have probably already heard of continuous localization. It's important as software development is a never-ending process, and with new features, you usually need to add new strings.

Fully automated localization is a level above it. As a developer, you only set up it once, and then, you can forget about it completely. 

And as we are going to use **[Github Actions](https://github.com/features/actions)**, it's gonna be fun!

---

## What's going on? 

Using Github Actions, on each commit touching it, the file `locales/en.json` is automatically uploaded to the [Localazy translation platform](https://localazy) where all the translations as well as translators, contributors and volunteers can be easily managed using beautiful UI.

Another Github action demonstrates how to download all localized strings when building the final release of the app. 

And as a bonus, **Localazy can translate your app to up to 80 languages for free** by sharing translations with other app. 

---

**[Read more in the blog post](https://localazy/blog/automated-localization-github-actions-localazy)**:

- How to set up project with Localazy as a localization solution

- How to ignore localizable files except for the source language and why you should

- How to store credentials using Github Secrets and how to use them with Github Actions

- How to automatically upload strings for localization whenever the source language file is changed

- How to download translated strings when building the release of your app

