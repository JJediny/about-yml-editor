<<<<<<< HEAD
## Welcome!

We're so glad you're thinking about contributing to an 18F open source project! If you're unsure about anything, just ask -- or submit the issue or pull request anyway. The worst that can happen is you'll be politely asked to change something. We love all friendly contributions.

We want to ensure a welcoming environment for all of our projects. Our staff follow the [18F Code of Conduct](https://github.com/18F/code-of-conduct/blob/master/code-of-conduct.md) and all contributors should do the same.

We encourage you to read this project's CONTRIBUTING policy (you are here), its [LICENSE](LICENSE.md), and its [README](README.md).

If you have any questions or want to read more, check out the [18F Open Source Policy GitHub repository]( https://github.com/18f/open-source-policy), or just [shoot us an email](mailto:18f@gsa.gov).

## Public domain

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.
=======
Contributing
===============
This document briefly lists the guidelines for contributing to JSON Editor.

Reporting Bugs
----------------
When creating an issue in GitHub, try to include when feasible:
*  A brief description of the issue
*  An example JSON schema that causes the issue
*  Steps to reproduce

If you can reproduce the issue on the demo page (http://jeremydorn.com/json-editor/), it's helpful to attach the "Direct Link" url (top right of page).  Note: the direct link might not work for very large schemas or JSON values.


Contributing Code
--------------------------
One of the major goals of JSON Editor is to be easy to modify and hack.

If you fix a bug or add a cool feature, please submit a pull request!


### Code Style

*  Use 2 spaces for indentation
*  Use comments whenever the code's meaning is not obvious
*  When in doubt, try to match the style in existing source files

###Grunt

The easiest way to hack on JSON Editor is to run `grunt watch`, which 
re-builds `dist/jsoneditor.js` every time a source file changes.

To do a full grunt build which includes jshint and minification, run `grunt`.

### Submitting Pull Requests
Try to limit pull requests to a single narrow feature or bug fix.

__Do not submit `dist/` files!__ 

The following is done when a pull request is accepted.  There is no need to do any of these steps yourself.

1.  Merge pull request into master
2.  Increment version number in `src/intro.js` and `bower.json`.  Set date in `src/intro.js`.
3.  Build `dist/` files with grunt
4.  Commit and push to github
5.  Add a git tag and release for this version with a short changelog

Sometimes, multiple pull requests will be merged before doing steps 2-5.
>>>>>>> 26e221593e3678794d4abf6c0ba98ccb180c7387
