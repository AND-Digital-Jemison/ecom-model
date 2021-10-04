# Interaction Vue-storefront

![diagram](https://www.plantuml.com/plantuml/svg/0/NLF1Rjim3BtxAxYU4Y1nBZtjrCuDi1Rj4iJPW9q2HMOS8RBaILGI__qeExRJdcoJxv5yZ_IJ9-4eL3hvfepKeK0u4jN--sBXn2Kj5Ht3FdXqqXf2GwcqrK8KJWbprg4EY-nnljR2qE-FzuKMX9uujCiY-aff7IidFrzVbhjykzmiLzk_w-LacYH9tdZ2Qd8EE8E7Fm7ddgp3WsFY0qSS-jeQhyu85zn37fFGPQSzLrPahVQCpcnLyOW8snY8_BMpHP34oTefYVnKbIZHGvgcOmMXIyO-wz9g9I8jH-7aSGJ4ePgzjgUOwzyZCFl8xmOnXtQ8rg53q5y1k-ML9buw3hCfw8pGa4kdQfh1y_eLfD1Hni6wIX2yvQjVK0WIp4_UHRFRT2xTv4xRsCijPWwVlbdGf-zX_ZuwUCRZSFaVQeDw37RRwBq3hNZwWiVeO7s7mIVu5z0rGxvDTILQ3PqUhW2tRI938_3ErGxEPW7Vs9dt4yy6X2buNwMF6sSDWfICP-0LzILQoqUoLkR4VSXsV6jq0tE0zIgxnzyTpCYvy8dpaNII1otjjaRyiAKeYjkSqCnw4kFuxalh57xXTrxLmH_RVSRnzWZA57Zbnli6-ilZJJoXAVXd-Gy0)

**Commerce Tools**

Serves as a db for our products, prices, descriptions, internationalization

**Vue-storefront**

Front end for our store, linked with commercetools to show products, prices etc..
Linked with Algolia to search through products that are indexed in Algolia

**Algolia search**

Have indexed products that and it performs search on them.
It has set categories as facades so that can be used in search results or breadcrumbs.

**Import script for Algolia**

Running custom script imports products and all other info we want to be searchable from commercetools to Algolia and its ready to perform search queries.
The script requests categories from commerce tools and swapt the `id` in genereated product json file so it is available for queries.
Formats the data to JSON format required for veu-storefront so it is displayed correctly.

### **CMS**

**Storyblok**

CMS integrated into Vue-storefront


**Contentful**

CMS integrated paritally with Commercetools and vue-storefront as a POC.
