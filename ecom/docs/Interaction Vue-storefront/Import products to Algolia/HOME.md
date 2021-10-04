# Import products to Algolia

![diagram](https://www.plantuml.com/plantuml/svg/0/RLB1Rjim3BtxApYVKY2pBpljrCG3XXJh6ZJTEU0apX4cIwv4TIk6_Viest4ShBwO5Dzx9FLq6na3fyuMxunJDcc24tCVFzPrm5zLQ_YKlgT8GNd7vBXIlgjH1uFknQO-rSs7ztkBZh_TVwajCaMMesFZkzwxZE-pjdoDyD4u2gkeWkbv3ULEC85Xp4ivS5xJtI57duaZiFz9RWqAhOqWVJkPWjXxoJRxNLn3cr5zy3ef2T1fmJArFXYIgXdbDJAA56niwwt1ycOn2jfMcaqLE106TOBSVmh9jOAR6Wr2Ftm0upJzDguLgSLUnwrFJcDuNQcyN3FD2qzvuF86_XGWttmngrvs4Dn-73zlL5vI6RyFHerhO9l_qsgliFi4LLL9ysizDUerymsS9HV4XOh3ZjxKmL5da_XqLi0S3su8-czHRCqZsTd7YV0qr2NOojrHcF7Nu6bhUL5dUwzCpFoxmyFN_tZgRTx5xmLJUCV7otY3n-9RXoo9dHz4eETa0cd8jE7rH78wNbjyKIrkfIgF-Hy0)

## **Import script**

- gets bearer token to be able  call commercetools APIs 
- calls API to get `products`
- calls API to get `categories`

- inserts categroy name to the each product based on the matching id

- calls algolia with formatted JSON and push the data for indexing 

