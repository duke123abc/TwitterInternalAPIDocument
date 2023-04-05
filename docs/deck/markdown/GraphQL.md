# Twitter Internal GraphQL API Document<br>
This document is entirely auto-generated and may contain errors.<br>
Please do not take what is written for granted, especially since static analysis of `variables` is very difficult. Most likely it is wrong.<br>
## Usage<br>
If the parameter is an array type, encode it in json format.<br>
Body example:<br>
```Python
json.dumps({
        "queryId": "oPHs3ydu7ZOOy2f02soaPA",
        "variables": json.dumps({
            "userId": "900282258736545792",
            "count": 40,
            "includePromotedContent": True,
            "withQuickPromoteEligibilityTweetFields": True,
            "withSuperFollowsUserFields": True,
            "withDownvotePerspective": False,
            "withReactionsMetadata": False,
            "withReactionsPerspective": False,
            "withSuperFollowsTweetFields": True,
            "withVoice": True,
            "withV2Timeline": True,
        }),
        "variables": json.dumps({
            "responsive_web_twitter_blue_verified_badge_is_enabled": True,
            "responsive_web_graphql_exclude_directive_enabled": False,
            "verified_phone_label_enabled": False,
            "responsive_web_graphql_timeline_navigation_enabled": True,
            "responsive_web_graphql_skip_user_profile_image_extensions_enabled": False,
            "longform_notetweets_consumption_enabled": True,
            "tweetypie_unmention_optimization_enabled": True,
            "vibe_api_enabled": True,
            "responsive_web_edit_tweet_api_enabled": True,
            "graphql_is_translatable_rweb_tweet_is_translatable_enabled": True,
            "view_counts_everywhere_api_enabled": True,
            "freedom_of_speech_not_reach_appeal_label_enabled": False,
            "standardized_nudges_misinfo": True,
            "tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled": False,
            "interactive_text_enabled": True,
            "responsive_web_text_conversations_enabled": False,
            "responsive_web_enhance_cards_enabled": False,
        }),
    })
```
`json.dumps` is equivalent to `JSON.stringify` in javaScript<br>
## BakeryQuery<br>
Request URL: `https://api.twitter.com/graphql/pROR-yRiBVsEjJyHt3fvhg/BakeryQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CheckTweetForNudge<br>
Request URL: `https://api.twitter.com/graphql/C2dcvh7H69JALtomErxWlA/CheckTweetForNudge`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                          | type    | variable   |
|:-----------------------------|:--------|:-----------|
| standardized_nudges_toxicity | boolean | False      |

#### queryId<br>
`None`<br>
## ConversationControlChange<br>
Request URL: `https://api.twitter.com/graphql/hb1elGcj6769uT8qVYqtjw/ConversationControlChange`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ConversationControlDelete<br>
Request URL: `https://api.twitter.com/graphql/OoMO_aSZ1ZXjegeamF9QmA/ConversationControlDelete`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateBookmark<br>
Request URL: `https://api.twitter.com/graphql/aoDbu3RHznuiSkQ9aNM67Q/CreateBookmark`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateNoteTweet<br>
Request URL: `https://api.twitter.com/graphql/C0dqBvnAKw4lRt6jufljXg/CreateNoteTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CreateRetweet<br>
Request URL: `https://api.twitter.com/graphql/ojPdsZsimiJrUGLR1sjUtA/CreateRetweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateTweet<br>
Request URL: `https://api.twitter.com/graphql/ADqGYPOhoHnTSqf6K9CqOQ/CreateTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CreateTweetDownvote<br>
Request URL: `https://api.twitter.com/graphql/Eo65jl-gww30avDgrXvhUA/CreateTweetDownvote`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateTweetReaction<br>
Request URL: `https://api.twitter.com/graphql/D7M6X3h4-mJE8UB1Ap3_dQ/CreateTweetReaction`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteBookmark<br>
Request URL: `https://api.twitter.com/graphql/Wlmlj2-xzyS1GN3a6cj-mQ/DeleteBookmark`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteRetweet<br>
Request URL: `https://api.twitter.com/graphql/iQtK4dl5hBmXewYZuEOKVw/DeleteRetweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteTweet<br>
Request URL: `https://api.twitter.com/graphql/VaenaVgh5q5ih7kvyVjgtg/DeleteTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteTweetDownvote<br>
Request URL: `https://api.twitter.com/graphql/VNEvEGXaUAMfiExP8Tbezw/DeleteTweetDownvote`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteTweetReaction<br>
Request URL: `https://api.twitter.com/graphql/GKwK0Rj4EdkfwdHQMZTpuw/DeleteTweetReaction`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## FavoriteTweet<br>
Request URL: `https://api.twitter.com/graphql/lI07N6Otwv1PhnEgXILM7A/FavoriteTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ModerateTweet<br>
Request URL: `https://api.twitter.com/graphql/pjFnHGVqCjTcZol0xcBJjw/ModerateTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TweetResultByRestId<br>
Request URL: `https://api.twitter.com/graphql/Piv9rEvfUUS51xtrjYwTJQ/TweetResultByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UnfavoriteTweet<br>
Request URL: `https://api.twitter.com/graphql/ZYKSe-w7KEslx3JhSIk5LA/UnfavoriteTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UnmentionUserFromConversation<br>
Request URL: `https://api.twitter.com/graphql/xVW9j3OqoBRY9d6_2OONEg/UnmentionUserFromConversation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UnmoderateTweet<br>
Request URL: `https://api.twitter.com/graphql/pVSyu6PA57TLvIE4nN2tsA/UnmoderateTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UsersVerifiedAvatars<br>
Request URL: `https://api.twitter.com/graphql/Bjbv9tA3kxsmhHDy_4yImw/UsersVerifiedAvatars`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |
| blue_business_consumption_api_enabled                 | boolean | True       |
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |

#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## DisableUserAccountLabel<br>
Request URL: `https://api.twitter.com/graphql/_ckHEj05gan2VfNHG6thBA/DisableUserAccountLabel`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserAccountLabel<br>
Request URL: `https://api.twitter.com/graphql/rD5gLxVmMvtdtYU1UHWlFQ/UserAccountLabel`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## articleNudgeDomains<br>
Request URL: `https://api.twitter.com/graphql/88Bu08U2ddaVVjKmmXjVYg/articleNudgeDomains`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AudioSpaceById<br>
Request URL: `https://api.twitter.com/graphql/3ezvhrC0YbcS2zW22Jekmg/AudioSpaceById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| spaces_2022_h2_clipping                                                 | boolean |          1 | nan       |
| spaces_2022_h2_spaces_communities                                       | boolean |          1 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## AudioSpaceSearch<br>
Request URL: `https://api.twitter.com/graphql/NTq79TuSz6fHj8lQaferJw/AudioSpaceSearch`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscribeToScheduledSpace<br>
Request URL: `https://api.twitter.com/graphql/Sxn4YOlaAwEKjnjWV0h7Mw/SubscribeToScheduledSpace`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UnsubscribeFromScheduledSpace<br>
Request URL: `https://api.twitter.com/graphql/Zevhh76Msw574ZSs2NQHGQ/UnsubscribeFromScheduledSpace`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchAliasSelect<br>
Request URL: `https://api.twitter.com/graphql/3ss48WFwGokBH_gj8t_8aQ/BirdwatchAliasSelect`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchContributorNotesSlice<br>
Request URL: `https://api.twitter.com/graphql/uXX-W7zb5joLyu2WL5PCfg/BirdwatchFetchContributorNotesSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BirdwatchCreateAppeal<br>
Request URL: `https://api.twitter.com/graphql/TKdL0YFsX4DMOpMKeneLvA/BirdwatchCreateAppeal`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchCreateNote<br>
Request URL: `https://api.twitter.com/graphql/XqqIWMFp8CXvteuifu-WUw/BirdwatchCreateNote`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |

#### queryId<br>
`None`<br>
## BirdwatchCreateRating<br>
Request URL: `https://api.twitter.com/graphql/xWLuzZoATvfEIEGxnsLt7w/BirdwatchCreateRating`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchDeleteNote<br>
Request URL: `https://api.twitter.com/graphql/IKS_qrShkDyor6Ri1ahd9g/BirdwatchDeleteNote`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchDeleteRating<br>
Request URL: `https://api.twitter.com/graphql/OpvCOyOoQClUND66zDzrnA/BirdwatchDeleteRating`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchEditNotificationSettings<br>
Request URL: `https://api.twitter.com/graphql/FLgLReVIssXjB_ui3wcrRQ/BirdwatchEditNotificationSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchAliasSelfSelectOptions<br>
Request URL: `https://api.twitter.com/graphql/szoXMke8AZOErso908iglw/BirdwatchFetchAliasSelfSelectOptions`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchAliasSelfSelectStatus<br>
Request URL: `https://api.twitter.com/graphql/LUEdtkcpBlGktUtms4BvwA/BirdwatchFetchAliasSelfSelectStatus`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchAuthenticatedUserProfile<br>
Request URL: `https://api.twitter.com/graphql/pMbW6Y4LuS5MzlSOEqERJQ/BirdwatchFetchAuthenticatedUserProfile`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchBirdwatchProfile<br>
Request URL: `https://api.twitter.com/graphql/btgGtchypc3D491MJ7XXWA/BirdwatchFetchBirdwatchProfile`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchGlobalTimeline<br>
Request URL: `https://api.twitter.com/graphql/ijR7o61Rpg1D-SDaA3k41A/BirdwatchFetchGlobalTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BirdwatchFetchNotes<br>
Request URL: `https://api.twitter.com/graphql/w9KDAJy8ZupCbV9dvx-JZQ/BirdwatchFetchNotes`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |

#### queryId<br>
`None`<br>
## BirdwatchFetchOneNote<br>
Request URL: `https://api.twitter.com/graphql/MAp8aUiUHI7HmNZClf0gjQ/BirdwatchFetchOneNote`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |

#### queryId<br>
`None`<br>
## BirdwatchFetchPublicData<br>
Request URL: `https://api.twitter.com/graphql/9bDdJ6AL26RLkcUShEcF-A/BirdwatchFetchPublicData`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchProfileAcknowledgeEarnOut<br>
Request URL: `https://api.twitter.com/graphql/cED9wJy8Nd1kZCCYuIq9zQ/BirdwatchProfileAcknowledgeEarnOut`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BizProfileFetchUser<br>
Request URL: `https://api.twitter.com/graphql/6OFpJ3TH3p8JpwOSgfgyhg/BizProfileFetchUser`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BookmarkFolderTimeline<br>
Request URL: `https://api.twitter.com/graphql/fhWahIXb2rf77I5qXpB9Ww/BookmarkFolderTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BookmarkFoldersSlice<br>
Request URL: `https://api.twitter.com/graphql/i78YDd0Tza-dV4SYs58kRg/BookmarkFoldersSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## bookmarkTweetToFolder<br>
Request URL: `https://api.twitter.com/graphql/4KHZvvNbHNf07bsgnL9gWA/bookmarkTweetToFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key   | type   | variable   |
|:------|:-------|:-----------|
| ...o  | ...    | _          |

#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Bookmarks<br>
Request URL: `https://api.twitter.com/graphql/Xq0wQSWHlcfnXARLJGqTxg/Bookmarks`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| graphql_timeline_v2_bookmark_timeline                                   | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## createBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/6Xxqpq8TM_CREYiuof_h5w/createBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BookmarksAllDelete<br>
Request URL: `https://api.twitter.com/graphql/skiACZKC1GDYli-M8RzEPQ/BookmarksAllDelete`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/2UTTsO-6zs93XqlEUZPsSg/DeleteBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EditBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/a6kPp1cS1Dgbsjhapz1PNw/EditBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RemoveTweetFromBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/2Qbj9XZvtUvyJB4gFwWfaA/RemoveTweetFromBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key              | type   | variable   |
|:-----------------|:-------|:-----------|
| twitterArticleId | ...    | l          |
| visibility       | ...    | s          |
| ...()(0,a.d)     | ...    | _          |

