# Jay-Mark Gallardo | Portfolio Website

A personal portfolio website for a UI/UX designer and DevOps student. It introduces me, shows the projects I work on, my seminar certificates, and my experience, and lets visitors send me a message.

**Live site:** https://github.com/Jaymarkui

**My Portfolio** https://jaymarkui.github.io/Jay-Mark-Portfolio/

## About me

Hi, I'm Jay-Mark Gallardo, a 4th year BSCOE student at ICCT Colleges. I'm a UI/UX designer who also works in DevOps.

## Features

- Animated space background with stars, meteors, a satellite, and a spaceship that keep passing while you scroll
- Text that appears letter by letter as you scroll
- Project cards with photo galleries: tap a project photo to see all of its pictures
- Seminar certificates that open larger when tapped
- Experience section showing the projects I made, the year, and the school
- Skills section with tilt and glow effects
- Message form where visitors send their name, email, and message
- Works on phones, tablets, and computers

## Projects

| Project | Year | Description |
| --- | --- | --- |
| Library Management | 2024 | A library management system for keeping track of books and records. |
| AlertNet PH | 2025 | A disaster and risk management system, made with my group, where people see alerts for incoming disasters and find emergency contacts and preparedness tips. |

Both were made for study at ICCT Colleges in Cainta.

## Seminar certificates

- Advancing Secure Networking for Smart Environment
- Bioinformatics and Digital Science Information in the Philippine Context
- Advancing Research and Development in IoT for Smart Environments

## Skills

HTML, CSS, Java, and NetBeans.

## Built with

- HTML
- CSS
- JavaScript
- Hosted on GitHub Pages

## Project structure

```
index.html                                 The whole website (HTML, CSS, and JavaScript)
Messenger_creation_7086332242879336292.jpeg  My portrait
LibraryManagement.jpg                      Library Management photo
received_1122719289943840.jpeg             AlertNet PH photo
received_842425114810148.jpeg              AlertNet PH photo
Screenshot_20261019-004029.jpg             Seminar certificate
Screenshot_20261019-004009.jpg             Seminar certificate
Screenshot_20261019-003948.jpg             Seminar certificate
README.md                                  This file
```

## How to run it on my computer

1. Download or clone this repository.
2. Open `index.html` in a web browser.

## How to put it online with GitHub Pages

1. Go to the repository's **Settings**, then **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the `main` branch and the `/ (root)` folder, then save.
4. Wait 1 to 2 minutes, then open the link GitHub shows.

## How to update it

- **Add project pictures:** upload the pictures to the repository, then add their file names to that project's `data-gallery` list in `index.html`.
- **Add a certificate:** upload the picture, then copy one `<figure class="cert rv">` block in `index.html` and change the file name and the title.
- **Add a repository link:** in `index.html`, replace `href="#"` under a project with the link to the code files.
- **Message form:** create a free form at [formspree.io](https://formspree.io) and paste its link into `FORM_ENDPOINT` in the script. Without it, the form opens the visitor's email app instead.

## Contact

- GitHub: https://github.com/Jaymarkui
- LinkedIn: https://www.linkedin.com/in/jay-mark-gallardo-b8ab4a444
- Email: justinemaeallen28@gmail.com
