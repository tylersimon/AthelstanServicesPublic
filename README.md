# athelstanservices.co.uk

The company website, published with GitHub Pages.

Before publishing, replace `[CONTACT_EMAIL]` and `[COMPANY_NUMBER]` in `docs/index.md`.

Repo: `AthelstanServicesPublic` (github.com/tylersimon/AthelstanServicesPublic).

Setup: push to that repo, then Settings → Pages → deploy from the main branch, folder `/docs`, and set the custom domain to `athelstanservices.co.uk` (`docs/CNAME` already says so). At the registrar, replace the parking page with four `A` records for `@` (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a `CNAME` for `www` → `tylersimon.github.io`. Leave the `MX` records alone so email keeps working. Once it's live, tick **Enforce HTTPS**.

Because of the `CNAME` file, https://tylersimon.github.io/AthelstanServicesPublic/ redirects to athelstanservices.co.uk, so the site only shows once the DNS records are in place.
