Sep 22, 2025
Kyle Jacobs and Christopher Gora - Transcript
00:00:00
 
Kyle Jacobs: Oh, you got it. Cool.
Christopher Gora: Yeah.
Kyle Jacobs: Yeah, I would appreciate if you'd like link that afterwards so I can look through all of our stuff and kind of combine it into some kind of research article.
Christopher Gora: Okay. Sounds good. Uh, yeah, I'll definitely do that. Let me see. I've never really uh Okay. All right. It It should start. There we go. It should be recording and transcribing now. All right.
Kyle Jacobs: Cool. Um, I can share with you what uh my goal is for like this project I'm working on.
Christopher Gora: Sounds good.
Kyle Jacobs: Cool. Um, so you guys are partnering with Opouls, right? And then you have a vault that does, I believe, reinsurance that uh the easy I'm assuming that's uh deposited is is backing the reinsurance. Is that correct?
Christopher Gora: So, we're not we're not using easy e uh we set up a separate vault that uses a USD. So, that's Aora's stable coin.
 
 
00:01:05
 
Christopher Gora: I think you know it's back they have it's it's it's genius like approved and it like complies with all the different stable coin regulations. um they hold reserves with State Street and I think one other bank. So we use their stable coin instead of easy eth or any other crypto-based collateral uh specifically for Ooulis and essentially our users uh when when the deposits were open would deposit a USD um and then it would become locked for a period of six months. So, uh, the way we set up the bond, it's essentially like a like a zero coupon bond, um, where you can't withdraw until until the six-month time period has already passed.
Kyle Jacobs: Mhm.
Christopher Gora: Um, and so our first deposit campaign, uh, had a cap of of 500,000 uh, dollars. So 500,000 AUSD, and that's all going to to Secure Oops's uh, like liquid liquid reserves.
Kyle Jacobs: Did that fill up?
Christopher Gora: Yeah, we hit apps uh within within a week I think it was uh rather quickly. Um but essentially like you can't it all goes to to OPOS's needs.
 
 
00:02:23
 
Christopher Gora: Um it can't be withdrawn until after the six months is over. Um, Opouls is uh I think they have an IGEN grant that they are uh incentivizing this this pool with to start and then eventually they're going to be paying out some of those premiums from from the insurance and reinsurance that they're doing themselves into future versions of this bond. Um, and if if if there is any need for OPIOS to actually use those funds, there is slashing um planned for future bonds. So in the future, if we do some of these bonds, there might be some sort of slashing uh possibly to to get those funds redistributed to OP if they need them. But as of right now, we we think that the I think the first bond doesn't have slashing enabled yet. It's just to meet their, you know, regulatory requirements for for having some funds in in reserves.
Kyle Jacobs: So they're preparing to basically use layer and yourselves the flow vaults. Is that what these are called?
Christopher Gora: Yes, we're calling flow flow vaults is what we call any custom LRT.
 
 
00:03:27
 
Christopher Gora: So we we have the ability to create a fully custom LRT uh liquid restaking token that can use any asset and then like like with this bond for example, we can uh set time locks that don't allow you to withdraw in case you really need that liquidity to stay there for a certain time period. So in Oops's case is 6 months. But yeah, we call them flow volts.
Kyle Jacobs: Cool. um this is like a trial period then and then you'll use iigen layers a like slashing capabilities to sort of like automate uh payouts in the future and you'll also sort of you're you're kind of also priming the depositors now to be okay with depositing again in the future because you're saying here's some initial yield you're going to get some premiums see that wasn't so bad do you want to do another six months higher the caps Um, you're like Yeah.
Christopher Gora: Yes. Um from from from our side, we're trying to be mostly just a service provider.
Kyle Jacobs: Mhm.
Christopher Gora: uh you know, we're building the infrastructure and the smart contracts that are allowing this kind of thing to to actually go on chain and use restaking for it because we think, you know, restaking is is could be used specifically for this use case.
 
 
00:04:46
 