#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## LiveCommerceItemsSlice<br>
Request URL: `https://api.twitter.com/graphql/-lnNX56S2YrZYrLzbccFAQ/LiveCommerceItemsSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunitiesMainDiscoveryModule<br>
Request URL: `https://api.twitter.com/graphql/5-xqzGjFNR0N3wIXDXtU-Q/CommunitiesMainDiscoveryModule`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunitiesMainPageTimeline<br>
Request URL: `https://api.twitter.com/graphql/dcvNIcJT33Qew_ecZF3SsA/CommunitiesMainPageTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunitiesMembershipsSlice<br>
Request URL: `https://api.twitter.com/graphql/zuzTaN-XQMfhbkf1Bg_gHw/CommunitiesMembershipsSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunitiesMembershipsTimeline<br>
Request URL: `https://api.twitter.com/graphql/pKn7MKUpZaBFUp4CikEBnA/CommunitiesMembershipsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityAboutTimeline<br>
Request URL: `https://api.twitter.com/graphql/5cYFk5MrDsRTIaMVHfe8gQ/CommunityAboutTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CreateCommunity<br>
Request URL: `https://api.twitter.com/graphql/jOGxwQAtlISDFeBPejZcPg/CreateCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityDiscoveryTimeline<br>
Request URL: `https://api.twitter.com/graphql/bvx9dLyT3WeGJ7xINotKQA/CommunityDiscoveryTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityByRestId<br>
Request URL: `https://api.twitter.com/graphql/miaziJ8r2gMLMx2gSWCIWA/CommunityByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityHashtagsTimeline<br>
Request URL: `https://api.twitter.com/graphql/6H6G5z8F8FsgPMlGqFdwQA/CommunityHashtagsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## JoinCommunity<br>
Request URL: `https://api.twitter.com/graphql/Km7pos_ECDxyGuTrcz_LIw/JoinCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## LeaveCommunity<br>
Request URL: `https://api.twitter.com/graphql/5NAZbr_aCBp7COG2pVJGIA/LeaveCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityModerationKeepTweet<br>
Request URL: `https://api.twitter.com/graphql/OuWtDezV-8sW6c07EXxKQA/CommunityModerationKeepTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityModerationTweetCasesSlice<br>
Request URL: `https://api.twitter.com/graphql/1NS2BIyC6WzLMc7gzmqyRg/CommunityModerationTweetCasesSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RequestToJoinCommunity<br>
Request URL: `https://api.twitter.com/graphql/PR3PekeLK-Bz_JVlmPGJ4g/RequestToJoinCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityTweetsRankedTimeline<br>
Request URL: `https://api.twitter.com/graphql/Tya9tok5PpWr71FI3xL2Ug/CommunityTweetsRankedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/o-i_HxOG_T1v-ZzAYhKtlg/CommunityTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityUpdateRole<br>
Request URL: `https://api.twitter.com/graphql/cCUFo7d99y3T1_BS4_xCWA/CommunityUpdateRole`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityUserInvite<br>
Request URL: `https://api.twitter.com/graphql/el2xSrgrXBxyWvbz193qaA/CommunityUserInvite`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityCreateRule<br>
Request URL: `https://api.twitter.com/graphql/F87EsTHL2xuS6scArXHMDg/CommunityCreateRule`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditBannerMedia<br>
Request URL: `https://api.twitter.com/graphql/jRtMj3b-FyV2OR33Wk6vvw/CommunityEditBannerMedia`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditName<br>
Request URL: `https://api.twitter.com/graphql/PG2jxeN0zVbdINXViLEeww/CommunityEditName`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditPurpose<br>
Request URL: `https://api.twitter.com/graphql/-Wp3BPVvBh6KPDt2lsySQg/CommunityEditPurpose`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditRule<br>
Request URL: `https://api.twitter.com/graphql/_5THczaO5qZPAmWl7x0dLg/CommunityEditRule`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditTheme<br>
Request URL: `https://api.twitter.com/graphql/EkbBmRvDq4j_QiTcZDVHoQ/CommunityEditTheme`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityRemoveBannerMedia<br>
Request URL: `https://api.twitter.com/graphql/lzJvo9o9W6pWJBYDrTReog/CommunityRemoveBannerMedia`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityRemoveRule<br>
Request URL: `https://api.twitter.com/graphql/pfkQvHtD3trZ4hXuU9Emdg/CommunityRemoveRule`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityReorderRules<br>
Request URL: `https://api.twitter.com/graphql/P3qfEypw7aErj_LkBS7slw/CommunityReorderRules`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## TweetDetail<br>
Request URL: `https://api.twitter.com/graphql/nDM-d-uWksu2D4Xj0Wl_Ig/TweetDetail`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## DmAllSearchSlice<br>
Request URL: `https://api.twitter.com/graphql/EbxQ7cQUrv8cW3Y6cJGGMw/DmAllSearchSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key                             | type   | variable                                                                                                                                                                             |
|:--------------------------------|:-------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| count                           | ...    | (optional) t.count                                                                                                                                                                   |
| query                           | ...    | t.query                                                                                                                                                                              |
| withAttachments                 | ...    | i.isTrue()&&i.isTrue("dm_inbox_search_message_attachment_previews_enabled")&&i.isTrue("dm_inbox_search_message_results_enabled")                                                     |
| withConversationQueryHighlights | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")&&i.isTrue("dm_inbox_search_query_highlighting_conversation_results_enabled")                                                 |
| withMessageQueryHighlights      | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")&&i.isTrue("dm_inbox_search_query_highlighting_message_results_enabled")&&i.isTrue("dm_inbox_search_message_results_enabled") |
| withMessages                    | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")&&i.isTrue("dm_inbox_search_message_results_enabled")                                                                         |
| withSafetyModeUserFields        | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")                                                                                                                              |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## DmGroupSearchSlice<br>
Request URL: `https://api.twitter.com/graphql/5zpY1dCR-8NyxQJS_CFJoQ/DmGroupSearchSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DmMutedTimeline<br>
Request URL: `https://api.twitter.com/graphql/WkmUeSSOVNPxh-rbC_Mkzw/DmMutedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## DmPeopleSearchSlice<br>
Request URL: `https://api.twitter.com/graphql/xYSm8m5kJnzm_gFCn5GH-w/DmPeopleSearchSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DismissRitoSuggestedAction<br>
Request URL: `https://api.twitter.com/graphql/jYvwa61cv3NwNP24iUru6g/DismissRitoSuggestedAction`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateDraftTweet<br>
Request URL: `https://api.twitter.com/graphql/cH9HZWz_EW9gnswvA4ZRiQ/CreateDraftTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteDraftTweet<br>
Request URL: `https://api.twitter.com/graphql/bkh9G3FGgTldS9iTKWWYYw/DeleteDraftTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EditDraftTweet<br>
Request URL: `https://api.twitter.com/graphql/JIeXE-I6BZXHfxsgOkyHYQ/EditDraftTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## FetchDraftTweets<br>
Request URL: `https://api.twitter.com/graphql/ZkqIq_xRhiUme0PBJNpRtg/FetchDraftTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## WriteEmailNotificationSettings<br>
Request URL: `https://api.twitter.com/graphql/2qKKYFQift8p5-J1k6kqxQ/WriteEmailNotificationSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ViewerEmailSettings<br>
Request URL: `https://api.twitter.com/graphql/JpjlNgn4sLGvS6tgpTzYBg/ViewerEmailSettings`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ImmersiveMedia<br>
Request URL: `https://api.twitter.com/graphql/xyZOS_yKFat0w0HWKFRIuw/ImmersiveMedia`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GraphQLError<br>
Request URL: `https://api.twitter.com/graphql/2V2W3HIBuMW83vEMtfo_Rg/GraphQLError`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## HomeLatestTimeline<br>
Request URL: `https://api.twitter.com/graphql/1UNiFOLvPTRpu8zVk-LAXw/HomeLatestTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## HomeTimeline<br>
Request URL: `https://api.twitter.com/graphql/v7m3-T8yGC5cqy7doGpi5Q/HomeTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CardPreviewByTweetText<br>
Request URL: `https://api.twitter.com/graphql/N9yLYAxjVMlHUX0qENfZNQ/CardPreviewByTweetText`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_enhance_cards_enabled                              | boolean | False      |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CombinedLists<br>
Request URL: `https://api.twitter.com/graphql/NCzWxXF4zmQgfkb9-X12Hw/CombinedLists`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListAddMember<br>
Request URL: `https://api.twitter.com/graphql/05BjoR7aurmYI22etXocBQ/ListAddMember`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## DeleteListBanner<br>
Request URL: `https://api.twitter.com/graphql/CygCjKvWmZHHLLM7oLLX-g/DeleteListBanner`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key          | type   | variable   |
|:-------------|:-------|:-----------|
| listId       | ...    | r          |
| ...()(0,s.S) | ...    | _          |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## EditListBanner<br>
Request URL: `https://api.twitter.com/graphql/bdkWhnAxpzgwGwH-lPkMsA/EditListBanner`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListBySlug<br>
Request URL: `https://api.twitter.com/graphql/623MECMdC6fBnc49itmwdQ/ListBySlug`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CreateList<br>
Request URL: `https://api.twitter.com/graphql/XPAynCMUA_CaP7MNQOXbCw/CreateList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListCreationRecommendedUsers<br>
Request URL: `https://api.twitter.com/graphql/YJNbpuZJY95YYeWK6qxr7g/ListCreationRecommendedUsers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## DeleteList<br>
Request URL: `https://api.twitter.com/graphql/UnN9Th1BDbeLjpgjGSpL3Q/DeleteList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListEditRecommendedUsers<br>
Request URL: `https://api.twitter.com/graphql/WPtiML6oz9WDmMz2UZ_WrQ/ListEditRecommendedUsers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListLatestTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/FDI9EiIp54KxEOWGiv3B4A/ListLatestTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListMembers<br>
Request URL: `https://api.twitter.com/graphql/XsAJX17RLgLYU8GALIWg2g/ListMembers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListMemberships<br>
Request URL: `https://api.twitter.com/graphql/jnu-SyjP7-jiY8CuE0WsCQ/ListMemberships`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MuteList<br>
Request URL: `https://api.twitter.com/graphql/ZYyanJsskNUcltu9bliMLA/MuteList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListOwnerships<br>
Request URL: `https://api.twitter.com/graphql/mHETbEwW2vWNU_L7JijWIQ/ListOwnerships`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListPinOne<br>
Request URL: `https://api.twitter.com/graphql/whBN4jUV_rUs8AiBBv-qVw/ListPinOne`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListPins<br>
Request URL: `https://api.twitter.com/graphql/xP0YPWA4fPm2hYFHoqDLnQ/ListPins`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListByRestId<br>
Request URL: `https://api.twitter.com/graphql/KlGpwq5CAt9tCfHkV2mwYQ/ListByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key    | type   | variable   |
|:-------|:-------|:-----------|
| listId | ...    | l          |
| ...a   | ...    | _          |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListRankedTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/6ldXqXu3hPLWV8ZM0sbcZA/ListRankedTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key          | type   | variable   |
|:-------------|:-------|:-----------|
| ...n         | ...    | _          |
| ...()(0,a.S) | ...    | _          |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListRemoveMember<br>
Request URL: `https://api.twitter.com/graphql/32lW2xl4fksrTRB25SIR9g/ListRemoveMember`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListSubscribe<br>
Request URL: `https://api.twitter.com/graphql/2ZDSj2DhUUlUklIaNsO1DA/ListSubscribe`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListSubscribers<br>
Request URL: `https://api.twitter.com/graphql/wCHENI0upPf0Ly8NGWAVNw/ListSubscribers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UnmuteList<br>
Request URL: `https://api.twitter.com/graphql/pMZrHRNsmEkXgbn3tOyr7Q/UnmuteList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListUnpinOne<br>
Request URL: `https://api.twitter.com/graphql/yIVCXYI7OvIOCKCDq1JrSw/ListUnpinOne`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListUnsubscribe<br>
Request URL: `https://api.twitter.com/graphql/2J-RcURzQMzhgnu2cryIhA/ListUnsubscribe`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key    | type   | variable   |
|:-------|:-------|:-----------|
| listId | ...    | i          |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## UpdateList<br>
Request URL: `https://api.twitter.com/graphql/wweOiADrdfgFeSXkHbXrlQ/UpdateList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListsDiscovery<br>
Request URL: `https://api.twitter.com/graphql/VYOjTMWzm7QmalmpmJl3sQ/ListsDiscovery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key          | type   | variable   |
|:-------------|:-------|:-----------|
| listIds      | ...    | l          |
| ...()(0,s.S) | ...    | _          |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListsManagementPageTimeline<br>
Request URL: `https://api.twitter.com/graphql/mp39ddRX8yCoQUyxjrqogw/ListsManagementPageTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListsPinMany<br>
Request URL: `https://api.twitter.com/graphql/QM9ThyyEmuf5CfsDhTTxiQ/ListsPinMany`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## EnableLoggedOutWebNotifications<br>
Request URL: `https://api.twitter.com/graphql/BqIHKmwZKtiUBPi07jKctg/EnableLoggedOutWebNotifications`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## PinReply<br>
Request URL: `https://api.twitter.com/graphql/GA2_1uKP9b_GyR4MVAQXAw/PinReply`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UnpinReply<br>
Request URL: `https://api.twitter.com/graphql/iRe6ig5OV1EzOtldNIuGDQ/UnpinReply`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Likes<br>
Request URL: `https://api.twitter.com/graphql/XbHBYpgURwtklXj8NNxTDw/Likes`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserAboutTimeline<br>
Request URL: `https://api.twitter.com/graphql/ZTrOLi1XhslPdFQUE322eA/UserAboutTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserBusinessProfileTeamTimeline<br>
Request URL: `https://api.twitter.com/graphql/Xz02rH0t5J-IM34vmQ5KYw/UserBusinessProfileTeamTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key                    | type    | variable    |
|:-----------------------|:--------|:------------|
| userId                 | ...     | r           |
| count                  | ...     | t           |
| cursor                 | ...     | n           |
| teamName               | ...     | i           |
| includePromotedContent | boolean | False       |
| ...()(0,a.d)           | ...     | _           |
| withClientEventToken   | boolean | False       |
| withVoice              | ...     | _.isTrue(_) |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserMedia<br>
Request URL: `https://api.twitter.com/graphql/MA_EP2a21zpzNWKRkaPBMg/UserMedia`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserPromotableTweets<br>
Request URL: `https://api.twitter.com/graphql/l92DbYOLlYkDXA-MtQ1eWQ/UserPromotableTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserSuperFollowTweets<br>
Request URL: `https://api.twitter.com/graphql/Of6dyatCC-Oiic4J_udPbQ/UserSuperFollowTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key                    | type    | variable    |
|:-----------------------|:--------|:------------|
| userId                 | ...     | i           |
| count                  | ...     | t           |
| cursor                 | ...     | n           |
| includePromotedContent | boolean | True        |
| ...()(0,a.d)           | ...     | _           |
| withVoice              | ...     | _.isTrue(_) |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserTweets<br>
Request URL: `https://api.twitter.com/graphql/9rys0A7w1EyqVd2ME0QCJg/UserTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserTweetsAndReplies<br>
Request URL: `https://api.twitter.com/graphql/ehMCHF3Mkgjsfz_aImqOsg/UserTweetsAndReplies`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## SetDefault<br>
Request URL: `https://api.twitter.com/graphql/QEMLEzEMzoPNbeauKCCLbg/SetDefault`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeletePaymentMethod<br>
Request URL: `https://api.twitter.com/graphql/VaaLGwK5KNLoc7wsOmp4uw/DeletePaymentMethod`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## PaymentMethods<br>
Request URL: `https://api.twitter.com/graphql/mPF_G9okpbZuLcD6mN8K9g/PaymentMethods`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AdAccounts<br>
Request URL: `https://api.twitter.com/graphql/a8KxGfFQAmm3WxqemuqSRA/AdAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AudienceEstimate<br>
Request URL: `https://api.twitter.com/graphql/1LYVUabJBYkPlUAWRabB3g/AudienceEstimate`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Budgets<br>
Request URL: `https://api.twitter.com/graphql/mbK3oSQotwcJXyQIBE3uYw/Budgets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Coupons<br>
Request URL: `https://api.twitter.com/graphql/R1h43jnAl2bsDoUkgZb7NQ/Coupons`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateQuickPromotion<br>
Request URL: `https://api.twitter.com/graphql/oDSoVgHhJxnd5IkckgPZdg/CreateQuickPromotion`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## QuickPromoteEligibility<br>
Request URL: `https://api.twitter.com/graphql/LtpCXh66W-uXh7u7XSRA8Q/QuickPromoteEligibility`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EnrollCoupon<br>
Request URL: `https://api.twitter.com/graphql/SOyGmNGaEXcvk15s5bqDrA/EnrollCoupon`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RitoActionedTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/DQ-r9abxxEcEt4FBU80WsA/RitoActionedTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RitoFlaggedAccountsTimeline<br>
Request URL: `https://api.twitter.com/graphql/M3Oke69NcBch2RLTgx7MlA/RitoFlaggedAccountsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RitoFlaggedTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/nSYVgN4Ev8XJlsHKqN3YjA/RitoFlaggedTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RitoSuggestedActionsFacePile<br>
Request URL: `https://api.twitter.com/graphql/GnQKeEdL1LyeK3dTQCS1yw/RitoSuggestedActionsFacePile`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateScheduledTweet<br>
Request URL: `https://api.twitter.com/graphql/LCVzRQGxOaGnOnYH01NQXg/CreateScheduledTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteScheduledTweet<br>
Request URL: `https://api.twitter.com/graphql/CTOVqej0JBXAZSwkp1US0g/DeleteScheduledTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EditScheduledTweet<br>
Request URL: `https://api.twitter.com/graphql/_mHkQ5LHpRRjSXKOcG6eZw/EditScheduledTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## FetchScheduledTweets<br>
Request URL: `https://api.twitter.com/graphql/ITtjAzvlZni2wWXwf295Qg/FetchScheduledTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DisableVerifiedPhoneLabel<br>
Request URL: `https://api.twitter.com/graphql/g2m0pAOamawNtVIfjXNMJg/DisableVerifiedPhoneLabel`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EnableVerifiedPhoneLabel<br>
Request URL: `https://api.twitter.com/graphql/C3RJFfMsb_KcEytpKmRRkw/EnableVerifiedPhoneLabel`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ProfileUserPhoneState<br>
Request URL: `https://api.twitter.com/graphql/5kUWP8C1hcd6omvg6HXXTQ/ProfileUserPhoneState`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UserSessionsList<br>
Request URL: `https://api.twitter.com/graphql/vJ-XatpmQSG8bDch8-t9Jw/UserSessionsList`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## getAltTextPromptPreference<br>
Request URL: `https://api.twitter.com/graphql/PFIxTk8owMoZgiMccP0r4g/getAltTextPromptPreference`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## updateAltTextPromptPreference<br>
Request URL: `https://api.twitter.com/graphql/aQKrduk_DA46XfOQDkcEng/updateAltTextPromptPreference`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## getCaptionsAlwaysDisplayPreference<br>
Request URL: `https://api.twitter.com/graphql/BwgMOGpOViDS0ri7VUgglg/getCaptionsAlwaysDisplayPreference`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## updateCaptionsAlwaysDisplayPreference<br>
Request URL: `https://api.twitter.com/graphql/uCUQhvZ5sJ9qHinRp6CFlQ/updateCaptionsAlwaysDisplayPreference`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DataSaverMode<br>
Request URL: `https://api.twitter.com/graphql/xF6sXnKJfS2AOylzxRjf6A/DataSaverMode`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## WriteDataSaverPreferences<br>
Request URL: `https://api.twitter.com/graphql/H03etWvZGz41YASxAU2YPg/WriteDataSaverPreferences`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DmNsfwMediaFilterUpdate<br>
Request URL: `https://api.twitter.com/graphql/of_N6O33zfyD4qsFJMYFxA/DmNsfwMediaFilterUpdate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GetSafetyModeSettings<br>
Request URL: `https://api.twitter.com/graphql/AhxTX0lkbIos4WG53xwzSA/GetSafetyModeSettings`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SetSafetyModeSettings<br>
Request URL: `https://api.twitter.com/graphql/qSJIPIpf4gA7Wn21bT3D4w/SetSafetyModeSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SharingAudiospacesListeningDataWithFollowersUpdate<br>
Request URL: `https://api.twitter.com/graphql/5h0kNbk3ii97rmfY6CdgAA/SharingAudiospacesListeningDataWithFollowersUpdate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GetUserClaims<br>
Request URL: `https://api.twitter.com/graphql/lFi3xnx0auUUnyG4YwpCNw/GetUserClaims`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateCustomerPortalSession<br>
Request URL: `https://api.twitter.com/graphql/2LHXrd1uYeaMWhciZgPZFw/CreateCustomerPortalSession`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListProductSubscriptions<br>
Request URL: `https://api.twitter.com/graphql/wwdBYgScze0_Jnan79jEUw/ListProductSubscriptions`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscriptionCheckoutUrlWithEligibility<br>
Request URL: `https://api.twitter.com/graphql/hKfOOObQr5JmfmxW0YtPvg/SubscriptionCheckoutUrlWithEligibility`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscriptionProductDetails<br>
Request URL: `https://api.twitter.com/graphql/GZF6Vha91bWrZjDmZZ-VNA/SubscriptionProductDetails`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## FeatureSettingsUpdate<br>
Request URL: `https://api.twitter.com/graphql/-btar_vkBwWA7s3YWfp_9g/FeatureSettingsUpdate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscriptionProductFeaturesFetch<br>
Request URL: `https://api.twitter.com/graphql/Me2CVcAXxvK2WMr-Nh_Qqg/SubscriptionProductFeaturesFetch`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ArticleTimeline<br>
Request URL: `https://api.twitter.com/graphql/B5ZPsQ6y65Sww_cf8LWm6Q/ArticleTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ArticleTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/I2Y6NF8iWaKn5OkqxFMeZg/ArticleTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## NoteworthyAccountsPage<br>
Request URL: `https://api.twitter.com/graphql/rJ7mCScwRUUX-y01aizNaA/NoteworthyAccountsPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicFollow<br>
Request URL: `https://api.twitter.com/graphql/ElqSLWFmsPL4NlZI5e1Grg/TopicFollow`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key     | type   | variable   |
|:--------|:-------|:-----------|
| topicId | ...    | n          |

