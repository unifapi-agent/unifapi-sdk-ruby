# Unifapi::InstagramPost

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Instagram URL slug (&#x60;shortcode&#x60;). Path parameter for /instagram/posts/{id}/... endpoints. |  |
| **shortcode** | **String** |  |  |
| **media_id** | **String** |  |  |
| **media_type** | **Float** | Source media_type: 1 &#x3D; image, 2 &#x3D; video, 8 &#x3D; carousel |  |
| **product_type** | **String** | Source product_type: &#39;feed&#39; (image/photo), &#39;clips&#39; (reel), &#39;carousel_container&#39;, &#39;igtv&#39;, etc. |  |
| **taken_at** | **Float** | Unix-seconds timestamp. |  |
| **caption** | **String** |  |  |
| **accessibility_caption** | **String** |  |  |
| **image_url** | **String** | Largest available preview image (cover, for video/carousel). |  |
| **video_url** | **String** | Highest-quality video URL when applicable; empty string otherwise. |  |
| **like_count** | **Float** |  |  |
| **comment_count** | **Float** |  |  |
| **play_count** | **Float** | Video plays. 0 for non-video media. |  |
| **view_count** | **Float** | Reel/video views (separate from plays on IG side). 0 when N/A. |  |
| **is_paid_partnership** | **Boolean** |  |  |
| **has_audio** | **Boolean** |  |  |
| **carousel_count** | **Float** | Number of carousel items, or 0 if not a carousel. |  |
| **carousel** | [**Array&lt;InstagramCarouselItem&gt;**](InstagramCarouselItem.md) | Carousel items when media_type &#x3D;&#x3D;&#x3D; 8; empty array otherwise. |  |
| **user** | [**InstagramUserPreview**](InstagramUserPreview.md) |  |  |
| **location** | [**InstagramLocationLite**](InstagramLocationLite.md) |  |  |

## Example

```ruby
require 'unifapi'

instance = Unifapi::InstagramPost.new(
  id: null,
  shortcode: null,
  media_id: null,
  media_type: null,
  product_type: null,
  taken_at: null,
  caption: null,
  accessibility_caption: null,
  image_url: null,
  video_url: null,
  like_count: null,
  comment_count: null,
  play_count: null,
  view_count: null,
  is_paid_partnership: null,
  has_audio: null,
  carousel_count: null,
  carousel: null,
  user: null,
  location: null
)
```

