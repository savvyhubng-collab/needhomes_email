# NeedHomes transactional emails

Twenty-seven responsive, table-based HTML email templates recreated from the supplied designs.

## Preview

Open `index.html` in a browser, then choose a template.

## Sending

- Replace every `{{...}}` field with escaped application data.
- Replace action URLs such as `{{KYC_URL}}` and `{{INVESTMENT_URL}}`.
- Host files in `assets/` on a public HTTPS origin and change each `../assets/...` image URL to an absolute URL before sending. Relative image paths only work in local previews.
- Inline the CSS before production delivery if your email provider does not do this automatically.
- Send a multipart message with a plain-text alternative.

Run `node build-templates.js` after editing shared content or styles.
