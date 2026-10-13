# Personal Landing Page

Custom Jekyll portfolio inspired by the typography, section structure, and
dark/paper contrast of https://dawidduniec.com/. The site uses a local layout
and self-hosted fonts, with no JavaScript or theme dependency.

The visual identity uses deep blue, cool off-white, and apricot accents.
Newsreader gives the large headings an editorial feel; Manrope handles body
copy, navigation, and smaller headings.

## Preview locally

With Ruby and Bundler 2 installed, run from the repository root:

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. Jekyll rebuilds content and CSS when files change.
Restart the server after changing `_config.yml`.

The Gemfile uses Jekyll 3.10, matching the [GitHub Pages dependency list](https://pages.github.com/versions/).
It also pins dependencies compatible with macOS' older Ruby 2.6.
If your `bundle --version` shows Bundler 1.x, install Bundler 2.4.22 first:

```sh
gem install --user-install bundler -v 2.4.22
```

Use `bundle _2.4.22_` in place of `bundle` if the old version remains the default.

To produce a static build:

```sh
bundle exec jekyll build
```

The generated site is in `_site/`, which is ignored by Git.

## Update content and design

- `index.md`: profile, work examples, experience overview, skills, and contact links.
- `assets/site.css`: colors, typography, diagrams, layout, and responsive styles.
- `_layouts/default.html`: document structure, metadata, and stylesheet loading.
- `_config.yml`: site title, description, public URL, and build exclusions.
- `assets/cv.pdf`: downloadable CV.

The October 2026 refresh uses the general CV and the newer profile details in
`/Users/pjendrusik/git/cv/general/pawel_jendrusik.md` and
`/Users/pjendrusik/git/cv/printify/pawel_jendrusik.md`. The download is the general
CV from `general/pawel_jendrusik.pdf`, rather than a role-specific application.
Private interview and career-strategy notes are not published.
Company names and detailed employment dates remain in the downloadable CV;
the landing page describes domains, roles, and contributions.

Font files and their SIL Open Font Licenses live in `assets/fonts/`. The CSS
URL includes a build timestamp so a new deployment refreshes cached styles.
Internal asset URLs use Jekyll's `relative_url` filter to support a `baseurl`.

## Deploy

Push or merge changes into the branch configured in **Settings > Pages**.
For a branch-based Pages build, select that branch and the repository root.
GitHub Pages builds the site using the local `_layouts/default.html` layout;
there is no remote theme to configure. `CNAME` keeps the existing custom domain.
