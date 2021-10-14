# gatsby-plugin-linkedin-insight

Easily add [LinkedIn Insight](https://business.linkedin.com/marketing-solutions/website-demographics) to your Gatsby site.

---

## 💡 This is a fork from [Florian Gächter's gatsby-plugin-linkedin-insight Gatsby plugin](https://github.com/floriangaechter/gatsby-plugin-linkedin-insight.git). The motivation for creating this fork is inactivity on the original repository: the original plugin's support goes up to Gatsby V2, and hasn't been updated for at least 7 months.

---

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

### Note

Out of the box this plugin will simply load LinkedIn Insight on the initial page/app load.

### Credit

Thanks to [gatsby-plugin-facebook-pixel](https://github.com/gabeskipio/gatsby-plugin-facebook-pixel) and [gatsby-plugin-google-tagmanager](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-plugin-google-tagmanager) for a great base for this plugin!

the original creator of this plugin: [Florian Gächter's gatsby-plugin-linkedin-insight](https://github.com/floriangaechter/gatsby-plugin-linkedin-insight.git)