#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicLandingPage<br>
Request URL: `https://api.twitter.com/graphql/xL5ANL241izMQEgOOX1fQw/TopicLandingPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicNotInterested<br>
Request URL: `https://api.twitter.com/graphql/cPCFdDAaqRjlMRYInZzoDA/TopicNotInterested`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicByRestId<br>
Request URL: `https://api.twitter.com/graphql/4OUZZOonV2h60I0wdlQb_w/TopicByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicToFollowSidebar<br>
Request URL: `https://api.twitter.com/graphql/-xObYcPAhdlqQc6iMEjNQA/TopicToFollowSidebar`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicUndoNotInterested<br>
Request URL: `https://api.twitter.com/graphql/4tVnt6FoSxaX8L-mDDJo4Q/TopicUndoNotInterested`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicUnfollow<br>
Request URL: `https://api.twitter.com/graphql/srwjU6JM_ZKTj_QMfUGNcw/TopicUnfollow`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicsManagementPage<br>
Request URL: `https://api.twitter.com/graphql/LuJBpoxjvhTw_cFK3-tSHg/TopicsManagementPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicsPickerPage<br>
Request URL: `https://api.twitter.com/graphql/HinWDnpV9U9bHAFU34_XLQ/TopicsPickerPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicsPickerPageById<br>
Request URL: `https://api.twitter.com/graphql/LO3CiCCH_GrX_lYSNdHRjQ/TopicsPickerPageById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ViewingOtherUsersTopicsPage<br>
Request URL: `https://api.twitter.com/graphql/_Eu7ZMeN5M-sgkQfnvxNng/ViewingOtherUsersTopicsPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## AuthenticatedUserTFLists<br>
Request URL: `https://api.twitter.com/graphql/QjN8ZdavFDqxUjNn3r9cig/AuthenticatedUserTFLists`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateTrustedFriendsList<br>
Request URL: `https://api.twitter.com/graphql/2tP8XUYeLHKjq5RHvuvpZw/CreateTrustedFriendsList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Favoriters<br>
Request URL: `https://api.twitter.com/graphql/n6OEAX4QBqXfjhLma-RxFg/Favoriters`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Retweeters<br>
Request URL: `https://api.twitter.com/graphql/Z83XAg6CcWvrA3l4uzmJgw/Retweeters`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TweetEditHistory<br>
Request URL: `https://api.twitter.com/graphql/q21DsW7qxOTEmBRfBFE1HA/TweetEditHistory`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GetTweetReactionTimeline<br>
Request URL: `https://api.twitter.com/graphql/ic7XPiBInWKYbPcwsIURNw/GetTweetReactionTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TweetStats<br>
Request URL: `https://api.twitter.com/graphql/EvbTkPDT-xQCfupPu0rWMA/TweetStats`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                             | type    | variable   |
|:------------------------------------------------|:--------|:-----------|
| profile_foundations_tweet_stats_enabled         | boolean | False      |
| profile_foundations_tweet_stats_tweet_frequency | boolean | False      |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## TwitterArticleCreate<br>
Request URL: `https://api.twitter.com/graphql/g2OX8USKYcus_Z6zfTomIw/TwitterArticleCreate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleDelete<br>
Request URL: `https://api.twitter.com/graphql/6st-stMDc7KBqLT8KvWhHg/TwitterArticleDelete`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TwitterArticleByRestId<br>
Request URL: `https://api.twitter.com/graphql/YshrJY7-EBd6ZZsROUxZBA/TwitterArticleByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateCoverImage<br>
Request URL: `https://api.twitter.com/graphql/zMWfBgPb36cA-1Hc-67hsA/TwitterArticleUpdateCoverImage`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateData<br>
Request URL: `https://api.twitter.com/graphql/DQPnbro9xDikTvb33zemRw/TwitterArticleUpdateData`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateMedia<br>
Request URL: `https://api.twitter.com/graphql/P2HjIzZEvTMN40DgVon9hQ/TwitterArticleUpdateMedia`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateTitle<br>
Request URL: `https://api.twitter.com/graphql/y_5RufkvEsE8no2_eEqRMQ/TwitterArticleUpdateTitle`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateVisibility<br>
Request URL: `https://api.twitter.com/graphql/xd_PZueE4W4LZQyYnWUlNA/TwitterArticleUpdateVisibility`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticlesSlice<br>
Request URL: `https://api.twitter.com/graphql/-ohxO2o6V1tQvCfXppeOMw/TwitterArticlesSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityMemberRelationshipTypeahead<br>
Request URL: `https://api.twitter.com/graphql/npEFiYc3sCX-YDHZ1B69nw/CommunityMemberRelationshipTypeahead`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityUserRelationshipTypeahead<br>
Request URL: `https://api.twitter.com/graphql/C9CUCfAvlaMEhJBmM2hZkg/CommunityUserRelationshipTypeahead`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## TrustedFriendsTypeahead<br>
Request URL: `https://api.twitter.com/graphql/_vUIWq3vpyL0amiNTjrM-w/TrustedFriendsTypeahead`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |

#### queryId<br>
`None`<br>
## ConnectTabTimeline<br>
Request URL: `https://api.twitter.com/graphql/55VdvUgJedG_f3hgxMxn2Q/ConnectTabTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ExplorePage<br>
Request URL: `https://api.twitter.com/graphql/yF0e2a26mrZQdZSQrokPiw/ExplorePage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## timelinesFeedback<br>
Request URL: `https://api.twitter.com/graphql/vfVbgvTPTQ-dF_PQ5lD1WQ/timelinesFeedback`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UrtFixtures<br>
Request URL: `https://api.twitter.com/graphql/pb8L8foE_-pGGCUhlbzZjA/UrtFixtures`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RemoveFollower<br>
Request URL: `https://api.twitter.com/graphql/QpNfg0kpPRfjROQ_9eOLXA/RemoveFollower`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UserByRestId<br>
Request URL: `https://api.twitter.com/graphql/QPSxc9lxrmrwnBzYkJI8eA/UserByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## UserByScreenName<br>
Request URL: `https://api.twitter.com/graphql/nZjSkpOpSL5rWyIVdsKeLA/UserByScreenName`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## UsersByRestIds<br>
Request URL: `https://api.twitter.com/graphql/RPzwimxhSjZiykM5FeLnDw/UsersByRestIds`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## Viewer<br>
Request URL: `https://api.twitter.com/graphql/WHlX9F4T8YVmDAkcPNYf8g/Viewer`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CreateColumn<br>
Request URL: `https://api.twitter.com/graphql/O4iIdjZUiZpm0KBSiftNGQ/CreateColumn`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RemoveColumn<br>
Request URL: `https://api.twitter.com/graphql/lfB7GP4w9oCpx5F_BxwRkw/RemoveColumn`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateColumn<br>
Request URL: `https://api.twitter.com/graphql/suRGd49L2EZ0nuuU4he4aw/UpdateColumn`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ReorderColumns<br>
Request URL: `https://api.twitter.com/graphql/JJpn5RKFDbYXC957QragBQ/ReorderColumns`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ReorderDecks<br>
Request URL: `https://api.twitter.com/graphql/u2A0QRHa7bBRBhZZSmJKXQ/ReorderDecks`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateDeck<br>
Request URL: `https://api.twitter.com/graphql/fVIC9NDfk0-Auids8FlqQQ/CreateDeck`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RemoveDeck<br>
Request URL: `https://api.twitter.com/graphql/c20tuAQJznmUHtmOAvHLyA/RemoveDeck`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateDeck<br>
Request URL: `https://api.twitter.com/graphql/XW307yOKJINBAvlwOnLteg/UpdateDeck`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GryphonDeleteAccountSync<br>
Request URL: `https://api.twitter.com/graphql/DiJkSLAFULTIt7Z6ZnFhgQ/GryphonDeleteAccountSync`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GryphonImportClientSyncColumns<br>
Request URL: `https://api.twitter.com/graphql/DIubYz5FD1NQk6-O1GEUgg/GryphonImportClientSyncColumns`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ViewerAccountSync<br>
Request URL: `https://api.twitter.com/graphql/4t9h5GMFYewreBfk9TUKhw/ViewerAccountSync`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ViewerHasGryphonAccess<br>
Request URL: `https://api.twitter.com/graphql/bO8-Z3udl8YNV62_MoRlVg/ViewerHasGryphonAccess`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateClientSettings<br>
Request URL: `https://api.twitter.com/graphql/MlAbo_-7Kslvk5mojg9ttg/UpdateClientSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateGryphonOnboardingState<br>
Request URL: `https://api.twitter.com/graphql/zCQ0LjxvX0Ky0br3nE__PA/UpdateGryphonOnboardingState`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## articleNudgeDomains<br>
Request URL: `https://api.twitter.com/graphql/88Bu08U2ddaVVjKmmXjVYg/articleNudgeDomains`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ArticleTimeline<br>
Request URL: `https://api.twitter.com/graphql/B5ZPsQ6y65Sww_cf8LWm6Q/ArticleTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ArticleTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/I2Y6NF8iWaKn5OkqxFMeZg/ArticleTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## AudioSpaceById<br>
Request URL: `https://api.twitter.com/graphql/3ezvhrC0YbcS2zW22Jekmg/AudioSpaceById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| spaces_2022_h2_clipping                                                 | boolean |          1 | nan       |
| spaces_2022_h2_spaces_communities                                       | boolean |          1 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## AudioSpaceSearch<br>
Request URL: `https://api.twitter.com/graphql/NTq79TuSz6fHj8lQaferJw/AudioSpaceSearch`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## getAltTextPromptPreference<br>
Request URL: `https://api.twitter.com/graphql/PFIxTk8owMoZgiMccP0r4g/getAltTextPromptPreference`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## updateAltTextPromptPreference<br>
Request URL: `https://api.twitter.com/graphql/aQKrduk_DA46XfOQDkcEng/updateAltTextPromptPreference`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## getCaptionsAlwaysDisplayPreference<br>
Request URL: `https://api.twitter.com/graphql/BwgMOGpOViDS0ri7VUgglg/getCaptionsAlwaysDisplayPreference`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## updateCaptionsAlwaysDisplayPreference<br>
Request URL: `https://api.twitter.com/graphql/uCUQhvZ5sJ9qHinRp6CFlQ/updateCaptionsAlwaysDisplayPreference`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AuthenticatedUserTFLists<br>
Request URL: `https://api.twitter.com/graphql/QjN8ZdavFDqxUjNn3r9cig/AuthenticatedUserTFLists`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchAliasSelect<br>
Request URL: `https://api.twitter.com/graphql/3ss48WFwGokBH_gj8t_8aQ/BirdwatchAliasSelect`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchContributorNotesSlice<br>
Request URL: `https://api.twitter.com/graphql/uXX-W7zb5joLyu2WL5PCfg/BirdwatchFetchContributorNotesSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BirdwatchCreateAppeal<br>
Request URL: `https://api.twitter.com/graphql/TKdL0YFsX4DMOpMKeneLvA/BirdwatchCreateAppeal`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchCreateNote<br>
Request URL: `https://api.twitter.com/graphql/XqqIWMFp8CXvteuifu-WUw/BirdwatchCreateNote`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |

