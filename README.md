# MERN Project Metro

An interactive landing page about **MERN stack projects ideas for job ready developers**, designed as a metro map. Instead of a plain list, learners ride four colour coded lines (Starter, Builder, Pro and Student) across twelve project stations, from a first notes app to a multi tenant workspace tool.

The colour palette is taken from the MERN logos: MongoDB green, Express white, React cyan and Node lime, set on a deep navy background.

## What is inside

- **Animated request flow** showing how MongoDB, Express, React and Node pass a request along, with tappable stations that explain each tool in plain words.
- **Project roulette** that spins through the ideas and picks your next build, with a button that jumps to its card on the map.
- **Project map** with twelve project cards, line filters, time estimates, skill tags and a "Mark built" toggle. Progress is saved in the browser with localStorage.
- **Resume lab** that turns a finished project into a clear, copy ready resume line.
- **Resources section** with course, bootcamp and blog cards, all fully clickable.
- **Quick answers** FAQ written for search and AI answer engines.
- Responsive layout, sticky header, modern cards, footer, keyboard friendly focus states and reduced motion support.

## Project structure

```
mern-stack-projects-metro-map/
  index.html   (HTML, CSS and JavaScript in one file)
  README.md
```

There are no build steps and no dependencies. Fonts load from Google Fonts with safe system fallbacks.

## Run it locally

Open `index.html` in any modern browser, or serve the folder with a simple static server:

```
npx serve .
```

## Deploy with GitHub Pages

1. Push this repository to GitHub.
2. Open **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Your landing page goes live at `https://your-username.github.io/mern-stack-projects-metro-map/`.

## Links used in the page

Learning paths

- [MERN Stack Developer course in Delhi](https://www.justacademy.co/job-bootcamp-detail/delhi/mern-stack-developer-course-in-delhi-live-online-react-full-stack-product-development-training)
- [JavaScript training in Delhi](https://www.justacademy.co/course-detail/delhi/javascript-training-in-delhi)
- [Python training in Delhi](https://www.justacademy.co/course-detail/delhi/python-training-in-delhi)
- [Data Analytics bootcamp in Delhi](https://www.justacademy.co/job-bootcamp-detail/delhi/data-analytics-bootcamp-in-delhi-live-online-business-analytics-training)

Guides

- [MERN stack projects ideas for job ready developers](https://www.justacademy.co/blog-detail/mern-stack-projects-ideas-for-job-ready-developers)
- [MERN stack developer skills companies look for in 2026](https://www.justacademy.co/blog-detail/mern-stack-developer-skills-companies-look-for-in-2026)
- [MERN stack vs full stack Java in 2026](https://www.justacademy.co/blog-detail/mern-stack-vs-full-stack-java-which-career-path-is-better-in-2026)
- [MEAN stack development explained](https://www.justacademy.co/blog-detail/mean-stack-development-explained-angular-nodejs-mongodb-career-guide)

## Customise

- Edit the `P` array in the script to add, remove or rewrite project stations.
- Change the four colour variables at the top of the stylesheet (`--mongo2`, `--express`, `--react`, `--node`) to retheme the page.
- Update the `<title>` and meta tags in the head to match your own repository.

## Suggested repository topics

`mern-stack` `mern-projects` `full-stack-development` `javascript` `react` `nodejs` `mongodb` `expressjs` `portfolio-projects` `landing-page` `github-pages`

## License

Released for educational use. Reuse the design and code freely, and keep the learning resources linked above attributed to their owners.
