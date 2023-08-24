>> Recording is on.
>> Okay. Hey, Bill, is that your hand or just randomly clicking?
I've got a presentation.
I'd like to -- some slides I'd like to go through.
Let me -- I'm going to try to do a thing here
where I've only done this a couple times.
I can share this with folks so that you can follow along on your own browser.
So let me try to do that real quick.
This also is inside this document.
I'm not sharing my -- yeah, I am sharing my screen.
Links are a little bit hard to click on the left.
so links are easier to click on the right.
You can go here and get to the slides.
Let me spend a couple secs to try to present this
also with a link.
I think I'd do this.
And this.
And this.
Except that didn't give me the link.
Ah, here you go.
Okay, so for those of you who aren't overwhelmed, I think if you click that link, you can watch
the presentation.
Maybe you can make Jitsi kind of small on one side and the presentation small on the
other side, and then you can kind of also have a little bigger desktop.
Okay, let's go for it.
So welcome to Markdown on Git for Collaborative Writing.
The way I was going to do this session, let's go for an hour.
I'm going to start off doing most of the talking, kind of presenting, going through stuff.
The idea of this session for me is mostly just to kind of present the idea of what we
could accomplish and not learn too much about the tools, things like that, the pitfalls.
So then the last 15 minutes of the call or so we'll spend talking about what we could
do next, whether it makes sense to get together again.
I would love to kind of continue to work on this project.
We could do that a bunch of different ways.
So let's see.
Down here in the lower right corner, you'll see this session is sponsored by Path Shift
People, purveyors of fine educational materials for AI and other things.
Path Shift People is essentially kind of an OGM startup, or a startup of OGMers.
It's me and Mathew Lowry and Wendy Elford.
Some of you know those folks.
The main thing that we're teaching right now is ChatGBT.
I'm going to start teaching some mid-journey and image synthesis.
We sell those courses for money to businesses, and doing that helps support our work in making
things like this free.
This material is going to end up getting open sourced somehow.
I'm not exactly sure how.
We'll see.
The things that I want to cover today is what you see is what you get versus markup.
And then talk about markdown.
And then talk about Git.
And then GitHub.
I've got a placeholder here for MassiveWiki.
I don't think I got the slide in there yet.
And then a little bit on tools.
So the goal of this session, and I don't have this on the presentation, the goal of this
session is just to kind of get our art oriented to where we are, what we could do.
My -- I'm going to go to my shared screen here real quick.
This is the -- by the way, this is the community that is hosted by Passive People.
And we've got a little space here called Markdown Git for Collaborative Writing.
It looks like this.
You can post things.
People can reply.
Stuff like that.
The choices for us continuing to collaborate are kind of a mailing list, chat system, or
maybe this forum.
I'm okay with any of those.
and we can kind of see who lands where.
We have another system called Mattermost chat system,
which would be a great place to land.
We might also end up with a set of shared Markdown files
that we can collaborate on too,
but we kind of need a way to message each other.
So this is a start.
I wanted to, I think that I posted,
or the thing that kicked this off
was me posting this kind of ranty thing to the OGM list.
Ray, thank you, picked this up recently and said, hey, Pete,
I would like to do that.
So there's a thing that software developers do.
And I kind of talk about this down here.
Software developers use text and Git
to successfully collaborate at high speed.
And I think that's true--
that could be true for writers, too.
I think there's some stuff to learn,
and there's some shoulder to the grindstone kinds of things
that you need to do.
But it's fairly mechanical, and you
can kind of unlock a lot of collaboration potential
by using the same tools that software developers use.
So that's kind of the preamble.
The goal of this session is to kind of go
through the moving parts of that so that we can decide,
yeah, that sounds like we should keep going,
or hey, this is too complicated and too involved.
I don't want to participate anymore.
I'm interested in continuing.
So with that, let's talk a little bit about WYSIWYG
and Markup Language.
If you're editing text, most people
in the world who are using a computer
know something like Microsoft Word.
It looks kind of like this thing on the left.
There's a place where you can edit your text.
And there's maybe a toolbar and stuff.
When you're editing the text, it looks exactly
like if you printed it out.
So, and if you want, you know, you can have headers,
you can have paragraphs, you can have bullet lists,
you can have tables and pictures.
When you wanna make a change to something,
you see exactly what it looks like all the time.
What you see is what you get.
So examples of this are Microsoft Word,
Apple Pages, Google Docs.
There's a different paradigm,
and it's not better or worse, it's just kind of different.
There's a different paradigm where instead of having the way it looks present at the
same time you're editing, you can abstract the way it looks a little bit into a few characters
of instructions to the computer, basically.
So you end up editing something that is all just like very plain text.
You can't see any of the fancy stuff in here
unless you actually kind of parse with your eyes
what's going on.
And then either automatically all the time continuously
or you push a button or something,
something happens that takes this text version of it
and hydrates it or turns it, you know,
flushes it out into the thing that looks a lot
like the WYSIWYG thing.
So I haven't talked about this in a long time.
When we first-- this markup language stuff,
it can be different languages.
The one we're talking about today
is going to be Markdown, which is a clever take on markup.
The wiki text, back in the days of wikis,
it was a very similar kind of formatting thing.
And there's other fancier things.
You can do full-on typesetting.
Back in the early 80s, I did full-on typesetting
for a newsletter with something very similar to this
with more instructions.
So I think there's a big conceptual thing
that goes on here.
This isn't a straightforward thing for a lot of people.
And I used to think that there were
people who kind of got this and people who didn't.
And now I don't think that's true anymore.
I think it just takes slowing down and thinking about it a little bit.
So you mean if I'm typing text and I want it to be bold, I have to add a little bit
of instruction for the computer?
Okay.
And then, oh, you mean that if I want this to actually see what it looks like or especially
give this to somebody else, I have to push this button and make it happen someplace?
Okay.
So that's the deal.
We're talking about a system where you're typing text, the text is all very plain, and
you add a few characters here and there to make it look fancy, but you can't see it looking
fancy until you push the button.
Nowadays, so HackMD, if you play around with HackMD a little bit, you'll see that it's
got two panes, and this is very common.
There's the pane where you're typing stuff, and it looks like that plain text.
the pain where in real time it's rendered like it's supposed to look.
And that is kind of a distracting thing, but you get used to it.
Even fancier editors now kind of mix those things together, and it looks a lot like you're
typing on a WYSIWYG editor.
Pros and cons to that, too.
So that's WYSIWYG versus markup.
Let's talk about that if that feels confusing or something like that.
And if everybody's cool with it, let's not talk about it later on in the call.
So let's learn some markdown.
So markdown, I put markdown on the left here and the rendered version on the right.
Say I wanted some italic text, what you do is put an underscore before and after the
text that you want to be italic.
Either when you push the button or automatically it just happens, you get italic text.
Bold, same thing, except you put two stars in front and two stars at the end.
So now you're conceptually about halfway into Markdown.
Hopefully that doesn't seem too hard.
thing we'll take is bullets. If you want to make a bullet list, instead of, you know,
selecting a set of text and going up to the toolbar and clicking the bullet thing, you
just type. You type a dash, a space, and the bullet text, and you hit return. Most editors,
if you're using a marked editor nowadays, they'll add another bullet for you again,
and you just keep typing. Same thing with numbered bullets. You'll notice something
weird about this numbered bullet, I put the same number here, one and one.
The markdown rule is because you want to be able to edit bullets and not have to renumber
each bullet by hand, the markdown rule is if the computer sees a number and a dot and
a space and it sees the lines of those together, it will fix the numbers for you.
So often, well, people can either type, you know, one, two, three, but then they go, hey,
I need to stick something between one and two, and I guess I'll have another one or
another two or whatever.
You can not worry about what number it is.
Okay.
So now we're like 60% of the way into learning Markdown.
Here's kind of like the final thing that you need for basic Markdown.
When you want bigger text or smaller text, you use a hash mark and then a space.
If you have one, it turns into the largest header, a header one.
If you use two, it's a header two.
If you use three, a header three.
I think this goes down to six, actually.
You can have six, although past three, they start not working very well.
You're not guaranteed exactly what the formatting of the headers look like, and the smaller
headers start to look just like bold text or something like that.
So three or four is kind of the way you go.
So what have we learned?
We've learned about 80% of the markdown
that you need to use ever.
We've actually probably learned about a third
of all of markdown.
There's some fancy stuff that you don't use very much.
Some of it you use a fair bit, like how to insert an image,
how to insert a table.
But this is day in and day out, 80%, 85%, 90%
of what you're typing is these things here.
I don't have a slide for this next thing,
and it's a little confusing.
And I apologize for presenting it so early.
But I want to just say something honest.
I've done a-- the characters I'm using here
are the characters that I would prefer people
to use for various reasons.
However, Markdown has got a little bit of flexibility to it.
And so it turns out that if you want bold text,
I always use stars.
And if I want italic text, I always use underscores.
But Markdown rules say that it's actually
the number of characters and not the character itself.
So you can use underscores and stars to make bold and italic.
If it's two, you're going to get bold.
If it's one, you're going to get a talk.
That sounds really confusing to me.
I wanted to be honest and say it.
Try to forget it now.
Same thing with bullets.
You can use a couple different characters.
You can use a dash or you can use a star.
And some people typing bullet lists,
it's very common for them to use a star instead of a dash.
There's reasons to use a dash, but stars are OK.
I think you can actually even use pluses.
The rule for those caveats is that if you're using one of
them, you should stick with it.
So these are all dashes, or I could use all stars.
Same thing like this.
If I'm using two stars or underscores,
I have to use two at the front and two at the back.
Two in front and one in back is going
to make weird stuff happen.
Here's some great resources for Markdown.
They're actually not as great as I wish,
because I didn't have time to find better ones.
So the thing that's missing here is a cheat sheet, Markdown
cheat sheet. What I would suggest you do is just search for Markdown cheat sheet. And
I'll also probably add something to the community or to a document someplace. We'll get some
better resources. These particular resources are kind of important. Daring Fireball is
the guy who -- it's the blog of the guy who invented Markdown. He didn't invent the idea
of markup, but he did specify the particular characters
to use for markdown.
So this is kind of the seminal document.
Common mark is a cleanup kind of spec for markdown
and a very common thing to use, at least for developers.
And that's leaked into other tools, so it's important.
There's something called GitHub Flavor Markdown.
These are links.
I think even now you could click on these and get to them
or if you have this presentation later, you can.
So let me go back to the beginning.
So we've just covered Markdown.
We're kind of a good chunk through what
we want to talk about today.
Next we'll cover Git and GitHub.
So Git is a, I call it an apparatus.
You could also call it a system.
You could also call it an application.
It's actually kind of a set of applications.
You could also call it a protocol.
It's kind of all of those things.
It was created by Linus Tarvalds, the guy behind Linux,
for working on the Linux kernel
because he had people scattered all over the world
trying to work together.
And he's like, "This is just annoying."
It turns out there's a long history
of version control systems.
They go back decades, decades and decades.
And the kind of the lore is, the history is,
the history is that Linus was actually using
different version control system which he actually liked a lot but the people who owned
it got kind of snippy about the way it was getting used.
They thought they should make money or something, more money than they were making based on
it getting used for Linux so much.
So Linus sat down and wrote git, kind of like sitting down and writing a Unix kernel.
what he does. So then GitHub came along later. You'll see that Git is a distributed version
control system, which this was a kind of an innovation of version control systems. Distributed
means that you can, you can, with your team, everybody can have a copy of the working materials
And you can exchange them peer to peer with any person you want.
So you don't have to have a central server someplace.
That was a big advance and let loose a lot of cool collaboration stuff.
It turns out that the centralization thing is also super important.
And so there are people who invented GitHub.
So let me get into the slides for these individual things
real quick.
Here's a system diagram that Bill Anderson and I
created a couple of years ago.
This happens to be for MassiveWiki.
And you don't have to--
sorry, it's kind of small.
But you don't really have to see very much here.
Conceptually, everybody's got a system
where they've got an editor.
and they're using Git software.
If you look at these document sets,
everyone's got a blue one, and everyone has other ones.
So one person might have a few documents
that they share just to themselves,
what they might share with a completely different team.
This team happens to be kind of defined
by that blue set of documents.
Everybody shares this.
And they could be sharing it via peer-to-peer.
But it turns out that mostly we end up sharing it
through a centralizing GitHub.
The generic term for what GitHub is is a GitForge.
Forge is the central place where you kind of--
the switching center to go through for everybody.
One of the cool things that happens with this is that that
means that if you need to swap files with a peer,
but her computer is offline because it's late at night
or early in the morning or whatever, she's not awake,
you can swap it with the centralizer with GitHub.
And then she can wake up later.
You can turn your computer off and her computer can,
or be offline, you know, in a tunnel or something like that.
The other thing that the centralizer does really,
really well is create a community of people
you don't really know that you can cooperate with.
So open source blossomed when GitHub was invented.
And we'll get into that.
That's a really amazing thing that happened
and maybe it'll happen for text too.
That'd be awesome.
Charles, got a hand.
- Hey, by the way, thanks and hi everyone.
And you're doing great.
I just, I had a quick question just to drop in the words
push and pull, 'cause I think that's probably related.
Yep.
- If you have a little quick thing maybe on that, thanks.
- Yeah, thanks Charles.
There's a couple things and I'm gonna switch over to,
so now I don't know how y'all are following along at home,
but I'm gonna switch over to the HackMD thing
and scroll down to maybe a good place.
I'll do it up at the top.
So at line 16, I'm making a new section.
Let me make this maybe a little bit bigger in my computer.
Get terminology.
As Charles says, there's push, there's pull.
Commit is another good one.
Clone is a good one.
And then there's kind of a fancy one called a pull request.
Another good one is merge.
Thinking through, there's a lot of stuff
I wanna explain all at once,
and obviously that's not gonna work.
but real--
- Just carry on your track, it's fine.
I just want to drop them in.
- No, yeah, it's awesome.
And let's cover them real quick.
When you wake up in the morning
and you wanna know what happened with everybody else
and you haven't had your computer automatically syncing,
what you do is you pull.
You say, I wanna get the freshest stuff.
Let me pull down, grab the stuff from the cloud,
pull it down to my computer.
You work on your stuff for a while.
There's a thing called commit,
which is when I feel like I'm kind of done with this stuff
and I want to commit it to posterity.
So I make a commit.
You can actually do a couple of commits at once
and things like that.
But anyway, I've got a bundle of stuff
that I'm ready to push.
So you pull from the cloud and you push to the cloud.
And then the cloud conceptually is also connected
to all your friends, your teammates.
So that's pull and push.
And that's good enough for now.
So another great term is merging.
This is maybe one of the most magic things about Git.
I think conceptually, I wrote this slide literally
like an hour and a half ago.
Conceptually, I think this slide doesn't actually
quite work, but follow along and it kind of works.
So say A has been writing stuff,
A and B both started writing something.
And A has got four score on seven years,
fourth on this continent, blah, blah, blah.
Maybe in a previous version, they've co-written part
this, but A doesn't have that important line here, "Ago our fathers brought." B typed that.
Conversely, A has liberty and dedicated to that, and B doesn't have that yet.
So there's a process where when you pull, you want to merge things. And the idea is that
Git will automatically, for text files, line by line,
it looks at the things.
And where it sees that the lines are the same,
that's how it kind of centers itself.
Where it sees a difference, Git can magically
tell that the second line in B isn't in A.
And so it'll add it to the result.
And this fifth line in B is missing what A has.
So it'll add it to the result.
Again, this is kind of a contrived example.
It doesn't work very well, I don't think.
But you kind of get the idea.
If I'm a software developer, she wrote a subroutine,
I wrote a subroutine, and we have a whole bunch
of subroutines in a file.
I can pull, and Git will automatically
give me her subroutines.
And when I push, it'll automatically
give her my subroutines or paragraphs or you know whatever. And this works, it's
very common for people to be working on a number of files at once. So in a book
for instance you might have a file per paragraph, sorry, a file per chapter. So
you've got a chapter 1 file, chapter 2 file, chapter 3 file, chapter 4. And so
Paul is working on chapter two.
Susan is working on chapter four.
They're typing away and stuff like that.
In the process of pushing and pulling during the day,
you don't just do it in the morning.
You do it when you're at a good stopping place
during the day.
Paul ends up with the changes that Susan's made.
Susan ends up with the changes that Paul's made.
And this scales dramatically.
It's okay if the team is 10 people
And it's OK if some of the people are working a lot
and some of the people aren't working a lot on the text.
Maybe Paul is working on it every day
as soon as he's working on it every month.
All of that kind of stuff just magically works.
A thing I didn't cover is merge conflicts.
And I will add that to line 26 here.
So the magic only goes so far.
If A had four score and seven years, and then another line here,
Mary had a little lamb, fourth on this continent,
and B had four score and seven years ago, our father's brat.
If A and B had conflicting lines in the same place, Git would go, "Huh, I don't know what
they meant and I'm not smart enough to figure it out."
So I'll kind of, I'll flag that as a conflict.
I'll fix all the other ones that I can do automatically, but my magic doesn't go that
far.
I don't know what they meant.
I'm going to leave the humans to figure it out.
So that happens.
In practice, you kind of collaborate out of band, you coordinate out of band to minimize
the times that that happens.
So when I said Paul is working on chapter 2 and Susan is working on chapter 4, part
of the reason they're doing that is because, you know, at the weekly meeting, they agreed,
hey, Paul, you're going to be working on chapter 2 a lot.
I don't want to make any merge conflicts.
So I'll work on chapter 4 this week.
Sound good?
And then Susan can follow along.
She can see how Paul is working on chapter two.
We'll get to GitHub collaboration.
She can actually make comments on some of the changes
or she can suggest changes into the stuff
that Paul is kind of working on mostly, things like that.
So same thing here.
I wish there was an easy Git cheat sheet.
Git itself, so we covered a lot of good news.
Good news is we have this fancy technology.
It's all free, it's all very powerful.
It's fun to use.
It's a blast to be productive with a team.
It's mind-blowingly cool in a way
that software developers get to do every day
and writers mostly don't.
And it makes me just terribly sad about that.
That's the way it is.
Bill.
- Yeah, quick question.
Does HackMD run on top of Git?
'Cause I noticed, I mean, it's using the Git.
- That's a great question.
- What are we seeing here?
'Cause you're illustrating on something
was actually doing what you're saying.
- That's a great question.
And it's using Git-like technology.
It's actually something different.
The general class of the things that HackMD is using--
and this is the same thing that Google Docs uses.
Instead of Microsoft Word, people
are using Google Docs because everybody gets to type, right?
or everybody gets to put in different things in the document.
Conceptually, it's a very similar technology,
except it's character by character.
And it's connected to a central server, generally,
which doesn't matter too much.
So your browser-- everybody's browser
is, for every character or every editing command,
like Backspace, it's doing this merge thing together
with everybody else.
So it's very similar in that sense.
Because it's every character and you
want to be able to type really fast
and have everything happen, you don't have that commit phase
where you can batch up a bunch of changes
and say, here's a bunch of changes I want to make.
let's all review that and see if it should get merged
into the main branch.
In some Nirvana future, probably not that far away,
but it might be years still,
we would have both things working together.
We'd have this real-time collaboration,
character by character,
and then we would also have that kind of more phased approach
line by line.
We're not quite there yet.
So I'm going to--
thanks, Bill.
I'm going to click into these links a little bit
because they've got cool--
at least the first one has cool pictures.
And I'm going to ask you to do a little bit of a tricky thing
here.
This merge thing is one concept you kind of
to hold in your head, and then another thing called branching. And I'm going to this particular page,
and I don't think this will follow along if you're watching the presentation,
so now you have to watch the screen. There's a couple things about this page. Git flow was a
revelation when it came out. And it's kind of funny the author has put a note here. It's like
GitFlow is kind of like old news now at this point. But it's still important and still foundational.
It's also got a great set of diagrams. So Git uses this thing called branches. And each branch
here is represented by these arrows, these lines going down.
And a lot of times you'll see them sideways too.
I have a really hard time understanding what
those lines mean. It's kind of like the branches of a tree or something like
that, and I find it confusing to kind of keep in
mind what's going on by looking at a picture. I think that's
probably not true for everybody. Some people probably makes a lot of sense.
some people it doesn't make any sense. So these diagrams are kind of helpful but kind of not,
I think. So anyway, this diagram kind of does work for me because it's got different colors and
and the side cross arrows and things like this. This is a very complicated collaboration scenario,
by the way. So this is what you would use in a heavyweight enterprise software development thing
where you've got 50 or 100 or 200 people working together.
And you've got different releases, and you've got to bug fix the existing versions out in the field,
and you have to keep track of different versions, because this company bought this version,
that company, and can't upgrade for a while. This other company has a newer version,
they upgrade a lot. So all of that complexity is kind of handled, managed by this amount of
overhead. So don't be like, you can kind of squint your eyes and go, okay, I kind of know
what's going on here. I kind of understand what's going on. We will probably never get this complex
doing anything. But at the same time, you want to know that you could do it. And you want to borrow
important chunks of this to kind of make a toy version of this that's as big as you need.
So, all the way on the right is a branch called master.
Master is the kind of original name for this going back 10 or 15 years.
It's now due to sensitivity around language, master is usually called main now.
So this is the main branch all the way at the right.
And as a developer, say I want to do some work,
what I do is I kind of copy or clone this master branch
maybe in the morning over to say the develop branch here
with the yellow balls.
I can make edits and I can make edits
and I can make edits.
And then at some point, if you follow this diagram
are down a ways, the yellow goes to green
and the green goes to blue.
So you can kind of simplify this.
You can skip that green step
unless you wanna do like a testing version
or something like that.
All these extra steps happen a lot in software development.
But for a writing project,
you'd probably just do blue and yellow and blue.
So then in the morning,
I pull and get a version that I can work on.
Susan pulls and gets a version she can work on.
So there's actually a couple yellow things
going on at the same time.
And we can both work and then we can kind of both
put our work back to the main branch at the right.
So that's kind of what happens.
Git flow is actually, it's got that complexity and it's an important model.
People have kind of moved on past a little bit.
They've gotten a little bit fancier, simplified in ways, but complexified in other ways.
It has that pretty picture, which is the main reason we were going there today.
Let me also look at this GitHub flow page.
doesn't have any pretty picture but this is a lot more what I was describing
where you have the blue main and the yellow develop things for different
people. So this describes that even though it doesn't have a picture. ProGit
is a ebook. It's kind of like the canonical documentation for Git. It's a
a good book, nobody except real geeks would ever read the whole thing.
So what you do is you do a web search and you find a page on here and you go, "Oh, that's
the way it's supposed to work."
Git is fantastically complex, behind the hood.
It's got a lot of capability because it was written by software developers trying to do
really hard stuff.
So they kept adding stuff and adding stuff and adding stuff.
It didn't get shepherded well for user experience.
So all the stuff that got added is it all works together, but it's all a little bit
different the way it works.
So the simple stuff, going back to our HackMD with the Git terminology, push, pull, commit,
merge, it's conceptually pretty simple.
You can fall into the deep end of Git and it can get really difficult.
So that's kind of a way for me to back into the, you know, there's, here be dragons.
We can work together to make it so that we don't get eaten by dragons.
It would take a little bit of work to make that happen.
So that's going to be the main cost probably for this whole thing.
Charles.
Another quick question, because you mentioned dragons, and I was just thinking to, I don't
if it fits exactly here or actually if GitHub is sort of related to where you we go with this but
you know the Microsoft acquiring GitHub is a is a kind of question with a lot of dimensions so I
don't know if that's a dragon that's relevant but it is it's super relevant and if somebody
could write down Microsoft someplace on the notes I would really appreciate it.
I don't want to get too deep into it.
GitHub was originally kind of a hero of open source.
It created a lot of the open source collaboration model
that we have today,
where people who don't know each other work together.
It was magical and wonderful.
20 years later, whatever, it wasn't a perfect thing either.
There's horror stories about some of the people at GitHub
stuff like that. But in the main, it was a beautiful and wonderful thing. It was a boon
to humanity. It actually, like, if you thought about the boost that it gave to productivity
in software, and then software goes everywhere, kind of, it's huge. It's a big thing. It's a big
deal. GitHub is awesome. And kind of like Twitter, it ended up being a super big thing. So not only
was it a cool thing for a few people, it ended up being like a society-wide thing where everybody
but it was using it day in, day out for a lot of stuff.
So that's the good news.
The other news is that Microsoft bought it a few years ago.
Microsoft has, if you zoom out
and get a 30,000 foot view of the open source ecosystem,
Microsoft has been kind of like cherry picking parts
of the ecosystem and acquiring it
and then improving it, improving that little part
in a way that you go, oh, well,
I could use the clunky, you know, open source version.
I could use the open source version
that Microsoft is supporting.
That would be a beautiful, wonderful thing
because there's more capability.
And everybody has been getting hypnotized
into using the Microsoft version of open source
rather than the open version of open source.
So if you look the right way,
Microsoft isn't fighting open source,
but they're embracing it and smothering it kind of.
Smothering it is a strong word.
They're not killing it,
but they are definitely bending it to their direction
in a big way and in massive ecosystem ways, not unlike,
it's the Twitter, the Microsoft takeover of GitHub
is kind of like the Elon takeover of Twitter.
It changed it from a community commons to a--
it's owned by interesting people.
And so because it's such a centralized location
for all of open source, it is hard to move away from.
And Microsoft isn't being quite so nasty as Elon is--
or crazy maybe is a different way to say it.
But there's definitely warning signs.
And long story short, there are a couple more open source
Gitforges.
There's one called--
I think actually if--
I'm going to skip ahead in the slides.
Yeah.
There are other forges.
There's one called Codeburg.
There's one called GitLab.
Those are both very open source friendly.
There's another one called Sourcehut.
Sourcehut is aggressively kind of open source
in a very opinionated way.
Sourcehut is an amazing and wonderful thing.
I'm sorry they didn't put it in this list here.
I'll add that.
But it's so opinionated that it can be hard to use.
Codeberg is kind of, I think, the best replacement for it.
Codeburg is using software called Forgeo.
Forgeo is a fork of Gitty.
So you can actually run your own Gitty or Forgeo instance.
You can even use a tiny little thing called
Git, which has no admin interface except a Git
repository.
What's that repository also?
A repository in Git is the set of all the files
you're working on.
So for a book, it would be all of the chapters and probably also some additional, you know,
like materials that you're using, notes, notes to yourselves, research things and stuff like
that.
That's a repository.
You can have lots of repositories, but you kind of cluster, you know, all your files
together into a repository.
We're running out of time.
I still want to cover one more thing real quick.
So this is kind of the pearl of this meeting.
It's an example that I have from an open source project
that I wrote a couple years ago called Obsidian Settings
Manager.
It happens to be for Obsidian.
That's not why I picked this.
I picked it because something really cool happened.
I wrote this code a couple of years ago.
And in July, this guy named Doug Phillips,
sorry, I didn't get what I wanted.
Doug Phillips kind of whizzed by on GitHub and he said,
"Huh, this is a software that I wanna use,
"except it doesn't quite work the way I want it,
"but it's on GitHub, so I can pull it down.
"I can clone it."
It's actually, cloning is grabbing everything,
a fresh version of everything.
I can clone it, I can make changes to it.
And then I can suggest those changes back to Pete.
So this uses a GitHub concept called the pull request.
And other forges do this now too.
They call it different things sometimes.
But what Doug did was he changed the way it worked.
And then he sent me a message through GitHub,
which is all kind of automated.
You can click this button, New Poll Request.
He did this thing where he said--
let me show it to you, actually.
Hi, Peter, I found your repo.
I'm on Linux.
I'm on Mac.
I needed to make some changes.
So he didn't even send me an email.
He sent me this to the GitHub collaboration mechanism.
So I get this message and I look at it
and he's got this whole set of changes that he's made.
So I can look at each of these changes
and I think it's reverse chronological.
So for each of these changes,
I can look at the changes he's made.
He's deleted things in red and added stuff in green.
And I can step through the various changes he made.
Doug is a careful software developer.
So he collapsed or when he made changes,
he made just an atomic change kind of,
and then said, I'm going to commit this.
All of those commits ended up being a bundle.
And that, sorry, it's a little bit hard
to talk and think here,
bit. That all ended up being one pull request. I can look at the pull request altogether.
This is actually just one file in this one. Let me get back to kind of where we were looking
at pull requests. You can see there's one open pull request, 10 closed. The process
of this is he makes a pull request, I look at it, make some comments, and I can either
comment on everything or I can comment on specific changes. Let me see if we can see
a more specific change. Yeah, I don't know. So here is bolded the exact part of this line
that's changed. This is not something that Git does, but GitHub has a fancy version of the
differences thing. I can go here and I can say, you know, "What the heck are you doing?"
or whatever, right? So literally line by line, I can go through and comment on changes. I can
you know, look at this whole thing and say,
this all looks great.
This looks, it's really common to say, looks good to me.
And you can, this ends up being in a,
kind of a threaded discussion
around all the different files.
This is pull request number four.
Here's me saying, looks good to me.
Here's me merging it.
There's with a little bit more prep, I could have taken a better tour through this.
There are places where we're going back and forth.
You know, that part looks good, except that you need to do it a little bit different way.
Or I'm going to take this part.
This looks great.
But let's work on this part because it's not quite right yet at all.
So you can bounce parts of the pull request out for later.
You can take parts of them and save them.
you can merge them all and do wonderful things.
So not that this was a very good demo of it,
but this is kind of where I'm hoping
at least some of us get to go
into a place where we're collaborating like that.
And real quick, let's hit tools.
The tools that you need are Git,
which I didn't even make this list,
your favorite text editor.
You don't really need a markdown editor,
but you can use other tools to get fancier
and stuff like that.
So that's where we are.
Let me stop sharing my screen
and I apologize for going over time a little bit.
Where should we go next?
Do we wanna do this again in a week?
Do we wanna do it again with Pete presenting,
talking head style and going through stuff?
Maybe a little bit more prep.
Do we want to slow down and do kind of a collaborative work
session?
What should we do?
Anything quick to say about the writing
compared to the software stuff?
Yeah, it's a great question.
Software is just another language, basically.
So it has lines of text.
It kind of has things like paragraphs.
It has things like chapters, and chapters are modules.
If you don't mind stepping back from Microsoft Word
or Google Docs a little bit into plain text
and making sure that you do things online
so that Git can do its automatic merging magic,
they're essentially the same thing.
Even down to software developers have a bunch of conventions
around noting problems, you know,
or bundling up sets of changes, you know,
here's a bunch of changes to chapter one.
And I also needed to change some wording in chapter three
and five to go along with the changes in chapter one.
All of that stuff that writers do,
software developers have figured out and systematized.
So I think it's a match made in heaven.
Bill?
- Sometimes I learn better by doing.
Once, you know, I like to have the kind
of the comprehensive view
of what is really gonna happen here.
But if we had a little short kind of an exercise
we could all participate in together,
maybe that would be an efficient way to get a feel for it
and would raise other questions.
But just a thought. - Yeah, that's brilliant.
Yeah.
>> Great.
>> So I want to say again, thank you very much.
Like I have sort of a vision that I had in mind of my personal motivation
when I saw that you wanted to do this for saying, great, let's do it.
And it is to, just as you said, to actually be able to facilitate
collaborative writing with exactly the same flows as developers use.
So you didn't say that explicitly when you were like waiting into
the project that you had on GitHub which somebody forked and
then started to make changes and gave you a pull request.
>> Yep. >> But I think it's important for
everyone to imagine being able to do exactly the same sort of thing,
to work together in an organized way on a document.
It could be an academic paper,
it could be a white paper for a project,
and really systematize that process
to efficiently work together to create something better
than one person might be able to do on their own.
And that's beautiful, both for the output
that can come from it, but also as a way
for people to learn to function well together as a team.
And that's what I think is really awesome about this.
- Yeah, I totally agree.
That's the dream.
That's the dream for me too.
Bill?
- Yeah, I just wanna support Bill Larson's idea
and maybe Ray, I think,
why don't we actually put together a document
that perhaps outlines what we're trying to get out of this,
where we think we might go.
We could comment on each other's things.
we could try and use what the affordances of Git
to just see how that works,
what kind of breakdowns we have,
because I agree with you.
I think there's a little bit of a learning curve,
but it's not that big to get to,
and we could, doing it ourselves,
learn how to help other people do it.
- Charles?
Great idea, Bill, by the way.
We should write that.
In fact, maybe everybody should write something
about what it is exactly that they want
to get out of this.
That would be really useful.
- That would be a great thing to do on the HackMD.
And you could either make your own section
or follow along in another section.
Sorry, Charles, go ahead.
- Oh, no worries.
This is great.
probably go shortly as many of us probably. So Bill noted to add fork to the list, so I thought,
you know, if there's something 20-30 seconds to say about forking, and then I don't know if this
is like too much to pile in, but I haven't actually heard any details about MassiveWiki in a long
time, but I was around, more or less around the inception time, and I know you and Bill,
Anderson and others
You know have been doing it relates and it overlaps, but it's not the same
but it probably relates more to the forking part, so I don't know just
Jumbling in my awareness of it here. Yeah, thanks
For folks who need to go at the top of the hour, it's the top of the hour. Thanks for thanks for everything
Let's get together again
Maybe I the easiest way for me to do that is to coordinate through that community thing
So you should have that link.
If you don't, send me an email.
If you don't want to join the community, you can kind of follow along.
I'll keep you in the loop.
So thanks for anybody who has to leave at that hour.
So Charles, real quick, you talked about massive wiki and then the thing before that is forking.
So let's cover those both real quick.
A caveat that I don't give to most people
is that there's actually two meanings for the word fork.
There's like a big fork, capital F fork,
and then there's little fork, capital,
or small, small F fork.
The fork terminology, I think,
comes from an old thing that used to happen
in software communities pre GitHub,
where you'd have the community going along
and everything was wonderful.
And then at some point there would be some leadership conflict.
Somebody would say, well, I think we should do it this way.
And leadership says, we're not going to do it that way. It's stupid.
So the, uh, you hit a fork in the road and the community splits in the two,
um, the, uh, the Protestants and the whatever's, um,
the conservatives and the, you know, uh, heretics. So, um,
uh, often that will kill a community. Um, sometimes, uh, the,
the, you know, there's a lot of pressure
to not do that kind of split
because you don't wanna split your resources
and stuff like that.
But sometimes it happens.
Sometimes the act of doing that
kind of relieves the pressure.
Everybody can like take a year to kind of like develop along
and then say, "Hey, we're doing the same thing anyway.
"Let's get back together."
So that's a big F fork.
It's a big deal.
GitHub used that language.
And I think it's a good thing that they did.
They use that language to mean something
conceptually very similar.
I wanna take all of your code the way that Doug did.
I wanna take all your code and make a copy of it for myself
and then make changes.
So now I've got this fork.
These two versions are, you know,
they could continue to evolve separately.
And on GitHub, it's very common for not just Doug to fork it
but it's very common for 10 people to fork something
or a hundred people.
So now you've got a hundred different copies of this thing.
They're all like, they're not even like arguments.
And they're not even disagreements, right?
Doug just had a different way of doing things
or needed some extra stuff added.
So at some point Doug can say, well, I've got my fork,
but it's, you know, I really want, you know,
to contribute to the thing with everybody in it,
not just me doing my stuff on a fork of everything.
So I'll make a pull request and the fork merges back.
So that fork is just the process of making a,
usually very temporary copy of the whole thing,
changing it so that it's all cohesive in itself
and then probably putting it back together.
So forks and pull requests go together.
