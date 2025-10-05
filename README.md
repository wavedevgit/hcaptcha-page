# Hcaptcha page
This page lets you solve hCaptchas and redirect to your API with the token.

- **Usage:** `https://hcaptcha-page.pages.dev?sitekey=site_key&redirect=api_url`
- **Optional params:** `&rqdata=VALUE&rqtoken=VALUE&sessionid=VALUE`
- **Useful params:** `&hostname=HOSTNAME&href=URL`

> **hostname & href** are used to fake that the captcha is running inside some app

> Redirect is sent to your api url with token added as query `token` and `rqtoken` if you include it 
