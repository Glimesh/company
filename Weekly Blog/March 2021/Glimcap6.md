# Glimcap Part 6

So much has been going on at Glimesh and we just can’t keep up with the excitement after launch. Our growth and the support from the GlimFamily has been huge!! This week's Glimcap is a special one as it's our first one since launching the Alpha. We took some time off last week and this week we are hoping to get back into the full swing of things.

This week is going to look a little different from our regular pattern and might continue to look different from here on out.

# Glimesh’s Growth


| <br/> | This Week | 2/23/21 | Diff |
| - | - | - | - |
| Discord | 6,141 | 3,667 | 2,474⬆ |
| Twitter | 8,858 | 5,944 | 2,914⬆ |
| Reddit | 517 | 366 | 151⬆ |
| Instagram | 1,084 | 533 | 551⬆ |
| Facebook | 500 | 266 | 234⬆ |
| <br/> | <br/> | <br/> | <br/> |
| Users | 32,981 | 17,782 | 15,199⬆ |
| Apps | 520 | 124 | 396⬆ |
| MRR | $8430 | $360 | $8,070⬆ |
| Support Tickets* | 262 | 96 | 166⬆ |

*Total support tickets for the past two weeks is 443

Our recent growth since launch has been phenomenal. We grew leaps and bounds across the board almost doubling our numbers on the site in the last 2 weeks. Our socials have all increased by good numbers as well thanks to the love you all have shared.

Launch Week Metrics


| Total Number of Streams | 6,604 |
| - | - |
| Total Views | 122,297 |
| Total Unique Streamers | 2,834 |
| Hours Streamed | 16,634 |

Here are some awesome numbers we saw during the launch week until now. We were surprised at the total amount of users who came to stream on day one and the number of views that we had. We are excited to see the hype that the platform has been making over the last 8 months. Just from February 28th to March 8th we’ve seen 1.8 million page views with 113K unique visitors!