Christopher Gora: Like there's different use cases for restaking, but this might be one of the the better uh more more yield heavy ones. um it's a good fit. You know, if there's any sort of slashing you need or any any time lock or any asset that you guys want, like anyone wants to use, uh we're just a service provider that helps them, you know, bridge that
Kyle Jacobs: She's
Christopher Gora: gap and do it all onchain so they don't have to do it themselves. And we just happen to use IGEN layer for it. But, um, you know, that's kind of on the back end. It's it's uh we try to keep that away from from the actual user so that they don't they don't necessarily even have to know that it's taking place on layer
Kyle Jacobs: What about Um, so if I'm depositing into this vault, what's the likelihood um, not now, but in the future that my capital will be slashed and then like how do you sort of make sure that it's enticing enough for me to earn more than the potential to lose?
 
 
00:05:42
 
Kyle Jacobs: like where's the who's responsible for that and how's that handled like
Christopher Gora: So it's the pitch from from Oops is essentially that the insurance industry is very um it's very inefficient. So so it generally healthcare typically runs on like a sort of cost plus model. So they have um because of regulations a cap on how much profit uh they can make which means that if you make you know a million dollars in revenue they can only make 15% of that as profit which then incentivizes a lot of these insurance companies to go and then mark up the prices that they charge in revenue so that they can charge a larger make more in profit because they're their percentage is still the same but they charge them more in revenue so they they are able to make more profit And a lot of these costs are passed on to reinsurance companies. So reinsurers have to go and uh they charge more too because it's both in the insurance company's interest and their own to just charge more and then the end user is the one who who ends up losing out.
 
 
00:06:52
 
Christopher Gora: Oops essentially pitched that they are going to cut out that middleman uh in this relationship. So, they're going to cut out the reinsurers who are inflating the prices that it costs to reinsure uh to the actual insurance companies and they're just going to supply it themselves. They're going to be the insurance company and then the reinsurers in this case are going to be onchain uh depositors who who it can be, you know, uh any the whoever deposits into into these vaults. So the pitch there is that they cut out a lot of the waste and a lot of those misaligned incentives uh because that cost plus model incentivizes these people to go and charge a higher price than they really need to um just so that they can capture more value and by cutting out those middlemen they can provide a cheaper service at the same quality to to anyone looking for insurance. Um, and in the future, you know, it should be like theoretically the bonds should become similar to reinsurance but with with less of those middlemen coming in. Uh, so they can provide better better services at a cheaper price to people looking for insurance.
 
 
00:07:59
 
Christopher Gora: And then also on the yield side, if you are someone depositing into one of these vaults, you could potentially uh get get good yields uh risk adjusted yields without taking on an undue amount of risk.
Kyle Jacobs: So this is a way for Renzo to build uh TVL and utility for um for IGEN layer and for themselves uh for restaking. Um, but it's all centered around AUSD agora.
Christopher Gora: So, Agora is a stable coin that is used in the reserves. Um, the reason we chose Agora is that there is some some level of yield share between the treasuries that are backing it and uh whichever entity it is that's holding it. So the cost of capital for OOIS is going to be slightly lower uh versus if you know you use something like USDC or USDT they typically don't share any of that you know four and a half 4% yield but backing the treasuries. So AUSD uh allows us to to bring that cost of capital a little bit lower um and ensure that you know OPOS can can get their get their insurance premiums uh as low as possible while still being you know reasonably uh reasonably priced.
 
 
00:09:19
 
Christopher Gora: So it's it's really just about bringing the cost of capital lower while providing the same service.
Kyle Jacobs: Uh what are your um like Renzo's KPIs like what is your it's like increasing the total amount of deposits that are there in these uh flow vaults.
Christopher Gora: That's one of our goals. I mean, I think generally we are so early with with reinsurance as a whole use case and in restaking that we just kind of want to see how it plays out and see if there's, you know, any any any demand for it going in the future. Um, we do see it being something that that will grow really really quickly and grow a lot uh over the next few years. We do think Ooulis is a good example of this. Um, I'm not too sure if you're familiar with CAP uh CAP uh the stable coin provider. They're doing something similar to this where they use restaking collateral for for sort of as insurance.
Kyle Jacobs: Please.
Christopher Gora: um cap it's uh if you go to cap.app app is their website.
 
 
00:10:20
 
