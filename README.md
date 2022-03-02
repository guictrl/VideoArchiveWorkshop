# VideoArchiveWorkshop

## About me

- I'm Adam, and got connected to LK through Em in Seattle
- I write image processing code for ultrasound machines at Philips Healthcare *(i.e. I'm familiar with code, but not with web development)
  ![](images/ultrasound.png)*
- I started making websites in October when Em told me her dream of having an online archive for all of LK's work
- [adamziel.today](https://adamziel.today)
### 💀DISCLAIMER!💀 I'm really new to this, so take everything with a grain of salt! These are just the things I've found that work best for me :)

## Agenda
1. [Tour of LK archive](#tour-of-lk-archive)
2. [Tour of LK archive design decisions + code + tools](#tour-of-tools)
3. [How to build a website from scratch](#building-a-website-from-scratch)

## Tour of LK archive
### Context
- Wanted a place to archive all the work that's been shown at in-person LK screenings over the years
- Experimental film libraries aren't super common, can be expensive to access

[www.linokinoarchive.com](https://www.linokinoarchive.com/)
![](images/lk-archive.png)

## Tour of tools

### Design decisions

#### Building from scratch vs. Wordpress, Wix etc.
- I wanted full freedom + control since I'm already familiar with coding
- Wanted to avoid cookie cutter WordPress look, fighting with templates, paid features etc.
- Wanted the archive to be aesthetically simple to provide a neutral backdrop that'd fit everyone's video. *I.e. focus on providing information, avoid window dressing*

#### Self-hosting videos vs. embedding from YouTube/Vimeo
- Again, this gives us more freedom (e.g. YouTube copyright + terms of service)

### Tools
| Tool     | Description | Cost |
| ----------- | ----------- | ----------- |
| [Visual Studio Code](https://code.visualstudio.com/download) | *The editor where I write all my code* | Free |
| [GitHub](https://github.com/)| *Where I host the raw source code (similar to collaborative Google Docs)* | Free |
| [Google Firebase Hosting](https://firebase.google.com/docs/hosting) | *The backend where I host the website on the internet* | Free tier |
| [Google Firestore Database](https://cloud.google.com/firestore) | *The backend where I host the content database (e.g. artist + film info)* | Free tier |
| [Google Cloud Storage](https://cloud.google.com/storage) | *Where I host the actual video content (as opposed to embedding YouTube/Vimeo videos)* | $1.76 |
| [Algolia Search](https://www.algolia.com/) | *The service I use for searching the database* | Free tier |
| | **Total** | $1.76 |

### Helpful learning resources
1. [Stack Overflow](https://stackoverflow.com/questions/114543/how-to-horizontally-center-an-element) - *The authoritative coding Q&A forum - usually the 1st site that will come up whenever you google a 'How do I do X?' coding question*
2. [W3School](https://www.w3schools.com/) - *Super clear tutorials for basic HTML, CSS, and Javascript stuff. It has really cool [Try it Yourself](https://www.w3schools.com/css/tryit.asp?filename=trycss_default) windows where you can live-edit sample code and then see what it does to the webpage in real-time

## Building a website from scratch
