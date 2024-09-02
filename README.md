# Blog App Backend (Strapi)

This is the backend API for a simple blog app, built with Strapi. It provides APIs to list and display blogs with a title, content, and image.

## Features
- Blog articles with title, content, and image
- API to list all blogs
- API to fetch a single blog by ID

## API Endpoints

1. **Get all blogs**:
    ```bash
    GET /api/articles?populate=Image

2. **Get a single blog by ID**:
    ```bash
    GET /api/articles/${id}?populate=Image

## Frontend Integration

1. **List Blogs**: Fetch and display all blog titles on one page.
2. **Display Blog**: Fetch and show full content and image of a selected blog on another page.

## Tech Stack
- **Strapi**: Headless CMS for API generation
- **PostgreSQL**: Database
- **Yarn**: Package manager

## Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/iGauravSingh/strapi-blog-host.git

2. Install dependencies:
    ```bash
    yarn install

3. Run the Strapi server:
    ```bash
    yarn develop