# Thinking Sand

Static site for [thinkingsand.org](https://thinkingsand.org).

## GitHub Pages

1. Publish this repository with GitHub Pages from the `main` branch, `/` (root).
2. The `CNAME` file already maps the site to `thinkingsand.org`.
3. At the DNS host, point `thinkingsand.org` at GitHub Pages:

   - `A` records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `AAAA` records: `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`

   Or a `CNAME` from `www` to `<user>.github.io`.
