---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Get a single product image by id
  description: Get a single product image by id.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/custom_collections.json:
    get:
      summary: Get a list of all custom collections
      description: Get a list of all custom collections.
      operationId: getAdminCustomCollections.json
      x-api-path-slug: admincustom-collections-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Custom
      - Collections
    post:
      summary: Create a new custom collection
      description: Create a new custom collection.
      operationId: postAdminCustomCollections.json
      x-api-path-slug: admincustom-collections-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Custom
      - Collection
  /admin/script_tags/373484.json:
    get:
      summary: Get a single  script tag
      description: Get a single  script tag.
      operationId: getAdminScriptTags373484.json
      x-api-path-slug: adminscript-tags373484-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Script
      - Tag
  /admin/comments/2941387470.json:
    put:
      summary: Update a comment
      description: Update a comment.
      operationId: putAdminComments2941387470.json
      x-api-path-slug: admincomments2941387470-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Comment
  /admin/smart_collections/401912846.json:
    get:
      summary: Get a single collection
      description: Get a single collection.
      operationId: getAdminSmartCollections401912846.json
      x-api-path-slug: adminsmart-collections401912846-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Collection
    put:
      summary: Update a single collection
      description: Update a single collection.
      operationId: putAdminSmartCollections401912846.json
      x-api-path-slug: adminsmart-collections401912846-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Collection
  /admin/products/9579007950.json:
    put:
      summary: Update a product and one of its variants
      description: Update a product and one of its variants.
      operationId: putAdminProducts9579007950.json
      x-api-path-slug: adminproducts9579007950-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Its
      - Variants
    delete:
      summary: Remove a product from the shop
      description: Remove a product from the shop.
      operationId: deleteAdminProducts9579007950.json
      x-api-path-slug: adminproducts9579007950-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Remove
      - Product
      - From
      - Shop
  /admin/orders/4554953422/refunds/calculate.json:
    post:
      summary: Calculate a refund for a line item and shipping
      description: Calculate a refund for a line item and shipping.
      operationId: postAdminOrders4554953422RefundsCalculate.json
      x-api-path-slug: adminorders4554953422refundscalculate-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Calculate
      - Refunda
      - Line
      - Item
      - Shipping
  /admin/collects.json:
    get:
      summary: List all collects
      description: List all collects.
      operationId: getAdminCollects.json
      x-api-path-slug: admincollects-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Collects
  /admin/blogs/62581763/articles.json:
    get:
      summary: Get a list of all articles from a certain blog
      description: Get a list of all articles from a certain blog.
      operationId: getAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Articles
      - From
      - Certain
      - Blog
    post:
      summary: Create a new article for a blog
      description: Create a new article for a blog.
      operationId: postAdminBlogs62581763Articles.json
      x-api-path-slug: adminblogs62581763articles-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Articlea
      - Blog
  /admin/metafields.json:
    get:
      summary: Get all metafields that belong to a store
      description: Get all metafields that belong to a store.
      operationId: getAdminMetafields.json
      x-api-path-slug: adminmetafields-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Metafields
      - That
      - Belong
      - To
      - Store
    post:
      summary: Create a new metafield for a store.
      description: Create a new metafield for a store..
      operationId: postAdminMetafields.json
      x-api-path-slug: adminmetafields-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Metafielda
      - Store
  /admin/gift_cards/61810574/disable.json:
    post:
      summary: Disable a gift card
      description: Disable a gift card.
      operationId: postAdminGiftCards61810574Disable.json
      x-api-path-slug: admingift-cards61810574disable-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Disable
      - Gift
      - Card
  /admin/webhooks/503738446.json:
    put:
      summary: Update a Webhook
      description: Update a webhook.
      operationId: putAdminWebhooks503738446.json
      x-api-path-slug: adminwebhooks503738446-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Webhook
    delete:
      summary: Delete a Webhook
      description: Delete a webhook.
      operationId: deleteAdminWebhooks503738446.json
      x-api-path-slug: adminwebhooks503738446-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Webhook
  /admin/blogs/62581763/articles/196805774.json:
    get:
      summary: Get a single article by its ID and the ID of the parent blog
      description: Get a single article by its id and the id of the parent blog.
      operationId: getAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Article
      - By
      - Its
      - ID
      - ID
      - Parent
      - Blog
    put:
      summary: Update an article
      description: Update an article.
      operationId: putAdminBlogs62581763Articles196805774.json
      x-api-path-slug: adminblogs62581763articles196805774-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Article
  /admin/metafields/33145232974.json:
    get:
      summary: Get a single store metafield by ID
      description: Get a single store metafield by id.
      operationId: getAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Store
      - Metafield
      - By
      - ID
    put:
      summary: Update an existing store metafield.
      description: Update an existing store metafield..
      operationId: putAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Existing
      - Store
      - Metafield
    delete:
      summary: Delete a store metafield
      description: Delete a store metafield.
      operationId: deleteAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Store
      - Metafield
  /admin/orders/4554953422/cancel.json:
    post:
      summary: Canceling an Order
      description: Canceling an order.
      operationId: postAdminOrders4554953422Cancel.json
      x-api-path-slug: adminorders4554953422cancel-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Canceling
      - Order
  /admin/gift_cards/61466894.json:
    get:
      summary: Show a specific gift card's details
      description: Show a specific gift card's details.
      operationId: getAdminGiftCards61466894.json
      x-api-path-slug: admingift-cards61466894-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Show
      - Specific
      - Gift
      - Cards
      - Details
  /admin/orders/4554953422/close.json:
    post:
      summary: Close a processed order
      description: Close a processed order.
      operationId: postAdminOrders4554953422Close.json
      x-api-path-slug: adminorders4554953422close-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Close
      - Processed
      - Order
  /admin/orders/4602125518/risks.json:
    get:
      summary: Get all Order Risks for an Order
      description: Get all order risks for an order.
      operationId: getAdminOrders4602125518Risks.json
      x-api-path-slug: adminorders4602125518risks-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Order
      - Risksan
      - Order
    post:
      summary: Add a fraud risk for Proxy detection
      description: Add a fraud risk for proxy detection.
      operationId: postAdminOrders4602125518Risks.json
      x-api-path-slug: adminorders4602125518risks-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Fraud
      - RiskProxy
      - Detection
  /admin/blogs.json:
    get:
      summary: Get a list of all blogs
      description: Get a list of all blogs.
      operationId: getAdminBlogs.json
      x-api-path-slug: adminblogs-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Blogs
    post:
      summary: Create a new blog
      description: Create a new blog.
      operationId: postAdminBlogs.json
      x-api-path-slug: adminblogs-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Blog
  /admin/policies.json:
    get:
      summary: getting the shops policies
      description: Getting the shops policies.
      operationId: getAdminPolicies.json
      x-api-path-slug: adminpolicies-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Getting
      - Shops
      - Policies
  /admin/orders/4554953422/events.json:
    get:
      summary: Get all the events from a particular order
      description: Get all the events from a particular order.
      operationId: getAdminOrders4554953422Events.json
      x-api-path-slug: adminorders4554953422events-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Events
      - From
      - Particular
      - Order
  /admin/pages/count.json:
    get:
      summary: Count all pages for a shop
      description: Count all pages for a shop.
      operationId: getAdminPagesCount.json
      x-api-path-slug: adminpagescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Pagesa
      - Shop
  /admin/orders/4554953422/transactions/count.json:
    get:
      summary: Get a count of transactions for an order
      description: Get a count of transactions for an order.
      operationId: getAdminOrders4554953422TransactionsCount.json
      x-api-path-slug: adminorders4554953422transactionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Transactionsan
      - Order
  /admin/gift_cards/count.json:
    get:
      summary: Retrieve a count of all gift cards
      description: Retrieve a count of all gift cards.
      operationId: getAdminGiftCardsCount.json
      x-api-path-slug: admingift-cardscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Count
      - Gift
      - Cards
  /admin/countries.json:
    get:
      summary: Get a list of all countries
      description: Get a list of all countries.
      operationId: getAdminCountries.json
      x-api-path-slug: admincountries-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Countries
    post:
      summary: Create a country
      description: Create a country.
      operationId: postAdminCountries.json
      x-api-path-slug: admincountries-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Country
  /admin/fulfillment_services.json:
    get:
      summary: List your app's fulfillment services
      description: List your app's fulfillment services.
      operationId: getAdminFulfillmentServices.json
      x-api-path-slug: adminfulfillment-services-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Your
      - Apps
      - Fulfillment
      - Services
    post:
      summary: Create a fulfillment service
      description: Create a fulfillment service.
      operationId: postAdminFulfillmentServices.json
      x-api-path-slug: adminfulfillment-services-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Fulfillment
      - Service
  /admin/pages/216307854.json:
    put:
      summary: update a page
      description: Update a page.
      operationId: putAdminPages216307854.json
      x-api-path-slug: adminpages216307854-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Page
    delete:
      summary: Delete a page
      description: Delete a page.
      operationId: deleteAdminPages216307854.json
      x-api-path-slug: adminpages216307854-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Page
  /admin/customers/3989659651/addresses/5484465742.json:
    put:
      summary: Updating a customers postal code
      description: Updating a customers postal code.
      operationId: putAdminCustomers3989659651Addresses5484465742.json
      x-api-path-slug: admincustomers3989659651addresses5484465742-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Updating
      - Customers
      - Postal
      - Code
    delete:
      summary: Removing a customers address
      description: Removing a customers address.
      operationId: deleteAdminCustomers3989659651Addresses5484465742.json
      x-api-path-slug: admincustomers3989659651addresses5484465742-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Removing
      - Customers
      - Address
  /admin/customers/search.json:
    get:
      summary: Get all customers with an address in the Brazil
      description: Get all customers with an address in the brazil.
      operationId: getAdminCustomersSearch.json
      x-api-path-slug: admincustomerssearch-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: query
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Customers
      - Address
      - In
      - Brazil
  /admin/application_charges.json:
    get:
      summary: Retrieving all one-time charges since a specified ID
      description: Retrieving all one-time charges since a specified id.
      operationId: getAdminApplicationCharges.json
      x-api-path-slug: adminapplication-charges-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: since_id
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieving
      - One-time
      - Charges
      - Since
      - Specified
      - ID
    post:
      summary: Create a new one-time application charge.
      description: Create a new one-time application charge..
      operationId: postAdminApplicationCharges.json
      x-api-path-slug: adminapplication-charges-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - One-time
      - Application
      - Charge
  /admin/blogs/62581763/articles/count.json:
    get:
      summary: Get a count of all articles from a certain blog
      description: Get a count of all articles from a certain blog.
      operationId: getAdminBlogs62581763ArticlesCount.json
      x-api-path-slug: adminblogs62581763articlescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Articles
      - From
      - Certain
      - Blog
  /admin/metafields/count.json:
    get:
      summary: Get a count of all metafields for a store
      description: Get a count of all metafields for a store.
      operationId: getAdminMetafieldsCount.json
      x-api-path-slug: adminmetafieldscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Metafieldsa
      - Store
  /admin/custom_collections/246409795.json:
    get:
      summary: Get a single custom collections
      description: Get a single custom collections.
      operationId: getAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Custom
      - Collections
    put:
      summary: update a custom collection
      description: Update a custom collection.
      operationId: putAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Custom
      - Collection
    delete:
      summary: delete a custom collection
      description: Delete a custom collection.
      operationId: deleteAdminCustomCollections246409795.json
      x-api-path-slug: admincustom-collections246409795-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Delete
      - Custom
      - Collection
  //admin/comments.json:
    post:
      summary: Create a new comment for an article
      description: Create a new comment for an article.
      operationId: postAdminComments.json
      x-api-path-slug: admincomments-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Commentan
      - Article
  /admin/customers/3989659651/addresses.json:
    get:
      summary: Get all of a customer's addresses
      description: Get all of a customer's addresses.
      operationId: getAdminCustomers3989659651Addresses.json
      x-api-path-slug: admincustomers3989659651addresses-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Customers
      - Addresses
    post:
      summary: Creating a new address for a customer
      description: Creating a new address for a customer.
      operationId: postAdminCustomers3989659651Addresses.json
      x-api-path-slug: admincustomers3989659651addresses-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Creating
      - New
      - Addressa
      - Customer
  /admin/comments/#{id}.json:
    get:
      summary: Get a single comment
      description: Get a single comment.
      operationId: getAdminComments#.json
      x-api-path-slug: admincommentsid-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Comment
  /admin/gift_cards.json:
    get:
      summary: Get a list of all gift cards
      description: Get a list of all gift cards.
      operationId: getAdminGiftCards.json
      x-api-path-slug: admingift-cards-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Gift
      - Cards
    post:
      summary: Create a new gift card with an automatically generated code
      description: Create a new gift card with an automatically generated code.
      operationId: postAdminGiftCards.json
      x-api-path-slug: admingift-cards-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Gift
      - Card
      - Automatically
      - Generated
      - Code
  /admin/articles/tags.json:
    get:
      summary: Get a list of all the tags of articles
      description: Get a list of all the tags of articles.
      operationId: getAdminArticlesTags.json
      x-api-path-slug: adminarticlestags-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Tags
      - Articles
  /admin/orders/4602125518/risks/8609858574.json:
    get:
      summary: Get a single Order Risk
      description: Get a single order risk.
      operationId: getAdminOrders4602125518Risks8609858574.json
      x-api-path-slug: adminorders4602125518risks8609858574-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Order
      - Risk
    put:
      summary: Update an existing risk detail line on an order
      description: Update an existing risk detail line on an order.
      operationId: putAdminOrders4602125518Risks8609858574.json
      x-api-path-slug: adminorders4602125518risks8609858574-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Existing
      - Risk
      - Detail
      - Line
      - "On"
      - Order
    delete:
      summary: Delete an erroneous risk entry
      description: Delete an erroneous risk entry.
      operationId: deleteAdminOrders4602125518Risks8609858574.json
      x-api-path-slug: adminorders4602125518risks8609858574-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Erroneous
      - Risk
      - Entry
  /admin/orders/4495703502/fulfillments.json:
    get:
      summary: Get a list of all fulfillments for an order.
      description: Get a list of all fulfillments for an order..
      operationId: getAdminOrders4495703502Fulfillments.json
      x-api-path-slug: adminorders4495703502fulfillments-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Fulfillmentsan
      - Order
  /admin/variants/34705478094.json:
    put:
      summary: Update an existing product variant
      description: Update an existing product variant.
      operationId: putAdminVariants34705478094.json
      x-api-path-slug: adminvariants34705478094-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Existing
      - Product
      - Variant
  /admin/customer_saved_searches/1189248515/customers.json:
    get:
      summary: Get all customers who match the criteria
      description: Get all customers who match the criteria.
      operationId: getAdminCustomerSavedSearches1189248515Customers.json
      x-api-path-slug: admincustomer-saved-searches1189248515customers-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Customers
      - Who
      - Match
      - Criteria
  /admin/orders/4554953422/refunds.json:
    get:
      summary: Get all refunds from a specific order
      description: Get all refunds from a specific order.
      operationId: getAdminOrders4554953422Refunds.json
      x-api-path-slug: adminorders4554953422refunds-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Refunds
      - From
      - Specific
      - Order
    post:
      summary: Create a new refund for an order
      description: Create a new refund for an order.
      operationId: postAdminOrders4554953422Refunds.json
      x-api-path-slug: adminorders4554953422refunds-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Refundan
      - Order
  /admin/orders/4528049998/fulfillments/3770145678/cancel.json:
    post:
      summary: Cancel a fulfillment.
      description: Cancel a fulfillment..
      operationId: postAdminOrders4528049998Fulfillments3770145678Cancel.json
      x-api-path-slug: adminorders4528049998fulfillments3770145678cancel-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Cancel
      - Fulfillment
  /admin/orders/4554953422.json:
    get:
      summary: Get a representation of a single order
      description: Get a representation of a single order.
      operationId: getAdminOrders4554953422.json
      x-api-path-slug: adminorders4554953422-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Representation
      - Single
      - Order
    put:
      summary: Update an order
      description: Update an order.
      operationId: putAdminOrders4554953422.json
      x-api-path-slug: adminorders4554953422-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Order
    delete:
      summary: Delete an order.
      description: Delete an order..
      operationId: deleteAdminOrders4554953422.json
      x-api-path-slug: adminorders4554953422-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Order
  /admin/orders/4554953422/open.json:
    post:
      summary: Re-opening a closed Order
      description: Re-opening a closed order.
      operationId: postAdminOrders4554953422Open.json
      x-api-path-slug: adminorders4554953422open-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Re-opening
      - Closed
      - Order
  /admin/orders/4528049998/fulfillments/3770145678/complete.json:
    post:
      summary: Complete a fulfillment.
      description: Complete a fulfillment..
      operationId: postAdminOrders4528049998Fulfillments3770145678Complete.json
      x-api-path-slug: adminorders4528049998fulfillments3770145678complete-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Complete
      - Fulfillment
  /admin/smart_collections.json:
    get:
      summary: Get all collection
      description: Get all collection.
      operationId: getAdminSmartCollections.json
      x-api-path-slug: adminsmart-collections-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Collection
    post:
      summary: Create a new collection
      description: Create a new collection.
      operationId: postAdminSmartCollections.json
      x-api-path-slug: adminsmart-collections-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Collection
  /admin/orders/4495703502/fulfillments/3763917198/events/9519874062.json:
    delete:
      summary: Delete a fulfillment event.
      description: Delete a fulfillment event..
      operationId: deleteAdminOrders4495703502Fulfillments3763917198Events9519874062.json
      x-api-path-slug: adminorders4495703502fulfillments3763917198events9519874062-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Fulfillment
      - Event
  /admin/events/58706658318.json:
    get:
      summary: Shows the same fields as the list action.
      description: Shows the same fields as the list action..
      operationId: getAdminEvents58706658318.json
      x-api-path-slug: adminevents58706658318-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Shows
      - Same
      - Fields
      - As
      - List
      - Action
  /admin/locations/8790723.json:
    get:
      summary: Get a single location
      description: Get a single location.
      operationId: getAdminLocations8790723.json
      x-api-path-slug: adminlocations8790723-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Location
  /admin/products/7990943555/images.json:
    get:
      summary: Get all product images
      description: Get all product images.
      operationId: getAdminProducts7990943555Images.json
      x-api-path-slug: adminproducts7990943555images-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Images
    post:
      summary: Create a new product image
      description: Create a new product image.
      operationId: postAdminProducts7990943555Images.json
      x-api-path-slug: adminproducts7990943555images-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Product
      - Image
  /admin/webhooks.json:
    get:
      summary: Get a list of all webhooks for your shop.
      description: Get a list of all webhooks for your shop..
      operationId: getAdminWebhooks.json
      x-api-path-slug: adminwebhooks-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Webhooksyour
      - Shop
    post:
      summary: Create a webhook
      description: Create a webhook.
      operationId: postAdminWebhooks.json
      x-api-path-slug: adminwebhooks-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Webhook
  /admin/products/7990943555/metafields/count.json:
    get:
      summary: Get a count of all metafields that belong to a product
      description: Get a count of all metafields that belong to a product.
      operationId: getAdminProducts7990943555MetafieldsCount.json
      x-api-path-slug: adminproducts7990943555metafieldscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Metafields
      - That
      - Belong
      - To
      - Product
  /admin/orders.json:
    get:
      summary: Get all orders from a customer
      description: Get all orders from a customer.
      operationId: getAdminOrders.json
      x-api-path-slug: adminorders-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: customer_id
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Orders
      - From
      - Customer
    post:
      summary: Create a pending order with an existing customer
      description: Create a pending order with an existing customer.
      operationId: postAdminOrders.json
      x-api-path-slug: adminorders-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Pending
      - Order
      - Existing
      - Customer
  /admin/webhooks/count.json:
    get:
      summary: Get a count of all webhooks for your shop.
      description: Get a count of all webhooks for your shop..
      operationId: getAdminWebhooksCount.json
      x-api-path-slug: adminwebhookscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Webhooksyour
      - Shop
  /admin/countries/444574734.json:
    put:
      summary: update a country
      description: Update a country.
      operationId: putAdminCountries444574734.json
      x-api-path-slug: admincountries444574734-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Update
      - Country
    delete:
      summary: delete a country
      description: Delete a country.
      operationId: deleteAdminCountries444574734.json
      x-api-path-slug: admincountries444574734-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Delete
      - Country
  /admin/carrier_services.json:
    get:
      summary: List carrier services
      description: List carrier services.
      operationId: getAdminCarrierServices.json
      x-api-path-slug: admincarrier-services-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Carrier
      - Services
    post:
      summary: Create a carrier service
      description: Create a carrier service.
      operationId: postAdminCarrierServices.json
      x-api-path-slug: admincarrier-services-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Carrier
      - Service
  /admin/collects/20713233987.json:
    get:
      summary: Return a collect with a certain id
      description: Return a collect with a certain id.
      operationId: getAdminCollects20713233987.json
      x-api-path-slug: admincollects20713233987-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Return
      - Collect
      - Certain
      - Id
  /admin/discounts/2951196163.json:
    get:
      summary: Retrieve a discount
      description: Retrieve a discount.
      operationId: getAdminDiscounts2951196163.json
      x-api-path-slug: admindiscounts2951196163-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Discount
    delete:
      summary: Delete a discount
      description: Delete a discount.
      operationId: deleteAdminDiscounts2951196163.json
      x-api-path-slug: admindiscounts2951196163-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Discount
  /admin/fulfillment_services/1357646.json:
    get:
      summary: Get a single fulfillment service by its ID
      description: Get a single fulfillment service by its id.
      operationId: getAdminFulfillmentServices1357646.json
      x-api-path-slug: adminfulfillment-services1357646-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Fulfillment
      - Service
      - By
      - Its
      - ID
    put:
      summary: Update a fulfillment service
      description: Update a fulfillment service.
      operationId: putAdminFulfillmentServices1357646.json
      x-api-path-slug: adminfulfillment-services1357646-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Fulfillment
      - Service
    delete:
      summary: Destroy a fulfillment service
      description: Destroy a fulfillment service.
      operationId: deleteAdminFulfillmentServices1357646.json
      x-api-path-slug: adminfulfillment-services1357646-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Destroy
      - Fulfillment
      - Service
  /admin/customers/3989659651/addresses/5436816654/default.json:
    put:
      summary: assigning a new default address to a customer
      description: Assigning a new default address to a customer.
      operationId: putAdminCustomers3989659651Addresses5436816654Default.json
      x-api-path-slug: admincustomers3989659651addresses5436816654default-json-put
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Assigning
      - New
      - Default
      - Address
      - To
      - Customer
  /admin/products/7990943555/variants/count.json:
    get:
      summary: Get a count of variants for a product
      description: Get a count of variants for a product.
      operationId: getAdminProducts7990943555VariantsCount.json
      x-api-path-slug: adminproducts7990943555variantscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Variantsa
      - Product
  /admin/pages.json:
    get:
      summary: Get a list of all pages
      description: Get a list of all pages.
      operationId: getAdminPages.json
      x-api-path-slug: adminpages-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Pages
    post:
      summary: Create a new page
      description: Create a new page.
      operationId: postAdminPages.json
      x-api-path-slug: adminpages-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Page
  /admin/comments/2941387470/spam.json:
    post:
      summary: Mark a comment as Spam
      description: Mark a comment as spam.
      operationId: postAdminComments2941387470Spam.json
      x-api-path-slug: admincomments2941387470spam-json-post
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Mark
      - Comment
      - As
      - Spam
  /admin/customers/3989659651/addresses/set.json:
    put:
      summary: destroying multiple customer addresses
      description: Destroying multiple customer addresses.
      operationId: putAdminCustomers3989659651AddressesSet.json
      x-api-path-slug: admincustomers3989659651addressesset-json-put
      parameters:
      - in: query
        name: address_ids[]
      - in: header
        name: Content-Type
      - in: query
        name: operation
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Destroying
      - Multiple
      - Customer
      - Addresses
  /admin//variants/25831837123.json:
    get:
      summary: Get a product variant by id
      description: Get a product variant by id.
      operationId: getAdminVariants25831837123.json
      x-api-path-slug: adminvariants25831837123-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Variant
      - By
      - Id
  /admin/themes/110163843/assets.json:
    get:
      summary: Get a list of all theme assets
      description: Get a list of all theme assets.
      operationId: getAdminThemes110163843Assets.json
      x-api-path-slug: adminthemes110163843assets-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Theme
      - Assets
    put:
      summary: Change an existing liquid template's value
      description: Change an existing liquid template's value.
      operationId: putAdminThemes110163843Assets.json
      x-api-path-slug: adminthemes110163843assets-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Change
      - Existing
      - Liquid
      - Templates
      - Value
    delete:
      summary: Remove assets from your shop
      description: Remove assets from your shop.
      operationId: deleteAdminThemes110163843Assets.json
      x-api-path-slug: adminthemes110163843assets-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Remove
      - Assets
      - From
      - Your
      - Shop
  /admin/redirects/count.json:
    get:
      summary: Get a countt of all URL redirect
      description: Get a countt of all url redirect.
      operationId: getAdminRedirectsCount.json
      x-api-path-slug: adminredirectscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Countt
      - URL
      - Redirect
  /account/login:
    post:
      summary: Hack Authentication
      description: Hack authentication.
      operationId: postAccountLogin
      x-api-path-slug: accountlogin-post
      parameters:
      - in: header
        name: Content-Type
      - in: formData
        name: customer[email]
      - in: formData
        name: customer[{{password}}]
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Hack
      - Authentication
  /admin/comments.json:
    get:
      summary: Get a list of all comments
      description: Get a list of all comments.
      operationId: getAdminComments.json
      x-api-path-slug: admincomments-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Comments
  /admin/products/7990943555/images/19489404942.json:
    get:
      summary: Get a single product image by id
      description: Get a single product image by id.
      operationId: getAdminProducts7990943555Images19489404942.json
      x-api-path-slug: adminproducts7990943555images19489404942-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - Image
      - By
      - Id
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---