# Minimal Personal Website

## your webpage is a markdown file 

+ Enter your name and contact info in `index.md`
+ Put papers or slides in `papers`
+ edit `index.md`; change fonts etc in `style.css`
+ let github take care of the rest (run pandoc to export index.md to html, then host)

## gh based hosting (one-time setup)

+ Host on github / gitlab / bitbucket / any version control setup that supports hosting webpages
  * get a github account
  * fork this repository (or download a zip if you want to keep the website repo private - your call)
    - make changes to `index.md` in your editor
    - make changes to `index.md` online (not recommended)
  * Enable github pages
    - Settings > Pages > Branch (main) > root

---

(deprecated - local rendering)
+ run `render.sh` whenever you make changes to the markdown file (linux/macos)
  + depends on [pandoc](https://pandoc.org/)
  + run analogous line on powershell if you're on windows 

