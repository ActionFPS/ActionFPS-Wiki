Crucial 
==
Imo most important bit is the **new user flow**:
> I'm a newbie and open this site. How and why do I end up playing the game, and coming back again?

Should optimise the living lights out of that.

***

The rest
==

the concept is to do the appropriate thing for the appropriate time
instead of guessing what the truth would be 2 years down the line, we try different things within 1 month timeframe or so
then we can align more closely with the truth and the right thing all the time
e.g. achievements was really really good at the beginning.
listing who achieved what on the homepage is quite nice, but at some point we'll have achievements coming in every 5 minutes so we'll remove that information, because it's no good any more
it's a conversation. And conversation is transitive, temporary, ephemeral
but you can't get to the conclusion without having the conversation and going through the motions, the immediate steps :grinning:

ScalaWilliam Jan 24 09:08
http://actionfps.com/players/ page
not useful any more, we should remove it and replace it with something different
but it was very useful at the beginning
@lucasgautheron I see 4 outstanding pull requests, planning to merge them at somepoint? :grinning:
just maybe not #111
oh I should merge some myself actually

ScalaWilliam Jan 24 09:16
hmm did I sound contradictory then Ketar?
I don't think so. We are putting focus on the game itself right now, because it's too much guesswork to know what'll be needed once the game is out there
goal is to have a game that is sustainable and attracts good people :smile:

ScalaWilliam Jan 24 10:26
in a way, we look at what the current situation is, and work on top of that. There's no single consistent answer imo

LionelVB Jan 24 14:53
@ScalaWilliam Could you share the google drive folder where you drawing the clan thing, to see what you have done?

ScalaWilliam Jan 24 15:29
https://drive.google.com/a/vynar.com/file/d/0B7BXpjZMKCAIb3RsS2c5SG94TVk/view
@LionelVB
next feature I think is most important now is having some sort of bulletin updates
to send messages out, especially to encourage formation of new clans and teams

ketarXVII 20:28
ok ty, enlighnting, in his own way.

ScalaWilliam 02:05
@/all I know what needs to be done
had a dream lol
big red button 'Play now' for unregistered users. Click that, opens a modal, modal shows: 1. Download the game 2. Download TeamSpeak 3. Join our TeamSpeak server (audio icon) 4. Join a server
Would include a screenshot, a video, whatever, whatever. We need a YouTube Video tutorial to show how to get in and communicate. It could be a brief introduction
now if I'm a new player I've no idea what anything means, and even if I do manage to download the game still I'm left clueless as to what it all is about

ScalaWilliam 02:11
Default download is for windows in the modal, Download page contains linux info
second, the download has to be 'verified secure'. No viruses, etc, etc.
I'll buy us an SSL certificate to make it appear more serious and reliable, it's quite important
this also means some links will be broken as it'll change from http to https. This will improve things massively
Then, the homepage needs cleaning up and 'all games' will have to go somewhere else
Then we need an Achievements charts page which would show a list of those who have completed major achievements
eg FURY just became Frag Master - so we have to have a hall of fame for these things
still missing are Clan Achievements, too, would belong in Hall of Fame
then we need a Clan Registration link in the Clans page, which would be a basic Google Form that would send LSD an e-mail (Lucas Sanzo Drakas)
A Bulletin/latest news item which would be fetched most likely from Tumblr or some place, based off content in our main spreadsheet.
almost like, Guides stuff
How to start a Clan
How to meet people
cause it's really about meeting people and playing with them, not just shooting random stuff
in that way we'll never be like QL where you open & shoot, it's much more organised

ScalaWilliam 02:16
so do you see how much work there is left to do, without even looking at the bigger picture - just to make what we have acceptable xD
now it is the HoF page that would contain all the achievement icons that DayliXx made
I've lots of work to do IRL so all I will do is talk
limited time resource, I'll be lead dev/dev manager
Parts of the site perhaps should be internationalised/localised. I had never done that on a serious site.
E.g. Play now in French and Brazilian
AF installer could as well do the TeamSpeak installation, & open TeamSpeak directly too
or add our server somehow

ScalaWilliam 02:22
bah I should stop coding for a living and do more of a mix xD
so 18 people in a channel, can we get some stuff done xD
I've already worked my arse off :>
my confidence in starting a proper gaming business is growing xD :D

ScalaWilliam 02:32
need also something to show that we have an active TS presence. List of players there. Available from homepage. 'players online' or sth
players who complete Capture Master, Flag Master, Cube Addict, Frag Master - the biggies, should get badges attached to their names everywhere on the site
like those things, I don't know what you call them, on his chest
 blob
blow their ego in front of everyone else
all what I said could be designed collaboratively on Realtimeboard
there's the idea part, which I did, then the analysis/design part which means seeing how it integrates into the current system, how it would look different visually
once you have that, work is described as an epic, one big task, could be in the github wiki
then gets split into tickets, tickets get estimated (see our waffle.io site), and you start working on it
implement a minimal concept, merge to master, keep on iterating : )
I hope this provides enough guidance for you all to make this game great :>
but really just need ActionFPS to be released on its own, which atm is Lucas's domain

ScalaWilliam 02:40
so yeah there's sooo much work that needs to be done immediately that I see no point working on 'ideas', but implementing what is quite important to get new players rolling in and understanding wtf is going on
too high a bounce rate :>

lucasgautheron 13:19
wow yeaah :D
hi from paris

ScalaWilliam 18:16
hey welcome :)

lucasgautheron 18:20
so much to do xD

ScalaWilliam 18:20
rofl ;D
yep

lucasgautheron 18:20
authentication nearly done (game & server part)

ScalaWilliam 18:20
that's why we need more devs

lucasgautheron 18:21
yep

ScalaWilliam 18:21
it's impossible to achieve on our own

lucasgautheron 18:31
how would you "recruit" people ?
IRC Bot has been updated : ActionFPS w00p|Lucas started an inter and is looking for players on aura 1999 (/connect aura.woop.ac 1999), 3 players online

ScalaWilliam 18:35
Cool gj
Well we need some more players
And finish up the essentials for communication
Then ask in public places, some people want to get programming experience
Imo most important bit ia
Is the new user flow. I'm a newbie and open this site. How and why do I end up playing the game?
Should optimise the living lights out of that.
