# BOONS — accountant & belastingconsulent

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `boonsaccountantbelastingconsulent.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/boonsaccountantbelastingconsulent.mjs`).
> To change the content, edit that file and run `node build.mjs boonsaccountantbelastingconsulent` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@boonsaccountantbelastingconsulent.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are BOONS ACCOUNTANT & BELASTINGCONSULENT, a certified accountancy and tax practice in Beringen, Limburg, working under the same direction since 2003. We keep books and prepare annual accounts, file corporate and personal tax returns and advise on them, handle VAT and the reporting obligations that come with it, and stand alongside clients during a tax audit. We are registered with the ITAA, which is what the titles of certified accountant and certified tax adviser require, and we carry the professional indemnity insurance that membership obliges. Two things we say at the first meeting rather than burying them. We are an obliged entity under the anti-money-laundering law, so we must verify your identity and that of your beneficial owners before we can act. And we do not build aggressive arrangements: a scheme the anti-abuse provision would strike down is not a saving, it is a deferred assessment with interest. Site: boonsaccountantbelastingconsulent.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
