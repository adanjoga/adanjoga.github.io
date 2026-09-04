# Adán José-García — academic homepage

Reconstructed editable source for [adanjoga.github.io](https://adanjoga.github.io/), based on the [`academic-homepage`](https://github.com/luost26/academic-homepage) Jekyll template.

The reconstruction preserves the public version last updated in October 2024:

- biography, contact details and portrait;
- education, experience and research interests;
- news, teaching and student supervision;
- 21 publications and the six selected publications;
- original images, covers, styling and responsive layout.

## Edit the content

- Personal information: `_data/profile.yml`
- Navigation and visible sections: `_data/navigation.yml` and `_data/display.yml`
- News: `_news/`
- Teaching: `_teaching/`
- Students: `_students/`
- Publications: `_publications/<year>/`
- Images: `assets/images/`

## Preview locally

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Publish with GitHub Pages

Push the source to the default branch (`main` or `master`) of the `adanjoga.github.io` repository. In **Settings → Pages**, select **GitHub Actions** as the publishing source. The included workflow builds Jekyll and deploys the generated site.
