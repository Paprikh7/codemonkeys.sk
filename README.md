# codemonkeys.sk

The website of Code Monkeys s. r. o. It is one static page, with no build step. GitHub Pages hosts it
for free.

## Files

| File | Purpose |
|---|---|
| `index.html` | The page. The styles are inline. |
| `404.html` | The page for an unknown address. |
| `favicon.svg` | The icon. |
| `CNAME` | The custom domain for GitHub Pages. |
| `.nojekyll` | Tells GitHub Pages to publish the files as they are. |

## Change the page

1. Edit `index.html`.
2. Open the file in a browser, and check the result.
3. Commit the change.
4. Push it to `main`. GitHub Pages publishes each push.

## DNS at Websupport

The DNS of `codemonkeys.sk` stays at Websupport.

| Name | Type | Value |
|---|---|---|
| `codemonkeys.sk` | A | `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` |
| `codemonkeys.sk` | AAAA | `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153` |
| `www.codemonkeys.sk` | CNAME | `paprikh7.github.io` |

Do not add a wildcard (`*`) record. GitHub warns that a wildcard record lets other people take over a
subdomain.

Do not change the MX, TXT, and `sig1._domainkey` records. iCloud Mail needs them.

## Company data

The company data on the page comes from the Slovak register of legal entities (RPO). When the register
changes, update the page.