Kyle Jacobs: spell that. Oh,
Christopher Gora: Um they're doing interesting things with with a use case similar to to this with a similar reinsurance uh through restaking use case. But we just want to you know we want to see this this sector expand because we think it could you know it there is a future where a lot of insurance comes on chain where people want the finality of of of a blockchain. They want the you know settlement of a blockchain. they want the the the verifiability of the blockchain. So, we think that it could be a superior form versus, you know, what the the existing status quo is. Um, and we think, you know, we want to be be the first and and and foremost uh place to do it, the easiest place to do it. Um, so like we said, we're we're a service provider. We're not necessarily uh opinionated on on on the actual use of of the insurance. We don't want to take a stance and say these guys are guaranteed to never slash you and yada yada.
 
 
00:11:26
 
Christopher Gora: Like we want our users to be able to make those decisions for themselves. We're just here to to help uh bring those opportunities to them if that makes Yeah.
Kyle Jacobs: Provide the vault structures.
Christopher Gora: I I don't know if uh if that was clear. Um let me know if anything was was a little confusing.
Kyle Jacobs: LP LPS like who's um who's depositing is are you guys sort of corraling those people or is a is a Agora mixed with Opel mixed with you guys like how are you getting the money in the vaults?
Christopher Gora: So, Agora um Agora like us are just a service provider. We haven't like we we spoke to their team just to get this all set up, but uh they're not help you're not you know they're not too involved. Uh we also uh we set up the flow vaults and we talked to a couple of LPs but most of it's on Oops. like Opelis is the one that the funds are securing. Obelis is the one that'll be using the funds in case of, you know, a slashing event.
 
 
00:12:32
 
Christopher Gora: They're the ones who are ultimately like the the the vault curator essentially. Um there's, you know, it's a it's a parallel to, you know, vault curators on Morpho or or something of that sort where uh we we are just the ones creating the vault and then someone else is is the
Kyle Jacobs: Yeah.
Christopher Gora: one actually in in control uh of those funds. So most of the LPs, most of the depositors are are linked to OIOS in in some way uh rather than, you know, us being the ones who are going out and and finding them for them.
Kyle Jacobs: Okay. And then are you exploring any other types of insurance, any other insurance providers or just focusing on Oops right now?
Christopher Gora: I mean, we're open to whatever insurance providers, uh, you know, are interested in building onchain. I think we're not we're not, you know, exclusively linked to Olo. They were just the first ones that we were in contact with and the first ones that actually started pushing to make this a real use case on on restaking.
 
 
00:13:34
 
Christopher Gora: Um but we are definitely interested in in any anyone and any organization or company that is interested in building something similar to what OPI did or uh you know changing it to meet their needs.
Kyle Jacobs: Cool.
Christopher Gora: Uh as long as it can be done on restaking then you know what Renzo can uh can help uh with with doing it.
Kyle Jacobs: Um, okay. So, uh, I'm going to sort of repeat back from the top like what our goals are and then what my understanding is of what Renzo what Renzo is doing.
Christopher Gora: What's that sound?
Kyle Jacobs: Um, So, what we want to do is make a PDF that we're sending out to like who are we sending that out to? Um, probably treasury companies, probably like uh people with capital who would be interested in depositing into vaults like these. Um, and we can't say put put your money in this vault because that's like advertising financial products. You can't do that. But you can provide information about like what this onchain insurance industry is. So there'll be a section in this PDF that talks about Renzo's flow vaults and the relationship with IGEN layer and how slashing um can be automated to repay and like so I guess the other question I have is like can you give me a contract for one of these uh flow vaults andor can you explain what the different parameters are like that that are taking place in
 
 
00:15:18
 
