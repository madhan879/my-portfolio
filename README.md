# Personal Portfolio Website

This project is a static personal portfolio built with HTML and CSS. It includes sections for:

- About Me
- Education
- Skills
- Projects
- Contact information

## Local preview

Open the project in a browser or run a local static server:

```bash
cd /workspaces/my-portfolio
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## AWS Amplify deployment

This project is compatible with Amplify Hosting for a static site.

- Build command: `npm install` (not required for plain HTML/CSS, but keep the app static)
- Publish directory: `.`
- Root directory: `/`

The repository is configured to work with Amplify using the included `amplify.yml` file.
