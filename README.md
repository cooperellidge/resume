# resume

A LaTex resume built with GitHub Actions and deployed to GitHub Pages.

Based off Jake's Resume [(GitHub repo)](https://github.com/jakegut/resume).

# Getting started

1. Fork this [GitHub repo](https://github.com/cooperellidge/resume).
2. Create a remote branch `gh-pages` and configure GitHub Pages to deploy from that branch.
3. Clone that repo locally.
4. Modify the `resume.tex` file.
5. To view the local changes, install TeX on your machine and compile `resume.tex`. If you are using VS Code, I suggest using the LaTeX Workshop extension (`james-yu.latex-workshop`) and following their instructions.
6. Once you are happy, push your changes to `main`.
7. Navigate to your gh pages site, e.g. `https://<username>.github.io/<repo>/resume.pdf`

Now continuing editing the `resume.tex` file or improving the entire repo itself!

# Upcoming

- Create pdfs from other branches (e.g. `companies/<company>.pdf`) and deploy it to a subdirectory `https://<username>.github.io/<repo>/<branch-name>.pdf` to allow for company-specific variant resumes.
- Use environment variables for personal information e.g. hide mobile numbers publically, but allow `.env` to insert them locally.

# Contributions

I am not currently accepting external contributions to this repo. However, feel free to fork and improve it yourself!