#### queryId<br>
`None`<br>
## BirdwatchCreateRating<br>
Request URL: `https://api.twitter.com/graphql/xWLuzZoATvfEIEGxnsLt7w/BirdwatchCreateRating`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchDeleteNote<br>
Request URL: `https://api.twitter.com/graphql/IKS_qrShkDyor6Ri1ahd9g/BirdwatchDeleteNote`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchDeleteRating<br>
Request URL: `https://api.twitter.com/graphql/OpvCOyOoQClUND66zDzrnA/BirdwatchDeleteRating`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchEditNotificationSettings<br>
Request URL: `https://api.twitter.com/graphql/FLgLReVIssXjB_ui3wcrRQ/BirdwatchEditNotificationSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchAliasSelfSelectOptions<br>
Request URL: `https://api.twitter.com/graphql/szoXMke8AZOErso908iglw/BirdwatchFetchAliasSelfSelectOptions`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchAliasSelfSelectStatus<br>
Request URL: `https://api.twitter.com/graphql/LUEdtkcpBlGktUtms4BvwA/BirdwatchFetchAliasSelfSelectStatus`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchAuthenticatedUserProfile<br>
Request URL: `https://api.twitter.com/graphql/pMbW6Y4LuS5MzlSOEqERJQ/BirdwatchFetchAuthenticatedUserProfile`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchBirdwatchProfile<br>
Request URL: `https://api.twitter.com/graphql/btgGtchypc3D491MJ7XXWA/BirdwatchFetchBirdwatchProfile`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchFetchGlobalTimeline<br>
Request URL: `https://api.twitter.com/graphql/ijR7o61Rpg1D-SDaA3k41A/BirdwatchFetchGlobalTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BirdwatchFetchNotes<br>
Request URL: `https://api.twitter.com/graphql/w9KDAJy8ZupCbV9dvx-JZQ/BirdwatchFetchNotes`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |

#### queryId<br>
`None`<br>
## BirdwatchFetchOneNote<br>
Request URL: `https://api.twitter.com/graphql/MAp8aUiUHI7HmNZClf0gjQ/BirdwatchFetchOneNote`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |

