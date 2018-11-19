# WordPress I18n Tools

This is a slightly extended version of the official WP I18n tools which allows
the exclusion of specified folders.

## Documentation

### POT File Generation

`php path/to/makepot.php project-type path/to/source-folder/ path/to/pot-destination-folder/filename.pot [exclude-folder-1,exclude-folder-2,...]`

The (optional) last parameter is a comma separated list of subfolders relative
to the given source folder.

The most common **project types** are wp-theme and wp-plugin, further options are
generic, wp-frontend, wp-admin, wp-network-admin, wp-core, wp-ms, wp-tz,
bb, mu, bp, glotpress, rosetta and wporg-bb-forums.

## Links

- [Full Documentation (WordPress Codex)](https://codex.wordpress.org/I18n_for_WordPress_Developers#Using_the_i18n_tools)
- [Official WP SVN Repo](https://develop.svn.wordpress.org/trunk/tools/i18n/)

## License

GPLv2 or later
