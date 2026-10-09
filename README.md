# Roy Liang – personal website

Built with [Hugo](https://gohugo.io/) and [Hugo Blox](https://hugoblox.com/). Deployed to GitHub Pages at https://royliang12.github.io/ by the workflow in `.github/workflows/deploy.yml`.

## Where to edit

| What | File |
| --- | --- |
| Name, bio, education, experience, skills, certifications, social links | `data/authors/me.yaml` |
| Home page sections (incl. Research text) | `content/_index.md` |
| Experience page | `content/experience.md` |
| Portfolio / projects | `content/projects/` (copy `_example-project`) |
| Publications | `content/publications/` (copy `_example-paper`) |
| Menu | `config/_default/menus.yaml` |
| Site name, description, colors | `config/_default/params.yaml` |
| Profile photo | add `assets/media/authors/me.jpg` (or .png) |
| CV download | add `static/uploads/resume.pdf`, then enable the button in `content/_index.md` |

## Preview locally

```
pnpm install
hugo server
```