![](https://lh4.googleusercontent.com/xOE_eaNXWNmtAq1KeQrvT88LHok9IS3UBOrTd3zTwfKkPjc0rDkpkFAf_r89mjwaR-qs-4H_Fv7SxXVxuVZqb1JR2z-9zxNzdkQVR-HE13DZHpZLu0P8pUhpDvr7Yt2hEhH--6nc)

![](https://lh6.googleusercontent.com/TX0qMlDhqiwKQuASkwogPakUO3MiwXNrI3p8r4ntDTLF8CEy4Gy-X5Ck-dPkreW56ersGRdw5sF-C12ndVwJd3CZ5r5rUgJAkx8REFusj3zuICIwwNDugoEZRTHMSbvm70rTD_-K)

# Financials

Our financials are also looking very nice from all the wonderful support we’ve seen. There has been a surprising number of the Glimfam that have been contributing with Platform subs and we want to thank you all for that support. We’ve also been seeing wonderful support for the streamers on the platform that we were able to payout over 1,800$ on Wednesday all thanks to your support.

We should have no problem with paying for our servers for the month with the current support we are receiving. As we grow the server costs will increase, but we also hope that the community will continue to help support us and each other, which will ensure that we can continually cover those costs.

![](https://lh3.googleusercontent.com/e91Z_7hNf7wNoh9olLrLj55TORbWH-IQs2wwV09alXgIN6bkqo9Nlp0YUf4UKUaaw4VdcYH-zVgqpvrSWB73UQeyvdeHzkE78kgBN7oolRQcM20YO2wxvEeKEBvuBvoHtejeg56a)

**Gross Platform Sub Revenue**

$6,290.00

**Gross Channel Subs**

$3,658.00

**Estimated Payout Wednesday**

$1,809.14

**Estimated Server+BW Cost**

$2,300.00

# So How Did Launch Go?

The launch on March 2nd was a pretty successful test but it did come with some difficulty. Right off the bat we had stream stability issues, API issues, and some general improvements that needed to be made.

On the stability side we started off a bit rough. But the dev team worked hard through the entire night to get a handful of fixes in right off the bat.

* Fixed a few places where the FTL servers would deadlock and stop relaying video or accept new connections
* Fixed a few places where the FTL servers would spin and eat excessive CPU
* Fixed a few random crashes related to unexpected connection failures
* Fixed an issue where Ingest nodes would delay incoming video packets while establishing connections to Edge nodes, which would cause streams to freeze or stutter

All these issues were all fixed in just the first few days of the service being up. And we are continuing to make overall improvements to the platform.

For the API we say some of these improvements

* Stopping stream will now update the API and the channel LIVE status
* Error in the API when querying a user endpoint with no parameters
* Debugging telemetry for common API calls & expensive functions
* API bug on querying for a nil channel
* Empty response for Stripe Webhook API

For the Streamers User Experience we worked on

* Some chat scrolling improvements for pop-out chat
* Added Ninety9Lives to the DMCA page
* Copy to Clipboard not working on unsupported browsers
* Click to Copy now functions as expected
* Add tag selector to the stream page edit menu
* Discord invite links are now acceptable in any format
* Add live message to user's profile

For our viewer experience we had

* Subscription error message when you are not eligible to subscribe to the channel
* Play audio un-muted if the browser will allow us
* Remember user's previous audio volume level across streams
* Chat scroll sticking not always functioning as chat gets larger
* Emotes not always appearing in large size
* Glimesh emotes are now first in the emote selector

And then our General User experience we have added and fixed

* Mods not having a subscriber icon if they subscribe
* Light mode not always showing visible text on homepage and stream pages
* Timing out a user no longer clears chat
* 2fa image not always generating for all users
* Moving to a semi-unique viewer count which will make you only count as a viewer once per stream
* Optimize chat timestamps enable / disable
* Remove emote selector from non-logged in users
* 44 new GlimDrops live on the site
* Adding "Where did this happen?" to the report menu

![](https://lh5.googleusercontent.com/gWk2sla1lNoNOrl30GyRuo9SMPPjE6duGuILVcVhFCcGOtI1QUqNz9ceaFOgAspf422AacFLlOvKi7EarzrCNGs9G37WFFmmWYCIYq7x-dD_0AZgLUBSG6S6ISk0TSVgLyomM5P4)![](https://lh6.googleusercontent.com/GbjNeSROF-w839knBmMRk-zKIDmslYpzyCDpQ_7E5J4XchAzqEVbWtPV-H_nQG0wjVV0krIiLQuBF1twkEqUAaUevcLpLzBD9FylLDgr6n4lBHN-8vttYoW7lls1YX1jHSd7zsCW)![](https://lh4.googleusercontent.com/jw-Cyb0FH7gq43qOCFfHKquzuLFWcm4qEeMNgrfszGVGTFLRd5j9APskw0KuIaduup8n3XdKQS0VWRal1G81VKppRdBZpHtlCyII6fJyWc5TNRPhExCT8_wvij8qhip4tsEH2BqQ)![](https://lh6.googleusercontent.com/QjcPMateKSshlFMql_Uo1xrrthJkth5f8Zg4UANIa9SSHHodDONVGmQKu-lVOXnl-HJ1YQaqCxhBEGPj5vfpgNsgCqAVt3wta3swpohHimReibtgDmNMO0fsE6tmsE9Y3_NGH4eP)![](https://lh5.googleusercontent.com/PBeWmbMOEOU2-dZfmkZslrTkF57KzDLuhvrhS7xTRIgPFsA7o_xV-UGRv4kuKb0zK8hrUPR6mVHwHThE0tmNVA_1Y4lRAgQnguOatwIxgGlensmEglmMr4ChtgnVjViOhHop3Wrg)

# What’s Our Immediate Focus?

So now that we are officially into the first stage of the Alpha what are our immediate points on focus you might ask?

* Channel Safety (anti-spam, etc) - Safety is one of our primary focuses as a platform and we want to make sure that we are always focused on keeping things safe and secure. So we added something to help your channel combat spammers. We’ve given the option now for you to add a timer for how old accounts have to be before chatting as well as only allowing those with a verified email to chat. Which will hopefully help keep your streams more safe.

![](https://lh4.googleusercontent.com/XxXkxiWXjiA3cWIs8bCpbxNC2obO8hRoyU9ur8m7KYMIOUFo0VNiiIWOsJTl5p06QTkkb0whwlyvXY19E_Vh8BCqOnbuFS0nmVEuG_aVlsuR6fD-F2_-X1GmGAizczaudxM4is98)

* Payouts

  * First payday Wednesday! We were able to send out over 1,800$ this Wednesday to over 400 streamers with only 4 issues in the payouts. These issues were from an internal test group that had old settings enabled so our payout system worked out as intended.
  * GCT Support tools for payouts is another focus for the near future. We are hoping to add more support to be able to help the GCT provide better support for payouts while keeping your information safe and secure.
* Stream Stability
* Architecture improvements to the FTL stack are being made to reduce the surface area for race conditions or deadlocks, and prioritize efficient routing of stream data. We are focusing on making improvements to the FTL and to the service to make a strong stable service.
* Tag Improvements - We want to make sure that with tags being a core part of our discovery tools that they are always going through iterations for improvement as we learn how people use them.

# What’s Next?

With our immediate focus being on the items above we also want to refocus on our roadmap some.

We want to start looking at these Phase 2 features and looking at the priorities of what is currently on there and what we have been receiving for feedback. While we are still working on Phase 1 we want to make sure that we are focusing towards the right things when Phase 2 starts. Currently it’s all still TBD but we want to start getting some feedback from the community and have some time to gather information on what the community believes will be important going forward.

![](https://lh4.googleusercontent.com/GUdjo_qupt6UmdbOcV9xDsJilc3ycc6L87wyoamF4tRwD9JlbnBX41LR_de-9D8VaWa_mnkO-u_uRwEi0kLnZiSsr4fJ04tD52sPiNIFOqhEl21AXfd_IPvBl0X429xY6U_fpnFM)

There is possibly a change coming up as well with our weekly meetings. We may move them to bi-weekly or monthly to help refocus some time on development of the site and the company. Keep an eye on Twitter and the Discord for more info.

# GlimFact of the Week

Glimesh is here to support you. Here are just some of the ways we offer to help you out on your streaming journey with us.

* Email [support@glimesh.tv](mailto:support@glimesh.tv) if you are experiencing any issues or would like to report something.
* Check out our [Support Site](https://support.glimesh.tv/en-us) for resources, guides, and FAQs!
* Visit our [Discord](https://discord.com/glimesh)! We have channels dedicated to #bugs, #questions, & #streaming-help to tackle any issues or answer any questions you might have on the fly.
* If all else fails, keep an eye on our [Twitter](https://twitter.com/glimesh) account. We’ll post any major announcements or need to know updates there, too.

**
