# Turso Todo

A browser-based todo list backed by your own [Turso](https://turso.tech) (SQLite) database. Access and edit todos from anywhere with no server, everything runs client-side. Credentials are stored in `localStorage` only and never sent anywhere except the Turso HTTP API.

**Live app:** [ivomac.github.io/turso-todo](https://ivomac.github.io/turso-todo)

The app is a single-page vanilla JS application. It talks directly to the Turso HTTP API from the browser, issuing SQL statements to create tables and read/write rows.

## Features

- Multiple named todo lists (each is a SQLite table)
- Add, toggle, and delete todos
- Show/hide completed items
- Settings for database URL and auth token
- Deployed as a static GitHub Page

## Setup

1. Create a free account at [turso.tech](https://turso.tech)
2. Create a database
3. Create an auth token ([docs](https://docs.turso.tech/sdk/authentication))
4. Enter the database URL and token in the app's settings
