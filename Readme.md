# cheerio Lightweight

The cheerio code [has been refactored](https://github.com/cheeriojs/cheerio/pull/864) so that it works without having the whole lodash module as dependency.

However, the package.json as of writing this (22nd of September 2017) still lists 'lodash' as dependency and not the individually required modules.

This fork simply updates package.json to use only those lodash dependencies required.

Using this fork instead of the main cheerio **significatly reduces the download size** of cheerio.
