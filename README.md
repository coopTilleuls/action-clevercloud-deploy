# Deploy to Clever Cloud

This action deploys to your app hosted on [Clever Cloud](https://clever-cloud.com). It needs `vars.APP_ID`, `secrets.CLEVER_TOKEN` and `secrets.CLEVER_SECRET` to be set in your preferred environment.

# Usage

```yaml
uses: coopTilleuls/action-clevercloud-deploy@v1
    with:
      # The name of the github environment where you defined
      # variable APP_ID and secrets CLEVER_TOKEN and CLEVER_SECRET
      deploy-environment: ''
    secrets:
      clever-token: ${{ secrets.CLEVER_TOKEN }}
      clever-secret: ${{ secrets.CLEVER_SECRET }}
```
