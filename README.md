# mi349-lab-samuel-hoyt

A small, static personal website created for the MI 349 lab. The page introduces Samuel, shares favorite things and goals, and includes a link to Michigan State University's website.

## What's Included

- A simple welcome header with an MSU-inspired message
- An "About Me" section
- Favorite colors, sport, and animal
- A numbered list of personal goals
- A campus photo section with accessible alt text
- A link to [Michigan State University](https://msu.edu)

## Run Locally

No build tools or dependencies are required. Open `index.html` directly in a browser, or start a local server from the project directory:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Project Structure

```text
.
├── index.html   # Page structure and content
├── image.jpg    # Campus image used by the page
└── README.md    # Project documentation
```

Add `image.jpg` to the project root for the campus image to display correctly. If the image is unavailable, the provided alt text still describes its purpose to visitors using assistive technology.

## Deployment

Because this is a static site, it can be hosted by any static web host. Deploy the project root and make sure `index.html` and `image.jpg` are uploaded together. Netlify, GitHub Pages, and similar services can serve it without a build command.