#### queryId<br>
`None`<br>
## BirdwatchFetchPublicData<br>
Request URL: `https://api.twitter.com/graphql/9bDdJ6AL26RLkcUShEcF-A/BirdwatchFetchPublicData`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BirdwatchProfileAcknowledgeEarnOut<br>
Request URL: `https://api.twitter.com/graphql/cED9wJy8Nd1kZCCYuIq9zQ/BirdwatchProfileAcknowledgeEarnOut`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BizProfileFetchUser<br>
Request URL: `https://api.twitter.com/graphql/6OFpJ3TH3p8JpwOSgfgyhg/BizProfileFetchUser`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BlockedAccountsAll<br>
Request URL: `https://api.twitter.com/graphql/PP3zOjycHYgV7jxk3zuA2A/BlockedAccountsAll`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsAutoBlock<br>
Request URL: `https://api.twitter.com/graphql/XqDPAy-ecLHJD2XoeXkS2g/BlockedAccountsAutoBlock`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BlockedAccountsImported<br>
Request URL: `https://api.twitter.com/graphql/Jaqls8IrYVBXd8LO33xv2g/BlockedAccountsImported`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BookmarkFolderTimeline<br>
Request URL: `https://api.twitter.com/graphql/fhWahIXb2rf77I5qXpB9Ww/BookmarkFolderTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## BookmarkFoldersSlice<br>
Request URL: `https://api.twitter.com/graphql/i78YDd0Tza-dV4SYs58kRg/BookmarkFoldersSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## bookmarkTweetToFolder<br>
Request URL: `https://api.twitter.com/graphql/4KHZvvNbHNf07bsgnL9gWA/bookmarkTweetToFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key   | type   | variable   |
|:------|:-------|:-----------|
| ...o  | ...    | _          |

#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Bookmarks<br>
Request URL: `https://api.twitter.com/graphql/Xq0wQSWHlcfnXARLJGqTxg/Bookmarks`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| graphql_timeline_v2_bookmark_timeline                                   | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CardPreviewByTweetText<br>
Request URL: `https://api.twitter.com/graphql/N9yLYAxjVMlHUX0qENfZNQ/CardPreviewByTweetText`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_enhance_cards_enabled                              | boolean | False      |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CombinedLists<br>
Request URL: `https://api.twitter.com/graphql/NCzWxXF4zmQgfkb9-X12Hw/CombinedLists`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunitiesMainDiscoveryModule<br>
Request URL: `https://api.twitter.com/graphql/5-xqzGjFNR0N3wIXDXtU-Q/CommunitiesMainDiscoveryModule`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunitiesMainPageTimeline<br>
Request URL: `https://api.twitter.com/graphql/dcvNIcJT33Qew_ecZF3SsA/CommunitiesMainPageTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunitiesMembershipsSlice<br>
Request URL: `https://api.twitter.com/graphql/zuzTaN-XQMfhbkf1Bg_gHw/CommunitiesMembershipsSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunitiesMembershipsTimeline<br>
Request URL: `https://api.twitter.com/graphql/pKn7MKUpZaBFUp4CikEBnA/CommunitiesMembershipsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityAboutTimeline<br>
Request URL: `https://api.twitter.com/graphql/5cYFk5MrDsRTIaMVHfe8gQ/CommunityAboutTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CreateCommunity<br>
Request URL: `https://api.twitter.com/graphql/jOGxwQAtlISDFeBPejZcPg/CreateCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityCreateRule<br>
Request URL: `https://api.twitter.com/graphql/F87EsTHL2xuS6scArXHMDg/CommunityCreateRule`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityDiscoveryTimeline<br>
Request URL: `https://api.twitter.com/graphql/bvx9dLyT3WeGJ7xINotKQA/CommunityDiscoveryTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityEditBannerMedia<br>
Request URL: `https://api.twitter.com/graphql/jRtMj3b-FyV2OR33Wk6vvw/CommunityEditBannerMedia`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditName<br>
Request URL: `https://api.twitter.com/graphql/PG2jxeN0zVbdINXViLEeww/CommunityEditName`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditPurpose<br>
Request URL: `https://api.twitter.com/graphql/-Wp3BPVvBh6KPDt2lsySQg/CommunityEditPurpose`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditRule<br>
Request URL: `https://api.twitter.com/graphql/_5THczaO5qZPAmWl7x0dLg/CommunityEditRule`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityEditTheme<br>
Request URL: `https://api.twitter.com/graphql/EkbBmRvDq4j_QiTcZDVHoQ/CommunityEditTheme`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityByRestId<br>
Request URL: `https://api.twitter.com/graphql/miaziJ8r2gMLMx2gSWCIWA/CommunityByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityHashtagsTimeline<br>
Request URL: `https://api.twitter.com/graphql/6H6G5z8F8FsgPMlGqFdwQA/CommunityHashtagsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## JoinCommunity<br>
Request URL: `https://api.twitter.com/graphql/Km7pos_ECDxyGuTrcz_LIw/JoinCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## LeaveCommunity<br>
Request URL: `https://api.twitter.com/graphql/5NAZbr_aCBp7COG2pVJGIA/LeaveCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityMemberRelationshipTypeahead<br>
Request URL: `https://api.twitter.com/graphql/npEFiYc3sCX-YDHZ1B69nw/CommunityMemberRelationshipTypeahead`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityModerationKeepTweet<br>
Request URL: `https://api.twitter.com/graphql/OuWtDezV-8sW6c07EXxKQA/CommunityModerationKeepTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityModerationTweetCasesSlice<br>
Request URL: `https://api.twitter.com/graphql/1NS2BIyC6WzLMc7gzmqyRg/CommunityModerationTweetCasesSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityRemoveBannerMedia<br>
Request URL: `https://api.twitter.com/graphql/lzJvo9o9W6pWJBYDrTReog/CommunityRemoveBannerMedia`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityRemoveRule<br>
Request URL: `https://api.twitter.com/graphql/pfkQvHtD3trZ4hXuU9Emdg/CommunityRemoveRule`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityReorderRules<br>
Request URL: `https://api.twitter.com/graphql/P3qfEypw7aErj_LkBS7slw/CommunityReorderRules`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## RequestToJoinCommunity<br>
Request URL: `https://api.twitter.com/graphql/PR3PekeLK-Bz_JVlmPGJ4g/RequestToJoinCommunity`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityTweetsRankedTimeline<br>
Request URL: `https://api.twitter.com/graphql/Tya9tok5PpWr71FI3xL2Ug/CommunityTweetsRankedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/o-i_HxOG_T1v-ZzAYhKtlg/CommunityTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunityUpdateRole<br>
Request URL: `https://api.twitter.com/graphql/cCUFo7d99y3T1_BS4_xCWA/CommunityUpdateRole`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityUserInvite<br>
Request URL: `https://api.twitter.com/graphql/el2xSrgrXBxyWvbz193qaA/CommunityUserInvite`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## CommunityUserRelationshipTypeahead<br>
Request URL: `https://api.twitter.com/graphql/C9CUCfAvlaMEhJBmM2hZkg/CommunityUserRelationshipTypeahead`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## ConnectTabTimeline<br>
Request URL: `https://api.twitter.com/graphql/55VdvUgJedG_f3hgxMxn2Q/ConnectTabTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ConvertRitoSuggestedActions<br>
Request URL: `https://api.twitter.com/graphql/2njnYoE69O2jdUM7KMEnDw/ConvertRitoSuggestedActions`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## createBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/6Xxqpq8TM_CREYiuof_h5w/createBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateCustomerPortalSession<br>
Request URL: `https://api.twitter.com/graphql/2LHXrd1uYeaMWhciZgPZFw/CreateCustomerPortalSession`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateDraftTweet<br>
Request URL: `https://api.twitter.com/graphql/cH9HZWz_EW9gnswvA4ZRiQ/CreateDraftTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateScheduledTweet<br>
Request URL: `https://api.twitter.com/graphql/LCVzRQGxOaGnOnYH01NQXg/CreateScheduledTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateTrustedFriendsList<br>
Request URL: `https://api.twitter.com/graphql/2tP8XUYeLHKjq5RHvuvpZw/CreateTrustedFriendsList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DataSaverMode<br>
Request URL: `https://api.twitter.com/graphql/xF6sXnKJfS2AOylzxRjf6A/DataSaverMode`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## WriteDataSaverPreferences<br>
Request URL: `https://api.twitter.com/graphql/H03etWvZGz41YASxAU2YPg/WriteDataSaverPreferences`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SetDefault<br>
Request URL: `https://api.twitter.com/graphql/QEMLEzEMzoPNbeauKCCLbg/SetDefault`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## BookmarksAllDelete<br>
Request URL: `https://api.twitter.com/graphql/skiACZKC1GDYli-M8RzEPQ/BookmarksAllDelete`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/2UTTsO-6zs93XqlEUZPsSg/DeleteBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteDraftTweet<br>
Request URL: `https://api.twitter.com/graphql/bkh9G3FGgTldS9iTKWWYYw/DeleteDraftTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeletePaymentMethod<br>
Request URL: `https://api.twitter.com/graphql/VaaLGwK5KNLoc7wsOmp4uw/DeletePaymentMethod`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteScheduledTweet<br>
Request URL: `https://api.twitter.com/graphql/CTOVqej0JBXAZSwkp1US0g/DeleteScheduledTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DisableUserAccountLabel<br>
Request URL: `https://api.twitter.com/graphql/_ckHEj05gan2VfNHG6thBA/DisableUserAccountLabel`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DisableVerifiedPhoneLabel<br>
Request URL: `https://api.twitter.com/graphql/g2m0pAOamawNtVIfjXNMJg/DisableVerifiedPhoneLabel`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DismissRitoSuggestedAction<br>
Request URL: `https://api.twitter.com/graphql/jYvwa61cv3NwNP24iUru6g/DismissRitoSuggestedAction`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DmAllSearchSlice<br>
Request URL: `https://api.twitter.com/graphql/EbxQ7cQUrv8cW3Y6cJGGMw/DmAllSearchSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key                             | type   | variable                                                                                                                                                                             |
|:--------------------------------|:-------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| count                           | ...    | (optional) t.count                                                                                                                                                                   |
| query                           | ...    | t.query                                                                                                                                                                              |
| withAttachments                 | ...    | i.isTrue()&&i.isTrue("dm_inbox_search_message_attachment_previews_enabled")&&i.isTrue("dm_inbox_search_message_results_enabled")                                                     |
| withConversationQueryHighlights | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")&&i.isTrue("dm_inbox_search_query_highlighting_conversation_results_enabled")                                                 |
| withMessageQueryHighlights      | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")&&i.isTrue("dm_inbox_search_query_highlighting_message_results_enabled")&&i.isTrue("dm_inbox_search_message_results_enabled") |
| withMessages                    | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")&&i.isTrue("dm_inbox_search_message_results_enabled")                                                                         |
| withSafetyModeUserFields        | ...    | i.isTrue("direct_messages_incremental_holdback_2022h1")                                                                                                                              |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## DmGroupSearchSlice<br>
Request URL: `https://api.twitter.com/graphql/5zpY1dCR-8NyxQJS_CFJoQ/DmGroupSearchSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DmMutedTimeline<br>
Request URL: `https://api.twitter.com/graphql/WkmUeSSOVNPxh-rbC_Mkzw/DmMutedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## DmNsfwMediaFilterUpdate<br>
Request URL: `https://api.twitter.com/graphql/of_N6O33zfyD4qsFJMYFxA/DmNsfwMediaFilterUpdate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DmPeopleSearchSlice<br>
Request URL: `https://api.twitter.com/graphql/xYSm8m5kJnzm_gFCn5GH-w/DmPeopleSearchSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EditBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/a6kPp1cS1Dgbsjhapz1PNw/EditBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EditDraftTweet<br>
Request URL: `https://api.twitter.com/graphql/JIeXE-I6BZXHfxsgOkyHYQ/EditDraftTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EditScheduledTweet<br>
Request URL: `https://api.twitter.com/graphql/_mHkQ5LHpRRjSXKOcG6eZw/EditScheduledTweet`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## WriteEmailNotificationSettings<br>
Request URL: `https://api.twitter.com/graphql/2qKKYFQift8p5-J1k6kqxQ/WriteEmailNotificationSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EnableLoggedOutWebNotifications<br>
Request URL: `https://api.twitter.com/graphql/BqIHKmwZKtiUBPi07jKctg/EnableLoggedOutWebNotifications`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EnableVerifiedPhoneLabel<br>
Request URL: `https://api.twitter.com/graphql/C3RJFfMsb_KcEytpKmRRkw/EnableVerifiedPhoneLabel`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ExplorePage<br>
Request URL: `https://api.twitter.com/graphql/yF0e2a26mrZQdZSQrokPiw/ExplorePage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Favoriters<br>
Request URL: `https://api.twitter.com/graphql/n6OEAX4QBqXfjhLma-RxFg/Favoriters`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FeatureSettingsUpdate<br>
Request URL: `https://api.twitter.com/graphql/-btar_vkBwWA7s3YWfp_9g/FeatureSettingsUpdate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Followers<br>
Request URL: `https://api.twitter.com/graphql/fc_Qn0zSCQyjAcRDQu3XRA/Followers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## FollowersYouKnow<br>
Request URL: `https://api.twitter.com/graphql/jV43y1ptcjPRVQK9sjo8QA/FollowersYouKnow`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Following<br>
Request URL: `https://api.twitter.com/graphql/vTZwBbd_gz6aI8v6Wze21A/Following`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GenericTimelineById<br>
Request URL: `https://api.twitter.com/graphql/AFH5BUKfoGEmNc78IYonag/GenericTimelineById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GraphQLError<br>
Request URL: `https://api.twitter.com/graphql/2V2W3HIBuMW83vEMtfo_Rg/GraphQLError`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateColumn<br>
Request URL: `https://api.twitter.com/graphql/O4iIdjZUiZpm0KBSiftNGQ/CreateColumn`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateDeck<br>
Request URL: `https://api.twitter.com/graphql/fVIC9NDfk0-Auids8FlqQQ/CreateDeck`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GryphonDeleteAccountSync<br>
Request URL: `https://api.twitter.com/graphql/DiJkSLAFULTIt7Z6ZnFhgQ/GryphonDeleteAccountSync`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GryphonImportClientSyncColumns<br>
Request URL: `https://api.twitter.com/graphql/DIubYz5FD1NQk6-O1GEUgg/GryphonImportClientSyncColumns`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RemoveColumn<br>
Request URL: `https://api.twitter.com/graphql/lfB7GP4w9oCpx5F_BxwRkw/RemoveColumn`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RemoveDeck<br>
Request URL: `https://api.twitter.com/graphql/c20tuAQJznmUHtmOAvHLyA/RemoveDeck`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ReorderColumns<br>
Request URL: `https://api.twitter.com/graphql/JJpn5RKFDbYXC957QragBQ/ReorderColumns`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ReorderDecks<br>
Request URL: `https://api.twitter.com/graphql/u2A0QRHa7bBRBhZZSmJKXQ/ReorderDecks`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateClientSettings<br>
Request URL: `https://api.twitter.com/graphql/MlAbo_-7Kslvk5mojg9ttg/UpdateClientSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateColumn<br>
Request URL: `https://api.twitter.com/graphql/suRGd49L2EZ0nuuU4he4aw/UpdateColumn`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateDeck<br>
Request URL: `https://api.twitter.com/graphql/XW307yOKJINBAvlwOnLteg/UpdateDeck`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateGryphonOnboardingState<br>
Request URL: `https://api.twitter.com/graphql/zCQ0LjxvX0Ky0br3nE__PA/UpdateGryphonOnboardingState`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ViewerAccountSync<br>
Request URL: `https://api.twitter.com/graphql/4t9h5GMFYewreBfk9TUKhw/ViewerAccountSync`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ViewerHasGryphonAccess<br>
Request URL: `https://api.twitter.com/graphql/bO8-Z3udl8YNV62_MoRlVg/ViewerHasGryphonAccess`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## HomeLatestTimeline<br>
Request URL: `https://api.twitter.com/graphql/1UNiFOLvPTRpu8zVk-LAXw/HomeLatestTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## HomeTimeline<br>
Request URL: `https://api.twitter.com/graphql/v7m3-T8yGC5cqy7doGpi5Q/HomeTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ImmersiveMedia<br>
Request URL: `https://api.twitter.com/graphql/xyZOS_yKFat0w0HWKFRIuw/ImmersiveMedia`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## Likes<br>
Request URL: `https://api.twitter.com/graphql/XbHBYpgURwtklXj8NNxTDw/Likes`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListAddMember<br>
Request URL: `https://api.twitter.com/graphql/05BjoR7aurmYI22etXocBQ/ListAddMember`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## DeleteListBanner<br>
Request URL: `https://api.twitter.com/graphql/CygCjKvWmZHHLLM7oLLX-g/DeleteListBanner`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key          | type   | variable   |
|:-------------|:-------|:-----------|
| listId       | ...    | r          |
| ...()(0,s.S) | ...    | _          |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## EditListBanner<br>
Request URL: `https://api.twitter.com/graphql/bdkWhnAxpzgwGwH-lPkMsA/EditListBanner`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListBySlug<br>
Request URL: `https://api.twitter.com/graphql/623MECMdC6fBnc49itmwdQ/ListBySlug`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## CreateList<br>
Request URL: `https://api.twitter.com/graphql/XPAynCMUA_CaP7MNQOXbCw/CreateList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListCreationRecommendedUsers<br>
Request URL: `https://api.twitter.com/graphql/YJNbpuZJY95YYeWK6qxr7g/ListCreationRecommendedUsers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## DeleteList<br>
Request URL: `https://api.twitter.com/graphql/UnN9Th1BDbeLjpgjGSpL3Q/DeleteList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## FetchDraftTweets<br>
Request URL: `https://api.twitter.com/graphql/ZkqIq_xRhiUme0PBJNpRtg/FetchDraftTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListEditRecommendedUsers<br>
Request URL: `https://api.twitter.com/graphql/WPtiML6oz9WDmMz2UZ_WrQ/ListEditRecommendedUsers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListLatestTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/FDI9EiIp54KxEOWGiv3B4A/ListLatestTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListMembers<br>
Request URL: `https://api.twitter.com/graphql/XsAJX17RLgLYU8GALIWg2g/ListMembers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListMemberships<br>
Request URL: `https://api.twitter.com/graphql/jnu-SyjP7-jiY8CuE0WsCQ/ListMemberships`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MuteList<br>
Request URL: `https://api.twitter.com/graphql/ZYyanJsskNUcltu9bliMLA/MuteList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListOwnerships<br>
Request URL: `https://api.twitter.com/graphql/mHETbEwW2vWNU_L7JijWIQ/ListOwnerships`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListPinOne<br>
Request URL: `https://api.twitter.com/graphql/whBN4jUV_rUs8AiBBv-qVw/ListPinOne`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListPins<br>
Request URL: `https://api.twitter.com/graphql/xP0YPWA4fPm2hYFHoqDLnQ/ListPins`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListProductSubscriptions<br>
Request URL: `https://api.twitter.com/graphql/wwdBYgScze0_Jnan79jEUw/ListProductSubscriptions`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListByRestId<br>
Request URL: `https://api.twitter.com/graphql/KlGpwq5CAt9tCfHkV2mwYQ/ListByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key    | type   | variable   |
|:-------|:-------|:-----------|
| listId | ...    | l          |
| ...a   | ...    | _          |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListRankedTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/6ldXqXu3hPLWV8ZM0sbcZA/ListRankedTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key          | type   | variable   |
|:-------------|:-------|:-----------|
| ...n         | ...    | _          |
| ...()(0,a.S) | ...    | _          |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListRemoveMember<br>
Request URL: `https://api.twitter.com/graphql/32lW2xl4fksrTRB25SIR9g/ListRemoveMember`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListSubscribe<br>
Request URL: `https://api.twitter.com/graphql/2ZDSj2DhUUlUklIaNsO1DA/ListSubscribe`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListSubscribers<br>
Request URL: `https://api.twitter.com/graphql/wCHENI0upPf0Ly8NGWAVNw/ListSubscribers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UnmuteList<br>
Request URL: `https://api.twitter.com/graphql/pMZrHRNsmEkXgbn3tOyr7Q/UnmuteList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ListUnpinOne<br>
Request URL: `https://api.twitter.com/graphql/yIVCXYI7OvIOCKCDq1JrSw/ListUnpinOne`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListUnsubscribe<br>
Request URL: `https://api.twitter.com/graphql/2J-RcURzQMzhgnu2cryIhA/ListUnsubscribe`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key    | type   | variable   |
|:-------|:-------|:-----------|
| listId | ...    | i          |

#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## UpdateList<br>
Request URL: `https://api.twitter.com/graphql/wweOiADrdfgFeSXkHbXrlQ/UpdateList`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ListsDiscovery<br>
Request URL: `https://api.twitter.com/graphql/VYOjTMWzm7QmalmpmJl3sQ/ListsDiscovery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key          | type   | variable   |
|:-------------|:-------|:-----------|
| listIds      | ...    | l          |
| ...()(0,s.S) | ...    | _          |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListsManagementPageTimeline<br>
Request URL: `https://api.twitter.com/graphql/mp39ddRX8yCoQUyxjrqogw/ListsManagementPageTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## ListsPinMany<br>
Request URL: `https://api.twitter.com/graphql/QM9ThyyEmuf5CfsDhTTxiQ/ListsPinMany`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## LiveCommerceItemsSlice<br>
Request URL: `https://api.twitter.com/graphql/-lnNX56S2YrZYrLzbccFAQ/LiveCommerceItemsSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ModeratedTimeline<br>
Request URL: `https://api.twitter.com/graphql/rnDPbgWcAV-3q0nQYW0V7Q/ModeratedTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## MutedAccounts<br>
Request URL: `https://api.twitter.com/graphql/rh1EKzLHYVwFa4N0ZsoHnQ/MutedAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## NoteworthyAccountsPage<br>
Request URL: `https://api.twitter.com/graphql/rJ7mCScwRUUX-y01aizNaA/NoteworthyAccountsPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## PaymentMethods<br>
Request URL: `https://api.twitter.com/graphql/mPF_G9okpbZuLcD6mN8K9g/PaymentMethods`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## PinReply<br>
Request URL: `https://api.twitter.com/graphql/GA2_1uKP9b_GyR4MVAQXAw/PinReply`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UnpinReply<br>
Request URL: `https://api.twitter.com/graphql/iRe6ig5OV1EzOtldNIuGDQ/UnpinReply`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ProfileUserPhoneState<br>
Request URL: `https://api.twitter.com/graphql/5kUWP8C1hcd6omvg6HXXTQ/ProfileUserPhoneState`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## PutClientEducationFlag<br>
Request URL: `https://api.twitter.com/graphql/IjQ-egg0uPkY11NyPMfRMQ/PutClientEducationFlag`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AdAccounts<br>
Request URL: `https://api.twitter.com/graphql/a8KxGfFQAmm3WxqemuqSRA/AdAccounts`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AudienceEstimate<br>
Request URL: `https://api.twitter.com/graphql/1LYVUabJBYkPlUAWRabB3g/AudienceEstimate`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Budgets<br>
Request URL: `https://api.twitter.com/graphql/mbK3oSQotwcJXyQIBE3uYw/Budgets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Coupons<br>
Request URL: `https://api.twitter.com/graphql/R1h43jnAl2bsDoUkgZb7NQ/Coupons`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CreateQuickPromotion<br>
Request URL: `https://api.twitter.com/graphql/oDSoVgHhJxnd5IkckgPZdg/CreateQuickPromotion`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## QuickPromoteEligibility<br>
Request URL: `https://api.twitter.com/graphql/LtpCXh66W-uXh7u7XSRA8Q/QuickPromoteEligibility`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EnrollCoupon<br>
Request URL: `https://api.twitter.com/graphql/SOyGmNGaEXcvk15s5bqDrA/EnrollCoupon`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RemoveFollower<br>
Request URL: `https://api.twitter.com/graphql/QpNfg0kpPRfjROQ_9eOLXA/RemoveFollower`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RemoveTweetFromBookmarkFolder<br>
Request URL: `https://api.twitter.com/graphql/2Qbj9XZvtUvyJB4gFwWfaA/RemoveTweetFromBookmarkFolder`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key              | type   | variable   |
|:-----------------|:-------|:-----------|
| twitterArticleId | ...    | l          |
| visibility       | ...    | s          |
| ...()(0,a.d)     | ...    | _          |

