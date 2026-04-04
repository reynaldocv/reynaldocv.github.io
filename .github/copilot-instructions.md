# Project Guidelines

## Code Style
- Use Jekyll frontmatter with consistent YAML formatting
- Follow file naming conventions: `_sections/*.md`, `_data/*.yml`, `_posts/YYYY-MM-DD-*.markdown`
- Always prefix asset URLs with `{{ site.baseurl }}` for GitHub Pages subpath compatibility

## Architecture
- Data-driven sections using `_data/*.yml` files looped in `_sections/*.md`
- Custom collections for seminars (`_seminars/`) and sections (`_sections/`)
- W3.CSS styling with Font Awesome icons

## Build and Test
- Local development: `bundle exec jekyll serve --livereload`
- Build: `bundle exec jekyll build`
- Docker: `docker build -t jekyll-site .`
- Dependencies: `bundle install`

## Conventions
- Frontmatter in `_sections` requires: `id`, `short`, `title`, `icon`, `sort_by_number`, `layout`
- Data YAML follows structured format with fields like `position`, `institution`, `start`, `end`, `description`
- Blog posts use standard Jekyll format with future dates avoided