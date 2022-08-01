My personal webpage written in [org-mode](https://orgmode.org/)!

I am currently using the [latex-css](https://github.com/vincentdoerig/latex-css) theme for my webpage, you can find other such CSS themes for your own website using [THIS](https://github.com/dohliam/dropin-minimal-css) javascript script (if you're also writing your webpage using emacs' org-mode, then to use this script simply place the `<script>` delimiter for `dropin-minimal-css` within a `#+HTML_CONTAINER` field in prelude of the org-file that you wanna test).

`./build-site.el` is the elisp script that performs the `.org` $\to$ `.html` conversions, and `build.sh` is a script that executes it within a fresh and localized emacs instance.

For creating your own webpage this way, feel free to basically copy the entire directory structure!
