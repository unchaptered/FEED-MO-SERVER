# What is FEED MO SERVER?

`Feedmo(2022~)` is Free Feedback Service for Web Developer.

> If you want more info, visit service repositories. <br>
> Link : _https://github.com/unchaptered/FEED-MO_

`Feedmo Server` is Serverless Application with cloudflare worker, using Wrangler.

Local Codes is automatically deployed with Github Action.

<hr>

## Configurations

1. Create new Github Action Files : [CI/CD for cloudflare workers, using wrangler](https://github.com/marketplace/actions/deploy-to-cloudflare-workers-with-wrangler#:~:text=You'll%20need%20to%20configure,so%20it%20should%20be%20safe!)

```yaml
name: Deploy
```

2. Publish new Cloudflare Token or Key : [Cloudeflare Token vs Key](https://developers.cloudflare.com/api/tokens/)

3. Set Configuration in Github Repository