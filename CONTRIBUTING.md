# Contributing to The Effect Patterns Hub

Thank you for your interest in contributing! This project aims to be the best
community-driven knowledge base for Effect-TS patterns. Every contribution helps.

## How to Add a New Pattern

1.  **Create a new file** in the `/content` directory.
2.  **Name the file** using a descriptive, kebab-case name, like
    `use-gen-for-business-logic.mdx`.
3.  **Copy the contents** from the `template.mdx` file into your new file.
4.  **Fill out the template** with the details of your pattern.
5.  **Submit a Pull Request.**

## The Pattern Structure

Each pattern is a single `.mdx` file with YAML frontmatter for metadata and a
Markdown body for the explanation. Please fill out all fields.

-   `title`: The human-readable title.
-   `id`: A unique, kebab-case identifier (matches the filename).
-   `skillLevel`: `beginner` | `intermediate` | `advanced`
-   `useCase`: An array of high-level goals (e.g., "Domain Modeling").
-   `summary`: A concise, one-sentence explanation.
-   `tags`: A list of relevant lowercase keywords.
-   `related`: (Optional) A list of related pattern `id`s.
-   `author`: Your GitHub username or name.