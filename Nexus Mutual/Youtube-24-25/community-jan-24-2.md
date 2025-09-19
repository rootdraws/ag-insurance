Transcript


0:00
welcome everybody to this week's bi-weekly Community call we hold these calls every other Tuesday at 8:00 a.m.
0:06
eastern and 1:00 p.m. UTC and talk about the future of risk sharing and everything new in the Nexus
0:14
Mutual this week we have the Uma team with us on the call they will talk about
0:20
their proposal to implement o snap for the Nexus Mutual Dow Treasury and then
0:25
Brave New D5 will walk us through the recent reviews uh of the economics
0:30
project we looked at the Redemption analysis and he will also review the
0:36
long-term State parameters with the RAM and then he'll go over the road map for
0:41
the next two quarters and also underline the budget request that we
0:47
currently have active on the Forum and then we'll hear from Hugh with his
0:53
weekly update from the foundation look at the last week in review and close the
0:59
call after an open Forum let's get things started with the
1:04
Uma team Bobby would you like to take it
1:12
away yeah sounds good glad to be here so me and Alex we're from uma uma is the
1:19
what we ter the decentralized trth machine but today we're going to be focusing on on o snap not Prett much it
1:24
just helps decentralize onchain execution directly from your safe so
1:29
what we kind of wanted to do was we had this phex Mutual we know that you guys have an an offchain uh you guys have two
1:37
typ of proposals the Nexus Mutual Dow proposal and the mpip so adding o snap
1:43
is really tailored towards the the Nexus Mutual Dow proposals Sur because um that
1:48
affects the Community Fund and we thought we could help streamline that process because right now when you guys
1:53
prove um a budget a team budget it could be like just paying out your different teams once you do a snap proposal then
2:01
the multi signers have to then manually execute after what this does is with o
2:06
snap that just automatically execute so there won't be any need for the multi signers to actually do that manual
2:12
effort and we know across dlls that is like takes a lot of coordination across different time zones and manual effort
2:17
so that will clean up that process so Alex will probably dig a bit deeper into how that process actually works by
2:23
setting up a proposal but just to be clear this old snap it only applies to the NEX Mutual D proposals the Community
2:30
Fund and will help unite that process so to actually add all snap to your safe um
2:37
it's very simple it's literally a few clicks so you're go into your snapshot space and then at the bottom there's a
2:43
settings and in advanced settings you can kind of connect your safe um to o
2:50
snap and once that's done it's two clicks and it's done that's set up so that would be an admin who controls your
2:55
snap space that that can do that quite easily and then to be very clear so that's the only change that you'll have
3:01
to do and then the current snap pH that you guys have for your n's Mutual da proposals will work the exact same
3:07
there's no difference there except every time that you create an snap enabled
3:13
snapshot proposal you can now incorporate transaction data so in your case in Nexus Style's case that could be
3:20
like sending token transfers so it could be sending usdc or Nexus Mutual tokens to those who have requested it besides
3:27
that nothing really changes and on the proposal we kind we work through this process as well and
3:33
hopefully Alex will be able to do this live as well um but for every proposal
3:39
that passes snapshot so a snapshot vote which is meeting quum and having a
3:44
majority of votes that means over 50% of the votes I 51% votes then after someone
3:50
proposes a bond which is 2 F and there's a challenge period of a couple days then
3:55
the proposal is automatically executed hence there being no multis signers necessary and to make this even easier for NEX
4:01
Mutual di we actually have an umot that also does the same for C swap across connects other Dows and this umabot will
4:09
automatically post the bond for you um and start that challenge period so that
4:14
no one from Nexus Mutual will have to post B thems and then once once the execution
4:21
is also executed the um also covers the gas cost for execution as well so for nex's Mutual there is no fees to use o
4:28
snap there's no fees to execute any to use or samp or to execute any transaction as
4:34
well and it just streamlines the whole process and then if there are any
4:41
disputes we also touch in touch touch on that into the proposal themselves um and
4:47
you can probably find a lot more detail there but after 60 proposals using o snap there's only been one dispute and
4:53
that has less to do with the proposal itself and more to do with a cloud flare related issue but besides that that kind
4:59
of covers what how oap will be tailored towards the Nexus Mutual snap. space um and to make it more tailored towards
5:06
Nexus Mutual there are a couple safeguards that could be incorporated into snow oh snap to make you guys feel a bit more comfortable it honestly
5:13
depends on how each Dow does it um I included an example of how cow incorporated safeguards into snapshot
5:19
space and I recommend checking that out but what they did was as a TDR They removed all administrators on the sub
5:25
space and they just kept only moderators um to add to add over moove proposals um
5:32
this minute of creting a proposal was permissionless and that's the way that they did that other DS they keep the
5:38
their rules the exact same but the two that we tailored for Nexus Mutual was
5:43
enabling moderators on on the snap space so in this case this could be the
5:49
next Mutual team leads I know you guys have like five six teams and each of those team leads could be a moderator and that would give them the ability to
5:55
either add or removal proposal um so like
6:00
you can still keep the creating a proposal a permissionless process but like if there are any spam proposals
6:06
then like moderates can remove that um then you also have the other mode which is an offer only mode so you could say
6:13
okay only the Nexus Mutual team needs have the only ability to upload a proposal onto the snapshot space for NEX
6:18
Mutual there are a few more examples and we can add them on but I thought those were the two that felt the most tailored
6:24
towards Nexus Mutual if anyone has any questions or comments just on the proposal feel free to like
6:29
drop a message in the Nexus Mutual Discord or even easier just put a comment on the the form post as well
6:36
please I I had one now if you're if you're open to taking them um yeah of course yeah so I think that'll make
6:43
sense I do like the fact that we don't have to coordinate the multi signers to get stuff done that's very helpful um so
6:50
I guess one of the things that um I'd like to know is like when so basically
6:55
when people vote they should actually verify the um transaction payload in the
7:01
in the proposal um is that I'm not sure quite sure how that looks Etc so is that
7:07
like um able to be done by regular people or is it um quite Technical and only um you know Dev type people would
7:14
be able to to do that verification yeah no that's a very very good question so I'll share some
7:20
examples um in the form post after as a comment but we make the data very readable so I think in Nexus mutuals
7:27
case um since it being token transfers that that is like anyone can check that
7:32
data it would be like transfer 50,000 usdc to this address and anyone should be able to check that themselves cool
7:40
that sounds good um yeah I think that was that was one of my that was one of the the concerns and I I guess the um
7:47
the other one was which you've kind of addressed was the um you know the the controls and stuff and it seems like
7:54
there's enough options there that we should be able to come up with something that that works so yeah thanks for
8:00
that yeah and then I just had um a quick one I know on the osnap site it says that um tenderly support is will be
8:08
implemented I was just wondering what the status of that is that's still in progress I will check
8:15
inney for a timeline but once I have an update I'll let you
8:21
know okay yeah that sounds good um I'll review in in a bit more detail I've
8:26
reviewed info about oap but I'll toss my thoughts on the Forum and everything as well um in the next day or
8:33
so hey everyone my name is Alex apologies I had some technical uh
8:38
difficulties and I was unable to do this demo during the community call Bobby
8:44
from our side was able to talk through osnap and the value
8:49
proposition um I just want to quickly include a short screen recording of just
8:55
um basically walking through a demo of what o snap looks like in production and I think it will highlight some of the
9:02
the small tweaks that will enable oap but also I think it'll make more sense
9:07
once you see it um in an existing space before I do that here is a proposal we
9:14
thought would be interesting one to use for oap it basically um when this uh
9:21
proposal was created the the Creator could have included this uh well yeah it' been this
9:30
these transfers that would have been made from the safe that would have been executed as long as the snap proposal
9:36
was valid so we'll just jump over to this test phase um if anyone who's created
9:44
proposal is should look familiar the only thing that is different is when you are choosing the
9:53
voting type you now have this option to make it a snapshot proposal or no snap
9:58
proposal and when you click this you now have uh
10:03
this um ability to include transactions in The Proposal I do want to mention
10:09
yeah it's very easy to not have non oap proposals it's just um once you add
10:15
osnap you just have the option of creating o snap proposals so it doesn't affect your your existing governance FL
10:21
any way uh on on a majority of your proposals and this is just uh quick
10:29
transfer I show I mean I I put in here it makes it really easy to do
10:34
transfers um it'll actually import all the tokens from your safe so for someone
10:40
to create a transfer they really just have to choose the token the amount and the address and then there's also this
10:47
option to import from safe transaction Builder if that's uh if that's like the
10:53
existing governance flow and then yeah once this is published
11:01
uh I know someone on the community call asked about what those transactions look like in The
11:06
Proposal um so you have this new transaction transactions container and
11:13
basically yeah that'll include all the specifics of the transaction that will
11:18
be executed uh if the proposal passes so it's really easy for people to visual
11:24
and especially since this proposal is really only pertaining to
11:29
grants and and these will only be simple transfers uh they are very easy to verify it's also worth mentioning we
11:37
have a verification program where three independent uh verifiers will come
11:43
through and just check that you know the transaction matches the intent of the proposal so for transfers they'll look
11:50
at is this um know is this a malicious contract or I mean does this is this the
11:56
actual token of the safe um it'll also make sure that the amounts are accurate and and match what is being asked for in
12:03
The Proposal um so that's I mean that's really the only changes uh in the flow
12:10
and then once this proposal ends um if you have if the proposal meets the
12:16
Quorum the voting period and the majority vote Yes um like Bobby mentioned in the call these will be we
12:24
have a bot that so the process is um a bond is posted for up two we for one to
12:30
three days uh a challenge period And so to not have to have the Dows actually do
12:37
this um we have a bot that will verify the criteria of the snapshot um proposal
12:42
here's an example in our in our Oracle UI but basically it has an in human
12:48
readable um plane text the Quorum the voting period uh the snapshot space
12:54
URL and this is the important one like the unique identifier of that proposal so it really makes it easy to automate
13:01
not only uh posting the bond for the proposals but also automatically disputing malicious
13:07
proposals and um we also pay for the execution costs once those proposals
13:13
have gone through that challenge period so it really automates the full um
13:19
governance flow um from uh yeah being able to do onchain execution and the
13:26
last thing I just want to mention is we have this really cool interesting them dashboard that shows all of our existing
13:31
Integrations thanks we have Brave New defi who will walk us through the tokenomics rospective
13:38
analysis Brave take it away all right good morning everyone I
13:44
wanted to provide a quick overview of the goals for the toomics revamp project talk about the results we saw during the
13:50
exit period and then provide some information about the long-term State parameters for the ram I'll talk about
13:56
the project goals on the next slide
14:01
so looking through these goals uh the first goal is to bring the price of wxm and nxm together again so that we could
14:08
remove the disparity between those two prices between the open market and nxm as priced through the protocol so after
14:15
the tokenomics upgrade was completed and the ram went live we saw the price of
14:21
wxm and nxm um converge upon each other once again or very close to it uh over
14:27
the one month Redemption period and as of yesterday evening the wxm and nxm
14:34
prices are within about 1% of each other at this time um so we have accomplished
14:40
this goal because they're still um liquidity flowing in and we have the target liquidity in the ram which I'll
14:45
talk about a little bit uh in more detail uh in further slides but there's
14:51
always going to be the ability to Arbitrage those prices if they get too far out of loop so um the ram is helping
14:57
to uh eliminate that disparity between the open market price and nxm so there's
15:03
not an opportunity to have a big discount on buying cover um or you know issues with mispricing risk the second
15:10
goal was just to allow members to exit which obviously we've been very successful um in accomplishing so this
15:16
goal has definitely been accomplished and we'll review this in more detail on the next slide um capturing Capital when
15:22
members wish to provide it uh this capability is there but I imagine we'll need to see more growth in sales before
15:28
we start seeing New Capital flow in but with this functionality we can work on growing the mutual over time as well and
15:35
the fourth goal is create positive value for long-term aligned members um this was definitely accomplished during the
15:40
exit period nxm holders earned a little more than 5.4 million in value from the
15:47
swaps in the ram so when members are redeeming their nxm for e in the ram um
15:56
the price at which they are willing to redeem nxm isn't always um extremely
16:03
close to book value we did see some people that were willing to get out at about 95% of Book value so any
16:09
differential between the Redemption price in Book value that value is
16:15
returned to members because the ram essentially automates a buyback process that allows people to exit um but if the
16:22
price that they're willing to exit at during that price Discovery period is less than Book value then that value is
16:28
creative for members who choose to hold nxm over the longer term so people that
16:34
were able to exit exited at the prices they were comfortable exiting at and this also led to valuable cruel for
16:41
members as the redemptions like I said are essentially BuyBacks overall the ram has been successful in three out of four
16:49
goals after being live for nearly two months uh over time I imagine that we'll hit goal number three as well but again
16:55
we'll need to see some more growth um but the performance today matches the simulations the R&D team ran ahead of
17:01
the tokenomics upgrade overall I think the process has been um very successful
17:06
and I've been really happy with the results myself but on the next slide I will go over the Redemption figures and
17:12
talk about that in a little bit more detail over the entire length of the exit period which was a little over a
17:18
month we saw the velocity of redemption slow as we progressed further into December until the transition from the
17:25
initial period to the long-term State parameters was complet which happened on the 25th of December so in the beginning
17:32
of the Redemption period um and the initial exit period members who redeemed were willing to exit around 95% of Book
17:40
value while those members who redeemed later in the initial period were willing to exit around 97 to 98% of Book value
17:47
uh the difference here is people in the beginning wanted to get at a certain price and the way the ratchet Works
17:53
within the ram is as people sell the price will move down and that ratchet speed will move that price back up so
18:01
more people were willing to exit at a slightly lower price and as more people waited and the uh demand to exit
18:07
lessened they were able to wait until Book value um or the ratchet moved up to
18:12
about 97 to 98% of Book value if you look at the Redemption figures and you
18:18
look at when people joined and how much they redeemed we can see that short-term Traders redeem most of the nxm during
18:24
this period however the largest number of redeemers were people who joined the mutual in 2020 during the height of tii
18:30
summer so the members who were trapped by the MCR lock were able to get out and
18:35
members interested in closing a short-term trade were able to exit as well all of this led to um you know that
18:42
price convergence between W nxm and nxm over time as well the few accounts that ran Arbitrage Bots helped Peg the open
18:49
market price back to the nxm price while providing people on the open market with an option to exit their positions as
18:55
well overall the community signals to provide 30% of the capital pool seem to be the right amount to meet the demand
19:00
to exit uh and in total we saw 266 members choose to redeem nxm for eth
19:05
either in total or in parts and to date we've seen 2.2 million nxm um redeemed
19:11
for a little over 45,500 e so you can see um you know a
19:20
little bit more information about that if you go directly to the ram contract but if anybody has any questions feel
19:25
free to take me on Discord about this um happy to provide any context but on
19:31
the next slide I'll talk about the long-term State parameters between the months of August
19:38
and October of 2023 the community discussed the various parameters on the Nexus Mutual governance forum for
19:44
tokenomics and sign support for the initial State and long-term State parameters which were subsequently
19:49
approved by members when nmip 209 was passed the ram was launched with the
19:54
initial State parameters that provided additional budget of
20:00
43835 eth of which a maximum of 1,500 eth was added to the ram pools every day
20:07
to allow members to redeem nxm for eth when members redeemed nxm for eth during the initial State the price of nxm
20:13
decreased but moved up toward the ratchet at a speed of 50% of Book value
20:18
on a daily basis the initial budget was completely redeemed as of the 25th of December and at that time the ram
20:24
transition from the initial State parameters to the long state uh long-term State parameters which you can
20:30
see on the screen and this changed the maximum amount of eth added to the ram pools every day from 1500 to 100 eth and
20:37
the ratchet speed from 50% of Book value to 4% of Book value every day so to be
20:43
clear that's the amount of new eth um the uh liquidity injection that's the
20:50
amount of new eth that's going into the pool but to be very clear the target liquidity for the ram remains at 5,000
20:57
eth which it was during the initial State too so if the amount of eth between the two rain pools drops below
21:03
5,000 eth then you can see um in the current state another 100 eth will be
21:10
injected over the course of a day to bring that back up to 5,000 eth if it drifts down it can move back up um but
21:18
overall that's how it works so for example if members redeemed say 200 eth worth of nxm in a given day and you went
21:26
down to 48 e between the two Ram pools another 100 eth would be injected into
21:32
the pool each day until the pools reach that Target liquidity of 5,000 eth once again so you can think of that as the
21:38
equilibrium um price you can also check that directly on the ram smart contract
21:43
if you'd like but there are plenty of Dune dashboards where you can see how much is being redeemed and see other
21:49
analytics there as well but as of this morning There is
21:54
49725 five eth in the ram reserves so not too far below the 5,000 eth Target
22:00
liquidity and over the next 24 hours we'll see more liquidity be injected until that balance goes back to that
22:05
5,000 e Target liquidity amount but based on these settings on these settings as members signaled during the
22:12
parameter discussion period the capital bll can be redeemed over a three-year period if members choose to redeem nxm
22:19
for eth at a maximum speed um I know this was a lot to go over so I just
22:24
wanted to stop and ask if there are any questions before I move on okay if not I will move on to do a
22:32
review of the q1 and Q2 2024 road map on the next
22:39
slide all right so every six months we share an updated road map that outlines the foundation and DOW team's high level
22:45
objectives and each team's priorities that help the mutual meet those objectives looking at our core
22:51
objectives here the core objectives largely remain the same as the previous six-month road map growth is still the
22:56
top priority for all teams and our Focus will be on growing cover sales in the next six months now that stage one of the tokenomics upgrade is complete we'll
23:04
be focused on growing and building our community so we can scale the Dow and work with more members looking to help us realize these high level objectives
23:11
while stage one of the tokenomics has been implemented the R&D and Engineering teams will need to conduct research to
23:17
finalize stage two of the tokenomics revamp which is focused on how the mutual manage capitalization levels when
23:23
the capital pool approaches the cover driven minimum Capital requirement limits
23:28
and Progressive decentral uh decentralization is the final high level objective as we grow our community
23:34
evaluate how more members can get active within the Dow and how we can update governance to allow more people and Specialists to get involved we can
23:41
continue down the path of decentralization now let's look at each team that will be supporting these
23:47
objectives and we'll start on the next slide with the engineering team and their priorities for the next six
23:53
months so to help us drive growth the engineering team will be updating the cover by UI to improve the user
23:58
experience in q1 as well as implementing the cover edits features so people can simply edit their existing cover nft to
24:05
renew or increase their coverage instead of needing to buy a whole new cover nft
24:11
so these features will help reduce friction and should contribute to higher renewal rates and cover buys over time
24:16
in addition the engineers are going to work to optimize the cover router and pursue gas optimizations throughout the
24:22
different functions within the protocol to help reduce gas costs for members when they are participating within the
24:27
Mutual the engineers are also going to launch a notification framework that will allow members to subscribe the
24:33
notifications or when they join his members to know when their kyc is complete to get updates when their cover
24:40
is close to expiring or when their staking pool deposit is close to expiring and and other things like that
24:46
you know when uh a governance proposal is coming up for vote that they want to get notifications about that
24:51
notification service will help people stay engaged and stay updated as well
24:56
the engineers are also going to work work on completing the technical work required to close the cover reinvestment and retrocession agreement and this will
25:03
significantly increase premiums flowing into the capital pool they'll also work to support the addition of new cover
25:08
products and work with the investment committee if new proposals to invest the capital pool float are
25:14
pursued the engineering team has a pretty full agenda for the next six months but over the last six months the
25:19
engineers were able to develop audit and Implement to economics in uh upgrade after members approved nmpi 209s or an
25:26
onchain vote that was the top priority over the last 6 months and I think everyone's very happy to see that
25:31
implemented they also improved the mutual security measures and we'll continue to do so over the next six months I'll move on to the next slide
25:38
and talk about the BD team's priorities for the next six months so the BT team will work with
25:45
staking pool managers to develop and launch new cover products there are currently cover products in development
25:50
that would allow the mutual expand in the new market segments and grow cover sales and premiums this also includes
25:56
working with the engineering team to to develop an MVP for new eth slashin
26:01
covered products to further expand into that market segment the bidy team will also be conducting Research into
26:07
traditional risk markets to evaluate other deal structures similar to the cover R deal so the mutual can use
26:12
onchain Capital to underwrite offchain risks and grow cover sales and premiums
26:18
and of course the BD team will continue to work in support existing St pool managers within the Nexus Mutual ecosystem to help managers scale and
26:25
still more cover through work with managers like Sherlock Uno and E and Distributors such as open cover the
26:31
mutual can create more open capacity and reach new users on l2s where gas costs are accessible for more retail users in
26:39
the last six months the BD team secured the cover Ral closed the retail Mutual deal on onboarded new staking pool
26:45
managers and scaled existing Partnerships with teams like liquid Collective we've seen protocol cover
26:50
sales decline in 2023 due to low yields but as we see yields picking back up um
26:56
we're seeing more INB found in a greater focus on new listings to keep an eye out for new protocol cover listings and our
27:02
listing spotlights on Twitter moving to the next slide I'll talk a bit about the foundation legal
27:09
team so the legal team has been working to finalize arrangements with members who have received claim payments from
27:16
the mutual and also received reimbursement through either bankruptcy proceedings or direct reimbursement per
27:21
their mandate in nmpi 205 this includes pursuing reimbursements to the capital
27:27
pool for FDX block by Gemini hold not Oiler and any other applicable claims so
27:34
reimbursement is being pursued to ensure cover holders can't earn a profit at the expense of nxm stakers as developments
27:41
are made on reimbursement will share updates but so far the legal team has done some incredible work on this end
27:46
legal also plays a major role in the cover re deal and other deals like it as well as in the development process for
27:52
new cover products over the last six months the legal team has pursued reimbursement established legal infrastructure for the foundation and
27:59
evaluated and helped update cover wording documents to provide members with greater Clarity on what protections
28:04
are included in addition to other initiatives on the next slide I'll go over the product and risk team
28:12
priorities um just as an FYI the product and risk team is jointly managed by myself and Hugh um and we're supported
28:18
by the legal team our work over the next six months will be in a support capacity when it comes to the cover Redal new
28:24
cover product development and new listings also support the account abstraction research project which will
28:31
involve the engineering and BD teams to evaluate how the mutual can use account abstraction in the future to improve the
28:37
user experience in the Nexus Mutual UI I'll also be working on a membership benefits program project to evaluate
28:45
supplementary Services which we can offer our members to improve the benefits of membership and support
28:50
growth in new members in the last six months we've created the claims history database worked with legal to create
28:56
cover wording templates and guidelines and expanded to managing list the listing process for new protocol cover
29:03
listings there's been a significant amount of support provided to the new cover product development process and
29:10
we've provided support to other teams as needed as well moving on to talk about the R&D
29:17
team um of course the major accomplishment for R&D in the last six months has been the management communication and the execution of the
29:23
tokenomics upgrade project but over the next six months the R&D team will continue to work with the engineering
29:28
team on stage two of the tokenomics project R&D is also going to create an improved process for refreshing the
29:35
cover based MCR calculation parameter on a regular basis um which will
29:41
include uh accounting for the various risks to Mutual is now underwriting to ensure there's always enough Capital to
29:47
pay all claims I'll also work to support the investment committee as well as maintain the existing Dune dashboards
29:53
that created um in the last six months and in 2023 and last six months the R&D
29:58
team has created the nxm staking Dune dashboard and the ratcheting amm Dune
30:04
dashboard which has been hugely popular in the last several months on the next slide I'll talk about
30:10
the community team priorities in the next six months our core goal is going to be to grow our
30:16
community increase engagement and re-engage members who maybe haven't been as involved as they were in the past and
30:22
improve awareness about the mutual through our social channels we'll be updating the Dow it to include the
30:28
governance Hub which will be a One-Stop shop for everything you need to know to stay involved and get involved in the
30:34
current governance proposals and votes the staking pool managers Hub which will be a central repository for new and
30:40
existing pool managers track new listings staking analytics and for guides on how to launch and effectively
30:46
manage the pool will include on the Dow website information on the Dow teams where we are and executing on our
30:53
priorities um resources about staying safe in Defi and more more we really want to expand the Dow website to be a
30:59
place where members can go um and find all the resources they need to stay involved and to learn more about
31:05
becoming active within the Dow we're also going to launch an interview series on Discord and Twitter spaces talk with
31:10
defi Builders about risks in defi what Primitives we need to see the powered mainstream adoption and how people are
31:16
building on top of the Nexus Mutual protocol and an effort to create greater awareness and build our community I'll
31:22
also be working to get the V2 contracts included on all the major portfolio aggreg such as zerion debank zapper and
31:29
others um this will help us improve our discoverability and will just be a nice perk for members who like to review all
31:36
of their portfolio Holdings um in one place I'm a big fan of xerion myself the
31:43
last six months have been quite busy as the community team played a pretty important role in educating uh people
31:48
about the tokenomics revamp project and facilitating discussions on the Forum about this as well we've also overhauled
31:54
our Discord server in the last six months to make it easier to find information and stay engaged and we've worked to improve communication between
32:00
the wider community and staking pool managers this of course is an ongoing process but we've seen more capacity
32:06
requests and subsequent cover buys when we've connected requests for cover with managers who are able to open up
32:12
capacity overall it's been an incredibly eventful six months for all of the foundation and DOW teams but we're
32:18
looking at another busy six months I'm looking forward to Growing cover sales and building our community in q1 and
32:26
Q2 so I'll move on and talk about the Dow team's budget proposal
32:32
RFC this leads uh to the discussion about the current RFC that's on the governance Forum I know we've just
32:39
reviewed the priorities for the next six months in the roadmap section so I'll touch on the performance reviews for
32:44
each team and take questions if anybody has them so on the community team side again we're focused on driving
32:50
engagement and growing our community Through the priorities listed here you can see more detail on the Forum as well
32:56
and the last months we've seen an increase in engagement on the Forum while engagement on Discord has remained consistent engagement on the Forum has
33:03
seen a major boost throughout 20123 with some of the highest page view counts in our history we've overhauled Discord and
33:10
add of the bot that allows members to query kpis and see active cover open capacity information and more we've also
33:16
upd updated the documentation and updated the token model section and any sections that discuss the token model or
33:23
the MCR in the next six months semai will build on the Foundation we created in Q3 and Q4 2023 to grow Community now
33:31
that the token model has been updated and members can fre the mint and redeem nxm
33:37
again talking about the R&D team priorities they're going to be focused
33:42
on stage two of the tokenomics upgrade project as I highlighted um and they're going to be revamping the MCR they will
33:49
also support the investment committee over the next six months to invest more of the capital pool float and manage exposure to investment assets held in
33:55
the capital pool um Q3 and Q4 were largely focused on and
34:00
dedicated to the stage one of the tokenomics upgrade looking at the investment
34:06
committee priorities um they will continue to evaluate investment opportunities for E staking they'll
34:11
provide recommendations and managing exposure to the Investments that are held in the capital pool and continue to
34:17
maintain the investment philosophy the investment Community will also review and evaluate more Dow treasury
34:23
management proposals and discussions now that the tokenomics upgrade is complete and in the last six months the IC helped
34:30
support investment of an additional 21,24 eth into staking Investments
34:35
across rocket pool and Kiln um from those Investments we are earning more eth for members every day and that's
34:41
accre to the capital pool looking at the RFC budget breakdown and timelines um again this is just an
34:49
overview of the proposals I encourage everyone to review and share their thoughts on the Forum before the request
34:54
for comment transitions to a formal next Mutual Dow proposal the Dow teams are
34:59
proposing a request for $153,500 for the next 6 months the investment Community will be funded from
35:06
their carried over Surplus and the team's discretionary budget will also be carried over from the last six months
35:11
the marketing team will request no new funding as we work to recruit another marketing lead for the Dow in light of
35:16
our last marketing lead moving on in the fall the previous funding for marketing is earmarked and held in the Dow teams
35:23
multi- sake as outlined in the RFC um kayy head of operations is still on maternity leave so no new funding will
35:29
be requested for her role until she returns the RFC will move to an nmdp on
35:36
the 22nd of January and it will move to an onchain vote if there are no major comments or concerns um and that will
35:43
move to an onchain vote on the 30th of January and that snapshot vote will close on the 5th of January I'm happy to
35:49
take any questions at this time if anybody has them
35:55
okay uh if there are no questions um just I would encourage you to review the proposal and share your thoughts on the
36:01
Forum but at this point I'm sure you're all sick of hearing me talk so I will pass things over to Hugh to share his
36:07
first Foundation update of 2024 thanks Brave um hey everyone um
36:13
good to be back um after a break over over Christmas and New Year so um yeah
36:18
and thanks pray for that really comprehensive update kind of gives you an overview of what everyone's up to um and what we've been doing recently um
36:25
I'm not going to say too much new but I'm just to give you a bit of flavor on the the specifics we're working on at
36:30
the at the moment um so cover R deal tends to be the um the major one that a lot of the foundation teams focused on
36:37
at the moment um two main streams uh legal making sure we do the proper due diligence review all the legal
36:43
documentation um that we have to enter into um and that all seems to be going
36:48
fine um but a little bit delayed where we would have liked to be but um but we're working with covery on that um and
36:56
the the other side is the the technical implementation um and so there'll have to be a bit of a smart contract upgrade
37:02
to to actually execute the um the um investment so that that's um all all
37:10
going fine should be hitting order next week it's a pretty relatively simple um change but um nonetheless a change that
37:16
we have to have to make so um that's all that's all going it's all going fine
37:21
we'll let you know if there are any obviously um issues that pop up or um when we know a bit more when when it's
37:28
actually going to execute um the other thing is uh there's definitely the UI been review um coming
37:37
out there's going to be a big update on the on the UI I'm still working through quite a bunch on that um got Sid trct
37:42
with to economics some late last year Etc but um but it's it's progressing really well and some of the stuff looks really good um so we're going to be
37:50
doing some internal testing as a foundation team over the over the coming weeks and we'll be able to share more
37:55
after that um claims recoveries on FTX in
38:01
particular um that that seems to be progressing quite well um you know
38:06
there's a lot of legal documentation and all that type of stuff that has to go by and so things do take time but um but we
38:11
are expecting to get um some meaningful funds back um we've already got um about
38:16
260 or 70,000 back from a variety of things mainly FTX but I'm on block five
38:23
um claim um and so we are making the the mutual is making um some recoveries of
38:28
of these claims so um that's that's good to see the I guess um the other thing to
38:34
note is we're working with um with open cover quite deeply on some on some new products and stuff so hopefully we got
38:41
to share more um in the near future but um there's some good there's some good work coming coming out of that and and I
38:47
think more generally just as a wider comment um obviously news of ETF and
38:52
that type of thing is um quite positive for the um crypto ecosystem in general but um you starting we're starting to
38:59
see yields come back in several places um and so that's kind of a core kind of
39:05
requirement for um a kind of main product the protocol cover to do well um
39:11
because you kind of need that that yield um before people are willing to give up some of that yield to get additional um
39:17
safety or security so um that's that's that's a good sign and we are seeing
39:22
more inbound and and more cover buys coming through so um the trend seem to be good and excited for um for 2024 and
39:29
what the what the rest holds but I I think um hopefully we're on a um a positive uptrend now with the with the
39:35
wider ecosystem and obviously where um Nexus is kind of a big part of that and hopefully will um will help out the next
39:42
wave of people to um safely interact with the crypto ecosystem so yeah lots
39:47
of lots of things going on um but in general I think I'm feeling quite positive about 2024 and um and hopefully
39:54
that um continues over the the next coming months and we can um deliver on some new products and and get the the
40:00
cover volumes up that's going to be our main focus growth growth on cover volumes so yeah and happy to take any
40:05
questions um if you have them thanks you and BR for the updates if there are no
40:11
questions to you let us continue with the weekly analysis like Hugh and brave pointed out
40:18
as yields are slowly returning we can see U quite High cover sales in the past four weeks um this week we have sold
40:26
more than $2 million in cover and the members earned more than $10,000 in
40:32
fees our active cover amount is almost $33 million and it has been on a roll for
40:40
the past 4 weeks as we see as we saw constant
40:45
growth looking at the cover sales um like you pointed out we can see some
40:50
figures that are generating more yields than before and we have also seen the
40:57
retail Mutual renew their cover sales just before uh the New Year's Eve so um
41:03
it has been all positive if you want to learn more look more in depth please review the weekly analysis on the Forum
41:11
and ask any questions if you have them for now let us continue with brave who
41:17
will walk us through the new cover listing so next is M UI right Sam um
41:23
yeah I just want to highlight to on the Forum every week s posts these great Recaps of cover sales you can see all
41:30
the cover sales for over the break um as well as the recent week there so I encourage you to check those out we also
41:36
tweet those out from the Nexus Mutual da account every Tuesday um I wanted to
41:41
talk about some of the new listings that you'll see in the Nexus Mutual UI in just the last week we've added some more
41:48
listings uh if we move on to the next slide we've added compound V3 D hedge
41:53
igen layer GMX V2 drone V2 and urine V3 in the UI uh you'll notice the pricing
42:00
for these protocols um may be a bit higher but that'll continue to decrease to the minimum price over the course of
42:06
this week and open cover will work to list many of these protocols so members can buy cover on l2s to reduce gas costs
42:14
as well I think specifically for compound V3 D hedge GMX V2 F drone V2
42:21
and urine V3 all of which uh have itbl L's and L2 and I know many users are
42:28
active um on l2s and other networks with a little bit more accessible
42:33
gas costs um but look out for our protocol cover spotlights on Twitter and
42:39
we ask you to amplify those tweets spread awareness about protecting crypto Assets in defi through new listings
42:45
we're looking to expand protocol cover sales as yelds are Rising once again um if there are any listings that you would
42:51
like to see in the Nexus Mutual UI just go ahead and tag me uh in Discord um in
42:57
the purchasing cover or members Lounge channels I'm happy to do a review of any
43:03
listings if there's a particular kind of cover that somebody wants to buy um we're going to be listing some more
43:09
protocol cover products here in the next week um once those are up and updated I'll share an update on that as well um
43:17
but yeah if there are any questions about the new listings I'm happy to take them otherwise I can hand things back
43:22
over to sim to go through the open forum and CL it the call thanks again Brave here's the
43:30
opportunity for um members to ask any open questions or raise any issues that
43:35
we haven't touched upon during this call and if there are no questions or
43:41
issues raised I want to thank everybody for joining us our next call will be on the 30th of January thanks again to UMO
43:49
team and Bobby for joining us at this call we really appreciate it have a great week and talk to you soon
43:56
bye bye everyone thanks everyone bye bye
44:06
everyone