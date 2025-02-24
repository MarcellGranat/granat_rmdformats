# rmdformats (development version)


# rmdformats 1.0.4

- Fix scrolling behavior for tabs in material (#122, @bersbersbers)
- Fix JS error in material
- Fix thumbnail sizing in material (#120, @DOSull)
- Fix TOC display in robobook when toc_depth > 2 (#126, @chamaoskurumi)
- Fix unreadable hover tab text color in readthedown (#127, @sciatro)
- Don't add magnific_popup dependency if lightbox is false (#128, @sciatro)
- Remove unneeded jQueryUI dependency (#130, @sciatro)

# rmdformats 1.0.3

- New `downcute chaos` theme (thanks @zac-garland)
- Fix position of search and pagination in DT tables in robobook and downcute (thanks @Lucius-Cesar)
- Add support for toc_depth = 3 in html_clean (thanks @megaraptor1)
- Make TOC vertically scrollable in html_clean (thanks @megaraptor1)
- Fix incompatibility between downcute dark mode toggler and downloadthis (thanks @baobabprince)

# rmdformats 1.0.2

- Add ability to disable lightbox effect on `img` with a "no-lightbox" class (thanks @Lucius-Cesar)
- Fix TOC not working in robobook and downcute when dots in headings (thanks @jrothsc)
- Fix position of search and pagination in DT tables in readthedown (thanks @heseber)
- Fix `ol` font size in readthedown (thanks @albertostefanelli)
- Fix footnote links presentation in readthedown postamble (thanks @albertostefanelli)
- Add overflow to wide tables in robobook and downcute (thanks @octmedina)

# rmdformats 1.0.1

- Fix DT display overflow
- Fix `pre` wrapping
- Remove link styling in `code`
- Fonts are now downloaded from Google Web Fonts in readthedown if embed is FALSE
- Fix subtitle in readthedown
- Remove ellipsis and add word-wrap in TOC in robobook
- Exclude leaflet tiles from lightbox (thanks @thatchersj)

# rmdformats 1.0.0

- Add downcute, robobook and lockdown templates
- The create_doc() function has been removed
- Add embed_fonts argument to readthedown (thanks @harrelfe)
- Set mathjax URL to mathjax.rstudio.com
- Add support for code_download (thanks @ltrainstg)
- Add support for dropdown tabsets (thanks @dktanwar)
- Improve handling of internal links between pages
- Code refactoring

# rmdformats 0.3.7

- Fix TOC overflow hidden by postamble in readthedown (thanks @derekmichaelwright)
- Upgrade to Bootstrap 3.3.7 to fix compatibility with jQuery 3/shiny (thanks @ FlavioLeccese92)

# rmdformats 0.3.6

- Upgrade navigation.js (thanks @vkoul)
- Fix improper page height for first `material` paged section
- Move `questionr` from Imports to Suggests (thanks @rCarto)
- Fix tabset headings not hidden in toc (thanks @poonv)
- Add support for `md_extensions` YAML header option
- Fix td background-color incompatibility with DT in readthedown (thanks @davidvilanova)
- Fix material toc links not working when dot in level 1 title (thanks @PriyaShaji)
- Fix problems with runtime:shiny in material (thanks @MiWebR)
- Fix smaller font size in lists in readthedown

# rmdformats 0.3.5

- Fix missing blank line at the end of `template.yaml` files (thanks @thomaselove)
- Fix long titles, author and date display in `material` (thanks @antuki)
- Fix settings not taken into accounts when using `make html` (thanks @gdevenyi)

# rmdformats 0.3.4

- Add a `cards` argument to the material `template` (thanks @Maiae)
- Remove deprecated ProjectTemplate templates.
- Bugfix : lghtbox images do not always fit vertically (thanks @paullemmens)
- Bugfix : handle toc: false in html_clean (thanks @8steen)
- Bugfix : add max-width for full images in material (thanks @tyokota)
- Bugfix : load Rambla Google Webfont via https in docco (thanks @jflycn)
- Bugfix : do not insert mathjax if `mathjax: null` in preamble (thanks @jflycn)
- Bugfix : add description field to template.yml (thanks @mjfrigaard)

# rmdformats 0.3.3

- Bugfix : HTML widgets not displayed in `material`
- Better DT::datatable styling
- Switch Mathjax CDN to cdnjs
- Bugfix : "Code" hiding/showing dropdown not working anymore in material

# rmdformats 0.3.2

- Bugfix : thumbnails should not upscale images (thanks @dmenne)
- Bugfix : tab not activated in pilltabs with default HTML template (thanks @dmenne)
- Bugfix : follow new CRAN policy regarding images in README file

# rmdformats 0.3.1

- Bugfix : Pandoc can't fid tabsets.js (thanks @m-stanley)
- Bugfix : Incompatibility between dark zenburn and readthedown (thanks Andrey Kostenko)
- Bugfix : Internal links not working in material (thanks Andrey Kostenko)

# rmdformats 0.3

- New `material` HTML template
- New feature : All templates now support code folding and tabsets (thanks @RCura)
- New feature : `lightbox`, `thumbnails` and `gallery` options for images display (thanks @noamross)
- New feature : `use_bookdown` argument for section numbering and cross references (thanks @rdiaz02)
- html_clean table of contents now uses rmarkdown instead of tocify
- Bugfix : embedded shiny apps should now work (thanks @mike-powell)
- Bugfix : wrong styling when no headings (thanks @dmenne)

# rmdformats 0.2

- New `readthedown` HTML template

# rmdformats 0.1.1

- Cleanup and document package for CRAN submission
- Copy html_dependency_* and default_mathjax from rmarkdown to fix check notes
- Add caption to magnific popup
- HTML formats refactoring : now derived from html_document(), much simpler code

# rmdformats 0.0.1

- First version
