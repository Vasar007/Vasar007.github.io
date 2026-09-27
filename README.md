# Vasar007.github.io

The Hugo source of [vasar007.github.io](https://vasar007.github.io/), Vasily Vasilyev's projects site: a short introduction and one page per project. The calling card is [vasar.dev](https://vasar.dev/).

## Preview locally

Install Hugo 0.166.0 (standard edition — the same version `.github/workflows/hugo.yml` pins), then run:

```bash
hugo server
```

and open <http://localhost:1313/>.

## Deployment

Every push to `main` runs `.github/workflows/hugo.yml`, which builds the site and deploys it to GitHub Pages. The repository's Pages source is "GitHub Actions".

To update the "Last updated" line, change `lastUpdated` in `hugo.toml`.

## Shared content

The bio, the stack list, the project descriptions and the links are shared with the calling card ([personal-site](https://github.com/Vasar007/personal-site)) and the GitHub profile README ([Vasar007](https://github.com/Vasar007/Vasar007)). Change all three together.

## Licence

The code is under the MIT licence (see `LICENSE`). The texts are under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