#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Retweeters<br>
Request URL: `https://api.twitter.com/graphql/Z83XAg6CcWvrA3l4uzmJgw/Retweeters`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RitoActionedTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/DQ-r9abxxEcEt4FBU80WsA/RitoActionedTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RitoFlaggedAccountsTimeline<br>
Request URL: `https://api.twitter.com/graphql/M3Oke69NcBch2RLTgx7MlA/RitoFlaggedAccountsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RitoFlaggedTweetsTimeline<br>
Request URL: `https://api.twitter.com/graphql/nSYVgN4Ev8XJlsHKqN3YjA/RitoFlaggedTweetsTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## RitoSuggestedActionsFacePile<br>
Request URL: `https://api.twitter.com/graphql/GnQKeEdL1LyeK3dTQCS1yw/RitoSuggestedActionsFacePile`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GetSafetyModeSettings<br>
Request URL: `https://api.twitter.com/graphql/AhxTX0lkbIos4WG53xwzSA/GetSafetyModeSettings`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SetSafetyModeSettings<br>
Request URL: `https://api.twitter.com/graphql/qSJIPIpf4gA7Wn21bT3D4w/SetSafetyModeSettings`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## FetchScheduledTweets<br>
Request URL: `https://api.twitter.com/graphql/ITtjAzvlZni2wWXwf295Qg/FetchScheduledTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SharingAudiospacesListeningDataWithFollowersUpdate<br>
Request URL: `https://api.twitter.com/graphql/5h0kNbk3ii97rmfY6CdgAA/SharingAudiospacesListeningDataWithFollowersUpdate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscribeToScheduledSpace<br>
Request URL: `https://api.twitter.com/graphql/Sxn4YOlaAwEKjnjWV0h7Mw/SubscribeToScheduledSpace`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscriptionCheckoutUrlWithEligibility<br>
Request URL: `https://api.twitter.com/graphql/hKfOOObQr5JmfmxW0YtPvg/SubscriptionCheckoutUrlWithEligibility`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscriptionProductDetails<br>
Request URL: `https://api.twitter.com/graphql/GZF6Vha91bWrZjDmZZ-VNA/SubscriptionProductDetails`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SubscriptionProductFeaturesFetch<br>
Request URL: `https://api.twitter.com/graphql/Me2CVcAXxvK2WMr-Nh_Qqg/SubscriptionProductFeaturesFetch`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SuperFollowers<br>
Request URL: `https://api.twitter.com/graphql/N2RJJDykhEHkg7uFyHzH9Q/SuperFollowers`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## timelinesFeedback<br>
Request URL: `https://api.twitter.com/graphql/vfVbgvTPTQ-dF_PQ5lD1WQ/timelinesFeedback`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicFollow<br>
Request URL: `https://api.twitter.com/graphql/ElqSLWFmsPL4NlZI5e1Grg/TopicFollow`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key     | type   | variable   |
|:--------|:-------|:-----------|
| topicId | ...    | n          |

#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicLandingPage<br>
Request URL: `https://api.twitter.com/graphql/xL5ANL241izMQEgOOX1fQw/TopicLandingPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicNotInterested<br>
Request URL: `https://api.twitter.com/graphql/cPCFdDAaqRjlMRYInZzoDA/TopicNotInterested`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicByRestId<br>
Request URL: `https://api.twitter.com/graphql/4OUZZOonV2h60I0wdlQb_w/TopicByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicToFollowSidebar<br>
Request URL: `https://api.twitter.com/graphql/-xObYcPAhdlqQc6iMEjNQA/TopicToFollowSidebar`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicUndoNotInterested<br>
Request URL: `https://api.twitter.com/graphql/4tVnt6FoSxaX8L-mDDJo4Q/TopicUndoNotInterested`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicUnfollow<br>
Request URL: `https://api.twitter.com/graphql/srwjU6JM_ZKTj_QMfUGNcw/TopicUnfollow`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TopicsManagementPage<br>
Request URL: `https://api.twitter.com/graphql/LuJBpoxjvhTw_cFK3-tSHg/TopicsManagementPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicsPickerPage<br>
Request URL: `https://api.twitter.com/graphql/HinWDnpV9U9bHAFU34_XLQ/TopicsPickerPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TopicsPickerPageById<br>
Request URL: `https://api.twitter.com/graphql/LO3CiCCH_GrX_lYSNdHRjQ/TopicsPickerPageById`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TrustedFriendsTypeahead<br>
Request URL: `https://api.twitter.com/graphql/_vUIWq3vpyL0amiNTjrM-w/TrustedFriendsTypeahead`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |

#### queryId<br>
`None`<br>
## TweetDetail<br>
Request URL: `https://api.twitter.com/graphql/nDM-d-uWksu2D4Xj0Wl_Ig/TweetDetail`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TweetEditHistory<br>
Request URL: `https://api.twitter.com/graphql/q21DsW7qxOTEmBRfBFE1HA/TweetEditHistory`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## GetTweetReactionTimeline<br>
Request URL: `https://api.twitter.com/graphql/ic7XPiBInWKYbPcwsIURNw/GetTweetReactionTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## TweetStats<br>
Request URL: `https://api.twitter.com/graphql/EvbTkPDT-xQCfupPu0rWMA/TweetStats`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                             | type    | variable   |
|:------------------------------------------------|:--------|:-----------|
| profile_foundations_tweet_stats_enabled         | boolean | False      |
| profile_foundations_tweet_stats_tweet_frequency | boolean | False      |

#### queryId<br>
`None`<br>
## TwitterArticleCreate<br>
Request URL: `https://api.twitter.com/graphql/g2OX8USKYcus_Z6zfTomIw/TwitterArticleCreate`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleDelete<br>
Request URL: `https://api.twitter.com/graphql/6st-stMDc7KBqLT8KvWhHg/TwitterArticleDelete`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TwitterArticleByRestId<br>
Request URL: `https://api.twitter.com/graphql/YshrJY7-EBd6ZZsROUxZBA/TwitterArticleByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateCoverImage<br>
Request URL: `https://api.twitter.com/graphql/zMWfBgPb36cA-1Hc-67hsA/TwitterArticleUpdateCoverImage`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateData<br>
Request URL: `https://api.twitter.com/graphql/DQPnbro9xDikTvb33zemRw/TwitterArticleUpdateData`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateMedia<br>
Request URL: `https://api.twitter.com/graphql/P2HjIzZEvTMN40DgVon9hQ/TwitterArticleUpdateMedia`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateTitle<br>
Request URL: `https://api.twitter.com/graphql/y_5RufkvEsE8no2_eEqRMQ/TwitterArticleUpdateTitle`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticleUpdateVisibility<br>
Request URL: `https://api.twitter.com/graphql/xd_PZueE4W4LZQyYnWUlNA/TwitterArticleUpdateVisibility`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## TwitterArticlesSlice<br>
Request URL: `https://api.twitter.com/graphql/-ohxO2o6V1tQvCfXppeOMw/TwitterArticlesSlice`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_article_data_v2_enabled                          | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UnsubscribeFromScheduledSpace<br>
Request URL: `https://api.twitter.com/graphql/Zevhh76Msw574ZSs2NQHGQ/UnsubscribeFromScheduledSpace`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UrtFixtures<br>
Request URL: `https://api.twitter.com/graphql/pb8L8foE_-pGGCUhlbzZjA/UrtFixtures`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserAboutTimeline<br>
Request URL: `https://api.twitter.com/graphql/ZTrOLi1XhslPdFQUE322eA/UserAboutTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserAccountLabel<br>
Request URL: `https://api.twitter.com/graphql/rD5gLxVmMvtdtYU1UHWlFQ/UserAccountLabel`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UserBusinessProfileTeamTimeline<br>
Request URL: `https://api.twitter.com/graphql/Xz02rH0t5J-IM34vmQ5KYw/UserBusinessProfileTeamTimeline`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key                    | type    | variable    |
|:-----------------------|:--------|:------------|
| userId                 | ...     | r           |
| count                  | ...     | t           |
| cursor                 | ...     | n           |
| teamName               | ...     | i           |
| includePromotedContent | boolean | False       |
| ...()(0,a.d)           | ...     | _           |
| withClientEventToken   | boolean | False       |
| withVoice              | ...     | _.isTrue(_) |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserByRestId<br>
Request URL: `https://api.twitter.com/graphql/QPSxc9lxrmrwnBzYkJI8eA/UserByRestId`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## UserByScreenName<br>
Request URL: `https://api.twitter.com/graphql/nZjSkpOpSL5rWyIVdsKeLA/UserByScreenName`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## GetUserClaims<br>
Request URL: `https://api.twitter.com/graphql/lFi3xnx0auUUnyG4YwpCNw/GetUserClaims`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UserMedia<br>
Request URL: `https://api.twitter.com/graphql/MA_EP2a21zpzNWKRkaPBMg/UserMedia`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserPromotableTweets<br>
Request URL: `https://api.twitter.com/graphql/l92DbYOLlYkDXA-MtQ1eWQ/UserPromotableTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserSessionsList<br>
Request URL: `https://api.twitter.com/graphql/vJ-XatpmQSG8bDch8-t9Jw/UserSessionsList`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UserSuperFollowTweets<br>
Request URL: `https://api.twitter.com/graphql/Of6dyatCC-Oiic4J_udPbQ/UserSuperFollowTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key                    | type    | variable    |
|:-----------------------|:--------|:------------|
| userId                 | ...     | i           |
| count                  | ...     | t           |
| cursor                 | ...     | n           |
| includePromotedContent | boolean | True        |
| ...()(0,a.d)           | ...     | _           |
| withVoice              | ...     | _.isTrue(_) |

#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserTweets<br>
Request URL: `https://api.twitter.com/graphql/9rys0A7w1EyqVd2ME0QCJg/UserTweets`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UserTweetsAndReplies<br>
Request URL: `https://api.twitter.com/graphql/ehMCHF3Mkgjsfz_aImqOsg/UserTweetsAndReplies`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## UsersByRestIds<br>
Request URL: `https://api.twitter.com/graphql/RPzwimxhSjZiykM5FeLnDw/UsersByRestIds`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ViewerEmailSettings<br>
Request URL: `https://api.twitter.com/graphql/JpjlNgn4sLGvS6tgpTzYBg/ViewerEmailSettings`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## Viewer<br>
Request URL: `https://api.twitter.com/graphql/WHlX9F4T8YVmDAkcPNYf8g/Viewer`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ViewerTeams<br>
Request URL: `https://api.twitter.com/graphql/tfZKKr99QUvqWcdUnuNIxQ/ViewerTeams`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |

#### queryId<br>
`None`<br>
## ViewingOtherUsersTopicsPage<br>
Request URL: `https://api.twitter.com/graphql/_Eu7ZMeN5M-sgkQfnvxNng/ViewingOtherUsersTopicsPage`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |

