# Personal Portfolio

A responsive, single-file portfolio site. The included profile details, links, and images are placeholders; replace them with your own before publishing.

## Edit your content

Open `index.html` in Codespaces and edit the `siteData` object near the top of its script:

- `name`, `role`, and `bio` set the introduction.
- `headshot` is the portrait image URL. Replace the temporary image with your own image URL, or add a photo to the project and use a relative path such as `assets/headshot.jpg`.
- `socials` contains the LinkedIn, Medium, and GitHub URLs.
- `projects`, `experience`, and `awards` are lists. Update each item's title, description, and link; project and experience items also have an image URL.

Add or remove list entries in the same object. The page renders each list from that data automatically. For a live preview in Codespaces, run `python3 -m http.server 8000` in the project directory, then open port 8000.
