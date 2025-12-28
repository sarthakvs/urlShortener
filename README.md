# UrlShortener
A simple and fast URL Shortener web application built using a microservice-style backend. It allows users to generate short URLs for long links and redirects them efficiently.
Built using Go, Node.js, Express, and PostgreSQL.
1. Go service handles URL creation (POST /shorten)
2. Node.js service handles fetching & redirecting (GET /urls, GET /:shortcode)
3. Frontend dynamically updates without page reload
4. Uses PostgreSQL for storage

![alt text](image.png)

Live link: https://shortify-3w0i.onrender.com

Key Features:
✅ Collision-Free: Implements a retry-loop logic in Go to ensure every short URL is 100% unique.
✅ Database Powered: Uses PostgreSQL for reliable data persistence.
✅ Dual-Service Architecture: Optimized for cloud deployment on Render.
✅ Responsive UI: Built with Bootstrap for a clean mobile-first experience.