#### queryId<br>
`None`<br>
## CommunitiesTabBarItemQuery<br>
Request URL: `https://api.twitter.com/graphql/ZesI-zwzK86uoWFu5IhLDg/CommunitiesTabBarItemQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## VerifiedRouteQuery<br>
Request URL: `https://api.twitter.com/graphql/inQHR9aa8pXO9Jqy4swaJw/VerifiedRouteQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## managementListsPageTimelineQuery<br>
Request URL: `https://api.twitter.com/graphql/G7N0CBYgbc7NJOUb2ngc2A/managementListsPageTimelineQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |

#### queryId<br>
`None`<br>
## urtModuleOperationsInjectEntryQuery<br>
Request URL: `https://api.twitter.com/graphql/null/urtModuleOperationsInjectEntryQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## urtModuleOperationsUpdateEntryQuery<br>
Request URL: `https://api.twitter.com/graphql/null/urtModuleOperationsUpdateEntryQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## usersModuleProtectedQuery<br>
Request URL: `https://api.twitter.com/graphql//usersModuleProtectedQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunitiesDashMenuItemQuery<br>
Request URL: `https://api.twitter.com/graphql/cFC8pqLWsfzTUOY674C6OA/CommunitiesDashMenuItemQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AccountSwitcherDelegateQuery<br>
Request URL: `https://api.twitter.com/graphql/1gowCMPzY09WyApNQM68kA/AccountSwitcherDelegateQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DelegatedAccountListQuery<br>
Request URL: `https://api.twitter.com/graphql/jvbCW8kzIoL8ps8Ry_cDqQ/DelegatedAccountListQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## DelegateAlertBannerContainerQuery<br>
Request URL: `https://api.twitter.com/graphql/zuUTzlnI-XomL9lfWFqSKg/DelegateAlertBannerContainerQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DMMessageDeleteMutation<br>
Request URL: `https://api.twitter.com/graphql/BJ6DtxA2llfjnRoRjaiIiw/DMMessageDeleteMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useDMReactionMutationAddMutation<br>
Request URL: `https://api.twitter.com/graphql/VvqwjKXjT6j6CTqvlqdYCw/useDMReactionMutationAddMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useDMReactionMutationRemoveMutation<br>
Request URL: `https://api.twitter.com/graphql/-vqtYGrnU8xx1d_9tVE0lw/useDMReactionMutationRemoveMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useTypingNotifierMutation<br>
Request URL: `https://api.twitter.com/graphql/HL96-xZ3Y81IEzAdczDokg/useTypingNotifierMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useSendMessageMutation<br>
Request URL: `https://api.twitter.com/graphql/MaxK2PKX1F9Z-9SwqwavTw/useSendMessageMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DMConversationSearchTabGroupsQuery<br>
Request URL: `https://api.twitter.com/graphql/8D8KoSq5q9d5Su3emu2dwg/DMConversationSearchTabGroupsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DMConversationSearchTabPeopleQuery<br>
Request URL: `https://api.twitter.com/graphql/qno3lU4_eSHtSFoWQUhEag/DMConversationSearchTabPeopleQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DMMessageSearchTabQuery<br>
Request URL: `https://api.twitter.com/graphql/hJS9lRFYUmvcWRsWWwW_iQ/DMMessageSearchTabQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## DMPinnedInboxAppend_Mutation<br>
Request URL: `https://api.twitter.com/graphql/o0aymgGiJY-53Y52YSUGVA/DMPinnedInboxAppend_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DMPinnedInboxDelete_Mutation<br>
Request URL: `https://api.twitter.com/graphql/_TQxP2Rb0expwVP9ktGrTQ/DMPinnedInboxDelete_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EvolutionDMInboxSecondaryNoQualityFilterQuery<br>
Request URL: `https://api.twitter.com/graphql/rj0wAEzfARRw5Lxv6vA9tA/EvolutionDMInboxSecondaryNoQualityFilterQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EvolutionDMInboxSecondaryQuery<br>
Request URL: `https://api.twitter.com/graphql/CR5eoCBq5F7Ot49qXfjzKQ/EvolutionDMInboxSecondaryQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMAllSearchTabQuery<br>
Request URL: `https://api.twitter.com/graphql/-_b_oSuiL0uHBBLzLjhpxg/evolutionDMAllSearchTabQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## evolutionDMConversationSearchTabGroupsQuery<br>
Request URL: `https://api.twitter.com/graphql/jU2lHFnuiEBmYbTBiLuBSA/evolutionDMConversationSearchTabGroupsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMConversationSearchTabPeopleQuery<br>
Request URL: `https://api.twitter.com/graphql/PMTCRjntjEssRRwk5s9ezg/evolutionDMConversationSearchTabPeopleQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMInboxPollQuery<br>
Request URL: `https://api.twitter.com/graphql/XyU1n6dQq8tKdnDVXhp-bA/evolutionDMInboxPollQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMInboxPrimaryQuery<br>
Request URL: `https://api.twitter.com/graphql/yWKGySeJxM-6SB-nb6RwWw/evolutionDMInboxPrimaryQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMInboxTertiaryQuery<br>
Request URL: `https://api.twitter.com/graphql/Fb14pDVMBtYifaNOE5h9xQ/evolutionDMInboxTertiaryQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMMessageSearchTabQuery<br>
Request URL: `https://api.twitter.com/graphql/Pc5QelfWw1Zgj9-W84zjYg/evolutionDMMessageSearchTabQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## evolutionPinConversationMutation<br>
Request URL: `https://api.twitter.com/graphql/ZHTYqgRlFOIozAdfcLAF_A/evolutionPinConversationMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionUnpinConversationMutation<br>
Request URL: `https://api.twitter.com/graphql/uZN4IpDCjHJcya7TpOKoNA/evolutionUnpinConversationMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMDrawerHeaderQuery<br>
Request URL: `https://api.twitter.com/graphql/3QhsL9LHWvfEHbIRXIb84g/evolutionDMDrawerHeaderQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDMDrawerQuery<br>
Request URL: `https://api.twitter.com/graphql/EaLKdvs0RLR9SFIi-XmwCg/evolutionDMDrawerQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CarouselQuery<br>
Request URL: `https://api.twitter.com/graphql/A9Lt_vHgiD1zkiB2fdU9Zw/CarouselQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunitiesCreateButtonQuery<br>
Request URL: `https://api.twitter.com/graphql/8daJzV6tGCTssiKBRFpXtQ/CommunitiesCreateButtonQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunitiesListActivityQuery<br>
Request URL: `https://api.twitter.com/graphql/ZnEsP44ZDzRe9aId7SVoZg/CommunitiesListActivityQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunitiesSearchQuery<br>
Request URL: `https://api.twitter.com/graphql/JLnMuCshIrWkJlp7LRvWFw/CommunitiesSearchQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunityAppBarButtonQuery<br>
Request URL: `https://api.twitter.com/graphql/hNQLWhD2pxRBtp7mg6hWEQ/CommunityAppBarButtonQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunityInviteButtonQuery<br>
Request URL: `https://api.twitter.com/graphql/8s4H3Tf6VXViIQuaHMJE1Q/CommunityInviteButtonQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
| key      | type   | variable   |
|:---------|:-------|:-----------|
| tweet_id | ...    | t          |

#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunityToolsScreenContainerQuery<br>
Request URL: `https://api.twitter.com/graphql/c7MAOYAoh0dfh_06YrxSpg/CommunityToolsScreenContainerQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DeleteCommunityMutation<br>
Request URL: `https://api.twitter.com/graphql/zHWYNyObppV8ZXY0o3oHTw/DeleteCommunityMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## EditMembershipTypeQuery<br>
Request URL: `https://api.twitter.com/graphql/ruZM8GnBs_0uuSjWLF6nkw/EditMembershipTypeQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## HashtagResultsCommunity_Query<br>
Request URL: `https://api.twitter.com/graphql/IqDv9dN3LO-GORp6lRMyoA/HashtagResultsCommunity_Query`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MemberRequests_Query<br>
Request URL: `https://api.twitter.com/graphql/WZkL3cX8Ht0d8TQO20Bk6w/MemberRequests_Query`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## NotificationSettingsModalQuery<br>
Request URL: `https://api.twitter.com/graphql/d86C1tsqqQ-_2b7xStjYJQ/NotificationSettingsModalQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## NotificationSettingsSaveButtonMutation<br>
Request URL: `https://api.twitter.com/graphql/GhfS-OCV4WH5I4aT2_i8jg/NotificationSettingsSaveButtonMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## PeopleCommunity_Query<br>
Request URL: `https://api.twitter.com/graphql/t7j24Zrx2IjCj13ndCU2hA/PeopleCommunity_Query`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## PrimaryContentQuery<br>
Request URL: `https://api.twitter.com/graphql/lieM2QpB7PLqe0qyABV3KA/PrimaryContentQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    |   variable | default   |
|:------------------------------------------------------|:--------|-----------:|:----------|
| c9s_list_members_action_api_enabled                   | boolean |          0 | nan       |
| c9s_superc9s_indication_enabled                       | ...     |        nan | error     |
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean |          1 | nan       |

#### queryId<br>
`None`<br>
## actions_approveMemberRequest_Mutation<br>
Request URL: `https://api.twitter.com/graphql/LVHUDWQ4jsU9iixwJUbT4Q/actions_approveMemberRequest_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## actions_denyMemberRequest_Mutation<br>
Request URL: `https://api.twitter.com/graphql/5AncQiBia2eEnbL_0_jYAA/actions_denyMemberRequest_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## communityPeopleActionMenu_roleUpdate_Mutation<br>
Request URL: `https://api.twitter.com/graphql/-z7ecfy5Y04vSJHD3xQ1aA/communityPeopleActionMenu_roleUpdate_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## edit_membershipSettings_Mutation<br>
Request URL: `https://api.twitter.com/graphql/YiJSKw8k6Mpy-pkVOwuQ7w/edit_membershipSettings_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## membersSliceTimeline_Query<br>
Request URL: `https://api.twitter.com/graphql/ohtbB6ZKiLYshYxPJz1RNw/membersSliceTimeline_Query`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## moderatorsSliceTimeline_Query<br>
Request URL: `https://api.twitter.com/graphql/FFpRSheri8ikANi1pyAfSQ/moderatorsSliceTimeline_Query`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## DelegateQuery<br>
Request URL: `https://api.twitter.com/graphql/GhQlWgEZ8wKf_JimVEG-Yw/DelegateQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GroupMenuMutation<br>
Request URL: `https://api.twitter.com/graphql/35IlHo3PPoKCgjGN9PyBEQ/GroupMenuMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GroupsDelegateQuery<br>
Request URL: `https://api.twitter.com/graphql/a8IpKTmRdGxQogYxbkvcaQ/GroupsDelegateQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## GroupsModalQuery<br>
Request URL: `https://api.twitter.com/graphql/fhf4gWuiGgRWDHdZy2Calw/GroupsModalQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## InviteMenu_accept_Mutation<br>
Request URL: `https://api.twitter.com/graphql/DpdMDix7rAjl6SVAs3SNSQ/InviteMenu_accept_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## InviteMenu_reject_Mutation<br>
Request URL: `https://api.twitter.com/graphql/QLNN5GVLRMe93lHnX3Um2w/InviteMenu_reject_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MembersDelegateQuery<br>
Request URL: `https://api.twitter.com/graphql/XH7fhVFAXoSLlrWHyczncg/MembersDelegateQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## useAddMemberModalMutation_add_Mutation<br>
Request URL: `https://api.twitter.com/graphql/SFV2FWbGnq-s473RcXrDsg/useAddMemberModalMutation_add_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useChangeMemberRoleModalMutation_change_Mutation<br>
Request URL: `https://api.twitter.com/graphql/bt_mUik7_sqXKofZmEBzAw/useChangeMemberRoleModalMutation_change_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useDelegateMutation_settings_Mutation<br>
Request URL: `https://api.twitter.com/graphql/2HD9lnvauHCbl4wRw2P_QQ/useDelegateMutation_settings_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useMemberMenuMutation_cancel_invite_Mutation<br>
Request URL: `https://api.twitter.com/graphql/QSkmmm7WG94DG9AfV2QHkg/useMemberMenuMutation_cancel_invite_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useMemberMenuMutation_remove_Mutation<br>
Request URL: `https://api.twitter.com/graphql/R8K9DRNeWen33po2wpZhZw/useMemberMenuMutation_remove_Mutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AdsCategoriesMutation<br>
Request URL: `https://api.twitter.com/graphql/eRWyTnzFgPgv9D4W8ujf6A/AdsCategoriesMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AdsCategoriesQuery<br>
Request URL: `https://api.twitter.com/graphql/FO_KX1o77E3vYL14rATn9Q/AdsCategoriesQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MonetizationSettingsQuery<br>
Request URL: `https://api.twitter.com/graphql/oi9OqvClsF9hkRsedoNvjw/MonetizationSettingsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## RepliesGetUserToxicReplyFilterSettingQuery<br>
Request URL: `https://api.twitter.com/graphql/kmAhocLFK1cbzXxGq5Boow/RepliesGetUserToxicReplyFilterSettingQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useToggleToxicReplyFilterSettingMutation<br>
Request URL: `https://api.twitter.com/graphql/2DSpolLNDpVL7KDJ-UWHSg/useToggleToxicReplyFilterSettingMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SensitiveMediaSettingsQuery<br>
Request URL: `https://api.twitter.com/graphql/ft92vAsha0RhDxwgq_ojWQ/SensitiveMediaSettingsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useEditSensitiveMediaSettingsMutation<br>
Request URL: `https://api.twitter.com/graphql/YWGRWrle16Fb6JvAjvjoTQ/useEditSensitiveMediaSettingsMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useSuperFollowsDeactivateMutation<br>
Request URL: `https://api.twitter.com/graphql/K5_KjMpjdtjQXzKGLqyFXw/useSuperFollowsDeactivateMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useSuperFollowsSaveOnboardingMutation<br>
Request URL: `https://api.twitter.com/graphql/tYYBdo8fCA4AHLbLpVCjSg/useSuperFollowsSaveOnboardingMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MonetizationAwardsRevenueQuery<br>
Request URL: `https://api.twitter.com/graphql/8jF4OXB6UikNJySm4YcMPw/MonetizationAwardsRevenueQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## MonetizationAwardsSettingsQuery<br>
Request URL: `https://api.twitter.com/graphql/9aX5g4DnUZtOROAY-c4zxg/MonetizationAwardsSettingsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MonetizationAwardsTransactionsQuery<br>
Request URL: `https://api.twitter.com/graphql/sAPSWMMizPG56c577mJzkw/MonetizationAwardsTransactionsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## MonetizationEarningsQuery<br>
Request URL: `https://api.twitter.com/graphql/OEDbqvCH79--KG7Qj-Ee7w/MonetizationEarningsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MonetizationPayoutHistoryQuery<br>
Request URL: `https://api.twitter.com/graphql/7p0HY_Hd7ZcK3uXqAmAoSg/MonetizationPayoutHistoryQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MonetizationSuperFollowsNewSubscriptionsQuery<br>
Request URL: `https://api.twitter.com/graphql/zSNaMxucPClZIhaMo1WrFg/MonetizationSuperFollowsNewSubscriptionsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## MonetizationSuperFollowsPerksQuery<br>
Request URL: `https://api.twitter.com/graphql/R3oGONdm5lb25R25U94N8w/MonetizationSuperFollowsPerksQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## MonetizationSuperFollowsRenewalsQuery<br>
Request URL: `https://api.twitter.com/graphql/O6MeVf9UpZhSsb3T6ezZiw/MonetizationSuperFollowsRenewalsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## MonetizationSuperFollowsRevenueQuery<br>
Request URL: `https://api.twitter.com/graphql/2SQNGD0l1hqKGa229sB4yw/MonetizationSuperFollowsRevenueQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## MonetizationSuperFollowsSettingsQuery<br>
Request URL: `https://api.twitter.com/graphql/aFWWcodXU_NhvBbfkXjleQ/MonetizationSuperFollowsSettingsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## MonetizationSuperFollowsTransactionDetailsQuery<br>
Request URL: `https://api.twitter.com/graphql/EWp9dMVitYnNjmyidTUy1A/MonetizationSuperFollowsTransactionDetailsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## useAwardsDeactivateMutation<br>
Request URL: `https://api.twitter.com/graphql/01C9DqWmpi6YUNYaIWMBwA/useAwardsDeactivateMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SuperFollowsApplicationSubmitScreenMutation<br>
Request URL: `https://api.twitter.com/graphql/3WMJN5LwxGA85U4iLzcfbg/SuperFollowsApplicationSubmitScreenMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SuperFollowsOnboardingPricingConfirmScreenMutation<br>
Request URL: `https://api.twitter.com/graphql/_97mdj3S3wU106zmC8Wy3A/SuperFollowsOnboardingPricingConfirmScreenMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SuperFollowsSettingsQuery<br>
Request URL: `https://api.twitter.com/graphql/a5NihPIqetRdmuJWRyXPCw/SuperFollowsSettingsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## useSuperFollowsCreateStripeOnboardingUrlMutation<br>
Request URL: `https://api.twitter.com/graphql/KCzv96qeUky_-C22g3lZSw/useSuperFollowsCreateStripeOnboardingUrlMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AwardsSettingsQuery<br>
Request URL: `https://api.twitter.com/graphql/c_ww6XqjHvIqQAZWzaRR2g/AwardsSettingsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useAwardsActivateMutation<br>
Request URL: `https://api.twitter.com/graphql/ql0nbxLYZcgEQyw5Z0PlWw/useAwardsActivateMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDmConversationMetadataQuery<br>
Request URL: `https://api.twitter.com/graphql/IljetauiTK1r1nzm9zNY-g/evolutionDmConversationMetadataQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## evolutionDmConversationTimelineQuery<br>
Request URL: `https://api.twitter.com/graphql/5rkutC9ILzPJYQfayYsbiw/evolutionDmConversationTimelineQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## AddParticipantsMutation<br>
Request URL: `https://api.twitter.com/graphql/oBwyQ0_xVbAQ8FAyG0pCRA/AddParticipantsMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## DMReportMessageListQuery<br>
Request URL: `https://api.twitter.com/graphql/V31NtOBqa1JKd42wgo7Z9w/DMReportMessageListQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## ProfileSpotlights_EditableProfileSpotlightsQuery<br>
Request URL: `https://api.twitter.com/graphql/r3pgxpnbcR10hKon3pxNEg/ProfileSpotlights_EditableProfileSpotlightsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UpdateProfileSpotlightVisibilityMutation<br>
Request URL: `https://api.twitter.com/graphql/mDq5tCOsuuDzxezaI30d3A/UpdateProfileSpotlightVisibilityMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## LocationSpotlightQuery<br>
Request URL: `https://api.twitter.com/graphql/PtT7DMn9eI8yFh-jkG-fGg/LocationSpotlightQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useDeleteLocationSpotlightMutation<br>
Request URL: `https://api.twitter.com/graphql/2ohYQLw6z3bqaCjSqs_LBQ/useDeleteLocationSpotlightMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useMapImageLoaderQuery<br>
Request URL: `https://api.twitter.com/graphql/1fFcufgOXV2EXGD578RpQw/useMapImageLoaderQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ProfessionalHomeQuery<br>
Request URL: `https://api.twitter.com/graphql/E4b4WwmzUESbbZJmz3vbjA/ProfessionalHomeQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## ReportDetailQuery<br>
Request URL: `https://api.twitter.com/graphql/iDoo9-T00DI2oypZ0YmRNQ/ReportDetailQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ReportDetailSafetyCenterQuery<br>
Request URL: `https://api.twitter.com/graphql/1wRoskRvcqMJ66YJuIJVJA/ReportDetailSafetyCenterQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## LoggedOutSearchHomeTrendsListQuery<br>
Request URL: `https://api.twitter.com/graphql/jFSVxO6XekDkqa9LhEqxug/LoggedOutSearchHomeTrendsListQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TweetActivityQuery<br>
Request URL: `https://api.twitter.com/graphql/1PcjM2Rbmn8rKYj8trjO6w/TweetActivityQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                       | type    | variable   |
|:------------------------------------------|:--------|:-----------|
| responsive_web_tweet_analytics_m3_enabled | boolean | False      |

#### queryId<br>
`None`<br>
## TweetCoinDetailsScreenQuery<br>
Request URL: `https://api.twitter.com/graphql/aRul9ilRrCc3jG7lF_9tJg/TweetCoinDetailsScreenQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## TwitterBlueSignUpV2Query<br>
Request URL: `https://api.twitter.com/graphql/B7I5HPN6jm5Mgv9N8fgFPg/TwitterBlueSignUpV2Query`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TwitterCoinsManagementCoinBalanceQuery<br>
Request URL: `https://api.twitter.com/graphql/7UIOQwnGlrNqaLd16fTwYg/TwitterCoinsManagementCoinBalanceQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TwitterCoinsManagementCoinPackQuery<br>
Request URL: `https://api.twitter.com/graphql/TtPtRW7yaLbnwCFJANYNFQ/TwitterCoinsManagementCoinPackQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useCoinPurchaseSessionUrlMutation<br>
Request URL: `https://api.twitter.com/graphql/QP5WVTrpvWikhlKybPX5jQ/useCoinPurchaseSessionUrlMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## combinedListsPageTimelineQuery<br>
Request URL: `https://api.twitter.com/graphql/X66kM5VU5GlNDs1Ud9RCCw/combinedListsPageTimelineQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                                     | type    |   variable | default   |
|:------------------------------------------------------------------------|:--------|-----------:|:----------|
| freedom_of_speech_not_reach_fetch_enabled                               | boolean |          0 | nan       |
| graphql_is_translatable_rweb_tweet_is_translatable_enabled              | boolean |          1 | nan       |
| interactive_text_enabled                                                | boolean |          1 | nan       |
| longform_notetweets_consumption_enabled                                 | boolean |          1 | nan       |
| longform_notetweets_richtext_consumption_enabled                        | ...     |        nan | error     |
| responsive_web_edit_tweet_api_enabled                                   | boolean |          1 | nan       |
| responsive_web_enhance_cards_enabled                                    | boolean |          0 | nan       |
| responsive_web_graphql_exclude_directive_enabled                        | boolean |          1 | nan       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled       | boolean |          0 | nan       |
| responsive_web_graphql_timeline_navigation_enabled                      | boolean |          1 | nan       |
| responsive_web_text_conversations_enabled                               | boolean |          0 | nan       |
| responsive_web_twitter_blue_verified_badge_is_enabled                   | boolean |          1 | nan       |
| standardized_nudges_misinfo                                             | boolean |          1 | nan       |
| tweet_awards_web_tipping_enabled                                        | boolean |          0 | nan       |
| tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled | boolean |          0 | nan       |
| tweetypie_unmention_optimization_enabled                                | boolean |          1 | nan       |
| verified_phone_label_enabled                                            | boolean |          0 | nan       |
| vibe_api_enabled                                                        | boolean |          1 | nan       |
| view_counts_everywhere_api_enabled                                      | boolean |          1 | nan       |

