#  Spotify Album Finder by Ishan A

A sleek and responsive web application that allows users to search for musical artists and explore their albums using the Spotify Web API. Built with React, Vite, and React-Bootstrap.

---

## Overview

Spotify Album Finder offers users a simple interface to:

*  Search for artists in real time
* Browse and view their complete discography
* Access album details with direct links to Spotify

Designed with modern frontend technologies and seamless API integration to deliver an intuitive music discovery experience.

---
##Demo:
![Click this link](https://spotify-album-finder-topaz.vercel.app/)

## 🛠 Tech Stack

* **Frontend Framework**: React 18
* **Build Tool**: Vite
* **Styling & Layout**: React-Bootstrap
* **API Integration**: Spotify Web API (Client Credentials Flow)
* **Tooling**: ESLint, environment variables, modular component structure

---

##  Environment Variables

To access the Spotify Web API, you must create a `.env` file in the project root directory with the following variables:

```env
VITE_CLIENT_ID=your_spotify_client_id
VITE_CLIENT_SECRET=your_spotify_client_secret
```

> ⚠ **Important:** Do not share your `.env` file or commit it to version control. This file is listed in `.gitignore` to ensure credentials remain secure.

---

##  Dependencies (`node_modules`)

The `node_modules/` directory is excluded from the repository to keep it lightweight and maintainable. All necessary dependencies are declared in the `package.json` file.

To restore the required modules locally, users should run:

```bash
npm install
```

This will generate the `node_modules/` folder with all project dependencies.
Kindly run a dev env. to locally host the site:
```bash
npm run dev
```

---

##  License


the software is provided "as is", without warranty of any kind, express or
implied, including but not limited to the warranties of merchantability,
fitness for a particular purpose and noninfringement. in no event shall the
authors or copyright holders be liable for any claim, damages or other
liability, whether in an action of contract or arising from,
out of or in connection with the software or the use or other dealings in the
software.



---

## Appendix

* [Spotify for Developers](https://developer.spotify.com/)
* [React Bootstrap](https://react-bootstrap.github.io/)
* [OpenAI](chatgpt.com)
* [Codedex](https://www.codedex.io/)

This document was created using the assistance of OpenAI
