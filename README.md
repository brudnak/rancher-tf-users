# Terraform Rancher Users

## Purpose of this Terraform?

To create a lot of local users.

## How to run

**Things you'll need**

1. A URL to a running Rancher server
2. ADMIN bearer token for that Rancher

## terraform.tfvars Setup

This is how your `terraform.tfvars` file should look like.

```hcl
rancher_url       = "url-to-your-rancher"
rancher_token_key = "bearer-token-you-create-in-rancher-ui"
user_count        = 1000
user_password     = "whatever-password-you-want-users-to-have"
```
