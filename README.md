# Cheatsheet for the Workshop

## Live Examples

* [workshop-apvode](https://codebar-shanghai.github.io/workshop-apvode/) - [source](https://github.com/codebar-shanghai/workshop-apvode)
* [ironblood.github.io](https://ironblood.github.io/) - [Custom Domain](https://test.yangthecoder.com/), [source](https://github.com/IronBlood/ironblood.github.io)

## Agenda

1. Create an account on GitHub (if you haven't yet)
2. Create a repo named `username.github.io` (replace `username` to your GitHub name), then create an `index.html` file with the content below.
3. Delete and recreate the repo `username.github.io`, then we'll do it the *real* way.

## Tools

1. [Git](https://git-scm.com/)
2. [GitHub CLI](https://cli.github.com)
3. [Visual Studio Code](https://code.visualstudio.com/)

## Snippet

### HTML (the most simple way)

```html
<h1>It works!</h1>
```

### HTML (more formal way)

```html
<!doctype html>
<html>
    <head>
        <title>test</title>
    </head>

    <body>
        <h1>It works!</h1>
    </body>
</html>
```

### Git

A more detailed [cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf) made by GitHub.

```bash
# 0. Run the following two commands only if you haven't set yet
# Replace with your user name and email
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

# 1. Navigate to project folder
cd ~/Projects/username.github.io

# 2. Initialize Git
git init

# 3. Add HTML file(s)
git add index.html

# 4. Commit changes
git commit -m "First commit"

# 5. Rename default branch to main (optional but recommended)
git branch -M main

# 6. Connect to GitHub repo (replace `username`), this is also only needed for the first time
git remote add origin https://github.com/username/username.github.io.git

# 7. Push to GitHub
git push -u origin main
```
