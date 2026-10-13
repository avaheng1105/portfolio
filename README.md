# avaheng.my

Personal portfolio site for Ava Heng, data analyst. Plain static HTML, no build step.

## Files

- `index.html`: the whole site (styles inline)
- `favicon.svg`: tab icon

## Editing

Open `index.html` and change the text directly. Each section is marked with an `id`: `about`, `work`, `skills`, `contact`.

## Deploying on Cloudflare Pages

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**, and pick `avaheng1105/portfolio`.
2. Build settings: framework preset **None**, build command empty, output directory `/`.
3. Once deployed, open the project → **Custom domains** → add `avaheng.my` (and `www.avaheng.my` if you want it). Cloudflare creates the DNS records for you once the domain is active on your account.

Every push to `main` redeploys the site automatically.