Christopher Gora: Yes, let me the link. Okay, I've got the doc link. I'll drop it in our Telegram chat. Um essentially we've got you know some most of these contracts uh are present in our in our docs.
Kyle Jacobs: Thank you.
Christopher Gora: Um but we have a number of different parameters. So there's the the deposit asset which um in in Olos's case was AUSD which is a genius regulated stable coin and it uh complies with all the same regulations as you know USDC or something of that sort. um we have the the um the promised APY assuming there is no slashing. So if there is no slashing uh Opouls is going to put up this much in rewards and then obviously that amount uh could change depending on how much is actually slashed uh depending on you know the the actual claims from the insurance pre uh policies that are written out. uh if that, you know, if that kind of thing ever happens, you know, if some if a ton of people claim file insurance claims, then some of these future bonds might be slashed to to pay out those those claims.
 
 
00:16:32
 
Christopher Gora: Um there's a bond duration, so it's configured, this one was configured for for six months. Um so that AUSD that's deposited is fully locked for that time period. You cannot withdraw it. Um you can only withdraw it after the six-month period. So it it gives Opelis or or anyone who who wants to build something like this the actual guarantee that their collateral is going to be there and that they can use it if they need to. Um and then you know all of this is put on chain uh and handled through our smart contracts. So in that link that I shared with you uh you can there's the vault contract uh that you guys can can inspect or view yourselves. Um yeah, this is on the internet.
Kyle Jacobs: Yeah. Is this a um is this on mainet? Ethereum mainet. Yeah.
Christopher Gora: Yes.
Kyle Jacobs: Cool. And then uh the way that you made these flow vaults is this um is this like derived from 4626 uh there's a receipt token and a vault structure like uh or is it a different thing?
 
 
00:17:42
 
Christopher Gora: Um I don't I'm not sure if we use 4626 specifically. That's like a subset of ERC20, right? Um we I I know for a fact it's it you get a receipt token in in ERC20.
Kyle Jacobs: Yeah. Cool.
Christopher Gora: Um so it's it works under a similar premise as our our large liquid restaking tokens like easy ETH where you deposit you know AUSD and then in return uh you get uh this one was called Opus One AUSD.
Kyle Jacobs: Yeah.
Christopher Gora: Um, and so that token gives you, it's an ERC20 that can be integrated into DeFi, but uh, at the moment, you know, it's not something that we really did. Uh, we didn't think that there's going to be much demand for that. But um you receive an ERC20 and then this ERC20 uh eventually when when uh claims open when the when the period is over after the six months you can go and and swap same as you would redeem Easy
Kyle Jacobs: Yeah.
Christopher Gora: ETH uh you you deposit that Opus 1 AUSD token back into the pool and then receive your share of the pool.
 
 
00:18:47
 
Kyle Jacobs: Yeah, that's um it's crazy. If you guys get like I don't know 50 60 of these things and they all have receipt tokens could like a market you know people can trade their positions while they're locked.
Christopher Gora: Yeah, I mean like uh we just have one of them and it's a 500k market cap. So it's you know it's hard to build liquidity for that. Like uh I think our our our focus is better spent elsewhere. Uh but we do see a future, you know, where where there are products like this, you know, 10 years down the line, it could be possible that there's going to be billions and billions of dollars of of insurance on chain. And we want to help help bring that future in. And we think that, you know, like like you said, like there could be, you know, an an LP pool for for unis swap where these tokens are paired with some sort of stable coin and then anyone who who wants an early withdrawal, an early exit can can swap through that pool or, you know, you might be able to use it as lending collateral on a on a market to borrow stable coins that you're partially liquid even though you're still locked for that six-month time period.
 
 
00:19:56
 
Christopher Gora: I mean there's a there's a lot of you know composability in DeFi and we think um that's another thing that's going to bring more of these these sorts of products onchain.
Kyle Jacobs: Cool.
Christopher Gora: Um you know we just want to we just want to help and and grow grow this market as much as we can this type of thing as much as possible over the next few years.
Kyle Jacobs: So, um what are some like uh what are some goals for for you in the next like quarter, maybe like 6 months or something like that? Like where where are your priorities at
Christopher Gora: um well Renzo is focused on a lot of things um but specifically with reinsurance and this type of thing I think we want to talk to everyone who's building something similar onchain so whether it's, you know, uh, health insurance or it's some sort of other, you know, yield, uh, yield insurance. We want to talk to them and and evaluate and see if we can fit in and help them build their their product. Um, so we want to to make sure that we are just an unopinionated service provider.
 
 
00:21:13
 
