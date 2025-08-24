# acupunctureinthevillage.com

This project is a Grav CMS website, configured to run in a Lando (Docker-based) local development environment.

## Prerequisites

- [Lando](https://docs.lando.dev/basics/installation.html) installed on your machine
- [Git](https://git-scm.com/) installed

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd acupunctureinthevillage.com
   ```

2. **Start the Lando environment:**
   ```bash
   lando start
   ```

3. **Install PHP dependencies with Composer:**
   ```bash
   lando composer install
   ```

4. **Install Grav dependencies:**
   ```bash
   lando grav install
   ```

5. **Access the site:**
   - Visit the URL provided by Lando (usually http://acupunctureinthevillage.lndo.site).

## Useful Lando Commands

- `lando start` — Start the development environment
- `lando stop` — Stop the environment
- `lando composer` — Run Composer commands inside the container
- `lando grav` — Run Grav CLI commands (e.g., `lando grav clear-cache`)

## Project Structure

- `web/` — Web root for Grav CMS
- `.lando.yml` — Lando configuration

---

Feel free to add more sections as needed (e.g., deployment, contributing, troubleshooting).
