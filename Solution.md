# Assignment 1.4 — Git Essentials I

### Commands

```bash
git --version
cd web-development-practice
git init
git config user.name "Your Name"
git config user.email "your-email@example.com"
```

Create `index.html`:

```html
<h1>Hello World!</h1>
```

### Make 3 Commits

```bash
git add index.html
git commit -m "Create HTML file"
```

Edit the HTML file, then run:

```bash
git add index.html
git commit -m "Update HTML content"
```

Edit it again, then run:

```bash
git add index.html
git commit -m "Add project heading"
git log --oneline
```

**Submission:** Screenshots of the project folder and the three commits shown by `git log --oneline`.