# Decisions





                                                      Gap CLosure 
“Pickup times are wrong.” How often, and out of how many pickup orders? Dev’s PM pack has this.
There are no options to choose pickup times, and the checkout only has an order number, no confirmation email/text, and also no final pickup time est. 

                                             The fix pretending to be a problem. 

 The problem of that solution would be that people often re-order the same and may not want to complete their order if they have to continuously do it. Having the ability to have a foundation even if you later want to add or change something to it is convenient. 


                                              The constraint nobody wrote down.

The constraints of having no tooltip, no popover, no accordion, table, pagination, or avatar, are all negatively impacting the app. Because rail has these constraints, the nav could be harder to read on a smaller tab and thus easier to make mistakes for both staff and guests. Another other thing is the backup of tables and popovers. Both of which help tremendously aid in leggability, and trustworthiness. In the legacy folder the estimated time is constantly set for 20 minutes, this will not change unless stopped during a rush. 



-----------------




                            Option A: Pickup times are shown before checkout
- In one sentence: Users are able to choose pickup times,before checkout, and are presented restaurant contact information if needed for different days, or times.
- What it costs the user: User would have to think about pickup time prior to starting to place order
- What it costs the system, including build effort:Low cost. No real new change just accessing the pickup times that are blocked off in the system
- What it assumes:User may not be able to pick up order asap.
- What would kill it?:Users miss the indication to choose a pickup time 



                  Option b: Live updates of pickup times and estimated time delays
 In one sentence: - Users can change pickup times with ones available, and also be notified of the window of wait time depending on the rush (10, 15, 25 minutes,etc.)
- What it costs the user: Would have updated information so it  could feel overwhelming to some users
- What it costs the system: Could be a higher cost for the system as it would mean having somewhat live update times during rush hours or when exceeding a certain amount of tickets. 
- What it assumes:Customer needs to know the exact time, and if not the estimated time range before placing order.
- What would kill it?:Users do not focus on the estimated time and only come during pickup time, and are upset that the time in inaccurate during a rush 

       Option C: User can choose pickup times, and there is a final detailed  confirmation page 
 - In one sentence: - Customer can change pickup time before and after checkout, they will also receive an order number, confirmation email/message, and pickup instructions
- What it costs the user: User would need to thoroughly readback feedback to prevent errors and miscommunications on both parts
- What it costs the system: Low cost. No new additions to the system other than a fully completed confirmation page with interactive elements( connecting an email or number for confirmation receipt) and also just general html text of instructions and and order details.  
- What it assumes:Customers need a full visual summary of order, in order to feel as ease and trustful of pickup time and procedures.
- What would kill it?:Users do not read over the summary, and are confused when arriving at restaurant







