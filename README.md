# Article Management System

The Article Management System is a backend project designed to handle articles. It allows users to add, search, and retrieve articles with metadata efficiently. This system is simple yet powerful, offering keyword-based searches and the ability to retrieve full article details.

---

## Features

2. **Search Articles**:
   - Search articles by keywords in the title or content.
   - Filter articles by tags.
   - Sort search results by:
     - **Relevance**: Based on keyword frequency.
     - **Date**: Most recent articles first.

3. **Retrieve Articles**:
   - Fetch full details of a specific article using its unique ID.

4. **Persistence**:
   - Articles are stored in memory for fast access.
   - Optional persistence to the filesystem using `fs`

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


