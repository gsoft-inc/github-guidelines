# Guidelines

You'll find below a few guidelines to follow when contributing to a Github repository in GSoft organization.

## Github Account

GSoft doesn't have any specific requirements regarding which account you use to contribute to any of the organization repository. You can use your personal account or create a new account related to GSoft.

However, before contributing, you must associate your Github account to [GSoft Github organization](https://github.com/gsoft-inc). To do so, **open a ticket with infra** and ask to be added to the `gsoft-inc` organization on Github.

## Repository name

Repositories that are bound to an organization within GSoft or a product developed by GSoft should match the following naming convention:

[organization | product]-[name]

Ex:

- sg-brand
- ov-eslint
- glab-stylelint

Repositories that are bound to the whole GSoft organization should match the following naming convention:

gsoft-[name]

Ex:

- gsoft-license

Repositories that are not bound to an organization or a product shouldn't have a prefix.

Ex:

- craco
- ansible-role-azure-devops-agent
- dotnet-certificate-tool
- azure-pipelines-lighthouse

## NPM package name

Packages that are bound to an organization within GSoft or a product developed by GSoft should be published under an [NPM scope](https://docs.npmjs.com/about-scopes) named after the organization or the product name and the whole package name should match the following naming convention:

@[organization | product]/[name]

Ex:

- @sharegate/sg-brand
- @ov/eslint
- @glab/stylelint

Packages that are bound to the whole GSoft organization should be published under the "@gsoft" [NPM scope](https://docs.npmjs.com/about-scopes) and match the following naming convention:

@gsoft/[name]

Ex:

- @gsoft/license

Packages that are not bound to an organization or a product can use the naming convention of their choice.

## NPM package author

The packages author should match an organization within GSoft or a product developed by GSoft.

Ex.

- Groupe GSoft inc.
- Groupe Sharegate inc.

## License

Every open source project developed by GSoft must be under the Apache 2.0 license and link to the following license: https://github.com/gsoft-inc/gsoft-license/blob/master/LICENSE
