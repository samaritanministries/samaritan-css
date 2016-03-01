# samaritan-css

## Releasing a New Version

Steps to release a new version:

1. cd examples/sass
2. sass -w example.scss:example.css
3. Update the version number in the `bower.json` file
    * See [here](http://keepachangelog.com/) for versioning conventions
4. Commit the changes made in the previous steps.
5. Tag the current commit with the appropriate version number, following the pattern `vX.Y.X`
    * `git tag vX.Y.Z`
6. `git push`
7. `git push --tags`
