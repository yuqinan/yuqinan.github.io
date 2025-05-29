# Qinan Yu - Personal Website

This is the personal website for Qinan Yu, PhD student at Stanford University, built with Jekyll and styled with Bulma CSS framework.

## Local Development

To run this website locally:

1. Install Ruby and Bundler if you haven't already
2. Clone this repository
3. Navigate to the repository directory
4. Run `bundle install` to install dependencies
5. Run `bundle exec jekyll serve` to start the local server
6. Visit `http://localhost:4000` in your browser

If you're using Ruby 3.4 or later, you'll need to install additional gems:
```
gem "csv"
gem "base64"
gem "logger"
```

## Site Structure

- `index.md`: Home page with personal information and recent news
- `research.md`: Research page with projects, publications, and talks
- `teaching.md`: Teaching experience and philosophy
- `contact.md`: Contact information and social media links
- `_layouts/`: Template files for the site
- `assets/css/main.css`: Custom styling
- `assets/images/`: Directory for images
- `assets/files/`: Directory for CV and other documents

## Customization

1. Edit `_config.yml` to update site settings
2. Update content in the various .md files:
   - `index.md` for the home page
   - `research.md` for research information
   - `teaching.md` for teaching details
   - `contact.md` for contact information
3. Add a profile photo to `assets/images/` and update the path in `index.md`
4. Add your CV to `assets/files/` and link to it from the home page
5. Modify styles in `assets/css/main.css`

## Deployment

This site is designed to be easily deployed to GitHub Pages:

1. Push your changes to the `main` branch of your GitHub repository
2. GitHub will automatically build and deploy your site
3. Your site will be available at `https://qinanyu.github.io/`

## License

The website content is licensed [CC BY NC SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). 