#### queryId<br>
`None`<br>
## TrustedFriendsAddRemoveButtonAddMutation<br>
Request URL: `https://api.twitter.com/graphql/_VDotBzHuuA7S_mVil4xJA/TrustedFriendsAddRemoveButtonAddMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## TrustedFriendsAddRemoveButtonRemoveMutation<br>
Request URL: `https://api.twitter.com/graphql/pwXaXTTpChehT6k27CLS9A/TrustedFriendsAddRemoveButtonRemoveMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## TrustedFriendsMembersQuery<br>
Request URL: `https://api.twitter.com/graphql/yQD4In2qJOzB634Gihn8OA/TrustedFriendsMembersQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## TrustedFriendsRecommendedQuery<br>
Request URL: `https://api.twitter.com/graphql/1OOnfeRa2lOFhK7sFUbT3g/TrustedFriendsRecommendedQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_timeline_navigation_enabled    | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## userNftContainer_Query<br>
Request URL: `https://api.twitter.com/graphql/gTkKcR0rAOGFRHAU_uAkTQ/userNftContainer_Query`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## SuperFollowsManageQuery<br>
Request URL: `https://api.twitter.com/graphql/9wSLGuGXeq_zKNUZYEAF6Q/SuperFollowsManageQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useSuperFollowsChangeBadgePrivacyAddMutation<br>
Request URL: `https://api.twitter.com/graphql/X6X4JiyQHfLz0SdTaZPixw/useSuperFollowsChangeBadgePrivacyAddMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useSuperFollowsChangeBadgePrivacyRemoveMutation<br>
Request URL: `https://api.twitter.com/graphql/Mg-0dMrg-__WGhnWqj4nfQ/useSuperFollowsChangeBadgePrivacyRemoveMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useSuperFollowsCreateStripePortalUrlMutation<br>
Request URL: `https://api.twitter.com/graphql/cot9fAsCQIQGNYu9Rica6w/useSuperFollowsCreateStripePortalUrlMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SuperFollowsSubscribeQuery<br>
Request URL: `https://api.twitter.com/graphql/Kl7SMuZW91heufwOO_NAQw/SuperFollowsSubscribeQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## useSuperFollowsCreateStripeSubscriptionUrlMutation<br>
Request URL: `https://api.twitter.com/graphql/1nNykZ_aQohdxHKoykBVmg/useSuperFollowsCreateStripeSubscriptionUrlMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## ProfileSpotlightsQuery<br>
Request URL: `https://api.twitter.com/graphql/9zwVLJ48lmVUk8u_Gh9DmA/ProfileSpotlightsQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AffiliateListItemMutation<br>
Request URL: `https://api.twitter.com/graphql/QSueyUwwWLaV6s50Z8Ct4Q/AffiliateListItemMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AffiliateListItemUpdateAffiliateTypeMutation<br>
Request URL: `https://api.twitter.com/graphql/v5rNoNo7tAvWpUn6pIdo9A/AffiliateListItemUpdateAffiliateTypeMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## AffiliatesScreenAffiliatesQuery<br>
Request URL: `https://api.twitter.com/graphql/0OGz7UtpFJ7gPkFh16s5Ow/AffiliatesScreenAffiliatesQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## InviteScreenMutation<br>
Request URL: `https://api.twitter.com/graphql/wlKXnGjJUQY3ORUxCTn0HA/InviteScreenMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## PriceQuery<br>
Request URL: `https://api.twitter.com/graphql/fEIrXM_SROA9quiRBq2QDA/PriceQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SettingsScreenCancelSubscriptionMutation<br>
Request URL: `https://api.twitter.com/graphql/UaL8qHOdA_HHqwjNX4Q74Q/SettingsScreenCancelSubscriptionMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## TabBarCreateStripePortalUrlMutation<br>
Request URL: `https://api.twitter.com/graphql/Ro4_N0mgeE5CyS6oD_Y13w/TabBarCreateStripePortalUrlMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## WelcomeScreenMutation<br>
Request URL: `https://api.twitter.com/graphql/vmeQkOLp4CLZ2zG0AgIe3A/WelcomeScreenMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useAffiliatesAndInvitesQuery<br>
Request URL: `https://api.twitter.com/graphql/R23fc4rldc6jOdcv8u_nRw/useAffiliatesAndInvitesQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## useCreateInvitationMutation<br>
Request URL: `https://api.twitter.com/graphql/TBPxcdVsUNF9iCIOsLwfKw/useCreateInvitationMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## useDeleteInvitationMutation<br>
Request URL: `https://api.twitter.com/graphql/crOZy3iUFNLxqbq41GQ7pg/useDeleteInvitationMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## FollowResourceButtonColumnMutation<br>
Request URL: `https://api.twitter.com/graphql/ffs8wfy3-doFmQZAxRiW9A/FollowResourceButtonColumnMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## SharedResourceFollowModalColumnQuery<br>
Request URL: `https://api.twitter.com/graphql/NmJS0Mmr25vNhTP9IflbPQ/SharedResourceFollowModalColumnQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## CommunitiesFetchOneQuery<br>
Request URL: `https://api.twitter.com/graphql/X0NHONtz51pwNp2mT6kjhQ/CommunitiesFetchOneQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## CommunitiesMembershipsRecentQuery<br>
Request URL: `https://api.twitter.com/graphql/-yNbGN1CWVwVCEmlMZJ6zw/CommunitiesMembershipsRecentQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## UsersGraphQLFetchByScreenNameQuery<br>
Request URL: `https://api.twitter.com/graphql/HXoFiEDAMHxO1kU1GMLd8Q/UsersGraphQLFetchByScreenNameQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## CommunitiesFetchOneQuery<br>
Request URL: `https://api.twitter.com/graphql/X0NHONtz51pwNp2mT6kjhQ/CommunitiesFetchOneQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## CommunitiesMembershipsRecentQuery<br>
Request URL: `https://api.twitter.com/graphql/-yNbGN1CWVwVCEmlMZJ6zw/CommunitiesMembershipsRecentQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## UsersGraphQLFetchByScreenNameQuery<br>
Request URL: `https://api.twitter.com/graphql/HXoFiEDAMHxO1kU1GMLd8Q/UsersGraphQLFetchByScreenNameQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                               | type    | variable   |
|:------------------------------------------------------------------|:--------|:-----------|
| responsive_web_graphql_exclude_directive_enabled                  | boolean | True       |
| responsive_web_graphql_skip_user_profile_image_extensions_enabled | boolean | False      |
| responsive_web_graphql_timeline_navigation_enabled                | boolean | True       |
| responsive_web_twitter_blue_verified_badge_is_enabled             | boolean | True       |
| verified_phone_label_enabled                                      | boolean | False      |

#### queryId<br>
`None`<br>
## DelegateSwitcherListQuery<br>
Request URL: `https://api.twitter.com/graphql/2gn-Pw5YoB31Ip_Jke_7tA/DelegateSwitcherListQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
| key                                                   | type    | variable   |
|:------------------------------------------------------|:--------|:-----------|
| responsive_web_twitter_blue_verified_badge_is_enabled | boolean | True       |

#### queryId<br>
`None`<br>
## FollowHostButtonQuery<br>
Request URL: `https://api.twitter.com/graphql/kURURMFUKw2d-eHgilgSzA/FollowHostButtonQuery`<br>
Request Method: `GET`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## PinTweetToCommunityMutation<br>
Request URL: `https://api.twitter.com/graphql/5jpFuDdu111UuWpne0_ajg/PinTweetToCommunityMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>
## UnpinTweetFromCommunityMutation<br>
Request URL: `https://api.twitter.com/graphql/GJ-aDJmAPMnisHg-52fI3g/UnpinTweetFromCommunityMutation`<br>
Request Method: `POST`<br>
Login Required: `...`<br>
### Param<br>
#### variables<br>
`None`<br>
#### features<br>
`None`<br>
#### queryId<br>
`None`<br>