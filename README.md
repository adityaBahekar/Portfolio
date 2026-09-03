# Aditya Bahekar | Full Stack Developer Portfolio

[![Built with HTML, CSS and JavaScript](https://img.shields.io/badge/built%20with-HTML%2C%20CSS%20%26%20JavaScript-2563eb)](https://developer.mozilla.org/en-US/docs/Web)
[![Deploy with GitHub Pages](https://img.shields.io/badge/deployed%20with-GitHub%20Pages-111827)](https://pages.github.com/)

Personal portfolio website for **Aditya Bahekar**, a Computer Science and Engineering student focused on full stack development with the MERN stack. The site presents my technical skills, selected projects, academic background, resume, and contact details in a responsive single-page experience.

## About the portfolio

The portfolio is designed to communicate how I approach building web applications across the stack. It highlights secure authentication, REST API design, database work, responsive interfaces, and practical deployment workflows.

## Highlights

- Terminal-inspired boot sequence and interactive command-line showcase.
- Responsive layout for mobile, tablet, and desktop screens.
- Scroll-reveal animations, active navigation, hover interactions, and cursor effects.
- Skills grouped by languages, frontend, backend, databases, security, and developer tooling.
- Selected projects with direct links to source code or a live demo.
- Downloadable resume and direct email, GitHub, and LinkedIn contact links.

## Selected projects

### Secure Auth and Session Management

Authentication backend built with Node.js, Express, MongoDB, Mongoose, and JWT. It includes access and refresh token rotation, multi-device sessions, RBAC, HTTP-only cookies, password hashing, protected routes, and centralized error handling.

[View the project on GitHub](https://github.com/adityaBahekar/secure-authentication-system)

### Globetrotter Travel Planning App

Responsive travel-planning application built with a four-member team during an eight-hour hackathon. The React frontend connects to Node.js and Express REST APIs backed by MongoDB.

[View the live demo](https://globe-trotter-swag9.vercel.app)

### Scalable URL Shortener API

REST API built with Node.js, Express, PostgreSQL, Redis, and Docker. Features include custom aliases, expiration, redirects, click analytics, validation, rate limiting, caching, and CI/CD support.

[View the project on GitHub](https://github.com/adityaBahekar/url-shortener)

## Technology

| Category | Tools |
| --- | --- |
| Languages | JavaScript (ES6+), HTML5, CSS3, Python, C, C++ |
| Frontend | React.js, Vite, responsive UI development |
| Backend | Node.js, Express.js, REST APIs, MVC |
| Databases | MongoDB, Mongoose, MySQL, PostgreSQL |
| Security | JWT, RBAC, HTTP-only cookies, CORS |
| Tools and DevOps | Git, GitHub, Docker, Redis, CI/CD, Postman |

## Run locally

This is a static website and does not require Node.js or a build step.

1. Clone the repository:

   ```bash
   git clone https://github.com/adityaBahekar/Portfolio.git
   cd Portfolio
   ```

2. Start a local static server. For example, with Python:

   ```bash
   python -m http.server 8000
   ```

3. Open `http://localhost:8000` in a browser.

Opening `index.html` directly also works for most content, but a local server is recommended for a more realistic preview.

## Project structure

```text
.
├── index.html                 # Portfolio markup, styles, and client-side behavior
├── aditya_pfp.png             # Profile image
├── aditya_img.png             # About-section image
├── Aditya_Bahekar_Resume.pdf  # Downloadable resume
└── .github/workflows/static.yml # GitHub Pages deployment workflow
```

## Deployment

The repository includes a GitHub Actions workflow for GitHub Pages. To deploy your own copy:

1. Push the repository to GitHub.
2. In the repository settings, open **Pages** and select **GitHub Actions** as the source.
3. Push changes to `main`; the workflow will publish the static site.

Before publishing, update the personal links, metadata, project URLs, images, and resume in `index.html` to match your own profile.

## Contact

- GitHub: [@adityaBahekar](https://github.com/adityaBahekar)
- LinkedIn: [adityabahekar](https://www.linkedin.com/in/adityabahekar)
- Email: [adityabahekar84@gmail.com](mailto:adityabahekar84@gmail.com)

## License

This project is available for personal and educational reference. Contact me before reusing personal images, resume content, or profile information.
