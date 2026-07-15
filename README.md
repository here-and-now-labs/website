# Here & Now Technologies website

Static, dependency-free website for [hereandnowtech.com](https://hereandnowtech.com).

## GitHub Pages

In the repository, open **Settings → Pages** and choose:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

The included `CNAME` file configures `hereandnowtech.com` as the custom domain.

At the DNS provider, configure the apex domain with GitHub Pages' four `A` records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Configure `www` as a `CNAME` pointing to `here-and-now-labs.github.io`.
