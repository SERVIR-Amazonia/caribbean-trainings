# Caribbean trainings page template

This repository is a template to set up a website on [`github-pages`](https://pages.github.com/) that hosts all the content (step-by-step instructions, slides, code, recordings, photos, etc) for training workshops.

:construction: Under Construction :construction:

:construction: Everything below this line is under construction and not final :construction:

## Configuration

The repository is configured according to the following structure:

```
repository (caribbean-trainings)
├── config.yml
├── README.md
├── index.md
├── _includes
│   ├── head_custom.html
│   ├── head.html
├── lesson1/day1 ("intro-to-gis")
│   ├── lesson1/day1.md ("intro-to-gis.md")
│   ├── introduction.md
│   ├── topic1.md
│   ├── topic2.md
│   ├── .....
├── lesson2/day2 ("intro-to-remote-sensing")
│   ├── lesson1/day1.md ("intro-to-remote-sensing.md")
│   ├── introduction.md
│   ├── topic1.md
│   ├── topic2.md
│   ├── .....
├── ..... (other lessons/days)
├── images
│   ├── lesson1/day1-images ("intro-to-remote-sensing-images")
│   │   ├── file.png ("reflected-energy-radiation.png")
│   │   ├── .....
│   ├── lesson2/day2-images
│   │   ├── .....
├── partners
├── resources
└── photos
```

## Setup Instructions

### Using this template

1. Click on `Use this template` and then `Create new repository` to create a new repository for your workshop. Select the location, name, and description of the repository as you desire.

<img align="center" src="./images/use-this-template.png"  vspace="10" width="800">

Alternative: If you are a member of the SERVIR-Amazonia repository, you can select it directly when creating a new repository:

<img align="center" src="./images/new-repo.png"  vspace="10" width="800">

<img align="center" src="./images/repo-template.png"  vspace="10" width="800">

### Setting up the github-page

1. To set up the `github-pages`, in your new repository, go to `Settings` and then `Pages`. Select the branch you want to use for the website. Usually it is `main`.

<img align="center" src="./images/pages.png"  vspace="10" width="800">

2. Then, hit `Save`.

<img align="center" src="./images/page-save.png"  vspace="10" width="400">

3. Go back to your repository's main page, and click on the gear icon next to `About` on the right side.

<img align="center" src="./images/about.png"  vspace="10" width="800">

4. Under `Website`, check the option "Use your GitHub Pages website" and click on `Save changes`. Now you can see the URL on the repository's main page.

<img align="center" src="./images/page-website.png"  vspace="10" width="600">

<img align="center" src="./images/page-url.png"  vspace="10" width="800">

5. Open it to see how it looks like at this first moment. It will look like the `caribbean-trainings` page.

<img align="center" src="./images/page-open.png"  vspace="10" width="800">

The following changes will reflect how your github page looks like.

### Customizing the repository to your training

2. Update the `README.md` file with the description of your repository.

3. config.yml

3. Got to the `index.md` file and update it according to your country or title of workshop/training.

<img align="center" src="./images/index-country-name.png"  vspace="10" width="800">

<img align="center" src="./images/index-country-name-githubpages.png"  vspace="10" width="800">

4. In the `index.md` file, The `Questions`, `Feedback`, and `Workshop Recordings` sections are buttons that link into specific Google Forms or Drive folders. Update the URLs appropriately.

e.g.: `[Give Feedback](https://forms.gle/8Jdm1aybL9sqzNEw6){: .btn .btn-purple }`

5. You can use the [Tables Generator](https://www.tablesgenerator.com/markdown_tables) to update the workshop `Agenda` in the `index.md` file: 

<img align="center" src="./images/agenda-raw.png"  vspace="10" width="800">

<img align="center" src="./images/agenda-githubpages.png"  vspace="10" width="800">

