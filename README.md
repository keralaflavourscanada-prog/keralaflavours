# Kerala Flavours static website

This is a simple static replacement for the WordPress site. It intentionally does not reproduce the old design or require WordPress, PHP, plugins, or a database.

## Cloudflare Pages
1. Create a GitHub repository and upload `index.html` and `style.css`.
2. In Cloudflare, choose Workers & Pages / Pages and connect the GitHub repository.
3. Framework preset: None.
4. Build command: leave blank.
5. Build output directory: `/`.
6. Deploy.
7. Add `keralaflavours.ca` as a custom domain in the Pages project.
