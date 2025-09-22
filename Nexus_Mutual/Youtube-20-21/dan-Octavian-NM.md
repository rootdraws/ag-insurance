Transcript


Search in video
Introduction
0:00
very much for waiting um yeah so here is the red direction that you can look uh we're gonna
0:06
post those videos to youtube channels um so you can access them later on so
0:11
yeah go ahead stand from next mutual [Applause]
0:18
uh yeah my name is dan uh i'm a core developer at nexus mutual uh nexus mutual is a
0:25
company that uh sure yeah nexus mutual is a company that uh
0:31
provides um cover against smart contract failures
0:37
and custodial uh custodian custodial hacks um as well so it's a decentralized
0:42
finance application so the main market is smart contracts um
0:47
currently on ethereum and it's going to expand other blockchains soon and luigi custodians like
0:54
finance or uh block flying things like that so uh i've been working with the team on
1:02
releasing a bunch of things for uh integrating with nexus mutual just for
1:07
for things like uh uh monetizing so how can you monetize
1:12
by integrating the nexus mutual um by reselling covers also we just launched a community fund uh
1:20
which enables people to develop stuff that helps mutual and get funded for that and um we're also
1:27
going to talk a little bit about the system architecture and just the overall insurance product offerings
1:32
so you guys get an idea of what the application is actually doing and then we're going to look at how like you guys can help or you know
1:41
use use the application so what nexus mutual does like you said it
1:47
uh provides smart contracting custodial cover against these failures that result
1:53
in lost funds uh like why do we even need this in the first place so we
1:59
all know that like d5 is riddled with perils because
2:05
we always have things like smart contracts that get hacked and there's massive cost funds so in the end what
2:10
you want is you want to be able to take the risk but you also want a safety net uh to follow up on right so um so far
2:19
at this point there's around like at least when i wrote this it was around 667 million
2:25
dollars worth of active cover amounts so like all the covers are currently active on the platform they sum up
2:32
that in dollars um around 356 covers sold the biggest payout so far
2:40
was the urine hack in february uh totaling around uh 1 361 eve and some died there
2:49
how much it was um and you can see like these full stats about how the
2:54
platform is performing on nexus tracker dot io that's built by richard chan so it's one of the
2:59
investors the nexus ratios you build this site and you can track all these stats over there um
3:06
and uh yeah we can dive a little bit into like what the system is structured
3:12
like um and what it does so we kind of have like these high-level
3:18
modules um to solve what we need so
3:23
uh we have of course of course the cover module for for people to buy the bike covers uh you
3:29
have a claims module because the the covers that are being uh that being purchased in case there's an
3:35
incident uh they will be voted on to decide whether that's a legitimate cover or not um
3:42
because currently it also needs to be accompanied by a proof of loss where you sign within with your address that was
3:48
affected by the hack and say okay like you you can check on change that i lost all these funds so
3:54
the claims module is gonna take care of care of that that voting process uh this token module which is the nexus
4:01
mutual token so we're going to see how that plays into like uh voting for claims governance earning
4:07
dividends uh and all those things and the capital module holds all the funds
4:14
and handles things like investing the the pool we also have uh the staking modules so
4:21
stakers need to stake an exam to back up the
4:26
back up the capacity that we're releasing and saying okay we can we can insure up to this this amount on this particular smart
4:33
contractor system right so and the governance um so yeah uh generally the covers the way
Governance
4:41
they're structured right now so they're pretty simple so you just say that okay uh
4:46
i'm covering this particular smart contract system which is currently identified by a smart contract
4:52
address this is turning into an identifier it's currently kind of like uh it started out as a contract address
4:59
but currently we have like custodians like binance or whatever so there we just like generate some artificial id
5:05
um the cover asset so currently that's eat or die that's all that's supported to
5:10
say that okay my cover is and eat i'm going to get paid out and eat if something happens or i'm going to get paid out and die but
5:16
there's there's more to come um the summer sure just like where you're going to get paid out if
5:22
the the cover is considered valid and a period which currently is between 30 and 365 days
5:28
uh so this is immutable at the moment so if you buy it and that's it if you want more you need to buy another one so there's no way to
5:35
extend it currently but it's something that we're working on um yeah so for uh
5:42
so the the money you're paying for this is dictated by
5:47
how much is uh staked on that particular insured contract it goes down to two point six percent uh
5:53
so like before the whole year you buy for like ten thousand dollars you're going to pay uh 260
6:01
60 dollars worth of premium um yeah that's like the floor
6:08
um it's more expensive if not many people stay um so yeah so you can also do
6:14
programmatic integration we're releasing like this gateway contract so it's easier so you don't need to poke around the system too
6:20
much you have all the functionality there the the gotcha is that nexus mutual still has kyc
6:26
unfortunately um basically because of the way it's structured there's a company in the
6:31
uk that packs this whole thing off it's not fully decentralized and we're gonna see which parts are not
6:37
so this is still a hurdle but there's ways for you to buy without kyc so we're gonna we're gonna take a look at
6:43
that as well um yeah so then like
6:48
touch briefly on the claims modules so
6:53
claim assistance are just nexus mutual members you block the nexus mutual token to vote on these claims
6:59
you'll get some small rewards for it uh basically these claim assessors have to vote with
7:06
a total state and exam for that particular vote larger five times
7:12
it's weirdly written but it needs to be big at least five times bigger than the
7:17
cover map voted on right um at the current uh point price for uh
7:23
for nxm and uh voting is closed right away if it's more than ten percent somebody
7:28
votes and it's like okay it's 10 otherwise it waits for a minimum uh voting time
7:33
for a for a minimum voting time um you need a 70 consensus
7:41
uh to decide whether okay this is uh either yes or no and there's no
7:47
consensus uh you're gonna go to a full member vote so all the members gotta vote and then you just need
7:52
fifty percent uh that's not a high level there's some there's some details around this uh like
7:58
for example if the uh if the members vote with less than five percent the five five times the sum of
8:05
shirt then it's just gonna take the decision of the famous sisters even though it was so so it's a little bit more detailed than this but
8:11
at a high level this is how the voting works so it's people vote currently on
8:17
each of these claims uh that that gets submitted so that's not super scalable right now so that's
8:23
that's one of the things we're going to talk a little bit more about um yeah we said that we have a capital
Capital Pool
8:30
pool so it also works as an investment module currently 162k eat in the pool some die
8:38
you you buy the unexcept token against this this pool so you give it eat and mint and exam and
8:45
um you give it an extent it burns it and gives you eat back uh this is calculate the price it is
8:52
it's calculated on a bonding curve we're gonna take a look at that like why did that's built in that particular way
8:57
uh also the investment module like also does these swaps on the union swap to say okay we have like uh to make sure that we
9:04
have for example enough dye to pay off all the dive times the the claims for the underlying is the
9:10
diet token and so on so forth and we're going to have things like investments so we're going to send
9:16
someone to eat sde so we can run on that east 2.0 uh staking
9:21
so that's coming soon uh also updates this concept that we have a
9:26
minimum capital requirement um
9:34
10 minutes okay good thing are you kidding me [Music] i thought it's dirty just okay
9:42
ah all right i might go through this a little bit faster um yeah so i might skip so far
9:48
so 10 minutes left all right all right so yeah the pool has this concept of a
9:53
minimal capital requirement it says that okay we need this much money at the very least to ensure everything we've got on the
9:59
table right now in terms of covers uh and the the gotcha is that if it
10:04
reaches mcr you can't sell your nxm so um but there's a wrapped version of
10:10
nxtm that's just trading publicly and people trade that it trades under so the mcr is currently started
10:16
100 when people started um you know it started climbing up the price
10:21
uh but it's probably gonna repack at some point if things go well and people keep buying covers so we'll see
10:27
how that turns out um i might just skip this because it's like kind of complicated and it's
Bonding Curve
10:33
um yeah it's um it's gonna be a mouthful to go through all of this if i have one in 10 minutes basically
10:41
the bonding curve is just at a high level it's just there so that um getting incentivized
10:48
it tries to keep a balance where like the the pool is not overly uh overly capitalized it has the right
10:55
amount of capital so the price climbs very quickly if there's uh there's a lot eat in the
11:01
pool and because it's the power four and people gonna sell it so it's not like
11:07
too much capital more than whatever we need um and of course we have this minimum cap requirement environment which just grows
11:14
slowly based on formula as well that's dependent on the total sum of shirts so this kind of reflects like the
11:20
overall growth of the platform as these things because it's like a four uh it's gonna it's gonna reflect uh the
11:26
demand because it's saying okay there's more active cover just start starting to start rising it
11:32
a little bit over time um yeah i think i'm going to skip over this
Staking
11:37
uh staking if you stay with leverage uh on all these contracts to say you're backing the contracts but then you're
11:43
also taking a bunch of risks if something gets hacked you're going to get burned uh
11:49
so you're going to get burned on your nxm otherwise you earn dividends because you're just 50 of the value of
11:55
every cover purchase on that let's see you stick on hobby curve and one inch and seven other
12:01
things with leverage on 100 xm or how much you have and you're going to earn 50 of those
12:09
fifty percent of the premiums just gonna be split amongst all the stakers uh sits on ave so you gotta get
12:15
proportional to your stake uh yeah you also have shield mining so
12:20
it's so like it's people throw tokens like saying like okay like uh you know per protocol did it so they
12:28
just said okay here's purp tokens take my perp you know boost capacity people get these
12:33
juicier rewards alongside the normal 50 percent um
Templating
12:39
i might just skip this because it's like system in terms of people have any questions so far
12:44
or or then sure yes so how does the templating work like
12:50
what is the incentive for everyone to like approve the claim or why would someone say oh actually that never happened
12:57
yeah so you get you get some rewards in an exam when you vote so that's the
13:03
monetary incentive and the the the members vote because
13:09
um well they want to vote legitimately because i guess it just it's basically the reputation the
13:15
platform to just pay uh to pay out times that are legit and
13:21
reject everything that doesn't make sense because that's just going to keep my young pulse for the people that are like
13:28
uh different from the numbers yeah they don't have to be the same person you could do both
13:36
um so when you approve a goal for something
13:44
can you do like partially like i would in my mind there could be scenario that
13:49
okay now this uh this hack happened but it's not as
13:54
severe right and so i may want to pay out but i may want to pay out partially yeah yeah you're right yeah that's
14:00
that's what we want to do in the long run it's just not implemented yet so it's like it's really good for cover buyers right now
14:06
there's no partial claims um so you're gonna get the whole thing um see if
14:13
you get hacked so it's actually it favors the cover buyers a lot but uh for for the interest of the
14:18
mutual that has to be added yeah you're right is there is there a programmatic
14:23
way of detecting that because if for example if the balance of the contract just falls below a certain
Programmatic detection
14:31
number there is no need to vote because it's obvious that the funds were with john for example you
14:37
mean like a general way of assessing that a hack happened yeah yeah like an automatic automated
14:43
way of doing that i think it's non-trivial because that could happen for multiple reasons
14:49
uh at least the way these systems are right now they're really complicated um to a point in which you still need
14:56
human inputs to evaluate a bunch of stuff if the judgment is like this hack half
15:01
or not so as far as i know there's no easy way to generalize across all these things right now so generally it's a human
15:07
assessment in some situations people are just like
15:12
there's a lot of situations quite ambiguous uh over what happens was debated over a few days on the discord
15:19
i made sure people like okay it was or it wasn't and also analyzes the cover wording so
15:24
it's like this document that says okay this is covered this is not covered blah blah blah and like that's like
15:29
you know human language so it's not it's not yeah it's not easy to automate um
15:38
yeah once you've got a question yeah go ahead um can i ensure next meter
Smart contract
15:44
itself like this is some smart contract okay this is insurance for
15:53
[Music]
16:03
[Music] but you can't use it to ensure itself okay
16:08
well yeah it's true it's a smart contract so it's true um any other
16:18
competition protocol any other question for you okay all right
16:26
um yeah do you want to give us something yeah yeah i'll try to get to this so like uh ways
16:32
you guys can integrate and make some planning maybe um so basically
16:39
we've been building this thing where like you can so we said we have kyc but we're using this distributor
16:45
contract to say that okay like you just registered this as a member mutual and
16:51
people can just buy covers from this as a proxy um this is the only thing
16:57
that the mutual knows about but everybody everybody else who buys this is not kyc like we don't care um
17:06
and this is uh we have like a template for this uh out of the box audited smart contract
17:12
uh it's almost done um and you can basically deploy it and
17:18
resell nexus mutual coverage you can add a little bit of a cut on top um
17:25
yeah so if you want to do something like this uh and basically if you could drive sales
17:31
the platform that's good for nexus and you can earn something on top so if you do want to do something like this please get in touch
17:37
um yeah so we're going to sit you up on telegram we can talk about it um and this is
17:44
already been used by so andre uh yearn yarn the creator uh
17:49
he he he used this first i don't remember sometime last year i was like but it was still like a
17:55
template back then so he sold a bunch of covers to something called ynft which is deprecated now because there was a
18:00
bug in it uh so it was kind of like everything was supported to the armor phi which are you use the same
18:07
power pattern and rnft so these covers are like the way this thing implements it is just
18:12
sells these covers as nfts so you can also just send it around trade
18:17
it with other people put it on wratable so it's pretty pretty uh
18:23
pretty easy to exchange it um because it's not tight to your body
18:29
so it's a lot more freedom than the normal next mutual cover where it's like it's tight here to your
18:41
of other stuff like address sticking on nexus a bunch of stuff it's pretty interesting you guys should check it out but
18:47
definitely if you want to build something like this you can just use or you can just use this out of the box um and just put it on your website
18:54
deploy it and it's just going to work with a little bit of configuration if you don't want to do something more complicated
18:59
you just fork it or um yeah you can even build so there's another company doing delegated staking
19:04
as well so they just stay for for other people so people are not like concerned like oh i
19:09
stick here here you know on steak like you know they have all that stuff us and just saying oh we're gonna give
19:16
you this amount of yield over here for over one year uh so
19:22
yeah there's some details here about how it's built so some parts of the system are still decentralized it's like this pricing
19:28
engine it's still centralized so it gives a sign code and says this is how much your cover costs
19:34
we're working on moving this on chain it's probably gonna happen sometime this year but it's still a caveat when you're
19:40
using this um yeah
Community fund
19:45
so i also got the nexus mutual community slide so um so and i
19:52
popped in 250 000 nxm which is minted for this it's in the next mutual community fund
19:59
so uh if you have a project that improves the nexus mutual you just come off the idea
20:07
you fill in the form describe the impact the budget you need
20:12
it could be awareness education uh distribution or sales so this could
20:17
be sales related it doesn't need to be technical necessarily it could be just a technical product as well so it could be like
20:24
you know that nexus tracker application i mentioned somebody else built it if you could build something like that or any other
20:30
feature on top and you just need the and the funding uh that can be arranged if it makes sense
20:36
so yeah there's more details you can read up on a medium medium post um uh
20:42
so yeah like we're really looking forward to to see how people use this um
20:52
and uh yeah i mean you can use like other ways you can what you can do now is you're just you're developing a d5 profile you just
20:59
buy cover for you you use response for the protocol itself you buy the
21:05
foundation foundation address i mean the user is just going to gain higher
21:12
degree of confidence than their funds are protecting just in case some hack happens so you just do it for your protocol as well if you're building your
21:18
own protocol uh don't necessarily or if you just put a link and say
21:23
okay you know if you want to buy insurance go ahead and do this but this may be more convenient because the users don't need like okay i'm using
21:30
your protocol then to go buy insurance maybe i need to kyc so that's like a complicated flow so this could be an easy way out
21:35
and maybe it's got to grant you more street credibility if you also have this kind of insurance on your protocol
21:44
and it's the future features coming up uh it might be pretty interesting uh dpeg d-peg defense so
21:52
if you have a token like adai or some young bearing token and it gets deep right or something
21:59
something bad happens uh where the value is also like let's say 89 falls to 50 cent of the dollar
22:06
um you can cover yourself against this deep egg and you're just gonna the claim is gonna turn into like
22:11
exercising a put option to redeem the underlying so you're going to get dye or usbc in exchange for the broken
22:17
like depict a diet let's say um the mcr calculation is currently
22:23
obtained so that's moving on chain uh in a pricing engine as well coming soon uh we're planning to overhaul the
22:30
staking uh because the rewards right now are uh they're not they're not streaming in the best way to the
22:37
stakers and they're not not as motivated to stake only uh 16 of nxm holders currently
22:43
staking so we want to we want to boost that up and also reduce gas costs um
Defect Protection
22:50
and yeah i'll go a little bit more into this defect protection so yeah um
22:57
the cool thing is that we're not going to have like this individual claim voting anymore we're just going to vote on an incident like a deep
23:03
incident so the the the rest of the claims are going to be instantaneous you're not gonna wait for the voting you're just gonna be like okay here's my
23:09
adai you know get you get the underlying doubts uh because it's you know and you're only
23:15
gonna do that if the dpig is still on like i guess nobody is gonna bother doing it if if the token got repaid so uh this is
23:23
gonna be more scalable than what we have now um and yeah the reason why this could be
23:30
a better fit and i guess it depends how you use your funds we're not super sure how people are gonna prefer this
23:35
to the normal cover the idea here being that like look we don't care which system got happy
23:40
behind the scenes like yeah maybe just versus just buying the insurance on ave
23:45
directly you just buy the insurance against the dpeg so whatever happens you know in terms of the hack
23:51
like whichever system caused it we don't really care just we're going to pay for the deep end the advantage that it's instantaneous as
23:58
well uh so yeah i guess that's the advantage behind this product and we'll see
24:03
we're gonna see how which one which one people prefer more um and yeah that's that's all i got and
Shield Mining
24:10
honestly i was thinking that just uh take some input from you guys yeah so i've got a question for you in
24:16
the uh
24:26
yeah there's a guy on my team called ricky and i can put you in contact with him
24:33
there's usually some evaluation on the project and people most of times do this
24:41
shield mining thing where they also juice up the rewards on the staking side and say that okay my platform
24:48
is this my protocol token is this i'm gonna put these shield mining rewards up for
24:53
a few months they're how long they're gonna last and uh you incentivize people to stake on
24:59
your protocol usually capacity goes up quite quickly because of that so a lot of people can buy it so those those are
25:06
usually the steps you can get in the team and most likely do the shield mining rewards
25:13
in your arm
25:20
um how uh do you think there's like a good like how efficient do you think the market is between the people that want
25:27
to buy the numbers and people want to sell them to like define the demand for
25:32
certain colors is matched by people supplying the other side
25:38
i guess there's some um so you mean on particular protocols or
25:44
yeah comparison between protocols yeah like is it you know that do the buyers find
25:51
is a good price or like the seller's mind is um you know they want a higher price and the buyers
25:56
want to pay or is like is that a good match or anything that could make it better
26:02
uh as far as i can tell the problem so far is uh so the cover price is pretty low premium
26:07
on most of these projects two point six percent if it's the four uh so i think that's a
26:13
it's a good price for the buyers uh and it's still like we don't have the cover like the partial
26:20
partial stuff yet so it's even more advantageous and if there's a hack on finance or something you bought cover on
26:26
finance there's basically no way to 100 check how much money you have so let's say you're
26:31
probably going to get paid in full anyway um and all these things are kind of favoring the buyer
26:38
i think the problem so far has been the stakers side they're not they don't feel like they're as incentivized
26:43
um so i think the the the the side of the market needs to be
26:51
uh more incentivized to to participate as a sticker so
26:56
it could be that the real price of these covers should be a little bit higher actually but there's other issues with
27:02
how the rewards are streamed so um currently like if anybody buys
27:07
anybody bought cover before you you staked you're not going to get the rewards from that which is not really fair uh it's
27:14
just something about what the system was currently built so that the staking needs to be improved there so
27:20
also if we look at the stats um yeah like the only only 60 percent of an example is
27:26
currently staking which is you know that should be higher ideally so i it could be that the real price of
27:32
these covers actually is actually higher um but it's it's good in a sense because it's like okay
27:38
i guess next is going to get more uh more tension like it's kind of a no-brainer at this price
27:44
like buy it for a lot of these systems so it could be that this hopefully this drives sales up
27:50
in the short term
28:00
it's a formula that's the same for all so there's uh it's based on the capacity
28:09
of that project which is calculated depends on based on how much people state on that project and then there's some
Heuristics
28:15
like heuristic factors applied so the code is open source you check everything's transparent but there's some heuristic factors where
28:21
like we said oh this protocol is older it's more trusted it gets like a 2x boost
28:27
artificial boosters capacity so there's things like that like heuristic put in to say that okay this one's new
28:33
like just leave it as this and then something that's like uni swap okay gets a 2x boost um so it's kind of crude
28:42
it's still because we kept changing it um and but at some point we're going to
28:47
have to like nail something down to say that okay we're going to build this on chain and this should be it
28:52
that's how it is currently so we don't do like a team assessment like a very deep team assessment of like
28:57
uh how secure that is yeah
29:03
it's a good question who are some of your competitors in this space
29:08
um as far as i know the people that do the exact same thing um cover protocol was a protocol
29:17
uh i think there's still a protocol but they're they yeah i i don't i seem like they
29:23
don't have a lot of traction currently like in the urine hack they didn't really pay out anything um
29:30
other than that there might be stuff on other blockchains like we saw these guys they've like cloned the entire ui of the nexus
29:38
there's some binance dudes they just clone the entire app like from start to finish and change the color schemes um
29:45
it's something yeah and some other guys like cloned and modified it like they were better on like graphics and
29:50
stuff so they did a better job there but as far as i know now like tml1 just at the moment there's nobody that's
29:57
really tackling the problem the same problem and in a significant way that they stood out um yeah
30:10
yeah so the protocol is deployed on l1 atm um and we're gonna
30:17
change the cover wording because that's all we need to do at the moment to say that look if one inch is also deployed on
30:23
binance we're covering that too um so we're gonna extend the cover warning to say like
30:29
okay like if there's a hack on you know if one inch deploys both on l1
30:34
and finance as well like we're gonna cover both uh so that's soon to come like pretty
30:39
soon like probably this month or next month uh but we don't have any deployments on any
30:46
of the blockchains and we're gonna look to l2s as well to see what we need to change there to say that
30:51
okay we're covering that too but yeah we're going to extend to these these side chains for now
31:00
so thanks very much