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
