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

## Shared content

Parts of this content can also appear on the calling card ([personal-site](https://github.com/Vasar007/personal-site)) and the GitHub profile README ([Vasar007](https://github.com/Vasar007/Vasar007)). When changing content here, check those two as well. The footer's link to the calling card comes from `cardURL` in `hugo.toml`.

## Licence

The code is under the MIT licence (see `LICENSE`). The texts are under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
