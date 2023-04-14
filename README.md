# Resolve HTTP Redirects in Alfred

[![GitHub Version][version-shield]][releases]
[![GitHub All Releases][downloads-shield]][releases]
[![GitHub][license-shield]][mit-license]

Follows any HTTP redirects and returns the canonical URL. Also displays information about the
primary host (hostname, IP address(es), aliases).

![][demo]

You can paste a URL into Alfred's query box or grab a URL directly from the
clipboard. If the URL contains no scheme (`http://`, `https://`, etc.),
`https://` will be assumed.

## Usage

- `resolve URL` — Find and display the canonical URL after all redirects.
  - `↩` — Open the new URL in your default browser
  - `⌘+↩` — Copy the new URL to the clipboard
- `resolvepb` — Grab the URL from the clipboard and resolve any redirects as above.

If the URL has no redirects, a "URL is canonical" message will be displayed.

## License, thanks

This workflow is released under the [MIT license][mit-license]. It uses
[Alfred-PyWorkflow][alfred-pyworkflow] for the plumbing and to resolve
HTTP redirects.

[demo]: https://raw.githubusercontent.com/harrtho/alfred-resolve-url/master/demo.gif "demo.gif"
[alfred-pyworkflow]: https://www.xdevcloud.de/alfred-pyworkflow
[downloads-shield]: https://img.shields.io/github/downloads/harrtho/alfred-resolve-url/total.svg
[license-shield]: https://img.shields.io/github/license/harrtho/alfred-resolve-url.svg
[mit-license]: https://opensource.org/licenses/MIT
[releases]: https://github.com/harrtho/alfred-resolve-url/releases
[version-shield]: https://img.shields.io/github/release/harrtho/alfred-resolve-url.svg
