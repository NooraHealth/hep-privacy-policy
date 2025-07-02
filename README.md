# HEP Privacy Policy – Minimal Jekyll Site

This repository contains a simple, no-header/no-footer Jekyll site that displays Privacy Policy using Markdown.  
It is designed to be hosted via **GitHub Pages** with a clean and distraction-free layout.

---

## Prerequisites

Jekyll requires the following:

- Ruby version **2.7.0** or higher
- RubyGems
- GCC and Make

## Local Development Setup

1. Install all prerequisites (see [Jekyll Requirements](https://jekyllrb.com/docs/requirements/) for guides and details).

2. Install the jekyll and bundler gems:

   ```bash
   gem install jekyll bundler
   ```

3. Clone this repository and navigate to the project directory:

   ```bash
   git clone <repository-url>
   cd hep-privacy-policy
   ```

4. Install dependencies:

   ```bash
   bundle install
   ```

5. Build the site and make it available on a local server:

   ```bash
   bundle exec jekyll serve
   ```

6. Browse to [http://localhost:4000](http://localhost:4000)

### Development Tips

- Pass the `--livereload` option to automatically refresh the page with each change:

  ```bash
  bundle exec jekyll serve --livereload
  ```

- If you're using Ruby version 3.0.0 or higher and encounter issues, add `webrick` to your dependencies:
  ```bash
  bundle add webrick
  ```

For more information, see the [Jekyll Documentation](https://jekyllrb.com/docs/).

---
