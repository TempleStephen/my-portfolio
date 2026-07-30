# Temple Stephen — Portfolio Website

A personal portfolio site built and deployed as a hands-on cloud/DevOps exercise — not just hosted, but manually provisioned, configured, and served from a live EC2 instance.

---

## 🔗 Live Site

| Environment | URL |
|---|---|
| EC2 (primary) | [http://52.44.142.73](http://52.44.142.73) |
| Cloudflare (edge) | [still-cake-4c67.temple-stephen100.workers.dev](https://still-cake-4c67.temple-stephen100.workers.dev) |

---

## Why This Project Exists

This isn't a portfolio spun up on a managed hosting platform — it's deployed the way a cloud engineer would set up a real server from scratch. The goal was to get hands-on with the fundamentals that sit underneath most "one-click deploy" services:

- Present my work publicly, on infrastructure I configured myself
- Practice deploying and serving a site on a real, self-managed server
- Learn `nginx` setup and configuration on Amazon EC2
- Explore webhook-based deployment workflows
- Build comfort debugging real production issues — not just local ones

---

## Tech Stack

| Layer | Tool |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Web Server | Nginx |
| Hosting | Amazon EC2 |
| Version Control | Git & GitHub |
| Tunneling / Webhooks | ngrok |

---

## Deployment Setup

The site is served directly from an EC2 instance running nginx as the web server.

### Server Details

| Item | Value |
|---|---|
| OS | Amazon Linux 2023 |
| Web Server | nginx |
| Public IP | `52.44.142.73` |

### Nginx Web Root

Site files are served from the default nginx web root:

\`\`\`bash
/usr/share/nginx/html/index.html
\`\`\`

---

## Author

**Temple Stephen**
Cloud & DevOps Engineer | AWS Certified Solutions Architect – Associate

- GitHub: [github.com/TempleStephen](https://github.com/TempleStephen)
- LinkedIn: [linkedin.com/in/temple-stephen-74664a1b3](https://linkedin.com/in/temple-stephen-74664a1b3/)
