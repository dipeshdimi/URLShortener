# URL Shortening Backend

This backend service provides URL shortening capabilities, allowing users to generate short links and retrieve analytics for their usage.

## Introduction

URL shortening is the process of converting long URLs into shorter, more manageable links. This backend service offers a scalable and efficient solution for URL shortening, providing features such as link generation and analytics tracking.

## Features

- Shorten long URLs to compact, user-friendly links.
- Retrieve original URLs from short links.
- Track analytics for link usage.
- Secure MongoDB integration for data storage.

## Usage

### API Endpoints

- `POST /url`: Shorten a long URL.
- `GET /:shortId`: Redirect to the original URL associated with the provided short ID.
- `GET /url/analytics/:shortId`: Retrieve statistics for a specific short ID.
