# Running the Jekyll Site Locally

## Prerequisites
- Ruby installed on your system
- Bundler gem installed (`gem install bundler`)
- Jekyll gem installed (`gem install jekyll`)

## Steps to Run

1. Clone the repository:
    ```bash
    git clone [repository-url]
    cd [repository-name]
    ```

2. Install dependencies:
    ```bash
    bundle install
    ```

3. Start the Jekyll server:
    ```bash
    bundle exec jekyll serve
    ```

4. View the site in your browser:
    - Open: http://localhost:4000
    - The site will automatically reload when you make changes

## Common Options

- To run with drafts enabled:
  ```bash
  bundle exec jekyll serve --drafts
  ```

- To specify a different port:
  ```bash
  bundle exec jekyll serve --port 4001
  ```

- To run with live reload:
  ```bash
  bundle exec jekyll serve --livereload
  ```

## Troubleshooting

If you encounter any issues:
1. Make sure all dependencies are up to date: `bundle update`
2. Clear the site build: `bundle exec jekyll clean`
3. Check error messages in the terminal output