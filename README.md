# Small PHP fixes or enhancements

This repository help you to get started with very small projects
that last few hours or few days.

1. Each project has a separate repository and GitHub Issues
1. Commits as made with the proper email address registered here on GitHub
1. Add a (MIT) license in the Initial commit `LICENSE.md`
1. Set repository Description and Website URL
   with the top right <kbd>Edit</kbd> button
1. Include Installtion and Usage in `README.md`
1. Set editor/IDE configuration in `.editorconfig`
1. List ignored files in `.gitignore`
   Thus do not keep downloaded or generated code in the repository
1. List files not intended to be ditributed (`export-ignore`) in ZIP archives in `.gitattributes`
1. Choose a coding standard (PSR-12, WPCS, Laravel) in `phpcs.xml`
1. Keep source code written in PHP in `/src` directory
   as per [PSR-4](https://www.php-fig.org/psr/psr-4/)
1. Use namespaces!
1. Keep class files free of [side-effects](https://www.php-fig.org/psr/psr-1/#23-side-effects)
   e.g. `if`, `new` etc.
1. Use Composer for class and function autoloading
1. Use Pull Requests to send code to the repository
1. Review PR-s even when working alone
1. Tag Releases!