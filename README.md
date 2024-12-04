# Article Management System

The Article Management System is a backend project designed to handle articles. It allows users to add, search, and retrieve articles with metadata efficiently. This system is simple yet powerful, offering keyword-based searches and the ability to retrieve full article details.

---

## Features

- **Add Articles**: Create new articles with metadata such as title, content, and tags.
- **Search Articles**: Search for articles using keywords or tags.
- **Retrieve Articles**: Fetch complete details of an article by its ID.

---

## Endpoints

### 1. Add Article (POST `/articles`)
Adds a new article with metadata.

**Request Body:**
```json
{
  "title": "Understanding Artificial Intelligence",
  "content": "Artificial Intelligence (AI) is transforming industries.",
  "tags": ["AI", "technology", "future"]
}
