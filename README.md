# Welcome 👋

This repository contains information about our onboarding processes.

To ensure a seamless onboarding experience, please follow these steps:

1.  Install Keybase to communicate with us and ask questions (find more information in the communicationPlatforms document).
2.  Familiarize yourself with the basic workflow of GitHub by completing the tasks outlined in the legalMatters document.
3.  <!--# others steps to complete -->
4.  Feel free to explore the repository, and if you have any questions, don't hesitate to reach out!

## Ignored files in .gitignore
We place a list of folders and files that are ignored for synchronization from the user’s client computer to Github and beyond.  These are usually passwords, login credentials, project management or log files used by your IDE or other work environment.We by default, excluded all Posit/RStudio standards, and usually all Jupiter Notebook standards, and a few Windows/Mac specific files.
We also ignore a standard folder called `not_included`,  which serves as the place of your personal scrapbook, sandbox, that you do not want to share with anybody.

# Folders

`Folders` appear like this in this repository.

We have two data folders:

`data-raw`: Raw, unprocessed data, as received, downloaded, collected

`data`: This folder contains the processed data or our outputs.

We save visualizations in folders corresponding to the file format.

`png`: contains visualizations in Portable Network Graphics format (our preferred format.)

`jpg`: Contains visualizations in Joint Photographic Experts Group format.

`webp`: Contains visualizations in WebP format. We prefer this for content intended for web use (presentations, blogposts), because it works much faster and better with browsers than PNG or JPG.

<br>

`docs:` This folder contains output files created by Quatro.

`bib`: Contains all bibliography: used citations, data used, visualisation used, datasets created, visualizations created, public text document outputs created.

## Standard File Names

1.  Use only lowercase alphanumeric characters, hyphen (`-`), underscore (`_`).
2.  Instead of using space, use `-` between words and abbreviations.
3.  Use underscore `_` between shorthand descriptions, dates, and other semantically different parts of the filename.
4.  If you use dates in file names, use the `YYYYMMDD` standard.
5.  Use a subfolder for logically connected intermediary files.

For example:

`data-raw/places/atelier-hungary-places_2012_20230316.xlsx`

`data-raw/persons/atelier-hungary-photographers_2012_20230316.xlsx`

## Tidy data

Make all tables [tidy](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html).

-   Use only machine-readable and programmable variable names: variable names (columns) use `snake_case` or `lowerCamelCase`, without space, hyphen, and other special characters.
-   For row names, row identification, use only alphanumeric characters, for example, integer numbers, without `.` or any other character.

## Contributors

🌈 Contribution guidelines - you must abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) Code of Conduct.
