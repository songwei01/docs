# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

https://objects.githubusercontent.com/github-production-release-asset-2e65be/801459371/04dce928-3ee6-48e3-ab9d-3c3a8a51eb2a?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20250710%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250710T082903Z&X-Amz-Expires=1800&X-Amz-Signature=5ab879838b98d33b80feeaa10822870abb939f7aeff0372962b732954c0eaa4f&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3D1.mp4&response-content-type=application%2Foctet-stream

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
