# mi349-lab-samuel-hoyt

A small, static personal website created for the MI 349 lab. The page introduces Samuel, shares favorite things and goals, and includes a link to Michigan State University's website.

This project is a Hello World page built with standard HTML5. It intentionally uses no CSS, so the content is presented with the browser's default styling.

## What's Included

- A simple welcome header with an MSU-inspired message
- An "About Me" section
- Favorite colors, sport, and animal
- A numbered list of personal goals
- A campus photo section with accessible alt text
- A link to [Michigan State University](https://msu.edu)
- HTML5 metadata for responsive behavior and page description

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

The included `image.jpg` must stay in the project root for the campus image to display correctly. If the image becomes unavailable, the provided alt text still describes its purpose to visitors using assistive technology.

Before publishing, confirm that the page loads at `http://localhost:8000` and that the campus image appears. Also test the MSU link and check that the page remains readable when the browser window is narrow.

## Lab Checklist

- `index.html` uses the HTML5 doctype and contains multiple elements inside `<body>`.
- The page uses semantic elements including `<header>`, `<main>`, `<section>`, `<nav>`, and `<footer>`.
- No CSS is used, as required by the lab.
- The repository history contains three or more meaningful commits documenting the work.
- The final site is deployed as a static Netlify site.

## Deployment

Because this is a static site, it can be hosted by any static web host. Deploy the project root and make sure `index.html` and `image.jpg` are uploaded together. Netlify, GitHub Pages, and similar services can serve it without a build command.

For a Netlify CLI deployment, run the following from the project root after authenticating with Netlify:

```bash
npx netlify deploy --prod --dir=.
```

When prompted for a site, select the existing site or create a new one. The published URL should be added to the submission links below.

## Submission Links

- GitHub repository: [Shoyt111/mi349-lab-samuel-hoyt](https://github.com/Shoyt111/mi349-lab-samuel-hoyt)
- Public Netlify site: add the final Netlify URL here after deployment
