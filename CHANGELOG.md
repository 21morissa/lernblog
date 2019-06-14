# Changelog

## Version 1.1.0 (2019-06-14)

- Use `/tags/...` as path to the tag overview and also every single tag page.
- Remove `enableGitInfo` from config and use the command line flag in netlify instead. This makes it easier for users to download the repo and run Hugo locally without using git (see https://github.com/gohugoio/hugo/issues/6035).

## Version 1.0.5 (2019-06-08)

- Make tags clickable on frontpage cards.
- Improve tag and tag overview pages.
- Remove Font Awesome icon font. Instead use HTML arrows and Emojis.
- Add custom svg pin icon.

## Version 1.0.4 (2019-06-05)

- Footnote: Use text field widget instead of markdown/rich-text area. Also improve footnote styling to support markdown footnotes.

## Version 1.0.3 (2019-06-03)

- CMS: Make profile image, icon, and logo to optional.
- Use relative url for images in blog overview. This is more stable during DNS and URL changes.

## Version 1.0.2 (2019-06-03)

- CMS: Make blog image optional.
- Compress the standard images.
- JSON Feed: Use "jsonify" instead of "HTML escape".
- ATOM Feed: Use "HTML escape".
- Add LICENSE und info about licens in README.
- Add CHANGELOG.

## Version 1.0.1 (2019-05-28)

- Make Footer optional.
- Change the date format of posts from date-time to date only.

## Version 1.0.0 (2019-05-28)

- Initial version.
