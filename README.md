# Resolve URL Alfred Workflow

[![GitHub Version][shield-version]][gh-releases]
[![GitHub All Releases][shield-downloads]][gh-releases]
[![GitHub][shield-license]][license-mit]

Follows any HTTP redirects and returns the canonical URL. Also displays information about the
primary host (hostname, IP address(es), aliases) in [Alfred][alfred].

![][preview]

## Download & Installation

Download the [latest workflow release][gh-latest-release] from GitHub. Open the workflow file to install in Alfred.

## Usage

You can paste a URL into Alfred's query box or grab a URL directly from the
clipboard. If the URL contains no scheme (`http://`, `https://`, etc.),
`https://` will be assumed.

- `resolve URL` — Find and display the canonical URL after all redirects.
  - `↩` — Open the new URL in your default browser
  - `⌘ + ↩` — Copy the new URL to the clipboard
- `resolvepb` — Grab the URL from the clipboard and resolve any redirects as above.

If the URL has no redirects, a "URL is canonical" message will be displayed.

## Bug Reports and Feature Requests

Please use [GitHub issues][gh-issues] to report bugs or request features.

## Contributors

This Alfred Workflow comes from the [abandoned Workflow][abandoned-workflow] of
[Dean Jackson][deanishe]

## License

Resolve URL Alfred Workflow is licensed under the [MIT License][license-mit]

The workflow uses the following libraries:

- [Alfred-PyWorkflow][alfred-pyworkflow] ([MIT License][license-mit])

[abandoned-workflow]: https://github.com/deanishe/alfred-resolve-url
[alfred-pyworkflow]: https://github.com/harrtho/alfred-pyworkflow/
[alfred]: https://www.alfredapp.com
[deanishe]: https://github.com/deanishe
[gh-latest-release]: https://github.com/harrtho/alfred-resolve-url/releases/latest
[gh-releases]: https://github.com/harrtho/alfred-resolve-url/releases
[license-mit]: https://opensource.org/licenses/MIT
[preview]: img/preview.png
[shield-downloads]: https://img.shields.io/github/downloads/harrtho/alfred-resolve-url/total.svg
[shield-license]: https://img.shields.io/github/license/harrtho/alfred-resolve-url.svg
[shield-version]: https://img.shields.io/github/release/harrtho/alfred-resolve-url.svg
