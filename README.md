Art Supplies Lending App

This project was developed as part of the Cataloging and Lending Apps (CLAs) initiative for CS 3240 at the University of Virginia. The goal of this CLA is to allow users to lend and borrow items from a shared collection — in our case, art supplies. Think of it as a community-powered "library" where users can organize, track, and lend out materials they don’t use every day, like brushes, paints, canvases, or other creative tools.

Core Features
- Catalog items with metadata like title, location, description, and status (e.g., checked in/out)
- Organize items into collections (e.g., a painting starter kit or a printmaking bundle)
- Search the library by keyword or title

Support for multiple user roles:
- Anonymous users can browse public collections
- Patrons can log in with Google, request to borrow items, rate and review
- Librarians can add/edit/delete items and approve lending requests
- Django Admins can manage system data through a separate admin panel

Tech Stack:
- Python 3, Django 5
- PostgreSQL (Heroku-hosted) for persistent data
- Amazon S3 for cloud file storage (e.g., item images)
- Heroku for deployment
- GitHub Actions for continuous integration
- Google OAuth for user login (Patrons & Librarians)

Roles and Contribution

I served as the Requirements Manager, responsible for leading the feature definition process and maintaining the GitHub issue tracker. I also actively contributed to the project’s backend and frontend development, including user flows, models, and system logic.
