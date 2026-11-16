# Evidence


HEARD-226 Pickup times are wrong when the kitchen is slammed

You are a single mother of 4, ordering takeout from a new restaurant. 

5-task script 

Script
1) Build an order for the five of you, keep in mind, each of your kids cannot have vegetables or cheese.
2)Your youngest asked for the Al Pastor tacos(surprise everyone else)
3)After you finish placing the order, your youngest child decides they do not want the tacos and you need to change it for something else
4)The total must be under 150
5)Place the order, and let me know the time your food will be ready. 



---

## Week 1: Rail parity check



| Token | Figma value | `tokens.css` value | Agree? |
|---|---|---|---|comfortable|
| primary/50 | #FEF3EE | #FEF3EE | yes |
| type/body/weight | 400| 400 | Yes, both have the same font-weight(thickness) |
| type/body/size  | 13px | 16px | body size is not the same; figma is 13px while the css code is 16px. value should be taken from Figma since the source of truth sepcifiec that the origin is figma for any font sizing errors.|
| radius/md | 12px | 12px | yes |
| comfortable (gap) | 8px | 8px | yes |


 Token | Figma value | `tokens.css` value | Agree? |
|---|---|---|---|compact|
| type/body/size| 14px| 14px | yes |
| type/body/line | 22px| 22px | Yes|
| space/inset/md | 12px | 12px | yes |
|  space/inset/lg | 16px | 16px | yes|
|  space/inset/sm | 6px | 6px | yes |

| Figma value | `tokens.css` value | Agree? |
|---|---|---|---|service|
| type/body/size| 24px| 24px | yes |
| type/body/line | 32px| 32px | Yes|
| space/inset/md | 24px | 24px | yes |
| space/inset/sm | 12px | 12px | yes |
| space/inset/lg | 32px | 32px | yes |




---

Week 2: Studio B 

                                                          Framed problem: 
The heard guest-line is very confusing. For starters, its main problem is failing heuristic #1 (visibility of system status). It fails the first rule because of its lack of feedback during the checkout process.  During checkout, users need to feel trust towards the application, you achieve this through clear communication of each part but my examination proves that this checkout process led to a lot of hesitation to continue forward. On a technical standpoint, there is a pickup time option dropbar, that is inaccessible to the client. In addition to this issue, there is a lack of information and confirmation details when order has been placed. This led both of my participants to claim they would need more information to feel as though the process is complete, and they can trust their order will be finished on time and fresh. 


                                                          Patterns: 
Both Baylee and Felipe hesitated a few times when doing the experiment. Noticeably, they both hesitated when making changes to original meals. Both of them were confused during checkout, unable to change pickup time, and wanted a receipt/email and confirmation of order and person ordering. 


                                                   Three moments worth quoting:
___Hestiation when removing cheese and veggies for each of the meals
______confusion when pickup times down arrow didnt open
_______confusion during checkout, feeling incomplete


                                                       Success Measure:
Participants can choose pickup times, and later confirm what final pickup time, and order summary is presented. This must be for both participants with no expectation. If participants feel the checkout process is incomplete and they are unsure of pickup times the measure is failed.




