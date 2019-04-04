# gatsby-plugin-linkedin-insight

Easily add [LinkedIn Insight](https://business.linkedin.com/marketing-solutions/website-demographics) to your Gatsby site.

## Install

`npm install --save gatsby-plugin-linkedin-insight`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-plugin-linkedin-insight`,
    options: {
      partnerId: `YOUR_LINKEDIN_INSIGHT_PARTNER_ID`,

      // Include LinkedIn Insight in development.
      // Defaults to false meaning LinkedIn Insight will only be loaded in production.
      includeInDevelopment: false
    }
  }
];
```

#### Note

Out of the box this plugin will simply load LinkedIn Insight on the initial page/app load.

#### Credit

Thanks to https://github.com/gabeskipio/gatsby-plugin-facebook-pixel and https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-plugin-google-tagmanager for a great base for this plugin!
