# Unifapi::SeoBacklinkItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **domain_from** | **String** | Domain of the page that links to the target. | [optional] |
| **url_from** | **String** | URL of the page that links to the target. | [optional] |
| **url_to** | **String** | Target URL the backlink points to. | [optional] |
| **domain_to** | **String** | Target domain the backlink points to. | [optional] |
| **anchor** | **String** | Anchor text of the backlink. | [optional] |
| **dofollow** | **Boolean** | Whether the backlink is dofollow. | [optional] |
| **item_type** | **String** | Type of backlink: anchor, image, link, redirect, or canonical. | [optional] |
| **rank** | **Integer** | Backlink rank of the referring page (0-1000). | [optional] |
| **page_from_rank** | **Integer** | Rank of the referring page itself (0-1000). | [optional] |
| **domain_from_rank** | **Integer** | Rank of the referring domain (0-1000). | [optional] |
| **backlink_spam_score** | **Integer** | Spam score of the referring page, 0-100. | [optional] |
| **is_new** | **Boolean** | Whether the backlink appeared since the last check. | [optional] |
| **is_lost** | **Boolean** | Whether the backlink was lost since the last check. | [optional] |
| **is_broken** | **Boolean** | Whether the backlink points to a broken page. | [optional] |
| **first_seen** | **String** | Date the backlink was first found. | [optional] |
| **last_seen** | **String** | Date the backlink was last seen. | [optional] |
| **prev_seen** | **String** | Previous date the backlink was seen before the last check (full view). | [optional] |
| **tld_from** | **String** | Top-level domain of the referring page (full view). | [optional] |
| **url_from_https** | **Boolean** | Whether the referring page uses HTTPS (full view). | [optional] |
| **url_to_https** | **Boolean** | Whether the target URL uses HTTPS (full view). | [optional] |
| **alt** | **String** | Alt text, if the backlink is an image link (full view). | [optional] |
| **image_url** | **String** | Image URL, if the backlink is an image link (full view). | [optional] |
| **text_pre** | **String** | Text immediately before the anchor (full view). | [optional] |
| **text_post** | **String** | Text immediately after the anchor (full view). | [optional] |
| **semantic_location** | **String** | Semantic location of the link on the page, e.g. article, footer (full view). | [optional] |
| **attributes** | **Array&lt;String&gt;** | Link rel attributes, e.g. nofollow, sponsored, ugc (full view). | [optional] |
| **links_count** | **Integer** | Number of identical links from the referring page (full view). | [optional] |
| **group_count** | **Integer** | Number of similar grouped links from the referring domain (full view). | [optional] |
| **page_from_title** | **String** | Title of the referring page (full view). | [optional] |
| **page_from_language** | **String** | Language of the referring page (full view). | [optional] |
| **page_from_status_code** | **Integer** | HTTP status code of the referring page (full view). | [optional] |
| **page_from_external_links** | **Integer** | Number of external links on the referring page (full view). | [optional] |
| **page_from_internal_links** | **Integer** | Number of internal links on the referring page (full view). | [optional] |
| **domain_from_country** | **String** | Country of the referring domain (full view). | [optional] |
| **domain_from_platform_type** | **Array&lt;String&gt;** | Platform types of the referring domain, e.g. cms, blogs (full view). | [optional] |
| **url_to_status_code** | **Integer** | HTTP status code of the target URL (full view). | [optional] |
| **url_to_redirect_target** | **String** | Redirect target of the backlink URL, if any (full view). | [optional] |
| **is_indirect_link** | **Boolean** | Whether the link reaches the target via a redirect or canonical (full view). | [optional] |

## Example

```ruby
require 'unifapi'

instance = Unifapi::SeoBacklinkItem.new(
  domain_from: null,
  url_from: null,
  url_to: null,
  domain_to: null,
  anchor: null,
  dofollow: null,
  item_type: null,
  rank: null,
  page_from_rank: null,
  domain_from_rank: null,
  backlink_spam_score: null,
  is_new: null,
  is_lost: null,
  is_broken: null,
  first_seen: null,
  last_seen: null,
  prev_seen: null,
  tld_from: null,
  url_from_https: null,
  url_to_https: null,
  alt: null,
  image_url: null,
  text_pre: null,
  text_post: null,
  semantic_location: null,
  attributes: null,
  links_count: null,
  group_count: null,
  page_from_title: null,
  page_from_language: null,
  page_from_status_code: null,
  page_from_external_links: null,
  page_from_internal_links: null,
  domain_from_country: null,
  domain_from_platform_type: null,
  url_to_status_code: null,
  url_to_redirect_target: null,
  is_indirect_link: null
)
```

