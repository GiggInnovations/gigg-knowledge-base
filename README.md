# Gigg Board API Documentation

## Base URL
`https://prodapi.gigg.com/core/fanboard/`

## Overview
This endpoint retrieves a list of posts from a fanboard. It allows for filtering by media type and pagination.

## Endpoint
- **Method:** GET
- **URL:** `https://prodapi.gigg.com/core/fanboard/{orgId}/{boardId}/{pageNumber}`

## Request Parameters

### Path Parameters:
- `orgId`: The organization ID.
- `boardId`: The board ID.
- `pageNumber`: The page number of results to return.

### Query Parameters:
- `size`: (Optional) The number of posts to return. Default is 20.
- `postType`: (Optional) Filter posts by media type. Possible values are:
  - `image`: Return only image posts.
  - `video`: Return only video posts.
  - `text`: Return only text posts.
  - `!image`: Return all posts except image posts.
  - `!video`: Return all posts except video posts.
  - `!text`: Return all posts except text posts.

## Response

### Response Body:
```json
{
  "posts": [
    {
      "caption": "",
      "link": "",
      "media": [
        {
          "thumbnail": "https://dev.gigg.com.s3.us-east-1.amazonaws.com/images/5cdd7da337454927a0dbffe3/62d0945c-0412-4f85-b5b4-8869cb3d919f/image-a9c82a43-8f14-42dc-b201-f3a9921f9e82.jpg?token=cOGjVncmBq2BJO7-7GdUn2UEZZX2h1MKBWBJg0uGCNk&expires=1717339393",
          "medium": "https://dev.gigg.com.s3.us-east-1.amazonaws.com/images/5cdd7da337454927a0dbffe3/62d0945c-0412-4f85-b5b4-8869cb3d919f/image-a9c82a43-8f14-42dc-b201-f3a9921f9e82.jpg?token=cOGjVncmBq2BJO7-7GdUn2UEZZX2h1MKBWBJg0uGCNk&expires=1717339393",
          "large": "https://dev.gigg.com.s3.us-east-1.amazonaws.com/images/5cdd7da337454927a0dbffe3/62d0945c-0412-4f85-b5b4-8869cb3d919f/image-a9c82a43-8f14-42dc-b201-f3a9921f9e82.jpg?token=cOGjVncmBq2BJO7-7GdUn2UEZZX2h1MKBWBJg0uGCNk&expires=1717339393",
          "video": null
        }
      ],
      "time": 1714751488014,
      "service": "custom",
      "customLink": {
        "linkText": "Buy Now",
        "linkUrl": ""
      },
      "id": "62d0945c-0412-4f85-b5b4-8869cb3d919f"
    },
    {
      "caption": "A cap shun",
      "link": "",
      "media": [
        {
          "thumbnail": "https://s3.amazonaws.com/dev.gigg.com/images/5cdd7da337454927a0dbffe3/aed1504f-cc66-44de-a22a-5c43e324792a/image-b4bc717e-7b29-48d2-a3b8-6010ee2d2f80.jpg?token=ZMuAxyLfOVLbNFIu1tMxt9KDuhB-vU7CVV6DzQMjFBk&expires=1717343251",
          "medium": "https://s3.amazonaws.com/dev.gigg.com/images/5cdd7da337454927a0dbffe3/aed1504f-cc66-44de-a22a-5c43e324792a/image-b4bc717e-7b29-48d2-a3b8-6010ee2d2f80.jpg?token=ZMuAxyLfOVLbNFIu1tMxt9KDuhB-vU7CVV6DzQMjFBk&expires=1717343251",
          "large": "https://s3.amazonaws.com/dev.gigg.com/images/5cdd7da337454927a0dbffe3/aed1504f-cc66-44de-a22a-5c43e324792a/image-b4bc717e-7b29-48d2-a3b8-6010ee2d2f80.jpg?token=ZMuAxyLfOVLbNFIu1tMxt9KDuhB-vU7CVV6DzQMjFBk&expires=1717343251",
          "video": null
        }
      ],
      "time": 1711643326516,
      "service": "custom",
      "customLink": {
        "linkText": "Buy Now",
        "linkUrl": ""
      },
      "id": "aed1504f-cc66-44de-a22a-5c43e324792a"
    }
  ],
  "totalPages": 16,
  "timestamp": 1716910073109,
  "keywords": [
    "habsgivingday"
  ],
  "hashtagImageUrl": "/images/5cdd7da337454927a0dbffe3/a8ab3fc0-f493-4fe2-aa88-fc87768b243d/image.jpg?d=Wed Feb 19 2020 18:19:48 GMT+0000 (Coordinated Universal Time)",
  "options": {
    "primaryColor": "#7ED321",
    "showCTA": true,
    "slideDuration": 10,
    "CTAFrequency": 3,
    "shareTitle": "Look the heck out of this!",
    "showMoreBtn": true,
    "loadCount": 20,
    "doCalloutCTA": true,
    "calloutInterval": 60,
    "calloutDuration": 10,
    "carouselAutoplay": false,
    "carouselInterval": 8,
    "carouselInfinite": true,
    "carouselPostLimit": 15,
    "disableHashtagLinks": true,
    "disableDates": false,
    "singleHideCaptions": true
  }
}
