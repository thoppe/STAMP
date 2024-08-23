# STAMP
Social media Testing and Analysis of Metadata Preservation

This project updates the [2015 analysis](https://www.embeddedmetadata.org/social-media-test-results.php) by testing the retention of C2PA embedded metadata in images uploaded to various social media platforms, image hosting services, and online applications. The goal is to determine whether the content provenance data is preserved.

An [image](images/Original_08-06-2024.png) with C2PA embedded metadata was uploaded to various social media platforms, image hosting services, and online applications to check whether the content provenance data was retained. C2PA metadata was verified using the official [verification tool](https://contentcredentials.org/verify). The image was created with OpenAI's DALLE3 which contained a valid and signed C2PA manifest. C2PA metadata was verified using the official [verification tool](https://contentcredentials.org/verify).



| Site            | C2PA preserved | Category       | Date       | Archive image                          | Post URL                                                                                                                     |
|-----------------|----------------|----------------|------------|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| DALLE3 Original | 🟢 Yes            | Generative AI  | 08/06/24   | [🖼️](images/Original_08-06-2024.png)  |                                                                                                                             |
| Facebook        | ❌ No             | Social Media   | 08/22/24   | [🖼️](images/Facebook_08-22-2024.jpg)  | [Link](https://www.facebook.com/share/p/kMAWMf4uqatV27Uf/)                                                                  |
| Instagram       | ❌ No             | Social Media   | 08/07/24   | [🖼️](images/Instagram_08-07-2024.jpg) | [Link](https://www.instagram.com/p/C-YxEBYPiBN/)                                                                             |
| Twitter/X       | ❌ No             | Social Media   | 08/08/24   | [🖼️](images/Twitter_08-08-2024.jpeg)  | [Link](https://x.com/stee70184/status/1821523974196449456)                                                                  |
| LinkedIn        | ❌ No             | Social Media   | 08/23/24   | [🖼️](images/LinkedIn_08_23_2024.jpeg)  | [Link]()                                                                  |
| Reddit          | ❌ No             | Social Media   | 08/22/24   | [🖼️](images/Reddit_08-22-2024.png)    | [Link](https://www.reddit.com/r/test/comments/1eypggi/testing_c2pa/)                                                        |
| Quora           | ❌ No             | Social Media   | 08/22/24   | [🖼️](images/Quora_08-22-2024.webp)    | [Link](https://www.quora.com/profile/Jaxon-Steele-12/Testing-C2PA-https-x-com-hashtag-C2PA-src-hashtag_click)               |
| Pintrest        | ❌ No             | Social Media   | 08/22/24   | [🖼️](images/Pintrest_08-22-2024.png)  | [Link](https://www.pinterest.com/pin/1142788474188235637)                                                                   |
| Tumblr          | ❌ No             | Social Media   | 08/22/24   | [🖼️](images/Tumblr_08-22-2024.jpg)    | [Link](https://www.tumblr.com/jaxon-steele/759534908388622336/testing-c2pa)                                                 |
| Yelp            | ❌ No             | Social Media   | 08/22/24   | [🖼️](images/Yelp_08-22-2024.jpg)      | [Link](https://www.yelp.com/biz_photos/lafayette-park-washington?select=BMG8RM76QCYMJk2mBcH8mA)                             |
| Imgur           | ❌ No             | Image hosting  | 08/22/24   | [🖼️](images/Imgur_08-22-2024.png)     | [Link](https://imgur.com/a/xPNFm66)                                                                                         |
| Flickr          | 🟢 Yes            | Image hosting  | 08/22/24   | [🖼️](images/Flickr_08-22-2024.png)    | [Link](https://www.flickr.com/photos/201306481@N06/53940879615/in/dateposted-public/)                                        |
| Google Sheets   | 🟢 Yes            | Application    | 08/22/24   | [🖼️](images/GoogleSheets_08-22-2024.png) | [Link](https://docs.google.com/spreadsheets/d/1yumsdwVOMhnpk48WBfC5W81l456zVJod0g1agCrVAtU/edit?usp=sharing)                |
| Google Docs     | ❌ No             | Application    | 08/22/24   | [🖼️](images/GoogleDocs_08-22-2024.png)   | [Link](https://docs.google.com/document/d/15Rm0kVvLYQmsyOqK0V3jTYlLmVX9UWaumqj8jmTLvTM/edit?usp=sharing)                    |
| Google Slides   | ❌ No             | Application    | 08/22/24   | [🖼️](images/GoogleSlides_08-22-2024.png) | [Link](https://docs.google.com/presentation/d/1QVAaX3OKd-FFqLWyLOlyzz-D1rH5lVk98P_4ohTAweg/edit?usp=sharing)                |
| Google Photos   | 🟢 Yes            | Application    | 08/22/24   | [🖼️](images/GooglePhotos_08-22-2024.png) | [Link](https://photos.app.goo.gl/MXEqdfLMEi8Nwc9k7)                                                                         |

## Excluded sites

+ WhatApp (mobile chat)
+ Snapchat (mobile chat)
+ Clubhouse (mobile chat)
+ Twitch (video)
+ Youtube (video)
+ TikTok (video)
+ Facebook Messenger (mobile chat)

## Notes

+ In Google Sheets used right-click -> Save As.
+ In Google Docs and Google Slides saved to Keep and then downloaded.
+ Instagram does not provide an easy way to download files. Extracted image was taken by finding the original within the source.
+ LinkedIn was tested with a personal account and the test posted was deleted.