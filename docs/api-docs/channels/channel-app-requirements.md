# Channel App Requirements

<div class="otp" id="no-in">

### On this Page
- [General Requirements](#general-requirements)
- [Storefronts](#storefronts)
- [Marketplaces & Marketing](#marketplaces--marketing)
- [Resources](#resources)

</div>

Once approved, channel apps are discoverable on BigCommerce's App Marketplace. Additionally, apps developed by [select partners](https://www.bigcommerce.com/partners/) are marketed in the Channel Manager within the Control Panel of every store. To be approved, channel apps must meet certain requirements. This article lists the requirements for publishing channel apps to both locations.

## General Requirements

**All Partners**:
* Uses [Channels API](https://developer.bigcommerce.com/api-reference/cart-checkout/channels-listings-api)
* [Creates a channel ](https://developer.bigcommerce.com/api-reference/cart-checkout/channels-listings-api/channels/createchannel) upon app installation using the `app_id`
* Reads and updates channel status via [Channels endpoints](https://developer.bigcommerce.com/api-reference/cart-checkout/channels-listings-api)
* Follows requirements for specific channel type.
* Contains an onboarding user flow

**Select Partners**:
* Uses [Big Design](https://developer.bigcommerce.com/big-design/)

## Storefronts

**All Partners**:
* Must use [Sites & Routes API](https://developer.bigcommerce.com/api-reference/cart-checkout/sites-routes-api) so that links generated within BigCommerce, such as "view storefront" and links sent in transactional emails to shoppers, will use the headless storefront's correct URL.

## Marketplaces & Marketing

**All Partners**:
* Must use [listings API](https://developer.bigcommerce.com/api-reference/cart-checkout/channels-listings-api), if supporting per product listings (i.e. not simply syncing the entire catalog).

<div class="HubBlock--callout">
<div class="CalloutBlock--info">
<div class="HubBlock-content">

<!-- theme: info -->

### Note
> * In order to promote app performance and user experience best practices, additional general and channel type requirements will be outlined as needed.

</div>
</div>
</div>

## Resources

### Channels
* [Channels Overview](https://developer.bigcommerce.com/api-docs/channels/overview)
* [Building Channel Apps](https://developer.bigcommerce.com/api-docs/channels/building-channel-apps)
* [Channels API Reference](https://developer.bigcommerce.com/api-reference/cart-checkout/channels-listings-api)
* [Sites and Rites API Reference](https://developer.bigcommerce.com/api-reference/cart-checkout/sites-routes-api)

### Building Apps
* [Becoming a Partner](https://developer.bigcommerce.com/api-docs/partner/becoming-a-partner)
* [Types of Apps](https://developer.bigcommerce.com/api-docs/getting-started/building-apps-bigcommerce/types-of-apps)
* [Authenticating BigCommerce's REST APIs](https://developer.bigcommerce.com/api-docs/getting-started/authentication/rest-api-authentication)
* [Building an App](https://developer.bigcommerce.com/api-docs/getting-started/building-apps-bigcommerce/building-apps)
* [App Store Approval Requirements](https://developer.bigcommerce.com/api-docs/partner/app-store-approval-requirements)