Christopher Gora: We don't want to say that these guys are the best and you guys should deposit with them and they're going to win and everything like that. like we want to give our users as much uh choice and of of their own as possible. We just want to bring the opportunities to them. So, we're focused on on helping uh we we've had a number of conversations with teams doing something similar or working to do something similar. Um obviously it's, you know, uh as much as we'd like it to be, it's not an instant process. It can't be done overnight. So, some of these things uh take a long time. Like with Opouls, we were we were helping with them. We were helping them get started from the idea phase. So we uh we worked closely with their engineering team to make sure that the vaults that we created for them met their needs specifically. Um so you know we're we're happy to talk to whoever and help them you know decide on what kind of parameters they need and how they want to build these vaults.
 
 
00:22:07
 
Kyle Jacobs: Okay. Um, can you can you give me a minute, please?
Christopher Gora: Sounds good. Yeah.
Kyle Jacobs: Cool. Um, I'm inviting uh Brian to the meeting here right now.
Christopher Gora: Sounds good.
Kyle Jacobs: Yeah. So, or maybe that And here we go.
Christopher Gora: How's it going?
Ross Gates: Good. How are you? I'm on Kyle's team.
Christopher Gora: Good. Nice. Nice to meet you. Uh we were just discussing, you know, uh Renzo's flow vault and how we worked with Opouls to get them an insurance product set up through restaking. Um and you know, kind of our goals with that going forward into the future.
Ross Gates: Very cool. It looks like you guys are just wrapping up, so If this is recorded, I won't make you reset everything.
Christopher Gora: Yeah, we uh we have a recording. So, uh I'll I'll make sure to share that with you guys.
Ross Gates: Cool. That be awesome.
Kyle Jacobs: Um, so we covered uh Renzo is a service provider.
 
 
00:24:54
 
Kyle Jacobs: They're creating these vaults. I have the documentation for the vaults here. It was linked in the chat. Um it's I can share screen and just show for a second. Um docs. So why is this? Yeah. So, this is uh a link that's in the chat. It shows the details of the type of vaults that it is. There's like it's like locked for 6 months. This is the APR. The APR is coming from Renzo. Uh sorry, no from IE layer initially and then in the next iteration of this they're going to have slashing. Um they are a reinsurance which means they are taking place after as a backs stop I think for Opouls. Um Opoulis is primarily responsible for depositing into these vaults and um and Renzo sees themsself as just sort of like an infrastructure um tool. Um Renzo has partnered with Agora which is a stable coin. the stable coin that like Agora is being used because they offer a slightly better subsidy for um making things more affordable to Obelis and they also comply with genius like stable coin requirements.
 
 
00:26:23
 
Kyle Jacobs: Um
Ross Gates: Just quick question like the premium and payout if you're enabling slashing where someone can I guess lose money from one of these funds. Do you have modeling or didopoulos provide modeling for like what the expected return is with the premiums paid and the slashing detracted?
Christopher Gora: So for our first spawn, the Opus series one that's uh being screen shared right now. Uh I believe it's no slashing. That one is just, you know, to to walk through all the kinks and everything of of the actual product. Um and then OPIOS needed some funds uh in liquid reserves I think to meet you know regulatory requirements but they wouldn't be slashed in the future. Uh future bonds might have slashing. Uh I'm not exactly you know sure about how how that slashing will will look. Uh we don't you know on our side we're just the you know service provider that allows them to build onchain. Uh, but then all the deposits, all the risk is kind of up to Obelis to to decide. They're the, you know, like I told Kyle, uh, we're kind of like the infrastructure provider and then Olo is the vault curator who's in charge of what happens with that vault.
 
 
00:27:40
 
