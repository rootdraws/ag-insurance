Transcript


0:00
welcome everybody to this episode of covering defi covering defi is an interview Series where we talk with
0:07
Builders and risk experts across defi today I'm joined by Ryan of wallfacer
0:13
labs if you're not familiar with wallfacer labs they are a product Studio that builds and contributes to products
0:19
to move crypto forward wallfacer Labs is the um Team behind VA FYI and DOW deals
0:28
um among other products and I'm happy to be joined by Ryan today we're going to talk through some of these products talk
0:34
about what wall facer is building so welcome Ryan Hey guys thank you very much for
0:39
having me here Ryan do you want to give a little intro for yourself and for wall faer
0:46
before we jump into things yeah sure so uh my name is Ryan I'm one of the co-founders of wallfacer labs uh I guess
0:54
this is year six uh professionally in crypto for me uh started my career back
1:00
at trust token uh in 2018 working on stable coins and then eventually trui
1:06
and real world access more broadly and then we started wall faer Labs back in
1:11
April of last year so we just celebrated our one-year anniversary and when we started we kind of started with uh a
1:19
thesis around contributing to different defi protocols whether that was on the technical side most of our team is
1:24
composed of engineering and product Talent today and then also around getting involved in govern governance of
1:30
different protocols and over time we've evolved a bit I guess you could say to
1:36
start building and developing more products of our own the first of those uh is vaults FYI which is you know one
1:43
of the reasons why we're here today and and one of the reasons we've gotten to know or one of the ways we've gotten to know the Nexus team so well uh but vault
1:51
is I would say today probably the easiest way to find onchain yields across ethereum and a number of l2s uh I
1:59
think we have something like 150 different yield opportunities across 20 or 30 protocols um across seven
2:06
different networks and continuously building that product
2:13
out yeah I think I think you know Ryan that I'm a big fan of Vault FYI um I've
2:18
been using it in the reports I put out on a weekly basis where I cover the state of defi yields it's a really nice
2:24
interface it's a very easy way for me to figure out what the base rate in defi is and you know since I've started using it
2:30
you guys have made a lot of um improvements you've added more protocols you've created different categories so I
2:37
can sort by lending um sort by tokens I mean there's quite a lot that you can do with it so I think it's a a really neat
2:43
uh really neat tool and really beneficial um so I think let's let's start and talk about bz FYI uh I'm going
2:51
to just drop the link to vaults um in
2:57
the thread below this here just just one sec
3:11
all right so you can find the Vault FYI site just underneath uh in the comments for the phace today um but I wanted to
3:19
talk a bit about uh vaults FYI um one I wanted to start with uh What mo what
3:26
motivated you to build um vaults and where do you see vaults
3:32
going uh you know in the next couple quarters in 2024 yeah so the the second question
3:39
actually would love to you know maybe even brainstorm with you a bit about what you'd like to see from the product but I think the brief history of it goes
3:46
back to maybe May or June of last year so right after we had started wall facer
3:52
and our team was exploring a couple different things one of them was just around like a simple kind of rebalancing
3:57
tool between the best you know USD yields on compound in a and additionally
4:03
our team had also always been a fan of the ERC 4626 token standard for
4:09
different yield vaults and you kind of put these two things together and there is actually I would say a real
4:16
difficulty in finding reliable historical yield data on chain today
4:22
that comes from a few different places one thing you see is that a lot of places that show you yields today use
4:29
third party data like you know different kind of apis rather than actually souring sourcing the direct data
4:35
directly from onchain in our case we take the share price of different vaults
4:41
to actually give what we think is the most uh objective historical yields and
4:46
then allow users to be able to make smarter decisions based off of that one of the other challenges today is that
4:54
and honestly this is something I didn't realize until we started working more on vaults but different protocols
5:00
uh basically calculate yield in different ways so what do I mean by that
5:05
there are protocols like a and compound that you know if you go to Vault actually today let's just you know I'll
5:11
pull up two quick examples or I can point you guys to two quick examples you can pull up any compound or a vault
5:18
essentially and if you click on one of the vaults on our page and you scroll down to the apy history you can see that
5:26
these operate you know more or less as a straight line like there are these linear calculations for yield where you
5:31
know every block you're getting something at the same time you can look at other you know big kind of stall words of the defi space even like a Lio
5:38
or a UR and in many cases the yield in these protocols is actually kind of like
5:45
pushed I I call it to the holders where it's not this simple linear calculation
5:52
and if you were for example to come in between two of these different pushes
5:57
you would actually get a much different yield than if you were to kind of time that before and after some of these so
6:02
one of the things we do on vault is just kind of standardize this into a way that makes it easier for all users to
6:08
understand uh for any technically inclined listeners that want to dig in we have a great page in our docs on the
6:13
methodology that I'm really proud of that I think just explains this in a very simple kind of way and then of
6:19
course there are real world assets which today are gaining in prominence and popularity and those calculate yield in
6:27
a completely different way where we have to Tak in these offchain oracles and stable coin prices and you know it winds
6:33
up just being this much more difficult calculation but in a lot of ways Vault uh at least our homepage is a way for a
6:40
user who wants to compare kind of like for like to be able to do that across all these different opportunities and uh
6:46
formulas for calculating yield yes I think I think that's one of
6:54
the very beneficial things about bs is um you know on AA you can look and kind of see like what the historic yield is
7:00
for the past month but maybe not as granular as what has been for the last seven days um but also broadly across
7:07
different D5 protocols when you're looking at yield um there's two there's two core
7:14
things one of them is can you see what the historic yield is or do you just see what the yield is at the moment um one
7:21
of the things I come across when I talk to people about yield is I'll see something on farcast or something on
7:26
Twitter where somebody goes oh on a you can earn you know 55% on LUSD um on a and I'm like yeah
7:35
but what is it you know over time because that's kind of how a controls supply and demand right they offer high
7:41
apy and then Capital flows in and so what is it actually over seven days um
7:46
because if I'm trying to figure out where can I get the best yield somewhere um for my risk profile and I see it's
7:52
55% here and it's 20% there I put it in but the actual 7day or 30-day average is
7:58
actually like 12% and the other one is stable around 20 then I haven't made the
8:03
best decision for myself um so I think having that information is very valuable
8:09
the other thing that is really important that a lot of people don't take into consideration is uh what is the yield
8:16
like what is it comprised of and so if I look at something like um like seamless
8:22
for example because you've listed seamless here in the last couple of weeks um I can see what the base yield
8:27
is for usdc or US USD BC and it's
8:33
5.47% and the rewards that I'm getting in seam are about 45% so noting the difference between the
8:41
base actual organic interest that you're earning in a lending Market versus what the token incentives are are really
8:47
important for a lot of people especially if you have to harvest that otherwise you're taking on that market risk
8:52
exactly these are really important things exactly and that's one of the toggles that we have today if you go to the homepage if you are someone that
9:00
actually just wants dollar or eth denominated yeld and you're not interested in token incentives you can
9:05
just toggle that off and so today if you were to toggle that off the highest 7-Day apy that we show are uh morphos
9:13
re7 Vault Sparks dival on Moro some hop opportunities but again on a smaller
9:19
base so that's been a very useful feature the other thing that actually um
9:25
was initially our homepage and and I think we we've edited a bit just based on what users like but we have this
9:31
optimate Optimizer tab as well so vault. FYI back Optimizer and there you can
9:36
actually type in your preferences so you can say you would like to earn on
9:42
10,000 let's say you're insensitive to any usdc coins and you plan to lock it up for 90 days will tell you what the
9:49
best opportunity is based on all of those factors and this goes back to the point that you highlighted with you know
9:55
some of these crazy temporary a yields which is the way these work is that if a
10:01
borrower on a were to repay I don't know half of the Vault or something you know
10:08
then there would be you know a big underutilization so the yield would drop
10:13
and vice versa if someone were to draw down all the available Supply the yield would spike and that's just kind of a
10:18
natural market mechanism to try and draw in more capital or convince Capital to withdraw rebalance themselves so that's
10:25
where things like the 7-Day and the 30-day come in handy um I actually have a friend right now who is trying to get
10:31
into crypto kind of for the first time and was looking at some of the vaults that we have on vaults and I was just talking him through like you know yes
10:37
this one is 55% today but you're going to wind up with a bunch of this token that you've never heard of uh or yes
10:43
this one is I don't know 90% today but yes you know for the past seven days it was 15% so I think just being able to
10:52
make more informed decisions is one of the things that Vault gives people today and uh you know your excellent newslet
10:59
there is a great highlight of how people can take advantage of that data yeah and I I could talk a bit about
11:05
that too um the optimizer feature is really cool I wasn't aware of that so um I also posted that down in uh in the
11:12
thread for for the call today as well but um yeah I think I think there's a
11:17
lot of stuff it's really intimidating when you're first getting into defi especially when you're talking to somebody that's newer about you know
11:23
where yield comes from uh what you're getting paid in what the factors are for
11:28
things um you know I have talk to people about risk uh but just even understanding like where things come
11:34
from I've been to conferences before and talked to financial advisers um about
11:39
things and they've asked a lot about yields and I'm like yeah but what is it com in is it just interest or you know what is the yield made up of is it
11:45
actually token incentives or how much of it is this and how much of it is that and I remember being in a room full of like just traditional financial advisers
11:52
being like what tokens and I was like yeah it's all tokens but um like what are token incentives and what are
11:58
natural like interest you're earning on the tokens that you're putting in and they were just kind of like very
12:04
confused by this by this notion so um having having that information is is really nice especially for people
12:10
getting started um but yeah you guys know that I've been putting out this state of defi yields report yeah for a
12:17
little over a month now and I use vaults just to establish like what is the base rate so looking at the highest yield
12:23
opportunities to kind of get a sense of like where are things at so I usually pick like the top like 10 or 15 and use
12:30
that as like the range of what the opportunities are if there's anything that's an outlier I kind of note that as well um but it's really useful because
12:38
one of the core building blocks for yield and defi always comes back to lending markets lending markets are
12:44
major drivers for yield and so being able to filter on vaults and look at the different lending markets and then you
12:50
know just kind of segment things out by either stable coins or eth is incredibly
12:57
valuable for me so it's been a big help when I'm when I've been writing this um and also a lot of this fits in
13:04
with a lot of the conversations that people have had here uh in the last oh I
13:09
would say month but definitely the last week about like um maker and Moro and
13:15
Athena and a and and kind of everything tied up in there you know with concerns about risk but when you're looking at
13:22
some of these yield strategies that people are using in Defi and then you look at yields on vault across markets
13:29
you can kind of see um you know some cor some correlation so if I'm looking at
13:35
the re7 US usdt Vault why is the yield so high right why is this higher than
13:41
other lending markets and if you actually go in and look at it by clicking through on vaults um to the
13:47
actual Market on Moro blue you can see what the main things in the market are
13:52
and the main things that people are borrowing usdt for is is to farm either
14:00
ssde yields or usde yields so again it's that um that appetite that people have
14:07
either earn that leveraged yield on the Stak usde token where that's earning
14:13
yield from the DTA neutral strategy that Athena is running on centralized exchanges or the people that are just
14:19
leveraging long on usde to farm the shards that will be uh available for um
14:26
that'll be converted to Ena at the end of their season two that they're running
14:32
so I mean Athena has been a big driver of yield but if you're looking at those things you can actually click through in those markets and kind of see oh this is
14:39
why it's so high so I think that's really interesting too is that I can usually track based on the yield I'm
14:44
looking at to some of the narratives that I can see on crypto Twitter and some of the things that I can read on
14:50
different governance forums whether it's makers um or AES so it's been really
14:56
helpful and I kind of covered that in this week's issue as well so um yeah really great yeah and obviously that's
15:04
one of the things that I should say not obviously but one of the things that I've certainly picked up from just
15:10
looking at vaults Daily Now is how really it feels like the first time
15:16
in lending markets in crypto in a while that we're seeing new entrance really make a splash you know if you were to
15:23
turn off the rewards filter on vaults today and look at the top yields it's
15:29
you know in the top 10 you've got morpha uh sorry Morpho Athena you've got X
15:34
savings die AA a lot of these are are fairly new um and you don't see the more
15:42
established names like aan compound near the top as often anymore some of them do
15:48
still have pretty high yielding vaults but just at a quick scroll here let's say so on the 7day
15:55
apy the first High yielding Vault we from compound and a or compound's usdp
16:02
vault which is very small I wouldn't even count that A's V2 LUSD which also is very small and probably the first
16:09
notable one here is av3 usdc on polygon which is 15% and that's you know a third
16:16
you know less than a third of some of these top Morpho bolts today so I also kind of feel like we're seeing a slow
16:23
Changing of the Guard now granted in this Morpho One Like You highlighted it's mostly just Athena but still
16:31
yeah it is interesting I mean um I think one thing that that I've definitely noticed is you've got compound and a
16:39
which have very different very different risk Frameworks and how they manage risk right so uh
16:46
compound collateral that goes in does not earn interest can only earn interest on either we or usdc that's the model
16:54
they've chosen a is the peer to pool where risk manag AG ment is basically handled by the risk providers um that
17:02
are active service providers within the a DA and they're managing things across multiple markets they're handling
17:08
onboarding for listings with other service providers like AVN um so there's a lot going on there
17:14
and the whole idea behind some of these other markets like asna um Silo Moro BL
17:20
now these are all permissionless lending markets some of them use oracles and some of them don't so asna does not use
17:26
oracles it's more of like a limit order basis for Lending where you put in the the rates at which you would like to
17:32
lend um they have a very interesting design on on how they operate without oracles basically you can add anything
17:39
in there and you know there's no one managing things somebody can set up a market and somebody can start using it
17:45
whereas Morpho blue is uh permissionless but still they have this layer that's
17:50
built on top called metamorpho where you can have Risk Managers come in create
17:55
vaults and make it easy for people to deposit into those vaults and then they kind of allocate those Capital within
18:01
the vaults to the markets that they make on moral Blu since it's it's not as easy to interact directly with permissionless
18:07
lending markets so right um You can you can definitely see a change of the Guard
18:12
happening uh but a lot of these a lot of these um permissionless lending Protocols are on the newer side um so
18:20
it's interesting to see them taking off uh one thing I wanted to ask about is how do you how do you decide what to add
18:27
into the vaults interface I know you talked about um having it be a friendly
18:32
place to look for yield but what are some of the things you're looking for when you're adding new protocols uh within
18:38
vaults uh yeah happy to take that I also just want to bookmark one of the things you said about
18:44
um you know compound and a kind of being driven by these Risk Managers and how places like Moro have have transformed
18:50
that maybe we can come back to that um you know in terms of what we add to vaults we have kind of some hard
18:56
criteria and then kind of some softer criteria too so historically um we've
19:01
looked for vaults that are at least about a million dollars in tvl we make some exceptions for that for more
19:07
established protocols like you'll see a bunch of smaller a and compound vaults on there um you know we kind of use tvls
19:14
almost like a proxy for excuse me kind of like security and the the lindin you could say of some of
19:20
these things you know how long they've been around uh what we don't want to do is show opportunities that are kind of
19:26
too early where you know we still think there's a ton of risk of the protocol actually being proven out from a
19:32
security and safety perspective uh you know at the same time that we try to find a balance with that like with some of these newer asna vaults that you know
19:40
we think that just kind of given the caliber of the team that those are safe vaults to show even though they are
19:46
relatively younger uh just as a protocol and then outside from there we get a lot of requests from people and so sometimes
19:53
we'll prioritize if you know people kind of you know show us something that maybe has been around and we haven't seen
19:59
there's been a bunch of cases of that where we've added things recently um but yeah just trying to show a good kind of
20:05
risk adjusted return for different people that are coming to the site um I guess the only other hard criteria worth
20:10
mentioning is that all of the things we show today are single asset yield opportunities so it's deposit one token
20:18
get a yield we don't have like Unis swap LP tokens or more complex positions like that part of that is just the desire to
20:24
keep the product kind of straightforward for users and make these actually easier opportunities deposit into and at least
20:30
from a market perspective as well the majority of of the market is uh majority of the yield Market are these single
20:36
asset yield earning opportunities yeah I would agree there I
20:42
would say having having a site where you can look at different yields for like
20:47
Unis swap LPS and everything would be interesting but for most people that are already doing that they kind of already
20:53
have their their strategy on how to calculate that out um and it's uh I would say for the average user cumbers
21:00
them to provide liquidity on Unis swap B3 directly which is why most people are going through some of these liquidity
21:06
management protocols as well so um I definitely agree with with that approach simple enough to look at the yields
21:11
simple enough to find the opportunities and then it's just going to the site looking at it yourself and then depositing a single token I think that's
21:19
a pretty good a pretty good place to start you could always make out like an advanced version of it but um there's
21:24
plenty of single asset yield opportunities out there to highlight yeah but uh but yeah happy to go back to the
21:32
uh the point that that you had bookmarked there on um risk management across Landing markets yeah so you know
21:39
we put out this wall faer weekly uh every week now and one of the themes we've covered is sort of this like
21:45
shifting of alliances maybe within crypto I guess you could say where uh Gauntlet for example who historically
21:52
was a very large uh service provider to a recently kind of publicly left the a
21:58
dow to become a vault curator at Moro or vault Creator and one of the shifts that
22:03
I think that I've seen here is you're right that these risk providers are one
22:09
very expensive and two very critical to these doubts I think right now A has two or three risk providers they have
22:14
another one that just proposed yesterday to to sort of join them as a risk provider and they spend I think upwards
22:20
of three or four million dollars a year on the service providers with compound today I mean just kind of going through
22:26
their governance forums it seems like the the day-to-day of the protocol is kind of basically run by Gauntlet just
22:32
updating parameters all the time and those are just a cost to these protocols today I think the way that these
22:38
protocols can now interact with a place like Moro is that they're more of a partner and someone like a gauntlet or a
22:44
chaos or whoever can actually think about building a business for themselves that has more of this uncapped upside on
22:51
a place like Moro than they could at a place like a compound where they're just getting an annual service fee and
22:58
historically they have tried to work some of these more incentive based mechanisms into their contracts with uh
23:04
you know the stall wordss like a and compound but they just kind of haven't paid out but now with a place like Moro
23:09
they can create these vaults they can earn a service fee and if the Vault grows to be a billion or1 billion
23:15
dollars they're earning a basis points fee on that AUM now so I actually think it's very transformative uh in the
23:20
relationship of how Risk Managers can think about monetizing their expertise
23:26
in these fields which I think is is one of the things most exciting to me about watching this change of the Guard
23:34
essentially yeah I think um I think it depends it depends on the model so I think there's benefits tradeoffs on both
23:40
sides I think that having a service provider um running their own markets on
23:47
Moro blue for example they can make money and basically their success is based on their drive to to Market this
23:54
thing to get it off the ground and to build up a over time and and earn fees off of it is it as lucrative as say
24:02
being a service provider within a or some of these other places I'm not I'm
24:08
not sure I guess it really depends on on how big they get and how big they grow but I know Gauntlet for quite some time
24:14
was being paid about $2 million a year uh within a I think it was probably
24:20
somewhere around the same for compound um and they also I know Gauntlet works with um with other protocols as well I
24:28
think the the the thing with with a that was kind of contentious is that Gauntlet was working with people that a consider
24:36
competitors or other a forks and everything um and gaunlet has made
24:41
mistakes in the past but I think every service provider is um is prone to do that at some point one notable thing I I
24:48
had covered in Issue four of my newsletter was that there was a mistake on the
24:54
compound um arbitrum Native usdc Market that resulted in the borrow interest
25:00
rate being very very high when utilization was not um and so that had
25:05
to go through governance through the 7-Day time lock and everything to get fixed so you know some of these things
25:11
can still end up but I would say if you have someone like got running their own Market if that impacts the
25:17
trustworthiness of them as a risk manager then people will allocate elsewhere right um so you have different
25:25
options within the same protocol so that maybe you're not losing using tvl but it's just shifting over into other
25:31
markets so I do think I do think it's interesting I think it's interesting separating out the risk players I think
25:38
both um over time both of them will still continue to grow but one of
25:46
the benefits of something like Moro or asna is that these Landing markets are isolated it's not um peer to pool right
25:54
so you're not being exposed to the risks in other markets based on theet Market that you're in like you are with some of
26:01
the some of the protocol designs like a but the benefit with a is that they're more Capital efficient um so that is one
26:09
of the tradeoffs but at the same time if you're trying to limit risk you can put your funds in one market you can lever
26:16
up you can kind of play across the different markets there's a lot of there's a lot of benefit to that as well
26:22
from a risk perspective so it will be interesting to see how this Stu scales over time but we're seeing more these
26:28
permissionless Landing markets come around and thankfully they're not a bunch of compound V2 farks anymore so
26:34
that's a that's a major plus right right yeah I one of the things we' talked about a bunch is just you know looking
26:40
at gauntlets work just as an example this applies to many service providers I think you know Gauntlet is probably one
26:47
of the foremost experts in the space in terms of optimizing lending markets you know they worked for compound a like you
26:54
said all of these V3 Forks pancakes uh Blend or you know whatever they work for all these different things and you could
27:00
make an argument that like they are probably one of the players in the space who in theory would be most primed to
27:06
like launch a lending protocol of their own that could do well and I think Moro is kind of a way to test that thesis and
27:13
and I think it's really cool um also ra7 I mean you know their VA I think is one of the highest yielding ones on Moro
27:19
today you know historically I know them as one of the smartest funds in the space for managing their own book and
27:25
and optimizing yields so it's it it's it's really cool actually I I'm excited
27:30
by Moro especially but a know I'm not as much of a a kind of deep expert on that
27:37
but obviously they're doing a lot of interesting stuff too yeah I think each each one has each
27:43
one has a different approach but I do agree I think Morpho blue and metamorpho are going to be really interesting um if
27:49
you're a fund that's already managing things uh you can kind of you can route your own deal flow
27:56
through your markets right so I mean there's 's a lot of benefit there and a lot of optionality um I think for a lot
28:03
of these people so I Gauntlet has been around forever right like everybody acknowledges them as um as a really
28:09
great risk expert and a great provider in the space um chaos Labs is a bit younger but they also have a very good
28:15
reputation absolutely um but I think some of the ones that people often um forget about or maybe aren't as aren't
28:22
as aware of because they've been working with maker and maker has been around for at least in D5 for forever right so like
28:30
what three or three to five years but uh yeah can't get much earlier than maker
28:35
yeah yeah so block analytica um has a market and they're working with a B protocol um and they've been around for
28:43
quite some time as well and they're also working with um with maker they've done the due diligence on Athena for the
28:50
allocation into the spark D VA um you know there's a lot of these different
28:55
risk players that have been working with these part calls and so the ability to make their own markets and scale these
29:01
up very much agree that it's it's exciting to see and um unlike a lot of
29:08
other permissionless Landing markets we've seen before it's not like you know create your own Market from scratch
29:14
choose whatever Oracle you want the kind there's some guard rails there as well so as far as I'm aware all of the
29:20
oracles used within um within Moro blue have been chain gorical so far maybe some Redstone
29:27
but I have uh dug too too deep into that yeah I mean it's a little bit of a
29:33
web Tu ISM but you look at some of these giant businesses like a Spotify or something or sorry Shopify businesses
29:39
that kind of allow other people to create businesses with all of this infrastructure you know in some way you could think about Moro that way Moro
29:46
blue I guess uh so yeah we'll see um obviously they're off to a great
29:52
start yeah I definitely agree um having the thin protocol approach where you allow people to build
29:58
on top and I think this was one thing that um Paul from from Moro had a long discussion about on Twitter with um with
30:07
the founder from Oiler was about what what is the product what's the protocol and what's the product but the the thin
30:13
protocol approach is essentially what we're doing at Nexus right you have this risk management infrastructure you can
30:18
build businesses on top of it you can develop new products you can do these things so um the ability for people to
30:24
come in and build their own businesses on top of a protocol and and essentially do whatever they want within reason um
30:32
is just I think kind of what we set out to do in Defi and what we set out to do in onchain markets to begin with so it
30:38
is neat to see a lot of those developments coming through absolutely but I think getting back to
30:45
talking about um what wall faer Labs is is building um is there anything before
30:52
I go back to Vault FY is there anything else that you guys are working on that uh you wanted to talk about yeah so
30:57
there's two other things we're working on and active with today uh I guess just
31:03
about two or three months ago we got a grant from the worldcoin foundation and we're building out some grants
31:09
distribution and kind of governance tooling for them that we're very excited about uh the app will be uh I don't know
31:16
what the right word here would be but kind of worldcoin native and that accepts the worldcoin ID and it's sort of built around that primitive which
31:22
we're very excited about and uh we hope we get to put it to use in their next or maybe two from now now round of Grants
31:29
um we'll probably have some more out about that within the within this month and then um where we have worked since
31:36
we've gotten the company off the ground is with trui trui is a uh I think many people will know trui as a crypt native
31:43
lending protocol historically for Lending to market makers trui has done about $ 1.8 billion in loan originations
31:49
and recently we've just had two big announcements out of trui as well cicada Partners which historically was one of
31:55
the largest Originators uh of loans on Maple is moving off of them and coming over to
32:01
trui Tech stack to start originating loans to market makers and trading firms again we believe it's a it's a good time
32:07
for that market as there is a lot of demand and there's not really anyone to fill that today uh as a part of that
32:13
we're looking to help expand TR fi at different l2s as well so we're looking at base a lot of things on the op stack
32:19
some of things within arbitrum and then secondarily there we also recently
32:25
proposed kind of within the trui ecosystem launching a new protocol called Trinity which takes advantage of
32:32
a lot of the things that I think we've learned from both studying the rwa market and some of our work on vaults
32:38
just trying to give the definative benefits to these different rwa assets
32:45
around composability transferability and many of those different principles um if anyone's listening is interested you can go to
32:51
forum. try. and learn about both what we're doing with cicada there and with Trinity as well
33:00
sounds like you guys are definitely busy we are we are um yeah this past week has been a long
33:07
one but yeah that that's uh that's all very exciting um I'm looking forward to
33:13
reading a little bit more about that do you have more other other um than you know what you have on on the TR fi Forum
33:20
do you have more about what you're working on with worldcoin is there anywhere that I or anybody else can go and and read about some of these
33:25
developments uh with the worldcoin so much I think we had a tweet on the wallfacer account um just kind of
33:30
detailing the spec of that but I'm hoping within this month we'll probably have a demo or some kind of live product
33:36
out there uh on the truy side um actually one of the the place I'll just
33:42
kind of plug some of the content we've been doing if you go to the wallfacer labs Twitter we just put out our quarterly stateof the rwa market recap
33:49
and we have a few slides on there towards the end of what we're doing with trui all right great I will definitely
33:56
check that out after this call awesome um yeah so I wanted to go back
34:01
and and talk a bit about vaults specifically I know um I can I can put
34:09
in basically in the URL like b.b. FYI and I can look at yield opportunities
34:14
within a given Market I know I can filter filter that out um within the the
34:19
main vaults FYI app but um am I right in saying that is that available for most of the big networks like Bas and
34:25
optimism yes that is um and then we also have if you go to .v
34:31
vault. FYI a custom sub page that we built with them to be able to capture
34:38
some of the Nuance around Ur V3 vaults so Ur V3 has this ability for the
34:45
community to be able to create vaults essentially in a semi- permissionless way and so if you go to .vs fii you can
34:51
see that we have some additional just kind of data around that so whether it's a curated Vault by ear or Community
34:59
strategy and we also want to try to expand this for some different protocols as well so you can see here at the top we have this tvl across all of &v 3 um
35:07
we have the search and Optimizer specified just for Ur bolts so if the UR team wants to make it easier for their
35:13
users to search they can point them here um and really any protocol that has a
35:19
lot of nuance that would be tough for us to capture on the main page we you know are open to doing these custom sub
35:24
vaults to try and capture some of that
35:31
it's really interesting um yeah and I can see here they you've got the tags
35:37
for um urine created fault or Community strategy which is really nice to see you as you're looking
35:44
through um one one thing I know you were we talked about you know how you
35:49
calculate apys earlier um but I wanted to go back real quick and ask for like the the juic vaults so the you're an of
35:57
vaults that you're calculating the yield for so for the D Vault for example you have the base rate and then the juice
36:03
rate if you choose the extra APR and based on what I understand from their docs that is generated on a weekly basis
36:10
when they liquidate the uh the AA tokens into extra yield is that right I believe that
36:17
is correct uh actually I see Tyler's on the call I think Tyler my my colleague would actually know that detail a bit
36:24
better but I believe that is the case and I think actually the the interesting
36:29
thing here about these Juiced vaults is that you know if you kind of look at aa's approach to how they've gone to
36:37
Market they've they've really partnered with a lot of people in trying to get themselves out there and I think are doing a great job of positioning
36:45
themselves as just this infrastructure kind of backend for yield without you know them feeling like they need to own
36:52
the front end or kind of marketing of some of these experiences so I think the work that they've done with yearn kind
36:58
of broadly here has been really smart and exciting in terms of the go to
37:03
market yeah I agree absolutely uh it's been really neat I mean you've had urine build on on it and create the juice
37:10
vaults product um and then they've had they've worked with Mom which is the I
37:16
think I think it's within the urine ecosystem but kind of their like frontend design arm um to make that
37:22
juice. apppp page where it's all specific and you can actually see the different the different pool pools so um
37:29
I haven't checked I'm going to look on defi llama right now just to see what asa's TV all looks like now but I I
37:37
remember looking at asna because they've been around for I don't know at least at least a
37:43
year if not um yeah they've been around for up just about a year um so yeah so they if I
37:52
remember correctly they actually launched in yeah about a year ago and then they had some they called it
37:58
something else but basically a bug and so they I think turned off deposits essentially for their vaults and then
38:04
they relaunched just back in January so if you look at the total tvl chart that's where you know you see that kind
38:09
of big Lull in the middle and then they started growing again back in January yeah um yeah they had like a
38:15
disclosure of and they kind of went from their V1 to their V2 but exactly um yeah when I looked on them at the beginning
38:21
of the year they were around like I think 11 11 million but if you look at it it's just like a straight line up and
38:26
they've been hovering right around you know like uh 20 20 to 30 mil uh ever
38:32
since so I think you know the only thing that's been kind of the market going back down the TV's gone down because there's a lot of eth and things on AA
38:39
but now they're on base they're doing quite a few things so it's been really interesting but um again going back to
38:45
that composability um how important composability is in defi is that you have someone like
38:50
you're that builds on top and uses that as as a growth building block um and to juice balls have been crazy I mean
38:56
they're not as high as they were let's say a couple months ago but consistently when I was looking on on vaults like
39:03
week over week they were one of the top performing uh you know yield vaults out there so that was really really cool to
39:10
see yeah one one of the other things that uh on AA I found kind of
39:16
interesting is that a little bit less on the yield side more on the kind of token go to market side is that you know their
39:22
token has been live for a bit but it's live at like I don't know maybe 1% or
39:27
like some you know half a percent of the total Supply or something and I think I uh I've been meaning to actually kind of
39:33
dig in a little bit more to this but they have I think an interesting go to market as well and sort of roll out of
39:39
their token that I think doesn't follow the traditional like investor threee foure vesting type of schedule and I
39:46
think it's more they're going to kind of launch the token all at once at some point uh in the near future which I also
39:53
think is kind of Novel like if you look back to you know early a with like eth lend and lend I guess was the token you
40:00
know more the Ico type of approach for a token launch I'm curious how that plays out in practice as
40:07
well yeah I think um if you want to go off on a tangent about token distribution let's do it yeah for a hot
40:14
SEC um it's been really interesting to see because there's been a big shift right so defi summer came compound put
40:20
out uh valueless governance tokens used it for liquidity Mining and then everybody for about a year and a half
40:26
did the same thing thing um now we're in this cycle uh within the last year
40:31
people have figured out that giving people governance and giving people the ability to vote on changes to the
40:37
protocol while theoretically is a good idea that direct democracy just like it doesn't work in the real world doesn't
40:44
really work on chain either so people have been trying to figure out how do we minimize governance because people tend
40:49
not to participate in voting gas fees can be prohibitive how do we add some token utility to this thing and remove
40:56
governance so for a lot of people that have had tokens out there like the governance um approach hasn't
41:03
been a successful one so there have been people that have kind of been experimenting with what's the more utility now for AA I'm not extremely
41:10
well versed in how they distribute their token but from what I understand um they have their uh Reserve that they get
41:18
which is just the net difference for people lising between the interest that's being paid by borrowers and the
41:23
interest that's going to lenders and that is basically auctioned off um
41:30
for uh four people so I believe it's you can basically sell AA tokens
41:38
back to the protocol for the reserve fees if I'm remembering this correctly
41:43
um and then they burn the AA tokens so it's supposed to be this like deflationary release over time
41:51
um it's been I think it's been a little bit since I've read about that but just a different like utility for their token
41:58
that makes sense for a lending Market but with things like um like the points
42:04
craze which I've written about a lot it's been really interesting to see protocols take off like pendall um and
42:11
gearbox everybody that's benefited from this points craze around liquid reaking tokens or just around Athena with the
42:19
tokenized basis trade so with these things people are Distributing tokens in
42:25
new ways where you have this essentially promise token the points um which are of
42:31
some of them are are web three but most of them aren't really on chain they're just web2 accounting um and instead of
42:37
just saying all right now your points are convertible for the token and you can do it over this amount of time it's
42:43
okay you've earned points for this season now you can redeem it for these tokens now but we're going to be doing
42:48
this 5% at a time per season so that you kind of continue that growth metric as
42:54
far as what these tokens will be used for some of it will be governed there's some different utility but just
42:59
a different distribution strategy which I think we can see for all of these liquid reaking protocols um has been
43:06
very successful mind you successful for protocols that don't actually have any real yield yet for the most part um you
43:13
have the staking yield that underlies them but for everything that's built on top of igen layer Igan layer has like
43:19
what 12 billion about 12 billion dollars in tvl and they're not actively validating um you know any different
43:27
networks yet so um they're not live there's no real yield it's just speculation around these points so it's
43:34
been really fascinating to see that take off over time as well yeah definitely I think
43:40
um that sort of more overtime sort of continuous distribution of points
43:46
whatever you know kind of these seasons and stuff that people have been doing is makes a lot more sense I think and I do
43:53
think there's still a ton of white space within you know overall token go to market distribution all that kind of
43:59
good stuff I'm surprised still that you know that I know a few protocols that do
44:05
it that are fairly large but that more protocols don't even have like uh a small annual inflation just to you know
44:14
almost like upfront as a head just to say hey we don't actually know in four or five years what the state of the
44:19
market will be like maybe we still need this for some reason but yeah I I think there's still a lot of white space
44:25
there you know there are tokens that have like you can issue new tokens there
44:31
like is inflation built in the contract but nobody ever wants to use it yeah because everyone is fixated on like you
44:37
know the Bitcoin example of there's no more than this and in fact it's deflationary of course um but my
44:43
personal opinion is that tokens are not like equities and they behave differently and that the buy back and
44:49
burn method doesn't work as effectively as some people think it does on chain
44:54
but um that's a whole other discussion yes um one thing that I think that
45:00
personally for me that would be interesting is like uh maybe not on the traditional vaults page but something um
45:07
that looks like a Marketplace for like Pendle yields or things like that like like a vaults for points basically um
45:14
the points Marketplace just because people are trading these things
45:20
like on know yeah like what is it whale
45:25
something sorry sorry whales Market
45:32
yes yeah so um you know there are some markets for these things and it is interesting to see people kind of
45:39
speculate on this and again like Pendle has been I think the primary place where people are basically kind of
45:46
dictating the current rate for some of these tokens so yeah it's been really
45:51
really interesting yeah I'd say just across the board there's so much to keep up with across uh all of Defi and yield right uh
46:00
right now which is exciting as it you know maybe didn't feel that way a year or so ago so having all these new
46:06
protocols come to Market these new distribution methods these new ways to earn yield to speculate uh that's what
46:12
makes crypto fun yes definitely it's it's very interesting um I think like I've said
46:18
I've said before on other formats but the whole reason I started writing the state of defi yields report is that I do
46:25
this basically every week when I'm going through through and doing risk assessments on different protocols staying up on governance forums and kind
46:31
of summarizing these things so I thought why not put it into a newsletter for for other folks and then of course you guys
46:36
came along and made my life a lot easier um by putting together nice calculations for the average apy over a week um but
46:45
there's a lot of new stuff coming around and so it's interesting to see what people are building it's also interesting to see the risk profile that
46:51
people take on as like you know the market evolves throughout the bull market that we're currently in um so
46:59
it's it's definitely interesting I will say for people listening um there's definitely still risk out there I think
47:05
one of again one of the benefits for Vault FYI is you present a lot of more like Risk adjust strategies and simple
47:11
strategies so you know people can kind of click in and do their own research but you break down a lot of the
47:16
important factors right there on vaults which I greatly appreciate as well especially when I'm trying to talk to
47:22
somebody about something and I'm sending them over to vaults great thank you for that
47:28
yeah so so what's your day-to-day like on the on the Nexus side as well with some of this risk and like you know I
47:33
guess from a practical perspective are you using vault at all in your day-to-day or yeah I usually um I'm usually looking
47:41
at vaults just to kind of gauge what interest uh interest rates are um across
47:46
lending markets lending markets uh usually act as as a signal sometimes um
47:52
so for example when everybody was talking about you know die with the allocation to um to Moro you know for
48:00
the atheno markets um and everybody was kind of uh upset about how quickly that
48:06
moved through and and some of the like the due diligence and things and I summarized that in issue five but um
48:11
there you saw lending rates kind of Spike for die in certain places because
48:17
some people transferred their debt over to die because they thought well if it is risky and something does happen then
48:23
I'll just hold die as my debt because if it deegs for some reason then it'll be much cheaper to pay this thing back so
48:29
you can kind of see Market rates react in a certain way and usually if something's higher I go and check it out
48:35
and just make sure like you know what is this thing reacting to um I'm also looking through governance Forums on a
48:41
pretty regular basis um I always tell people it's great to read uh defi
48:47
governance forums to your kids if you want them to go to bed uh but sometimes when you're reading them it'll something that'll keep you up awake at night so um
48:55
but that's kind of what things look like for me on the Nexus side I do a lot of risk I'm also looking for new protocols
49:00
that we can list that people basically want to deploy funds into but you know risk holds them back so I try to keep my
49:06
finger on the pulse for newer protocols coming across the way um I will say like
49:12
for Moro blue the approach that we take at Nexus is we list individual markets um as they come online because things
49:18
are permissionless you almost want to review every market look at the oracles they're using and then list them that
49:23
way instead of just saying you know full force anybody that creates some Market here is covered um so I use it to look
49:30
at some of the ones that are higher performing some of the ones that have traction with a certain amount of tvl
49:35
it's very beneficial for that but um yeah I will say that I use vaults every day in my day-to-day looking at yields
49:42
as a basis some of the more far farlong stuff isn't on vaults but um you know
49:47
then again that stuff isn't as easy to comprehend and it's not for the average User it's for some other power users but
49:54
um a lot of my job is looking at risk um trying to find different narratives keeping up on yield opportunities and
50:01
then taking things back on the product development side and seeing if there's something that's missing um if there's a
50:07
need within the market that doesn't have a cover product for it or if there's something that could be listed that people could benefit from that's usually
50:13
what I'm searching for uh on a day-to-day basis throughout the week yeah I'd love to you know we're
50:20
always open to feedback and if there's anything we can do on the Vault side to make your job easier and have that be a
50:26
bigger part your analysis we'd love to see what we can do yeah like I've said before adding
50:31
adding the different um categories like lending and stuff where I can kind of narrow things down and look at certain
50:36
markets has been a really big help um and again when I started writing this I basically just used like maybe a couple
50:43
screenshots from from vaults in my early uh newsletters but now I go through and
50:48
I just kind of provide screenshots of each individual Market as I filter through to give people some insight onto
50:54
like what are the what are the rates across different markets um so you know
51:00
the improvements that you've made since I started using vaults have been really helpful good GL but I will give you more
51:06
feedback as I come up with it though so can look forward to that for sure good
51:12
um but yeah we are getting close to time and everything so I can I can wrap things up um is there anything before we
51:19
uh we head off for the day is there anything that you wanted to highlight or anything you wanted to note Ryan uh well we've got a a bunch of new
51:27
things coming to vaults as well so we're adding some additional features around charting to make it easier to compare
51:32
historical yields between different vaults over time and I would also say we haven't
51:39
really announced it but if you go to our homepage you can see that we have kind of a vzero of our API out there we're in
51:45
the middle of making some fixes then we'll have a bigger announcement uh about that next week but uh people want
51:50
to use that or have questions about that please uh feel free to reach out you can
51:55
always reach out to me directly my telegram handle is just right in my Twitter bio or you can DM The Vault
52:01
account I think the DMS are open there we check those regularly when we get in touch with
52:07
people that is awesome um yeah I'm definitely looking forward to the optimizers I'm going to check that out
52:13
more for sure um and then the urine page as well I'll be looking at that more often and I'll probably put that in the
52:19
next report so thank you for for sharing that on this call awesome well thank you for your time and thank you for being
52:24
such a user and supporter of the product we greatly appreciate it yeah uh absolutely so for those listening uh if
52:31
you haven't checked it out yet head to vault. FYI um lots of lots of ways to
52:37
check out yield opportunities lots of ways to filter you can look in the comment section of this call and you can
52:43
find some of the different things that we talked about on the call um Ryan thank you very much on behalf of
52:49
everybody on the call for sharing some of what you're working on from wallfacer and Vault FYI uh we will announce the
52:58
next installment of the covering defi Series in the near future but thank you everybody for listening today I hope
53:04
everybody has a great day and we will see you on the next call thank you talk soon bye
53:12
everybody