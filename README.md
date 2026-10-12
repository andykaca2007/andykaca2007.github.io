# andykaca2007.github.io

My engineering portfolio, live at **https://andykaca2007.github.io**.

Plain HTML and CSS with no build step: edit a file, push, and the site updates in about a minute.

## How to edit

| I want to... | Do this |
|---|---|
| Change the intro or contact text | Edit `index.html` (look for `EDIT ME` comments) |
| Add a photo | Put it in `assets/img/`, then swap a `placeholder` div for `<figure><img src="../assets/img/name.jpg" alt="..."><figcaption>...</figcaption></figure>` |
| Add a build-log entry | Copy an `<div class="entry">` block in the project page; newest goes at the top |
| Add a new project | Copy `projects/_template.html` to `projects/<name>.html`, fill it in, then copy a project card in `index.html` and point it at the new page |
| Mark a project finished | Change `status wip` to `status done` and its text |
| Change colours | Edit the variables at the top of `assets/style.css` |

Tip: keep photos under ~500 KB (resize to ~1600 px wide) so the site stays fast.