Christopher Gora: Um, but I don't know if you guys want to be introduced to the OPOS team potentially.
Ross Gates: Got it.
Christopher Gora: Um, okay.
Ross Gates: We know them quite well.
Christopher Gora: Okay.
Ross Gates: Um, yeah. I guess my my curiosity is just with them because if they're the actual insurance company itself and you guys are the rails then yeah I'll ask them directly
Christopher Gora: Sounds good.
Kyle Jacobs: So, we can be helpful to Renzo by directing more insurance opportunities to Renzo to provide vault structures and We can be helpful to Renzo and by um finding LPS to deposit into this after this case study has taken place.
Christopher Gora: Yeah, I mean I think that about sums it up. Like uh like I said, I think you know, we want to talk to anyone who's who's interested in building anything similar to this. Like uh our flow vault structure allows us to create a fully custom LRT meeting most of the criteria that I think uh anyone anyone would need. uh we can customize the the duration uh that the the time lock lasts.
 
 
00:28:47
 
Christopher Gora: We can customize the deposit asset, you know. Um so I think that would be great. Like if if you guys are talking to anyone, we'd love to talk to them and see if they want to build on chain uh and we can help them simplify that process.
Ross Gates: that'd be awesome. Um, yeah, I'm actually thinking about starting a joint venture with a property management company that wants to start its own property insurance because they pay about $80 million a year to property insured third parties. And if they can tokenize part of it and then hold those reserves onchain in Athena or Agora or one of those other stable coins that has a higher yield, uh, they can get their investors to essentially deposit money there to allow them to become an insurance company.
Christopher Gora: I think that so so it's an ins do you mind telling me like a little bit more about how that works? So it's a property management company and they need insurance for their properties. Um they end up you know paying 80 million in premiums every year for that and they they want to bring some of that onchain.
 
 
00:29:46
 
Christopher Gora: Is that is that right?
Ross Gates: Correct. So, as a property management company, they own I think 2,000 properties.
Christopher Gora: Okay.
Ross Gates: Some of them are like six family unit houses. Some of them are 250 unit 25tory skyscrapers. They pay $80 million a year and let's say they pay $80 million a year. Someone breaks their toilet. The insurance company pays out like $7,000. They're like, "This is completely unnecessary. We know everyone because we're the property managers. We can fix that toilet for $300. We don't want to get paid out more. We want to pay lower premiums." And so they want to start their own insurance company because they have the funds to basically float it themselves. But in order to be an insurance company in the United States, you need about $2 to5 million in escrow per state that you want to be an insurance company in. So, they're starting with us or a joint venture using their the state that they have the most properties in that need the most property insurance that um has the lowest fire risk.
 
 
00:30:51
 
Ross Gates: So, the lowest risk of actual loss and then start from there. Get their investors to deposit on chain and then go from state to state asking their investors because they're already working with some large family offices that could basically just put the money directly on chain. Um, yeah, happy to talk more, but that that's like the general gist.
Christopher Gora: Yeah, I think um that's really interesting. I mean like we are we are seeing a lot of demand a lot of a lot of you know a lot of the newer ABS's on on restaking uh you whether it be on IGEN layer or symbiotic are thinking about uh how they can use potentially slashing as something to to bring insurance or reinsurance or some variation of it onchain and uh make it better for for end the end user.
Kyle Jacobs: That was cool.
Christopher Gora: Um, so if there's any interest there, like if there's anything more we can help you guys with, we'd love to, you know, talk more about it.
Ross Gates: For sure. Slashing is a big part of it.
 
 
00:31:55
 
Ross Gates: Like for every let's say 5 million that they take in in premium, they expect to pay out 3 to4 million. So they take in the premium and then they return let's say 14 to 30% APR but it is they have 10 years of historic data of knowing exactly what the claims are going to be and those claims need to be made in some way and if slashing's the mechanism would love to discuss it.
Christopher Gora: Okay. All right. Um, I'll I'll talk to our team to see if there's something that we can work with you guys on uh specifically to get that, you know, set up or built or whatever else. But we think, you know, like like we wanted to see the the the onchain reinsurance or insurance sector grow to be a thousand times bigger than it is today. Like we want to have some some future where there's, you know, billions of dollars using restaking or or something like that to be the settlement layer. Um so we we definitely want to stay in contact. If there's anything uh you guys want to share with us or anything you need from us, please let me know.
Ross Gates: Perfect. Thanks, Christopher.
 
 
Transcription ended after 00:33:38

This editable transcript was computer generated and might contain errors. People can also change the text after it was created.
