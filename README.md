# https://smithara.github.io

Personal website built with Hugo.

## Running locally

Install Hugo:
```bash
# Ubuntu/Debian
sudo apt install hugo

# macOS
brew install hugo

# Or download from https://gohugo.io/installation/
```

Run the development server:
```bash
git clone https://github.com/smithara/smithara.github.io.git
cd smithara.github.io
hugo server
```
Now browse to http://localhost:1313

## Building for production

```bash
hugo
```

This generates the site in the `public/` directory.

## Adding content

To add a new page, create a markdown file in `content/`:
```bash
hugo new content/your-page.md
```
