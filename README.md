# Gatsby WordPress Experimental inline images

`gatsby-source-wordpress-experimental` doesn't process images in blocks of text which means your admin site has to serve the images. This plugin solves that.

Require `gatsby-source-wordpress-experimental` and `gatsby-image` to be preinstalled

This is same plugin as `gatsby-source-inline-images` but working with newer source plugin `gatsby-source-wordpress-experimental`

## installation

```bash
yarn add gatsby-wordpress-experimental-inline-images
```

Add this plugin as a plugin of `gatsby-source-wordpress-experimental`.
Be sure to specify your baseurl and protocol a second time in the `gatsby-wordpress-experimental-inline-images` options, not just in the `gatsby-source-wordpress-experimental` options.

```javascript
  {
    resolve: `gatsby-source-wordpress-experimental`,
    options: {
      plugins: [
          {
            resolve: `gatsby-wordpress-experimental-inline-images`,
          }
        ]
      }
  }
```

# Orignal source

https://github.com/TylerBarnes/gatsby-wordpress-inline-images/
