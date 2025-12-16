# NextJS + MySQL DevOps Interview Tasks

This assessment is simple: complete the items below and share the resulting links. No how-to details are provided—just deliver the outcomes.

## Tasks to complete
1. Fork this repository to your GitHub profile and keep it public.
2. Create a Dockerfile to run the project.
3. Create `docker-compose.yml` with the app and a MySQL database.
4. Set up a GitHub Actions CI/CD pipeline that builds the web app image and pushes it to Docker Hub or GitHub Container Registry.
5. Document what you implemented.
6. Provide your public repository link and the published Docker image link(s).

## Build targets
- Node.js version: 18.x (use the same in Dockerfile, compose, and CI).
- Next.js build commands:
  ```bash
  npm ci
  npm run build
  npm run start
  ```
  (Use `npm install` locally if you are not in CI.)

## Links to provide (fill in after completion)
- Public fork: https://github.com/YOUR_USERNAME/nextjs-mysql-devops-test
- Published image: docker.io/YOUR_USERNAME/nextjs-mysql-devops-test:latest (or ghcr.io/YOUR_USERNAME/nextjs-mysql-devops-test:latest)
- Optional: Latest CI/CD run URL

## Final submission
Email the following to support@weblankan.com with CC to manager@weblankan.com:
- Link to your public fork.
- Link to the built Docker Hub (or GHCR) image.
- Screenshot of a successful GitHub Actions run.
- Screenshot of the running web app UI.
