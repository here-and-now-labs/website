# Here Now Labs website

Static, dependency-free website for [herenowlabs.xyz](https://herenowlabs.xyz).

## GitHub Pages

In the repository, open **Settings → Pages** and choose:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

The included `CNAME` file configures `herenowlabs.xyz` as the custom domain.

At the DNS provider, configure the apex domain with GitHub Pages' four `A` records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Configure `www` as a `CNAME` pointing to `here-and-now-labs.github.io`.
