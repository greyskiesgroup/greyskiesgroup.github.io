# All The Clouds Corporation

## "Delivering clouds since the dawn of time"

## About All The Clouds

- All The Clouds is one of the world's most respected providers of cloud.

- Having been in the business of cloud provision for eons, All The Clouds has an extensive network of production facilities and sales offices, enabling them to guarantee global cloud delivery.

- All The Clouds prides themselves on being a world-class provider of clouds, and thanks to the power of their enterprise finance systems and global scale, they are able to offer local currency pricing to customers in the currency of their choice.

- All The Clouds operates a huge enterprise ERP system to ensure on-time delivery of clouds, but as we know, most ERPs were developed back in the dark ages and whilst they provide massive scale for the back-office of companies, they often struggle to keep up with the fast-changing world of customer demands.

- All The Clouds has overcome this limitation by building a modern API in front of their ERP so that their customers and resellers can access product information and place orders through the API rather than through the original batch processing system provided by their ERP.

- The API was initially developed to service the needs of a single reseller, but as time has passed, its use has expanded to more and more of their customers.

- Initially there wasn't much consideration given to API strategy or architecture, and as the API has incrementally evolved, All The Clouds has realised they will need to introduce some more appropriate controls on the API such as authentication and rate limiting to avoid misuse.

## API Specifics

- FX Rates are updated daily by All The Clouds from their FX provider. These daily snapshot prices are used at the time of order to calculate the correct price in local currency for any international orders in currencies other than AUD.

- As a result of the ad-hoc nature of the API project initially, it has not employed any versioning strategy. So far this hasn't caused any problems as the data models and endpoints have been additive only. All The Clouds have recognised that this is probably not an ideal situation and they have added API Versioning to their roadmap, but have not yet communicated what this will mean

- The API currently only supports submission of orders. Grey Skies Group has requested the ability to query and adjsut orders, and this has been added to their roadmap. No definite timeframe has been given for this enhancement, but it has been scheduled for Q1 2020.

## API Road Map

All The Clouds have announced that some of the following features and changes have been included in their 2020 development roadmap.

- Rate Limiting
- API Authentication
- API Versioning
- Order Querying
- Order Editing
- Order Cancellation
- Regional Endpoints
