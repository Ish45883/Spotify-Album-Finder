#  Spotify Album Finder

A sleek and responsive web application that allows users to search for musical artists and explore their albums using the Spotify Web API. Built with React, Vite, and React-Bootstrap.

---

## Overview

Spotify Album Finder offers users a simple interface to:

*  Search for artists in real time
* Browse and view their complete discography
* Access album details with direct links to Spotify

Designed with modern frontend technologies and seamless API integration to deliver an intuitive music discovery experience.

---

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


THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT OR ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


---

## Appendix

* [Spotify for Developers](https://developer.spotify.com/)
* [React Bootstrap](https://react-bootstrap.github.io/)
