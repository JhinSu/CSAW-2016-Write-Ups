# CSAW CTF 2016 Quals: Eric_Zhi_Liang

**Category:** Recon
**Points:** 10
**Solves:** 42
**Description:**

We tried very hard to find Eric last year. You're going to have to try just as hard this year, since not even his friends can find him.

We heard Eric has his own subreddit. Can you find Eric for us?

## Write-up

Find the subreddit [r/ericliang](https://www.reddit.com/r/ericliang).

[theRealEricLiang](https://www.reddit.com/user/theRealEricLiang) is a moderator for the subreddit. Wading through his posts, he went to a [NYC Hackster Meetup](https://www.reddit.com/r/creativecoding/comments/51fas9/has_anyone_worked_with_the_intel_edison/). 

Looking for "nyc meetup hackster intel edison" on Google, the first result is a 
[Meetup event](http://www.meetup.com/Hackster-NYC/events/232881069/).

His Meetup event [profile](http://www.meetup.com/Hackster-NYC/members/175983362/) matches his name. 
His location is in Brooklyn and his account was made in Aug. 27th, 2016; just in time for CSAW'16.
His introduction says "I love fanfiction and Allen Lau!".

Allen Lau is a founder of Wattpad, which is a site where users can post their stories. 
After trying to find his profile and failing, I handed the reigns over to Janice who just typed in ericzhiliang as the user profile...
and boom the right [Eric Zhi Liang](https://www.wattpad.com/user/ericZhiLiang) was found, and so was the flag. The flag is on the left of his profile.


## Flag
`flag{i_readbear_fanfix}`
