# Analysis of Meta Facebook advertising daily account reports
This project aims to provide the general background and performance of 1000 records of 53 Meta Facebook advertising accounts, which from that visualizing the result as well as giving valuable insights and suggestions for the executives. The dataset contains the daily report of each individual account recorded from October to November 2026.

## Overview
The dataset comprises of 1000 value rows and 44 columns, with their following descriptions:
| Column    | Description |
| :-------- | :------- |
|<kbd>pkId</kbd>|	Primary key for each ID records|
|<kbd>user_id</kbd>| Facebook user ID assigned to the ad account|
|<kbd>createdAt</kbd>|	Time when the ad account is created|
|<kbd>account_id</kbd>|	Unique Facebook ad account|
|<kbd>account_name</kbd>|	Name of Facebook ad account|
|<kbd>account_currency</kbd>|	Billing currency of Facebook ad account|
|<kbd>date_start</kbd>|	Date when an ad account is activated|
|<kbd>date_stop</kbd>|Date when an ad account is stopped|
|<kbd>newMessagingConnectionsN</kbd>|	Number of customer first-time chats acquired by clicking on that ad|
|<kbd>costPerNewMessagingN</kbd>|	Cost spent per first-time customer chat acquired|
|<kbd>spend</kbd>|	Total spending for each Facebook ad account|
|<kbd>impressions</kbd>| Total impressions contributed by the ad account |
|<kbd>clicks</kbd>|	Total clicks contributed by the ad account|
|<kbd>cpc</kbd>| Average advertising cost per click|
|<kbd>cpm</kbd>|Average cost of generating 1,000 advertising impressions|
|<kbd>ctr</kbd>|Click through rate: Percentage of impressions that resulted in clicks |
|<kbd>reach</kbd>|Total reaches contributed by the ad account|
|<kbd>frequency</kbd>|	The average number of times a person sees the ad during a specific period|
|<kbd>newMessagingConnections</kbd>|	num of customer chats acquired by clicking on an ad|
|<kbd>costPerNewMessaging</kbd>|Cost to get a customer chat|
|<kbd>leads</kbd>|Total leads contributed by the ad account	|
|<kbd>costLeads</kbd>|Cost per lead contributed by the ad account	|
|<kbd>purchases</kbd>|	Number of purchase conversion events attributed to the ad account|
|<kbd>costPurchases</kbd>|	Cost per purchase conversion event attributed to the ad account|
|<kbd>purchaseValue</kbd>|	Total value of purchase conversion events attributed to the ad account|
|<kbd>purchaseROAS</kbd>|Total Return on Ad Spend attributed to the ad account	|
|<kbd>websitePurchases</kbd>|	Number of purchase conversion events occurred on the website that are attributed to the ad account|
|<kbd>onFacebookPurchases</kbd>|	Number of purchase conversion events occurred on Facebook that are attributed to the ad account|
|<kbd>updatedAt</kbd>|Date when an ad account is updated	|
|<kbd>addsToCart</kbd>|Number of times users added products to their carts	|
|<kbd>checkoutsInitiated</kbd>|	Number of users who began the checkout process|
|<kbd>completedRegistration</kbd>|Number of completed registration or sign-up events attributed to advertisements	|
|<kbd>costPerAddToCart</kbd>|Average advertising cost per AddToCart event	|
|<kbd>costPerCheckoutInitiated</kbd>|Average advertising cost per initiated checkout event	|
|<kbd>costPerCompletedRegistration</kbd>|Average advertising cost per completed registration	|
|<kbd>completedRegistrationValue</kbd>|Total monetary value assigned to completed registration events|
|<kbd>costPerLandingPageView</kbd>|	Average advertising cost per successfully generated landing page view|
|<kbd>costPerThruPlay</kbd>|	Average advertising cost per ThruPlay|
|<kbd>costPerUniqueLinkClick</kbd>|	Average advertising cost per unique person/account who clicks a link. Repeat clicks by the same person are not counted as additional unique people|
|<kbd>landingPageViews</kbd>|Number of times users clicked an ad link and successfully loaded the destination landing page	|
|<kbd>leadsConversionValue</kbd>|	Total monetary value associated with attributed Lead events, where a value has been supplied through the tracking setup|
|<kbd>linkClicks</kbd>|	Total number of clicks on links within advertisements that lead to advertiser-specified destinations, either on or outside Meta|
|<kbd>postComments</kbd>|Number of comments on advertisements or associated posts|
|<kbd>thruPlay</kbd>|	Number of times users watched video advertisements for a meaningful duration|

## Analysis architecture
![Local image](./imgs/data_architecture.png)


