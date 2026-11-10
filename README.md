# www.athelstanservices.co.uk

The company website, published with GitHub Pages.


Repo: `AthelstanServicesPublic` (github.com/tylersimon/AthelstanServicesPublic).

Setup: push to that repo, then Settings → Pages → deploy from the main branch, folder `/docs`, and set the custom domain to `www.athelstanservices.co.uk` (`docs/CNAME` already says so). At the registrar, replace the parking page with a `CNAME` for `www` → `tylersimon.github.io` (the site's address), plus four `A` records for `@` (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) so that athelstanservices.co.uk without `www` redirects to it. Leave the `MX` records alone so email keeps working. Once it's live, tick **Enforce HTTPS**.

Because of the `CNAME` file, https://tylersimon.github.io/AthelstanServicesPublic/ redirects to www.athelstanservices.co.uk, so the site only shows once the DNS records are in place.
