<div align="center">

⛅ &nbsp; **r2-setup-action** &nbsp; ⛅

configure the `aws` cli to use cloudflare r2


</div>

## getting started

```yaml
-   name: 💝 Setup R2 💝
    uses: your-org/r2-setup-action@v1
    with:
        cloudflare-account-id: ${{ vars.CLOUDFLARE_ACCOUNT_ID }}
        r2-access-key-id: ${{ secrets.R2_ACCESS_KEY }}
        r2-access-key: ${{ secrets.R2_ACCESS_SECRET }}
```

When using the AWS CLI, pass `--endpoint-url "$R2_ENDPOINT"` to upload to r2, instead of s3
