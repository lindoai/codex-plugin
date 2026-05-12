---
description: Creates a new page on an existing website using AI. Use when the user wants to add a page like About, Pricing, FAQ, or any custom page to their website.
---

# Create Page

Use the `create_page` tool to add a new AI-generated page to an existing website.

## When to use
- User wants to add a page to an existing website
- User asks for an About page, Pricing page, FAQ, Services page, etc.
- User wants to expand their website with new content

## How to use
1. You need a `website_id` — if the user hasn't specified one, use `list_websites` first and ask which website
2. Call `create_page` with the `website_id` and a descriptive prompt
3. Include `schedule_at` if the user wants to schedule it
4. Let the user know the page is being generated

## Tips
- Be specific in the prompt about the page purpose and content
- If the user mentions a style, include it in the prompt
- One page per call — if the user wants multiple pages, make separate calls
