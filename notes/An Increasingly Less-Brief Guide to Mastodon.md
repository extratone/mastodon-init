# An Increasingly Less-Brief Guide to [Mastodon][1]

<p style="text-align:center;"><h1>DON'T PANIC.</h1></p>

I've done my best to make this understandable, but you're welcome to suggest changes! If you have a Github account, you can submit change requests directly; otherwise, feel free to contact me [on Mastodon][2] or by email at `noelle AT noelle.codes`. 

When linking to this page, please use the link http://guidetomastodon.com, and please credit [@Noelle@elekk.xyz][3]. Thank you!

## Table of Contents

- [What is Mastodon?][4]
- [How is it like Twitter?][5]
- [How is it like email?][6]
- [How is it not like either of those; or, What are the Local and Federated Timelines?][7]
- [What is the Fediverse?][8]
- [How do I establish my brand's presence on Mastodon?][9]
- [How do I get verified on Mastodon?][10]
- [Okay, how do I let people know that I am who I say I am?][11]
- [HOW DO I PICK AN INSTANCE?][12]
- [How do I mention someone who's not on my instance?][13]
- [What are the rules?][14]
- [What if I see someone breaking the rules?][15]
- [What are the different kinds of posts?][16]
- [How do privacy settings work?][17]
- [How private is "Private"?][18]
- [What happens when someone follows me?][19]
- [So if I lock my account, only approved people can see my posts?][20]
- [What if someone's following or interacting with me and I don't want them to?][21]
- [How will I know if someone's muted or blocked me?][22]
- [What if I go over the character limit?][23]
- [What are hashtags?][24]
- [What does "CW" mean?][25]
- [I just attached a picture to my toot. What's with the new 'eye' icon?][26]
- [I just attached a picture to my toot. How can I add a caption to it?][27]
- [Why should I add a caption to my picture?][28]
- [How come my friend on another instance can use this emoji, but I can't?][29]
- [Why can't I search for a specific word or phrase?][30]
- [Why can't I quote someone's toot, like a quote-tweet?][31]
- [The Mastodon culture seems pretty weird?][32]
- [What does ![:redcandle:\](redcandle\*sm.png) mean?][image-1]
- [What's the generally-accepted Mastodon etiquette?][33]
- [I like mastodon but I prefer the way twitter looks.][34]
- [I like mastodon but I want to use it on my phone.][35]
- [How can I back up my Mastodon account?][36]
- [Can I use the keyboard to navigate Mastodon?][37]
- [How do favorites work on other server types?][38]
- [Weird, my server doesn't have a bunch of these features.][39]
- [Weird, my server has a bunch of extra features.][40]
- [I have other questions.][41]
- [How can I contribute to the Guide?][42]

## What is Mastodon?

Mastodon is Twitter-style social networking combined with email-style instanced servers. It's named after the metal band, but themed after the extinct megafauna.

## How is it like Twitter?

You post relatively-short status updates, and you can see a streaming list of your friends' status updates. You can keep notifications (replies, boosts, favorites, and DMs) in a separate column.

Mastodon's statuses are called "toots", like Twitter's are called "tweets". A toot can be up to 500 characters long.

Mastodon also supports hashtags, which are words prefixed by #, like "#gaming" or "#pineapple". You can click on a hashtag to search for other posts containing that tag.

## How is it like email?

Each Mastodon instance is independent but networked, like email servers. If you sign up for an email account on gmail.com, you don't automatically have an account on hotmail.com or aol.com, but you can send and receive messages to and from users on hotmail.com and aol.com. 

Likewise, if you sign up for an account on mastodon.social, that doesn't make an account for you on every other instance, but you can talk to users from other instances and they can talk to you. 

You can make accounts on multiple instances if you want to talk about different things separately. You could have an account on https://cybre.space to talk about technology, an account on https://elekk.xyz to talk about gaming, and an account on https://mastodon.social for general chatter. You have to sign into each account separately and keep each open in a separate browser tab or window.

Keep in mind that in general, when talking about Mastodon, "instance" and "server" mean the same thing.

## How is it not like either of those; or, What are the Local and Federated Timelines?

Mastodon has two additional timelines that you can view: the Local timeline and the Federated timeline.

The Local timeline is every post with a public status posted by users on your instance, with the exception of replies. (A reply is any toot posted in response to another toot - NOT any toot that simply mentions another user!)

The Federated timeline is every post with a public status posted by any user that your instance knows about, even from other instances. Your instance knows about a remote user if at least one user on your instance has EVER followed them.

The Local and Federated timelines can turn into firehoses sometimes. Be careful!

## What is the Fediverse?

\~\~Unfortunately, no one can be told what the Fediverse is\~\~

The Fediverse is the vast array of servers that communicate via the ActivityPub or OStatus protocols. (Generally speaking, unless you're making or editing software to interact with the fediverse, you don't need to know what those are.) There are lots of different kinds of server software on the fediverse, like Pixelfed, Pleroma, Misskey, or WriteFreely. Mastodon is one of the most popular of these, and it's what this guide is about. If you're using one of the others, this guide probably won't help you much.

## How do I establish my brand's presence on Mastodon?

The short answer: **Very carefully.**

We've had a decade of Twitter, Facebook, and heaven knows how many other social media platforms becoming platforms for Search Engine Optimization, Brand Awareness, and Corporate Synergy, and I'll be blunt: we're really, really tired of it.

Mastodon isn't about leveraging followers into customers. It's not about SEO or brand loyalty. \**Mastodon is about people.*- Don't treat people like potential customers who might buy your stuff; treat them like \*people- whom you might want to get to know.

If you're a person who makes or does something and you think someone might want to buy your product or use your service, great! You can tell people about it - just *treat them like people*, not marketing targets.

There's one behavior that companies often engage in that drives people nuts, and you *really- shouldn't do it: **don't send unsolicited messages to people advertising your product or service**. Get to know someone, engage in conversations with them, and if you think someone you know would be interested and doesn't already know about what you do, *then- tell them about what you do or what you make.

If you represent a company and your boss has told you that your company needs a Mastodon presence, here's what you can tell them (and you can tell them I told you to say it):

> Mastodon doesn't really work like that. If we're going to have a Mastodon presence, it needs to be one person who's free to \*be- a person on that account, instead of a corporate mouthpiece. That means the person on the Mastodon account isn't going to get along with everybody (although they should certainly try to) and is going to treat other users like they're people instead of marketing targets. If you're okay with that, then I'll get right on it. If not, then you need to do some more research into Mastodon before you establish a presence there.

## How do I get verified on Mastodon?

There's no such thing as a verified account on Mastodon. We assume you are who you say you are. If you see someone with a checkmark by their name (like ✅), they've just typed that emoji into their display name. 

If someone's impersonating you, contact the admin of the instance they're on to get it sorted out.

## Okay, how do I let people know that I am who I say I am?

Mastodon instances will allow you to add metadata to your profile - up to four items displayed in a table on your profile page that don't count against the length of your profile text. If you use these fields to link to your other websites, some instances will allow you to verify that you \*own- those websites by providing a link on those websites back to your Mastodon account. For instance, if you have a personal website, you can include the link to your website in your Mastodon metadata, and then include a link to your Mastodon account in the header of your website, and Mastodon will verify that you're the person who owns your website.

A Mastodon instance that allows this will have instructions on your \**Edit Profile*- page telling you how to add the verification link.

# HOW DO I PICK AN INSTANCE?

This one's big on purpose.

Picking an instance can be hard. Many instances have a specific focus: `mastodon.lol` is a safe space for queer folks, `hackers.town` is a haven for computer touchers, `wandering.shop` is built for fans of science fiction and fantasy, and `botsin.space` focuses on the hosting and development of automated bots. On `oulipo.social` it's illicit to post a toot containing any "e"s. 

If you haven't created a mastodon account yet, you might find it useful to try one of the larger instances, like `mastodon.social` - the flagship instance, with over 100,000 users - or `mas.to` . These instances have large, usually-friendly populations that will help you find a more niche instance if that's what you're looking for. Be warned, though, that because of their size, the Local timelines on these instances can move \*very- quickly.

(*A brief note about mastodon.social: it **is*- the largest general-purpose instance (the largest overall is a Japanese-language instance, [mstdn.jp][43]). Many people go there and never check out other instances. If you make an account on mastodon.social, consider treating it as a temporary waypoint while you find an instance that better fits your needs and interests. Once you've found one, you can export all the people you're following, muting, and blocking on mastodon.social and import them at your new account, so you don't have to go around and find everybody again.\*)

If you've already registered on an instance but you're not sure if it's a good fit for you, try asking around for instances where you might be a better fit. Also, try searching for a #hashtag that interests you; if you see a lot of people on one instance talking about that subject, it might be a good place for you to check out.

You can also try the instance picker on [joinmastodon.org][44] or the wizard at [instances.social][45], although these have \*lots- of instances listed and you might be overwhelmed. Take it slow and easy.

## How do I mention someone who's not on my instance?

Mastodon usernames take the form @*username*@*instance*. My account on mastodon.social is @<span>noelle</span>@mastodon.social; my account on elekk.xyz is @<span>noelle</span>@elekk.xyz. If you're mentioning someone on a different instance, you have to type the whole thing (although the toot input box will help you auto-complete the username if it's a name the instance knows already). 

If you're mentioning someone on your own instance, you just have to type the first part; if you're on elekk.xyz, @noelle will get to me just like @<span>noelle</span>@elekk.xyz will. If you leave off the "@*instance*" Mastodon understands that you want to talk to the local user.

## What are the rules?

The rules depend on which instance you're on. Each instance has a page at https://<span>*instance*</span>/about/more that usually contains more information about the instance and often describes the community guidelines. For example, mastodon.social has its community guidelines posted at https://mastodon.social/about/more .

Keep in mind that these are usually guidelines and not hard-and-fast rules. Since each instance is run by a separate team of moderators - often just one person! - they have the final say over what's allowed and not allowed on their instance. Your instance admins might even go so far as to block an entire other instance if their users turn out to be incompatible with your instance's values and the other instance's moderators won't help.

## What if I see someone breaking the rules?

If you see someone breaking the rules, you can send a report. Click on the `...` under the offending post, and select `Report @user` (which is usually at the very bottom of that menu). This will bring up a window where you can select additional recent posts from that user, if you need to, and also type out a \*reason- for the report, so that the moderator who receives the report will understand why you sent it. 

If the user is from a different instance, then underneath the report reason, you will also see a switch next to "Forward to *their instance*". This not only reports the user to the moderators on your instance, it sends the report to the other user's instance as well. Before you do this, **check the rules of the instance they're on**. They may not be breaking their local rules.

**The moderators and administrators of *your- instance will be able to see that it was you who sent the report. If you forward the report to a remote user's instance, the moderators and administrators of that instance *will not- be able to see who sent the report — only that it came from your instance.**

By default, you will not get any notification about actions that any moderators or administrators take in response to your reports. You can ask them, but be prepared to hear something like "we don't comment on how we resolve reports".

## What are the different kinds of posts?

Mastodon (and other fediverse) posts can be chained together in different ways. I use three terms to refer to different kinds of posts. These might not be the terms other people use.

- \**Stand-alone posts*- are posts that are not replies to any other post. (That is, you did not click on the Reply button to start the post.) They are at the head of a chain. You can include people's usernames in stand-alone posts to tag them; doing that does not make the post a reply. \**For example:*- You use the standard compose box ("What's on your mind?" in the default Mastodon settings) to create a new post.
- **Self-replies*- are posts that are a direct reply to *one of your own- stand-alone posts or another self-reply. Again, they can include references to another person. You can continue to reply to your own posts as long as you like, and *as long as someone else's post isn't above what you're currently writing in the chain*, they'll continue being self-replies. **For example:*- You click on the reply button on one of your own stand-alone posts to reply to yourself, then click on the reply button on *that- post to reply to yourself again.
- **Replies*- are posts that are replies to someone else *or replies to a reply to someone else*. **For example:*- You click on the reply button on someone else's post to reply to them, **or\*- you click on the reply button on one of your own posts that's a reply to someone else's post.

I've included a diagram [here][46] (it's a link because it's big). Notice how as soon as someone else's post enters the chain, your replies stop being self-replies. This is important, because self-replies and replies work differently in your followers' timelines.

## How do privacy settings work?

Under each post, you'll see three icons: a camera, a globe or a padlock, and the letters "CW". Click on the globe or padlock to choose the privacy settings for your post. *You can set the default privacy level for your posts under **Preferences \> Other \> Posting Privacy**.*

- \**Public*- means that everyone can see your post. It will appear on your list of posts and in your followers' Home timelines. Your *stand-alone posts- and *self-replies- that are public will appear in your list of toots, in your followers' Home timelines, in the public local and federated timelines, and in the Mentions of anyone you mention by username. Your *replies- that are public will appear in your list of *toots and replies- (*not- the primary list of toots; it's a separate list!), in the Home timelines of any of your followers who *also- follow the person you're replying to, and in the Mentions of anyone you mention by username.
- \**Unlisted*- means that everyone can see your post, but it won't appear on the public timelines - either Local or Federated. Other than that, Unlisted posts behave exactly like Public posts.
- **Followers-Only*- means that only people who follow you and people mentioned in the post can see your post in their timelines or on your profile page. If someone who doesn't follow you views your profile, they won't see your followers-only posts. *For your followers\*, followers-only posts behave exactly like Unlisted posts. **Your followers-only posts that mention another user will also appear in that user's mentions, even if they don't follow you!\*\*
- \**Private*- means that only people who are mentioned in your post can see it. It will appear in their mentions and, on Mastodon servers above version 3.0, will appear in their Direct Messages column.

Keep in mind that some servers, which run software that's compatible with but not the same as Mastodon, will ignore these privacy settings if you send a message to their users, so be careful!

## How private is "Private"?

I cannot stress this enough: **Private toots are not encrypted or secure.**

The admin of your server may be able to read *any- toot posted on their server, as well as *any- toot sent to a user on their server. **However**, it's a pain in the ass to do so. Your private posts will not appear in the admin panel on the website; your admin has to manually, directly access the database -- typically through logging into the server's command line -- in order to access them. This isn't something admins do on a whim; they only do it when they absolutely have to, and this is because:

This is a necessary security precaution. Admins *don't want- to read your private toots, but they have to be *able- to because otherwise private toots allow some users to secretly harass others or to conduct illegal dealings without the admin's knowledge, and under many laws the admin will be responsible for enabling the harassment or illegal behavior *even if they didn't know it was happening*.

That said, in general, your admin will only look over the toots you've marked Private if they have reason to believe harassment or illicit dealings are going on. Make sure you trust your admin to act like this, and if you don't, it might be time to look for another instance.

While we're on the subject, it's worth noting that this is true of nearly any social media software. Twitter admins can read your DMs. Forum admins can read your private messages. This is not a novel or unusual feature of Mastodon; I'm just making sure you know about it.

**As a general rule, if an application you're using isn't [peer-to-peer][47] and relies on an intermediary like a server, the information you're sending isn't secure unless you take extra steps outside the application to secure it.**

## What happens when someone follows me?

\~\~If someone follows you, you incur a life debt to that person. You will be required to lay down your life for that person when they need it. Once you've done so, they will unfollow you and, if you survived, you are free to go about your life normally.\~\~

Just kidding.

If someone follows you, they will see your posts on their Home timeline and they will be able to see your followers-only posts. If you want, you can limit the people who can follow you by clicking on **Edit profile\*- and selecting **Lock account\*\*, which will allow you to manually approve and reject people who want to follow you.

## So if I lock my account, only approved people can see my posts?

Yes and no.

With a locked account, you get to approve who can follow you *through the Mastodon interface*. This means that only the people you approve will be able to see your **followers-only*- posts. Your **unlisted*- posts will still show up on your profile, and your **public\*- posts will still show up on your profile and on the local and federated timelines.

**However.**

Every Mastodon account (on an unmodified server) also creates an RSS feed of their public and unlisted posts - i.e. the posts that appear on the account's profile. It does not include followers-only toots or direct messages, and if you've [put a CW on a toot][48], only the CW appears in the RSS feed, not what's underneath it. 

Your RSS feed appears at `https://<your-server>/users/<your-username>.rss` ; for example, since I'm `https://elekk.xyz/@noelle`, my RSS feed is `https://elekk.xyz/users/noelle.rss` . (Remember to remove the `@`!)

\**Anyone can subscribe to these feeds using an RSS reader to see your public and unlisted posts when you post them.*- You can't control who can see these feeds, but they do not (and, by design, cannot) contain your followers-only or private toots. *If you only post followers-only toots, your RSS feed will be empty.*

Remember, you can set the default privacy level for your posts under **Preferences \> Other \> Posting Privacy**. If you have a locked account, you might prefer to set that default to followers-only so you have to make an active effort to post an unlisted or public toot.

## What if someone's following or interacting with me and I don't want them to?

You have a couple options.

- **If you just don't want to see them in your feed anymore**, you can \*mute- them. This will prevent their posts from showing up in any of your feeds; you can optionally block notifications (Favorites, Boosts, and Mentions) from them, so that if you don't want to see someone's stand-alone posts but do want to see their attempts to interact with you, you can.
- **If you don't want to see them and you don't want them to see you**, you can *block- them. This will automatically mute them; if they were following you and/or you were following them, it will sever those as well. They will not be able to follow you or show up in *any- of your feeds unless you unblock them. (But see below.)
- **If they are harassing you or otherwise breaking the rules**, you can [report them][49], and hopefully, your moderator will deal with it.

All three of these options are available by clicking the `...` under one of the user's toots or on their profile inside the Mastodon web interface.

**However.**

Just like with a [locked account][50], any user — even ones you've blocked or that have been suspended by a moderator — can go to your public page or your RSS feed to view your public and unlisted toots. There is not a good way around this, unfortunately, except to make all of your toots followers-only.

## How will I know if someone's muted or blocked me?

You will not get a notification if someone mutes or blocks you.

If someone's muted you, there's really no way for you to tell. If they consistently don't reply to you when you mention their username, you might get suspicious, but Mastodon deliberately makes it almost impossible to know if you've been muted. (Among other things, this is a stopgap to try to prevent someone harassing you by creating multiple accounts to get around mutes.)

If someone's blocked you, you will no longer be following them, their posts won't appear in your feed, and when you view their account profile *within Mastodon's web interface*, none of their posts will load. (It is worth noting that if you're looking at the profile of someone you *don't- follow, sometimes their posts won't load and it's just because the server is being slow, not because they've blocked you, so don't be *too- quick to make an assumption.)

If someone has blocked you, you *can- still go to their public page and see their public and unlisted toots; public profiles don't require authentication (i.e. you don't have to be signed into that instance to view them) and so they can't tell who you are or that the user has blocked you. **That said**, let's be honest. If someone's blocked you, they don't want you around. You *can- keep reading their public and unlisted posts, but maybe don't? In a substantial way you're invading their privacy and deliberately crossing a boundary they've set up, and "the software allows me to, so it must be okay" is a pretty flimsy justification. Just leave them alone, please.

## What if I go over the character limit?

Don't worry. First, you can't; Mastodon won't let you post a toot over the instance's character limit. You won't get in trouble or anything.

If you find that what you want to say is too long for a single toot, or if you think of something else after you've posted a toot, you can *reply to your own toot*. Mastodon supports toot threads, so you can toot as many times as you want to, replying to each toot in sequence, and the whole series will show up when someone clicks on any of the toots in the thread.

So if your toot is too long, just split it up and make the second half a reply to the first; if you think of something else later, just reply to your original toot and the reply will show up whenever anyone clicks on the original toot.

## What are hashtags?

To make a hashtag, type "#" and then any number of letters or numbers. Accents count; punctuation, spaces, symbols, and emoji don't. #howismydaygoing is a valid hashtag; #höwísmydàygôíng is valid; #how-is-my-day-going isn't (it'll just catch #how).

A hashtag is metadata about your toot: it provides additional information that doesn't necessarily belong in the body of the toot, but is useful for understanding. If you're a programmer, it's sort of like a code comment.

As a bonus†, hashtags are tracked by each instance. Clicking on a hashtag takes you to a list of public posts with that hashtag. You can use them to track #politics, check out the users people are recommending on #FollowFriday, or see people's artwork using #mastoart.

Don't go overboard with hashtags. As a guideline, your hashtags probably shouldn't be more than 10% of the total length of your toot. If you find yourself going over that, you might be spreading things a bit too thin.

† *This was actually the original intent of hashtags, but the usage has moved on since then.*

## What does "CW" mean?

CW stands for Content Warning. It hides your post behind text (which you get to choose); it's like a Read More link.

You might use CWs for:

- Politics
- Sex
- Gross topics
- Common phobias, like spiders or blood
- Health discussions
- Punchlines to jokes
- Long posts that might otherwise fill up people's timelines
- Commentary on discussions that are going on elsewhere in the fediverse, often with the CW "meta" or "discourse"

Some common abbreviations you'll find in CWs are:

- mh: mental health
- ph: physical health
- alc: alcohol
- pol: politics, sometimes plus locale, like "uspol" means United States politics
- pda: public display of affection
- nsfw: not safe for work
- ec: eye contact, usually used when there's a photograph attached

In general, just use your best judgment; think "is there a reason someone might not want to see this?". You have the opportunity to take an extra moment and make the fediverse a nicer place for people to be. Why wouldn't you take that opportunity?

\**An important note:*- Mastodon *does not- track hashtags that are in the text of a CW. Mastodon *does- track hashtags that are \*under- a CW. Always put your hashtags in the body of your toot, never in the content warning.

## I just attached a picture to my toot. What's with the new 'eye' icon?

Clicking that will hide your image behind a "Sensitive content" overlay. This is good for nudity, gore and violence, political topics, etc.

You'll notice that if you have both an image and a CW on a toot, the "Sensitive content" overlay is turned on automatically and can't be turned off. That's on purpose.

## I just attached a picture to my toot. How can I add a caption to it?

When you attach an image, you'll see "Edit" (plus a pencil icon) at the top right of the image. Clicking this will pop up a dialog box that lets you determine what part of the image should show in the preview; it also allows you to set alt-text for the image, which people can read if they mouse over the text, and which screen-readers (such as for the visually-impaired) can read instead of just saying "embedded image".

Text in the description box has its own character limit of 1,500 characters; it \**does not*- count against the character limit for your toot!

## Why should I add a caption to my picture?

In a word: Accessibility. 

Some people who use Mastodon are visually impaired and use screen readers. Some people who use Mastodon have images turned off to conserve their data usage. Sometimes disk errors or server errors happen, or your admin decides to prune old files, and your image just doesn't load anymore. Captioning an image allows people in these conditions to participate in your toots with full context.

You can also use image captions to insert additional jokes (like webcomics often do) or additional commentary on the image. Take advantage of the fact that image descriptions have their own separate character limit and put whatever you like in there. The sky's the limit.

## How come my friend on another instance can use this emoji, but I can't?

Each instance can define custom emoji for their users to use, and many have taken advantage of this. Your instance admin can copy emoji that they like from other instances. If you see an emoji that you like and it's not available on your instance, ask your admin to copy it over.

## Why can't I search for a specific word or phrase?

It's an anti-harassment feature. Harassers often search for particular words or phrases (like "TERF" or "homophobic" or "white supremacy") in order to attack and dogpile people they disagree with. By limiting search to usernames and hashtags, Mastodon allows users to decide how they want their toots to show up in others' searches. (While some Mastodon instances \*do- allow full-text search, you can only search your own toots on those instances. This makes it easier to find something that you posted a while ago without exposing you to harassment.)

## Why can't I quote someone's toot, like a quote-tweet?

Like search, it's an anti-harassment feature. If you want to reply to someone's toot, you have to actually reply to it; you can't just broadcast it to your followers with a snarky comment.

*(Don't try to get around this by screencapping toots and attaching them as images. You **can*- do it, but the Mastodon community tends to frown on it and you'll get a bad reputation pretty quickly if you keep it up.)\*

## The Mastodon culture seems pretty weird?

It can be! But it gets to be a comfortable weirdness.

Here are some common weirdnesses:

- :pineapple\:: nobody really knows. [acw][51] posted it, someone else picked it up, and it's been going ever since. It's just silliness. When in doubt, just post a :pineapple:.
- AWOO: [Awoo.Space][52] was one of the earlier Mastodon instances. "Awoo" is the sound of a wolf howling. It's fun to say. Awoo! (Pawoo.net has nothing to do with this; in Japanese, "pawoo" is the sound of an elephant trumpeting.) Someone got irritated at the awoos and instituted a $350 fine for awooing. Nobody's ever actually paid it, don't worry.
# - gameing: There was (and still is) a perception that #gaming is "hardcore" and elitist, and there were (and are) worries about certain breeds of gamer overrunning the #gaming hashtag. #gameing was a pre-emptive strike; it's about a fun, lighthearted, and accessible approach to games, video and otherwise.
- IT'S BEEN/SOME as CWs: a reference to the Barenaked Ladies song [*One Week*][53] and the Smash Mouth song [*All Star*][54] respectively. A common meme on Mastodon is to put the first word or two of the song into the CW and then subvert expectations by posting something else under the cut.

You'll get used to it.

## What does ![:red*candle:](red*candle.png) mean?

In early November 2017 we lost a popular Mastodonian to suicide. ![:red*candle:](red*candle\*sm.png) and ![lattentacle][image-2] commemorate our friend Natalie Nguyen.

## What's the generally-accepted Mastodon etiquette?

There are no hard-and-fast rules for everybody, and (as noted above) different instances have different guidelines. That said, many people follow some simple guidelines meant to make Mastodon a friendlier place for everybody.

- If you attach an image to your toot but don't describe it in the toot, use [alt text][55] to describe the image so that people using screen readers can understand it.
- If you attach an image that contains **nudity, porn or sexually-suggestive content, gore, violence, or politics**, or any of a number of common PTSD/anxiety triggers (such as food, spiders, etc.), [mark it sensitive][56].
- If the \*text- of your toot contains any of those subjects, [use a content warning][57].
- You don't need to use a URL shortener. Mastodon assumes that all URLs are exactly 20 characters long. Let people see what you're actually linking to.
- If you make a bot that posts automatically, have it post using the [unlisted privacy setting][58]. This avoids having your bot flagged as spam.
- If you use a script that cross-posts your Twitter tweets to Mastodon, have the script set to use a CW. This avoids sensitive topics (see above) being cross-posted to Mastodon.
- If you see a conversation and have a comment you'd like to add:
	- Click through to the full conversation and make sure your thought hasn't already been expressed by someone else. 
	- Make sure that your comment adheres to the tone of the conversation, is kind to the other posters in the conversation, and gives the other posters the benefit of the doubt.
- "noadvice", as a hashtag or a CW, indicates that the user is just venting and is not looking for help or suggestions. Sympathy and comfort are welcome, though.
- Remember that if someone doesn't reply to you, that doesn't mean they're ignoring you. They might be away from Mastodon; they might have so many notifications that they missed your post; they might have muted the conversation, so your reply didn't even show up! There are many reasons for someone to miss a toot, even one directed at them; don't take it personally.

## I like Mastodon but I prefer the way Twitter looks.

You might get some mileage out of [Pinafore][59], an interface for Mastodon by [Nolan Lawson][60].

[Halcyon][61] is a web client for Mastodon that replicates the Twitter interface. Since Halcyon is itself open-source software, there are [multiple servers running it][62]; you can choose the one you like. Use your existing Mastodon login when you use Halcyon; for example, if you have an account on elekk.xyz, you would use `your-account@elekk.xyz` and your Elekk password to log in.

Remember that Pinafore and Halcyon are third-party clients, and make sure you trust them before you give them your login information!

## I like Mastodon but I want to use it on my phone.

Mastodon has a responsive design, so you can use it in your phone's browser. Alternately, there are many apps available for Mastodon, including an official "Mastodon for iPhone" app released in August 2021. On iOS, try [Toot!][63]. On Android, try [Tusky][64].

*(NB: I've been told that "Tootdon silently forwards copies of posts you interact as well as the auth token to your account to its to own servers." I don't know if that still holds. As always, be cautious when giving apps your information.)*

## How can I back up my Mastodon account?

[Alex Schroeder][65] has an excellent [Mastodon Archiver][66] that will help you back up your account and much more.

## Can I use the keyboard to navigate Mastodon?

In the web interface, yes. The Mastodon web hotkeys are documented at `https://<your-server>/web/keyboard-shortcuts` , which you can access when you're logged into the web interface. (You can find the link at the bottom of the \**Getting Started*- column, labeled "Hotkeys".)

## How do favorites work on other server types?

In general:

- If you click 'favorite' on a post from a different server type (Misskey, Pleroma, GNU Social, etc.) it will federate properly. Some of these servers allow multiple response emoji, and each of them selects a generic "favorite" emoji, which will show up on the recipient's post.
- If someone on a different server type selects an emoji to respond to your post, it will federate to you on Mastodon as a favorite, *no matter what the emoji is*.

## Weird, my server doesn't have a bunch of these features.

You might not be on Mastodon! The Fediverse - the vast collection of servers connected by the ActivityPub/OStatus protocol - has a lot of different kinds of servers on it. Your server might be running Pleroma, Misskey, GNU Social, or something else! Unfortunately, I don't know much about them, so you'll have to ask their users for a getting-started guide like this one.

## Weird, my server has a bunch of extra features.

Because [Mastodon is open source][67], you can make a copy of it and make any changes you want. Some people have decided to make their changes public; one of the most popular edited versions of Mastodon is [Mastodon Glitch Edition][68], or "glitch-soc". (It's called that, as far as I know, because it originated with the instance [glitch.social][69]. Glitch-soc has a bunch of extra features that users often appreciate, like the ability to use Markdown in toots and the option to make a given post only show up on your local instance and not get federated out to other servers.

## I have other questions.

Ask around! People are usually pretty happy to answer questions and help out. Also, [FediThing][70] has [an excellent website][71] that covers the Fediverse from a different perspective, and you might find your answer there.

If you really get stuck, ask me: https://elekk.xyz/@noelle

## How can I contribute to the Guide?

Please check out [the contributions guide][72]!

[1]:	https://joinmastodon.org
[2]:	https://elekk.xyz/@noelle
[3]:	https://elekk.xyz/@noelle
[4]:	#what-is-mastodon
[5]:	#how-is-it-like-twitter
[6]:	#how-is-it-like-email
[7]:	#how-is-it-not-like-either-of-those-or-what-are-the-local-and-federated-timelines
[8]:	#what-is-the-fediverse
[9]:	#how-do-i-establish-my-brands-presence-on-mastodon
[10]:	#how-do-i-get-verified-on-mastodon
[11]:	#okay-how-do-i-let-people-know-that-i-am-who-i-say-i-am
[12]:	#how-do-i-pick-an-instance
[13]:	#how-do-i-mention-someone-whos-not-on-my-instance
[14]:	#what-are-the-rules
[15]:	#what-if-i-see-someone-breaking-the-rules
[16]:	#what-are-the-different-kinds-of-posts
[17]:	#how-do-privacy-settings-work
[18]:	#how-private-is-private
[19]:	#what-happens-when-someone-follows-me
[20]:	#so-if-i-lock-my-account-only-approved-people-can-see-my-posts
[21]:	#what-if-someones-following-or-interacting-with-me-and-i-dont-want-them-to
[22]:	#how-will-I-know-if-someones-muted-or-blocked-me
[23]:	#what-if-i-go-over-the-character-limit
[24]:	#what-are-hashtags
[25]:	#what-does-cw-mean
[26]:	#i-just-attached-a-picture-to-my-toot-whats-with-the-new-eye-icon
[27]:	#i-just-attached-a-picture-to-my-toot-how-can-i-add-a-caption-to-it
[28]:	#why-should-i-add-a-caption-to-my-picture
[29]:	#how-come-my-friend-on-another-instance-can-use-this-emoji-but-i-cant
[30]:	#why-cant-i-search-for-a-specific-word-or-phrase
[31]:	#why-cant-i-quote-someones-toot-like-a-quote-tweet
[32]:	#the-mastodon-culture-seems-pretty-weird
[33]:	#whats-the-generally-accepted-mastodon-etiquette
[34]:	#i-like-mastodon-but-i-prefer-the-way-twitter-looks
[35]:	#i-like-mastodon-but-i-want-to-use-it-on-my-phone
[36]:	#how-can-i-back-up-my-mastodon-account
[37]:	#can-i-use-the-keyboard-to-navigate-mastodon
[38]:	#how-do-favorites-work-on-other-server-types
[39]:	#weird-my-server-doesnt-have-a-bunch-of-these-features
[40]:	#weird-my-server-has-a-bunch-of-extra-features
[41]:	#i-have-other-questions
[42]:	#how-can-i-contribute-to-the-guide
[43]:	https://mstdn.jp
[44]:	https://joinmastodon.org/communities
[45]:	https://instances.social/
[46]:	replies.png
[47]:	https://en.wikipedia.org/wiki/Peer-to-peer
[48]:	#what-does-cw-mean
[49]:	#what-if-i-see-someone-breaking-the-rules
[50]:	#so-if-i-lock-my-account-only-approved-people-can-see-my-posts
[51]:	https://cybre.space/@acw
[52]:	https://awoo.space
[53]:	https://www.youtube.com/watch?v=fC*q9KPczAg
[54]:	https://www.youtube.com/watch?v=L*jWHffIx5E
[55]:	#i-just-attached-a-picture-to-my-toot-how-can-i-make-sure-its-accessible
[56]:	#i-just-attached-a-picture-to-my-toot-whats-with-the-new-eye-icon
[57]:	#what-does-cw-mean
[58]:	#how-do-privacy-settings-work
[59]:	https://pinafore.social/
[60]:	https://toot.cafe/@nolan
[61]:	https://notabug.org/halcyon-suite/halcyon
[62]:	https://notabug.org/halcyon-suite/halcyon#instances
[63]:	https://apps.apple.com/app/toot/id1229021451?ls=1
[64]:	https://tusky.app/
[65]:	https://octodon.social/@kensanata
[66]:	https://github.com/kensanata/mastodon-backup/
[67]:	https://github.com/mastodon/mastodon
[68]:	https://glitch-soc.github.io/docs/
[69]:	https://glitch.social
[70]:	https://tech.lgbt/@FediThing
[71]:	https://fedi.tips/
[72]:	contributing.md

[image-1]:	#what-does--mean
[image-2]:	lattentacle*sm.png

#mastodon #guide #documentation