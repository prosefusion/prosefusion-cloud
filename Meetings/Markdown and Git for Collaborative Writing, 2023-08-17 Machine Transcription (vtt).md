WEBVTT

00:00:00.000 --> 00:00:05.000
>> Recording is on.


00:00:05.000 --> 00:00:14.360
>> Okay. Hey, Bill, is that your hand or just randomly clicking?


00:00:14.360 --> 00:00:16.840
I've got a presentation.


00:00:16.840 --> 00:00:19.680
I'd like to -- some slides I'd like to go through.


00:00:19.680 --> 00:00:22.400
Let me -- I'm going to try to do a thing here


00:00:22.400 --> 00:00:25.560
where I've only done this a couple times.


00:00:25.560 --> 00:00:37.000
I can share this with folks so that you can follow along on your own browser.


00:00:37.000 --> 00:00:41.320
So let me try to do that real quick.


00:00:41.320 --> 00:00:46.400
This also is inside this document.


00:00:46.400 --> 00:00:52.020
I'm not sharing my -- yeah, I am sharing my screen.


00:00:52.020 --> 00:00:54.160
Links are a little bit hard to click on the left.


00:00:54.160 --> 00:00:56.060
so links are easier to click on the right.


00:00:56.060 --> 00:00:58.160
You can go here and get to the slides.


00:00:58.160 --> 00:01:04.260
Let me spend a couple secs to try to present this


00:01:04.260 --> 00:01:05.940
also with a link.


00:01:05.940 --> 00:01:09.280
I think I'd do this.


00:01:09.280 --> 00:01:15.340
And this.


00:01:15.340 --> 00:01:19.540
And this.


00:01:19.540 --> 00:01:21.340
Except that didn't give me the link.


00:01:21.340 --> 00:01:28.340
Ah, here you go.


00:01:28.340 --> 00:01:39.180
Okay, so for those of you who aren't overwhelmed, I think if you click that link, you can watch


00:01:39.180 --> 00:01:40.980
the presentation.


00:01:40.980 --> 00:01:45.300
Maybe you can make Jitsi kind of small on one side and the presentation small on the


00:01:45.300 --> 00:01:49.340
other side, and then you can kind of also have a little bigger desktop.


00:01:49.340 --> 00:01:51.300
Okay, let's go for it.


00:01:51.300 --> 00:01:55.220
So welcome to Markdown on Git for Collaborative Writing.


00:01:55.220 --> 00:02:03.620
The way I was going to do this session, let's go for an hour.


00:02:03.620 --> 00:02:08.740
I'm going to start off doing most of the talking, kind of presenting, going through stuff.


00:02:08.740 --> 00:02:13.740
The idea of this session for me is mostly just to kind of present the idea of what we


00:02:13.740 --> 00:02:22.060
could accomplish and not learn too much about the tools, things like that, the pitfalls.


00:02:22.060 --> 00:02:27.580
So then the last 15 minutes of the call or so we'll spend talking about what we could


00:02:27.580 --> 00:02:30.540
do next, whether it makes sense to get together again.


00:02:30.540 --> 00:02:38.180
I would love to kind of continue to work on this project.


00:02:38.180 --> 00:02:39.780
We could do that a bunch of different ways.


00:02:39.780 --> 00:02:42.220
So let's see.


00:02:42.220 --> 00:02:49.340
Down here in the lower right corner, you'll see this session is sponsored by PathShift


00:02:49.340 --> 00:02:54.940
People, purveyors of fine educational materials for AI and other things.


00:02:54.940 --> 00:02:59.740
PathShift People is essentially kind of an OGM startup, or a startup of OGMers.


00:02:59.740 --> 00:03:02.540
It's me and Matthew Lowery and Wendy Alford.


00:03:02.540 --> 00:03:09.080
Some of you know those folks.


00:03:09.080 --> 00:03:11.100
The main thing that we're teaching right now is ChatGBT.


00:03:11.100 --> 00:03:16.700
I'm going to start teaching some mid-journey and image synthesis.


00:03:16.700 --> 00:03:26.140
We sell those courses for money to businesses, and doing that helps support our work in making


00:03:26.140 --> 00:03:27.940
things like this free.


00:03:27.940 --> 00:03:31.380
This material is going to end up getting open sourced somehow.


00:03:31.380 --> 00:03:33.780
I'm not exactly sure how.


00:03:33.780 --> 00:03:35.780
We'll see.


00:03:35.780 --> 00:03:43.920
The things that I want to cover today is what you see is what you get versus markup.


00:03:43.920 --> 00:03:46.260
And then talk about markdown.


00:03:46.260 --> 00:03:48.340
And then talk about Git.


00:03:48.340 --> 00:03:50.140
And then GitHub.


00:03:50.140 --> 00:03:52.220
I've got a placeholder here for MassiveWiki.


00:03:52.220 --> 00:03:54.920
I don't think I got the slide in there yet.


00:03:54.920 --> 00:03:57.740
And then a little bit on tools.


00:03:57.740 --> 00:04:06.480
So the goal of this session, and I don't have this on the presentation, the goal of this


00:04:06.480 --> 00:04:13.040
session is just to kind of get our art oriented to where we are, what we could do.


00:04:13.040 --> 00:04:20.440
My -- I'm going to go to my shared screen here real quick.


00:04:20.440 --> 00:04:27.680
This is the -- by the way, this is the community that is hosted by Passive People.


00:04:27.680 --> 00:04:31.780
And we've got a little space here called Markdown Git for Collaborative Writing.


00:04:31.780 --> 00:04:33.180
It looks like this.


00:04:33.180 --> 00:04:37.480
You can post things.


00:04:37.480 --> 00:04:39.560
People can reply.


00:04:39.560 --> 00:04:42.800
Stuff like that.


00:04:42.800 --> 00:04:49.440
The choices for us continuing to collaborate are kind of a mailing list, chat system, or


00:04:49.440 --> 00:04:51.320
maybe this forum.


00:04:51.320 --> 00:04:52.840
I'm okay with any of those.


00:04:52.840 --> 00:04:56.380
and we can kind of see who lands where.


00:04:56.380 --> 00:04:59.600
We have another system called Mattermost chat system,


00:04:59.600 --> 00:05:01.440
which would be a great place to land.


00:05:01.440 --> 00:05:07.480
We might also end up with a set of shared Markdown files


00:05:07.480 --> 00:05:10.240
that we can collaborate on too,


00:05:10.240 --> 00:05:12.200
but we kind of need a way to message each other.


00:05:12.200 --> 00:05:14.240
So this is a start.


00:05:14.240 --> 00:05:18.560
I wanted to, I think that I posted,


00:05:18.560 --> 00:05:21.360
or the thing that kicked this off


00:05:21.360 --> 00:05:27.920
was me posting this kind of ranty thing to the OGM list.


00:05:27.920 --> 00:05:32.400
Ray, thank you, picked this up recently and said, hey, Pete,


00:05:32.400 --> 00:05:35.280
I would like to do that.


00:05:35.280 --> 00:05:39.560
So there's a thing that software developers do.


00:05:39.560 --> 00:05:45.520
And I kind of talk about this down here.


00:05:45.520 --> 00:05:50.200
Software developers use text and Git


00:05:50.200 --> 00:05:54.560
to successfully collaborate at high speed.


00:05:54.560 --> 00:05:56.760
And I think that's true--


00:05:56.760 --> 00:05:59.120
that could be true for writers, too.


00:05:59.120 --> 00:06:03.260
I think there's some stuff to learn,


00:06:03.260 --> 00:06:07.280
and there's some shoulder to the grindstone kinds of things


00:06:07.280 --> 00:06:08.480
that you need to do.


00:06:08.480 --> 00:06:12.400
But it's fairly mechanical, and you


00:06:12.400 --> 00:06:15.680
can kind of unlock a lot of collaboration potential


00:06:15.680 --> 00:06:18.960
by using the same tools that software developers use.


00:06:18.960 --> 00:06:22.560
So that's kind of the preamble.


00:06:22.560 --> 00:06:25.080
The goal of this session is to kind of go


00:06:25.080 --> 00:06:30.340
through the moving parts of that so that we can decide,


00:06:30.340 --> 00:06:32.200
yeah, that sounds like we should keep going,


00:06:32.200 --> 00:06:35.800
or hey, this is too complicated and too involved.


00:06:35.800 --> 00:06:38.240
I don't want to participate anymore.


00:06:38.240 --> 00:06:39.640
I'm interested in continuing.


00:06:39.640 --> 00:06:46.760
So with that, let's talk a little bit about WYSIWYG


00:06:46.760 --> 00:06:47.760
and Markup Language.


00:06:47.760 --> 00:06:51.640
If you're editing text, most people


00:06:51.640 --> 00:06:53.160
in the world who are using a computer


00:06:53.160 --> 00:06:55.520
know something like Microsoft Word.


00:06:55.520 --> 00:06:59.200
It looks kind of like this thing on the left.


00:06:59.200 --> 00:07:01.440
There's a place where you can edit your text.


00:07:01.440 --> 00:07:04.000
And there's maybe a toolbar and stuff.


00:07:04.000 --> 00:07:07.400
When you're editing the text, it looks exactly


00:07:07.400 --> 00:07:09.300
like if you printed it out.


00:07:09.300 --> 00:07:13.720
So, and if you want, you know, you can have headers,


00:07:13.720 --> 00:07:16.480
you can have paragraphs, you can have bullet lists,


00:07:16.480 --> 00:07:18.500
you can have tables and pictures.


00:07:18.500 --> 00:07:21.640
When you wanna make a change to something,


00:07:21.640 --> 00:07:24.680
you see exactly what it looks like all the time.


00:07:24.680 --> 00:07:26.200
What you see is what you get.


00:07:26.200 --> 00:07:28.200
So examples of this are Microsoft Word,


00:07:28.200 --> 00:07:29.820
Apple Pages, Google Docs.


00:07:29.820 --> 00:07:33.320
There's a different paradigm,


00:07:33.320 --> 00:07:36.360
and it's not better or worse, it's just kind of different.


00:07:36.360 --> 00:07:46.320
There's a different paradigm where instead of having the way it looks present at the


00:07:46.320 --> 00:07:52.680
same time you're editing, you can abstract the way it looks a little bit into a few characters


00:07:52.680 --> 00:07:55.960
of instructions to the computer, basically.


00:07:55.960 --> 00:08:02.000
So you end up editing something that is all just like very plain text.


00:08:02.000 --> 00:08:05.840
You can't see any of the fancy stuff in here


00:08:05.840 --> 00:08:07.760
unless you actually kind of parse with your eyes


00:08:07.760 --> 00:08:08.600
what's going on.


00:08:08.600 --> 00:08:14.560
And then either automatically all the time continuously


00:08:14.560 --> 00:08:17.280
or you push a button or something,


00:08:17.280 --> 00:08:21.280
something happens that takes this text version of it


00:08:21.280 --> 00:08:24.040
and hydrates it or turns it, you know,


00:08:24.040 --> 00:08:27.120
flushes it out into the thing that looks a lot


00:08:27.120 --> 00:08:28.280
like the WYSIWYG thing.


00:08:29.640 --> 00:08:33.800
So I haven't talked about this in a long time.


00:08:33.800 --> 00:08:38.400
When we first-- this markup language stuff,


00:08:38.400 --> 00:08:39.960
it can be different languages.


00:08:39.960 --> 00:08:41.340
The one we're talking about today


00:08:41.340 --> 00:08:44.320
is going to be Markdown, which is a clever take on markup.


00:08:44.320 --> 00:08:51.560
The wiki text, back in the days of wikis,


00:08:51.560 --> 00:08:53.800
it was a very similar kind of formatting thing.


00:08:53.800 --> 00:08:55.180
And there's other fancier things.


00:08:55.180 --> 00:08:57.800
You can do full-on typesetting.


00:08:57.800 --> 00:09:00.880
Back in the early 80s, I did full-on typesetting


00:09:00.880 --> 00:09:03.880
for a newsletter with something very similar to this


00:09:03.880 --> 00:09:06.840
with more instructions.


00:09:06.840 --> 00:09:14.660
So I think there's a big conceptual thing


00:09:14.660 --> 00:09:15.640
that goes on here.


00:09:15.640 --> 00:09:20.080
This isn't a straightforward thing for a lot of people.


00:09:20.080 --> 00:09:21.600
And I used to think that there were


00:09:21.600 --> 00:09:23.760
people who kind of got this and people who didn't.


00:09:23.760 --> 00:09:25.480
And now I don't think that's true anymore.


00:09:25.480 --> 00:09:31.800
I think it just takes slowing down and thinking about it a little bit.


00:09:31.800 --> 00:09:36.760
So you mean if I'm typing text and I want it to be bold, I have to add a little bit


00:09:36.760 --> 00:09:38.800
of instruction for the computer?


00:09:38.800 --> 00:09:40.300
Okay.


00:09:40.300 --> 00:09:44.740
And then, oh, you mean that if I want this to actually see what it looks like or especially


00:09:44.740 --> 00:09:49.040
give this to somebody else, I have to push this button and make it happen someplace?


00:09:49.040 --> 00:09:50.320
Okay.


00:09:50.320 --> 00:09:53.720
So that's the deal.


00:09:53.720 --> 00:09:58.960
We're talking about a system where you're typing text, the text is all very plain, and


00:09:58.960 --> 00:10:04.040
you add a few characters here and there to make it look fancy, but you can't see it looking


00:10:04.040 --> 00:10:09.360
fancy until you push the button.


00:10:09.360 --> 00:10:14.880
Nowadays, so HackMD, if you play around with HackMD a little bit, you'll see that it's


00:10:14.880 --> 00:10:17.160
got two panes, and this is very common.


00:10:17.160 --> 00:10:20.000
There's the pane where you're typing stuff, and it looks like that plain text.


00:10:20.000 --> 00:10:27.440
the pain where in real time it's rendered like it's supposed to look.


00:10:27.440 --> 00:10:32.520
And that is kind of a distracting thing, but you get used to it.


00:10:32.520 --> 00:10:37.400
Even fancier editors now kind of mix those things together, and it looks a lot like you're


00:10:37.400 --> 00:10:42.320
typing on a WYSIWYG editor.


00:10:42.320 --> 00:10:44.560
Pros and cons to that, too.


00:10:44.560 --> 00:10:52.200
So that's WYSIWYG versus markup.


00:10:52.200 --> 00:10:56.800
Let's talk about that if that feels confusing or something like that.


00:10:56.800 --> 00:11:01.760
And if everybody's cool with it, let's not talk about it later on in the call.


00:11:01.760 --> 00:11:05.760
So let's learn some markdown.


00:11:05.760 --> 00:11:12.980
So markdown, I put markdown on the left here and the rendered version on the right.


00:11:12.980 --> 00:11:19.300
Say I wanted some italic text, what you do is put an underscore before and after the


00:11:19.300 --> 00:11:22.740
text that you want to be italic.


00:11:22.740 --> 00:11:27.780
Either when you push the button or automatically it just happens, you get italic text.


00:11:27.780 --> 00:11:35.700
Bold, same thing, except you put two stars in front and two stars at the end.


00:11:35.700 --> 00:11:39.780
So now you're conceptually about halfway into Markdown.


00:11:39.780 --> 00:11:41.980
Hopefully that doesn't seem too hard.


00:11:41.980 --> 00:11:47.420
thing we'll take is bullets. If you want to make a bullet list, instead of, you know,


00:11:47.420 --> 00:11:52.060
selecting a set of text and going up to the toolbar and clicking the bullet thing, you


00:11:52.060 --> 00:11:58.380
just type. You type a dash, a space, and the bullet text, and you hit return. Most editors,


00:11:58.380 --> 00:12:04.340
if you're using a marked editor nowadays, they'll add another bullet for you again,


00:12:04.340 --> 00:12:10.420
and you just keep typing. Same thing with numbered bullets. You'll notice something


00:12:10.420 --> 00:12:17.140
weird about this numbered bullet, I put the same number here, one and one.


00:12:17.140 --> 00:12:22.620
The markdown rule is because you want to be able to edit bullets and not have to renumber


00:12:22.620 --> 00:12:29.260
each bullet by hand, the markdown rule is if the computer sees a number and a dot and


00:12:29.260 --> 00:12:37.040
a space and it sees the lines of those together, it will fix the numbers for you.


00:12:37.040 --> 00:12:44.520
So often, well, people can either type, you know, one, two, three, but then they go, hey,


00:12:44.520 --> 00:12:47.600
I need to stick something between one and two, and I guess I'll have another one or


00:12:47.600 --> 00:12:49.640
another two or whatever.


00:12:49.640 --> 00:12:53.240
You can not worry about what number it is.


00:12:53.240 --> 00:12:54.240
Okay.


00:12:54.240 --> 00:12:59.480
So now we're like 60% of the way into learning Markdown.


00:12:59.480 --> 00:13:03.560
Here's kind of like the final thing that you need for basic Markdown.


00:13:03.560 --> 00:13:10.220
When you want bigger text or smaller text, you use a hash mark and then a space.


00:13:10.220 --> 00:13:14.400
If you have one, it turns into the largest header, a header one.


00:13:14.400 --> 00:13:16.320
If you use two, it's a header two.


00:13:16.320 --> 00:13:18.320
If you use three, a header three.


00:13:18.320 --> 00:13:20.040
I think this goes down to six, actually.


00:13:20.040 --> 00:13:25.160
You can have six, although past three, they start not working very well.


00:13:25.160 --> 00:13:29.960
You're not guaranteed exactly what the formatting of the headers look like, and the smaller


00:13:29.960 --> 00:13:33.120
headers start to look just like bold text or something like that.


00:13:33.120 --> 00:13:36.360
So three or four is kind of the way you go.


00:13:36.360 --> 00:13:40.560
So what have we learned?


00:13:40.560 --> 00:13:43.760
We've learned about 80% of the markdown


00:13:43.760 --> 00:13:47.000
that you need to use ever.


00:13:47.000 --> 00:13:49.600
We've actually probably learned about a third


00:13:49.600 --> 00:13:51.640
of all of markdown.


00:13:51.640 --> 00:13:55.200
There's some fancy stuff that you don't use very much.


00:13:55.200 --> 00:13:58.760
Some of it you use a fair bit, like how to insert an image,


00:13:58.760 --> 00:14:00.960
how to insert a table.


00:14:00.960 --> 00:14:05.160
But this is day in and day out, 80%, 85%, 90%


00:14:05.160 --> 00:14:07.560
of what you're typing is these things here.


00:14:07.560 --> 00:14:13.480
I don't have a slide for this next thing,


00:14:13.480 --> 00:14:15.280
and it's a little confusing.


00:14:15.280 --> 00:14:17.280
And I apologize for presenting it so early.


00:14:17.280 --> 00:14:21.480
But I want to just say something honest.


00:14:21.480 --> 00:14:27.360
I've done a-- the characters I'm using here


00:14:27.360 --> 00:14:29.760
are the characters that I would prefer people


00:14:29.760 --> 00:14:31.560
to use for various reasons.


00:14:31.560 --> 00:14:36.040
However, Markdown has got a little bit of flexibility to it.


00:14:36.040 --> 00:14:40.400
And so it turns out that if you want bold text,


00:14:40.400 --> 00:14:41.440
I always use stars.


00:14:41.440 --> 00:14:45.520
And if I want italic text, I always use underscores.


00:14:45.520 --> 00:14:48.760
But Markdown rules say that it's actually


00:14:48.760 --> 00:14:52.600
the number of characters and not the character itself.


00:14:52.600 --> 00:14:58.080
So you can use underscores and stars to make bold and italic.


00:14:58.080 --> 00:14:59.720
If it's two, you're going to get bold.


00:14:59.720 --> 00:15:03.720
If it's one, you're going to get a talk.


00:15:03.720 --> 00:15:05.960
That sounds really confusing to me.


00:15:05.960 --> 00:15:08.440
I wanted to be honest and say it.


00:15:08.440 --> 00:15:10.800
Try to forget it now.


00:15:10.800 --> 00:15:12.840
Same thing with bullets.


00:15:12.840 --> 00:15:15.040
You can use a couple different characters.


00:15:15.040 --> 00:15:19.680
You can use a dash or you can use a star.


00:15:19.680 --> 00:15:24.200
And some people typing bullet lists,


00:15:24.200 --> 00:15:28.200
it's very common for them to use a star instead of a dash.


00:15:28.200 --> 00:15:33.520
There's reasons to use a dash, but stars are OK.


00:15:33.520 --> 00:15:36.240
I think you can actually even use pluses.


00:15:36.240 --> 00:15:43.080
The rule for those caveats is that if you're using one of


00:15:43.080 --> 00:15:44.360
them, you should stick with it.


00:15:44.360 --> 00:15:46.840
So these are all dashes, or I could use all stars.


00:15:46.840 --> 00:15:50.560
Same thing like this.


00:15:50.560 --> 00:15:53.760
If I'm using two stars or underscores,


00:15:53.760 --> 00:15:56.120
I have to use two at the front and two at the back.


00:15:56.120 --> 00:15:57.620
Two in front and one in back is going


00:15:57.620 --> 00:15:58.760
to make weird stuff happen.


00:15:58.760 --> 00:16:10.680
Here's some great resources for Markdown.


00:16:10.680 --> 00:16:14.640
They're actually not as great as I wish,


00:16:14.640 --> 00:16:17.240
because I didn't have time to find better ones.


00:16:17.240 --> 00:16:23.720
So the thing that's missing here is a cheat sheet, Markdown


00:16:23.720 --> 00:16:29.640
cheat sheet. What I would suggest you do is just search for Markdown cheat sheet. And


00:16:29.640 --> 00:16:36.200
I'll also probably add something to the community or to a document someplace. We'll get some


00:16:36.200 --> 00:16:41.720
better resources. These particular resources are kind of important. Daring Fireball is


00:16:41.720 --> 00:16:48.640
the guy who -- it's the blog of the guy who invented Markdown. He didn't invent the idea


00:16:48.640 --> 00:16:52.940
of markup, but he did specify the particular characters


00:16:52.940 --> 00:16:54.340
to use for markdown.


00:16:54.340 --> 00:16:57.340
So this is kind of the seminal document.


00:16:57.340 --> 00:17:02.380
Common mark is a cleanup kind of spec for markdown


00:17:02.380 --> 00:17:06.100
and a very common thing to use, at least for developers.


00:17:06.100 --> 00:17:10.300
And that's leaked into other tools, so it's important.


00:17:10.300 --> 00:17:13.020
There's something called GitHub Flavor Markdown.


00:17:13.020 --> 00:17:14.780
These are links.


00:17:14.780 --> 00:17:19.580
I think even now you could click on these and get to them


00:17:19.580 --> 00:17:24.540
or if you have this presentation later, you can.


00:17:24.540 --> 00:17:27.980
So let me go back to the beginning.


00:17:27.980 --> 00:17:34.380
So we've just covered Markdown.


00:17:34.380 --> 00:17:37.060
We're kind of a good chunk through what


00:17:37.060 --> 00:17:39.900
we want to talk about today.


00:17:39.900 --> 00:17:44.900
Next we'll cover Git and GitHub.


00:17:44.900 --> 00:17:53.820
So Git is a, I call it an apparatus.


00:17:53.820 --> 00:17:56.340
You could also call it a system.


00:17:56.340 --> 00:18:00.060
You could also call it an application.


00:18:00.060 --> 00:18:01.780
It's actually kind of a set of applications.


00:18:01.780 --> 00:18:04.500
You could also call it a protocol.


00:18:04.500 --> 00:18:06.460
It's kind of all of those things.


00:18:06.460 --> 00:18:11.460
It was created by Linus Tarvalds, the guy behind Linux,


00:18:11.460 --> 00:18:14.860
for working on the Linux kernel


00:18:14.860 --> 00:18:18.140
because he had people scattered all over the world


00:18:18.140 --> 00:18:19.180
trying to work together.


00:18:19.180 --> 00:18:22.100
And he's like, "This is just annoying."


00:18:22.100 --> 00:18:23.520
It turns out there's a long history


00:18:23.520 --> 00:18:25.780
of version control systems.


00:18:25.780 --> 00:18:28.520
They go back decades, decades and decades.


00:18:28.520 --> 00:18:33.460
And the kind of the lore is, the history is,


00:18:33.460 --> 00:18:35.340
the history is that Linus was actually using


00:18:35.340 --> 00:18:42.540
different version control system which he actually liked a lot but the people who owned


00:18:42.540 --> 00:18:47.000
it got kind of snippy about the way it was getting used.


00:18:47.000 --> 00:18:52.320
They thought they should make money or something, more money than they were making based on


00:18:52.320 --> 00:18:55.680
it getting used for Linux so much.


00:18:55.680 --> 00:19:02.200
So Linus sat down and wrote git, kind of like sitting down and writing a Unix kernel.


00:19:02.200 --> 00:19:12.520
what he does. So then GitHub came along later. You'll see that Git is a distributed version


00:19:12.520 --> 00:19:18.560
control system, which this was a kind of an innovation of version control systems. Distributed


00:19:18.560 --> 00:19:25.960
means that you can, you can, with your team, everybody can have a copy of the working materials


00:19:25.960 --> 00:19:32.600
And you can exchange them peer to peer with any person you want.


00:19:32.600 --> 00:19:37.280
So you don't have to have a central server someplace.


00:19:37.280 --> 00:19:43.520
That was a big advance and let loose a lot of cool collaboration stuff.


00:19:43.520 --> 00:19:47.520
It turns out that the centralization thing is also super important.


00:19:47.520 --> 00:19:51.080
And so there are people who invented GitHub.


00:19:51.080 --> 00:19:54.200
So let me get into the slides for these individual things


00:19:54.200 --> 00:19:54.800
real quick.


00:19:54.800 --> 00:20:00.880
Here's a system diagram that Bill Anderson and I


00:20:00.880 --> 00:20:03.120
created a couple of years ago.


00:20:03.120 --> 00:20:06.120
This happens to be for MassiveWiki.


00:20:06.120 --> 00:20:07.360
And you don't have to--


00:20:07.360 --> 00:20:08.560
sorry, it's kind of small.


00:20:08.560 --> 00:20:12.800
But you don't really have to see very much here.


00:20:12.800 --> 00:20:15.760
Conceptually, everybody's got a system


00:20:15.760 --> 00:20:17.280
where they've got an editor.


00:20:17.280 --> 00:20:23.480
and they're using Git software.


00:20:23.480 --> 00:20:26.120
If you look at these document sets,


00:20:26.120 --> 00:20:30.600
everyone's got a blue one, and everyone has other ones.


00:20:30.600 --> 00:20:35.160
So one person might have a few documents


00:20:35.160 --> 00:20:36.920
that they share just to themselves,


00:20:36.920 --> 00:20:40.040
what they might share with a completely different team.


00:20:40.040 --> 00:20:42.200
This team happens to be kind of defined


00:20:42.200 --> 00:20:43.920
by that blue set of documents.


00:20:43.920 --> 00:20:45.680
Everybody shares this.


00:20:45.680 --> 00:20:53.360
And they could be sharing it via peer-to-peer.


00:20:53.360 --> 00:20:56.000
But it turns out that mostly we end up sharing it


00:20:56.000 --> 00:20:59.720
through a centralizing GitHub.


00:20:59.720 --> 00:21:05.000
The generic term for what GitHub is is a GitForge.


00:21:05.000 --> 00:21:08.280
Forge is the central place where you kind of--


00:21:08.280 --> 00:21:12.040
the switching center to go through for everybody.


00:21:12.040 --> 00:21:14.560
One of the cool things that happens with this is that that


00:21:14.560 --> 00:21:19.560
means that if you need to swap files with a peer,


00:21:19.560 --> 00:21:22.100
but her computer is offline because it's late at night


00:21:22.100 --> 00:21:25.160
or early in the morning or whatever, she's not awake,


00:21:25.160 --> 00:21:28.800
you can swap it with the centralizer with GitHub.


00:21:28.800 --> 00:21:30.240
And then she can wake up later.


00:21:30.240 --> 00:21:33.840
You can turn your computer off and her computer can,


00:21:33.840 --> 00:21:36.840
or be offline, you know, in a tunnel or something like that.


00:21:36.840 --> 00:21:40.640
The other thing that the centralizer does really,


00:21:40.640 --> 00:21:42.960
really well is create a community of people


00:21:42.960 --> 00:21:45.720
you don't really know that you can cooperate with.


00:21:45.720 --> 00:21:50.180
So open source blossomed when GitHub was invented.


00:21:50.180 --> 00:21:52.640
And we'll get into that.


00:21:52.640 --> 00:21:54.920
That's a really amazing thing that happened


00:21:54.920 --> 00:21:57.440
and maybe it'll happen for text too.


00:21:57.440 --> 00:21:58.340
That'd be awesome.


00:21:58.340 --> 00:22:02.800
Charles, got a hand.


00:22:02.800 --> 00:22:05.880
- Hey, by the way, thanks and hi everyone.


00:22:05.880 --> 00:22:06.720
And you're doing great.


00:22:06.720 --> 00:22:09.880
I just, I had a quick question just to drop in the words


00:22:09.880 --> 00:22:12.800
push and pull, 'cause I think that's probably related.


00:22:12.800 --> 00:22:13.640
Yep.


00:22:13.640 --> 00:22:16.340
- If you have a little quick thing maybe on that, thanks.


00:22:16.340 --> 00:22:19.680
- Yeah, thanks Charles.


00:22:19.680 --> 00:22:30.720
There's a couple things and I'm gonna switch over to,


00:22:30.720 --> 00:22:32.980
so now I don't know how y'all are following along at home,


00:22:32.980 --> 00:22:36.040
but I'm gonna switch over to the HackMD thing


00:22:36.040 --> 00:22:39.080
and scroll down to maybe a good place.


00:22:39.080 --> 00:22:40.760
I'll do it up at the top.


00:22:40.760 --> 00:22:44.960
So at line 16, I'm making a new section.


00:22:44.960 --> 00:22:48.000
Let me make this maybe a little bit bigger in my computer.


00:22:48.000 --> 00:22:58.160
Get terminology.


00:22:58.160 --> 00:23:01.720
As Charles says, there's push, there's pull.


00:23:01.720 --> 00:23:03.200
Commit is another good one.


00:23:03.200 --> 00:23:04.700
Clone is a good one.


00:23:07.120 --> 00:23:12.120
And then there's kind of a fancy one called a pull request.


00:23:12.120 --> 00:23:18.560
Another good one is merge.


00:23:18.560 --> 00:23:32.800
Thinking through, there's a lot of stuff


00:23:32.800 --> 00:23:34.560
I wanna explain all at once,


00:23:34.560 --> 00:23:36.000
and obviously that's not gonna work.


00:23:36.000 --> 00:23:37.640
but real--


00:23:37.640 --> 00:23:39.160
- Just carry on your track, it's fine.


00:23:39.160 --> 00:23:40.720
I just want to drop them in.


00:23:40.720 --> 00:23:42.360
- No, yeah, it's awesome.


00:23:42.360 --> 00:23:43.960
And let's cover them real quick.


00:23:43.960 --> 00:23:47.680
When you wake up in the morning


00:23:47.680 --> 00:23:50.120
and you wanna know what happened with everybody else


00:23:50.120 --> 00:23:52.920
and you haven't had your computer automatically syncing,


00:23:52.920 --> 00:23:56.120
what you do is you pull.


00:23:56.120 --> 00:23:58.480
You say, I wanna get the freshest stuff.


00:23:58.480 --> 00:24:01.720
Let me pull down, grab the stuff from the cloud,


00:24:01.720 --> 00:24:03.120
pull it down to my computer.


00:24:03.120 --> 00:24:08.120
You work on your stuff for a while.


00:24:08.120 --> 00:24:10.520
There's a thing called commit,


00:24:10.520 --> 00:24:15.260
which is when I feel like I'm kind of done with this stuff


00:24:15.260 --> 00:24:19.560
and I want to commit it to posterity.


00:24:19.560 --> 00:24:23.020
So I make a commit.


00:24:23.020 --> 00:24:24.780
You can actually do a couple of commits at once


00:24:24.780 --> 00:24:25.960
and things like that.


00:24:25.960 --> 00:24:28.240
But anyway, I've got a bundle of stuff


00:24:28.240 --> 00:24:30.340
that I'm ready to push.


00:24:30.340 --> 00:24:34.040
So you pull from the cloud and you push to the cloud.


00:24:34.040 --> 00:24:36.640
And then the cloud conceptually is also connected


00:24:36.640 --> 00:24:39.960
to all your friends, your teammates.


00:24:39.960 --> 00:24:41.160
So that's pull and push.


00:24:41.160 --> 00:24:46.060
And that's good enough for now.


00:24:46.060 --> 00:24:53.640
So another great term is merging.


00:24:53.640 --> 00:24:57.300
This is maybe one of the most magic things about Git.


00:24:58.440 --> 00:25:02.660
I think conceptually, I wrote this slide literally


00:25:02.660 --> 00:25:03.600
like an hour and a half ago.


00:25:03.600 --> 00:25:06.520
Conceptually, I think this slide doesn't actually


00:25:06.520 --> 00:25:10.160
quite work, but follow along and it kind of works.


00:25:10.160 --> 00:25:14.920
So say A has been writing stuff,


00:25:14.920 --> 00:25:17.440
A and B both started writing something.


00:25:17.440 --> 00:25:20.840
And A has got four score on seven years,


00:25:20.840 --> 00:25:23.000
fourth on this continent, blah, blah, blah.


00:25:23.000 --> 00:25:27.320
Maybe in a previous version, they've co-written part


00:25:27.320 --> 00:25:37.720
this, but A doesn't have that important line here, "Ago our fathers brought." B typed that.


00:25:37.720 --> 00:25:43.640
Conversely, A has liberty and dedicated to that, and B doesn't have that yet.


00:25:43.640 --> 00:25:52.680
So there's a process where when you pull, you want to merge things. And the idea is that


00:25:54.680 --> 00:25:59.440
Git will automatically, for text files, line by line,


00:25:59.440 --> 00:26:00.640
it looks at the things.


00:26:00.640 --> 00:26:04.320
And where it sees that the lines are the same,


00:26:04.320 --> 00:26:06.360
that's how it kind of centers itself.


00:26:06.360 --> 00:26:10.120
Where it sees a difference, Git can magically


00:26:10.120 --> 00:26:14.680
tell that the second line in B isn't in A.


00:26:14.680 --> 00:26:17.080
And so it'll add it to the result.


00:26:17.080 --> 00:26:23.560
And this fifth line in B is missing what A has.


00:26:23.560 --> 00:26:26.520
So it'll add it to the result.


00:26:26.520 --> 00:26:29.000
Again, this is kind of a contrived example.


00:26:29.000 --> 00:26:30.720
It doesn't work very well, I don't think.


00:26:30.720 --> 00:26:34.600
But you kind of get the idea.


00:26:34.600 --> 00:26:39.240
If I'm a software developer, she wrote a subroutine,


00:26:39.240 --> 00:26:44.000
I wrote a subroutine, and we have a whole bunch


00:26:44.000 --> 00:26:46.160
of subroutines in a file.


00:26:46.160 --> 00:26:49.160
I can pull, and Git will automatically


00:26:49.160 --> 00:26:50.720
give me her subroutines.


00:26:50.720 --> 00:26:52.680
And when I push, it'll automatically


00:26:52.680 --> 00:27:00.280
give her my subroutines or paragraphs or you know whatever. And this works, it's


00:27:00.280 --> 00:27:05.400
very common for people to be working on a number of files at once. So in a book


00:27:05.400 --> 00:27:11.520
for instance you might have a file per paragraph, sorry, a file per chapter. So


00:27:11.520 --> 00:27:17.560
you've got a chapter 1 file, chapter 2 file, chapter 3 file, chapter 4. And so


00:27:17.560 --> 00:27:20.820
Paul is working on chapter two.


00:27:20.820 --> 00:27:22.540
Susan is working on chapter four.


00:27:22.540 --> 00:27:24.880
They're typing away and stuff like that.


00:27:24.880 --> 00:27:28.120
In the process of pushing and pulling during the day,


00:27:28.120 --> 00:27:29.380
you don't just do it in the morning.


00:27:29.380 --> 00:27:31.940
You do it when you're at a good stopping place


00:27:31.940 --> 00:27:32.780
during the day.


00:27:32.780 --> 00:27:37.100
Paul ends up with the changes that Susan's made.


00:27:37.100 --> 00:27:40.580
Susan ends up with the changes that Paul's made.


00:27:40.580 --> 00:27:43.860
And this scales dramatically.


00:27:43.860 --> 00:27:47.300
It's okay if the team is 10 people


00:27:47.300 --> 00:27:49.340
And it's OK if some of the people are working a lot


00:27:49.340 --> 00:27:53.700
and some of the people aren't working a lot on the text.


00:27:53.700 --> 00:27:55.540
Maybe Paul is working on it every day


00:27:55.540 --> 00:27:58.460
as soon as he's working on it every month.


00:27:58.460 --> 00:28:00.340
All of that kind of stuff just magically works.


00:28:00.340 --> 00:28:06.780
A thing I didn't cover is merge conflicts.


00:28:06.780 --> 00:28:12.660
And I will add that to line 26 here.


00:28:12.660 --> 00:28:25.660
So the magic only goes so far.


00:28:25.660 --> 00:28:30.660
If A had four score and seven years, and then another line here,


00:28:30.660 --> 00:28:34.660
Mary had a little lamb, fourth on this continent,


00:28:34.660 --> 00:28:39.660
and B had four score and seven years ago, our father's brat.


00:28:39.660 --> 00:28:49.140
If A and B had conflicting lines in the same place, Git would go, "Huh, I don't know what


00:28:49.140 --> 00:28:51.540
they meant and I'm not smart enough to figure it out."


00:28:51.540 --> 00:28:56.740
So I'll kind of, I'll flag that as a conflict.


00:28:56.740 --> 00:29:00.380
I'll fix all the other ones that I can do automatically, but my magic doesn't go that


00:29:00.380 --> 00:29:01.380
far.


00:29:01.380 --> 00:29:02.380
I don't know what they meant.


00:29:02.380 --> 00:29:04.660
I'm going to leave the humans to figure it out.


00:29:04.660 --> 00:29:07.300
So that happens.


00:29:07.300 --> 00:29:15.440
In practice, you kind of collaborate out of band, you coordinate out of band to minimize


00:29:15.440 --> 00:29:18.800
the times that that happens.


00:29:18.800 --> 00:29:23.280
So when I said Paul is working on chapter 2 and Susan is working on chapter 4, part


00:29:23.280 --> 00:29:27.960
of the reason they're doing that is because, you know, at the weekly meeting, they agreed,


00:29:27.960 --> 00:29:30.640
hey, Paul, you're going to be working on chapter 2 a lot.


00:29:30.640 --> 00:29:33.060
I don't want to make any merge conflicts.


00:29:33.060 --> 00:29:35.400
So I'll work on chapter 4 this week.


00:29:35.400 --> 00:29:37.120
Sound good?


00:29:37.120 --> 00:29:38.900
And then Susan can follow along.


00:29:38.900 --> 00:29:42.320
She can see how Paul is working on chapter two.


00:29:42.320 --> 00:29:44.940
We'll get to GitHub collaboration.


00:29:44.940 --> 00:29:47.580
She can actually make comments on some of the changes


00:29:47.580 --> 00:29:51.380
or she can suggest changes into the stuff


00:29:51.380 --> 00:29:54.460
that Paul is kind of working on mostly, things like that.


00:29:54.460 --> 00:30:02.520
So same thing here.


00:30:02.520 --> 00:30:07.520
I wish there was an easy Git cheat sheet.


00:30:07.520 --> 00:30:14.160
Git itself, so we covered a lot of good news.


00:30:14.160 --> 00:30:16.120
Good news is we have this fancy technology.


00:30:16.120 --> 00:30:18.480
It's all free, it's all very powerful.


00:30:18.480 --> 00:30:20.040
It's fun to use.


00:30:20.040 --> 00:30:23.160
It's a blast to be productive with a team.


00:30:23.160 --> 00:30:24.760
It's mind-blowingly cool in a way


00:30:24.760 --> 00:30:27.360
that software developers get to do every day


00:30:27.360 --> 00:30:28.920
and writers mostly don't.


00:30:28.920 --> 00:30:31.200
And it makes me just terribly sad about that.


00:30:31.200 --> 00:30:32.200
That's the way it is.


00:30:32.200 --> 00:30:34.940
Bill.


00:30:34.940 --> 00:30:40.840
- Yeah, quick question.


00:30:40.840 --> 00:30:44.400
Does HackMD run on top of Git?


00:30:44.400 --> 00:30:48.920
'Cause I noticed, I mean, it's using the Git.


00:30:48.920 --> 00:30:52.400
- That's a great question.


00:30:52.400 --> 00:30:53.760
- What are we seeing here?


00:30:53.760 --> 00:30:55.400
'Cause you're illustrating on something


00:30:55.400 --> 00:30:57.480
was actually doing what you're saying.


00:30:57.480 --> 00:31:00.880
- That's a great question.


00:31:00.880 --> 00:31:06.640
And it's using Git-like technology.


00:31:06.640 --> 00:31:08.280
It's actually something different.


00:31:08.280 --> 00:31:15.720
The general class of the things that HackMD is using--


00:31:15.720 --> 00:31:20.680
and this is the same thing that Google Docs uses.


00:31:20.680 --> 00:31:22.200
Instead of Microsoft Word, people


00:31:22.200 --> 00:31:25.880
are using Google Docs because everybody gets to type, right?


00:31:25.880 --> 00:31:31.600
or everybody gets to put in different things in the document.


00:31:31.600 --> 00:31:34.280
Conceptually, it's a very similar technology,


00:31:34.280 --> 00:31:37.240
except it's character by character.


00:31:37.240 --> 00:31:40.880
And it's connected to a central server, generally,


00:31:40.880 --> 00:31:43.600
which doesn't matter too much.


00:31:43.600 --> 00:31:47.400
So your browser-- everybody's browser


00:31:47.400 --> 00:31:51.560
is, for every character or every editing command,


00:31:51.560 --> 00:31:57.400
like Backspace, it's doing this merge thing together


00:31:57.400 --> 00:31:58.960
with everybody else.


00:31:58.960 --> 00:32:01.640
So it's very similar in that sense.


00:32:01.640 --> 00:32:07.200
Because it's every character and you


00:32:07.200 --> 00:32:08.720
want to be able to type really fast


00:32:08.720 --> 00:32:13.760
and have everything happen, you don't have that commit phase


00:32:13.760 --> 00:32:16.480
where you can batch up a bunch of changes


00:32:16.480 --> 00:32:19.640
and say, here's a bunch of changes I want to make.


00:32:19.640 --> 00:32:22.640
let's all review that and see if it should get merged


00:32:22.640 --> 00:32:25.420
into the main branch.


00:32:25.420 --> 00:32:32.920
In some Nirvana future, probably not that far away,


00:32:32.920 --> 00:32:35.880
but it might be years still,


00:32:35.880 --> 00:32:38.580
we would have both things working together.


00:32:38.580 --> 00:32:40.580
We'd have this real-time collaboration,


00:32:40.580 --> 00:32:41.600
character by character,


00:32:41.600 --> 00:32:44.820
and then we would also have that kind of more phased approach


00:32:44.820 --> 00:32:45.760
line by line.


00:32:45.760 --> 00:32:48.400
We're not quite there yet.


00:32:48.400 --> 00:32:54.800
So I'm going to--


00:32:54.800 --> 00:32:56.260
thanks, Bill.


00:32:56.260 --> 00:32:58.220
I'm going to click into these links a little bit


00:32:58.220 --> 00:32:59.340
because they've got cool--


00:32:59.340 --> 00:33:01.260
at least the first one has cool pictures.


00:33:01.260 --> 00:33:12.100
And I'm going to ask you to do a little bit of a tricky thing


00:33:12.100 --> 00:33:13.540
here.


00:33:13.540 --> 00:33:16.580
This merge thing is one concept you kind of


00:33:16.580 --> 00:33:25.380
to hold in your head, and then another thing called branching. And I'm going to this particular page,


00:33:25.380 --> 00:33:31.940
and I don't think this will follow along if you're watching the presentation,


00:33:31.940 --> 00:33:41.460
so now you have to watch the screen. There's a couple things about this page. Git flow was a


00:33:41.460 --> 00:33:48.260
revelation when it came out. And it's kind of funny the author has put a note here. It's like


00:33:48.260 --> 00:33:54.980
GitFlow is kind of like old news now at this point. But it's still important and still foundational.


00:33:54.980 --> 00:34:05.540
It's also got a great set of diagrams. So Git uses this thing called branches. And each branch


00:34:05.540 --> 00:34:10.340
here is represented by these arrows, these lines going down.


00:34:10.340 --> 00:34:14.580
And a lot of times you'll see them sideways too.


00:34:14.580 --> 00:34:18.260
I have a really hard time understanding what


00:34:18.260 --> 00:34:22.820
those lines mean. It's kind of like the branches of a tree or something like


00:34:22.820 --> 00:34:26.020
that, and I find it confusing to kind of keep in


00:34:26.020 --> 00:34:30.260
mind what's going on by looking at a picture. I think that's


00:34:30.260 --> 00:34:34.980
probably not true for everybody. Some people probably makes a lot of sense.


00:34:34.980 --> 00:34:41.620
some people it doesn't make any sense. So these diagrams are kind of helpful but kind of not,


00:34:41.620 --> 00:34:50.180
I think. So anyway, this diagram kind of does work for me because it's got different colors and


00:34:50.180 --> 00:34:56.500
and the side cross arrows and things like this. This is a very complicated collaboration scenario,


00:34:56.500 --> 00:35:04.820
by the way. So this is what you would use in a heavyweight enterprise software development thing


00:35:04.820 --> 00:35:07.940
where you've got 50 or 100 or 200 people working together.


00:35:07.940 --> 00:35:15.620
And you've got different releases, and you've got to bug fix the existing versions out in the field,


00:35:15.620 --> 00:35:20.660
and you have to keep track of different versions, because this company bought this version,


00:35:20.660 --> 00:35:24.980
that company, and can't upgrade for a while. This other company has a newer version,


00:35:24.980 --> 00:35:31.300
they upgrade a lot. So all of that complexity is kind of handled, managed by this amount of


00:35:33.860 --> 00:35:44.660
overhead. So don't be like, you can kind of squint your eyes and go, okay, I kind of know


00:35:44.660 --> 00:35:52.180
what's going on here. I kind of understand what's going on. We will probably never get this complex


00:35:52.180 --> 00:35:58.260
doing anything. But at the same time, you want to know that you could do it. And you want to borrow


00:35:58.260 --> 00:36:02.820
important chunks of this to kind of make a toy version of this that's as big as you need.


00:36:02.820 --> 00:36:11.820
So, all the way on the right is a branch called master.


00:36:11.820 --> 00:36:18.820
Master is the kind of original name for this going back 10 or 15 years.


00:36:18.820 --> 00:36:24.820
It's now due to sensitivity around language, master is usually called main now.


00:36:24.820 --> 00:36:28.820
So this is the main branch all the way at the right.


00:36:28.820 --> 00:36:33.820
And as a developer, say I want to do some work,


00:36:33.820 --> 00:36:42.080
what I do is I kind of copy or clone this master branch


00:36:42.080 --> 00:36:46.540
maybe in the morning over to say the develop branch here


00:36:46.540 --> 00:36:47.980
with the yellow balls.


00:36:47.980 --> 00:36:51.120
I can make edits and I can make edits


00:36:51.120 --> 00:36:52.380
and I can make edits.


00:36:52.380 --> 00:36:57.380
And then at some point, if you follow this diagram


00:36:57.380 --> 00:37:00.260
are down a ways, the yellow goes to green


00:37:00.260 --> 00:37:01.620
and the green goes to blue.


00:37:01.620 --> 00:37:04.380
So you can kind of simplify this.


00:37:04.380 --> 00:37:06.420
You can skip that green step


00:37:06.420 --> 00:37:09.980
unless you wanna do like a testing version


00:37:09.980 --> 00:37:10.900
or something like that.


00:37:10.900 --> 00:37:15.380
All these extra steps happen a lot in software development.


00:37:15.380 --> 00:37:17.300
But for a writing project,


00:37:17.300 --> 00:37:21.000
you'd probably just do blue and yellow and blue.


00:37:21.000 --> 00:37:25.780
So then in the morning,


00:37:25.780 --> 00:37:30.780
I pull and get a version that I can work on.


00:37:30.780 --> 00:37:34.780
Susan pulls and gets a version she can work on.


00:37:34.780 --> 00:37:37.180
So there's actually a couple yellow things


00:37:37.180 --> 00:37:38.700
going on at the same time.


00:37:38.700 --> 00:37:43.200
And we can both work and then we can kind of both


00:37:43.200 --> 00:37:47.380
put our work back to the main branch at the right.


00:37:47.380 --> 00:37:48.980
So that's kind of what happens.


00:37:48.980 --> 00:38:01.700
Git flow is actually, it's got that complexity and it's an important model.


00:38:01.700 --> 00:38:03.860
People have kind of moved on past a little bit.


00:38:03.860 --> 00:38:08.560
They've gotten a little bit fancier, simplified in ways, but complexified in other ways.


00:38:08.560 --> 00:38:12.820
It has that pretty picture, which is the main reason we were going there today.


00:38:12.820 --> 00:38:18.420
Let me also look at this GitHub flow page.


00:38:18.420 --> 00:38:22.200
doesn't have any pretty picture but this is a lot more what I was describing


00:38:22.200 --> 00:38:26.120
where you have the blue main and the yellow develop things for different


00:38:26.120 --> 00:38:33.680
people. So this describes that even though it doesn't have a picture. ProGit


00:38:33.680 --> 00:38:41.600
is a ebook. It's kind of like the canonical documentation for Git. It's a


00:38:41.600 --> 00:38:48.500
a good book, nobody except real geeks would ever read the whole thing.


00:38:48.500 --> 00:38:53.140
So what you do is you do a web search and you find a page on here and you go, "Oh, that's


00:38:53.140 --> 00:38:55.700
the way it's supposed to work."


00:38:55.700 --> 00:39:01.280
Git is fantastically complex, behind the hood.


00:39:01.280 --> 00:39:05.420
It's got a lot of capability because it was written by software developers trying to do


00:39:05.420 --> 00:39:06.940
really hard stuff.


00:39:06.940 --> 00:39:09.860
So they kept adding stuff and adding stuff and adding stuff.


00:39:09.860 --> 00:39:14.080
It didn't get shepherded well for user experience.


00:39:14.080 --> 00:39:19.300
So all the stuff that got added is it all works together, but it's all a little bit


00:39:19.300 --> 00:39:20.980
different the way it works.


00:39:20.980 --> 00:39:28.740
So the simple stuff, going back to our HackMD with the Git terminology, push, pull, commit,


00:39:28.740 --> 00:39:32.820
merge, it's conceptually pretty simple.


00:39:32.820 --> 00:39:39.640
You can fall into the deep end of Git and it can get really difficult.


00:39:39.640 --> 00:39:46.920
So that's kind of a way for me to back into the, you know, there's, here be dragons.


00:39:46.920 --> 00:39:53.840
We can work together to make it so that we don't get eaten by dragons.


00:39:53.840 --> 00:39:56.320
It would take a little bit of work to make that happen.


00:39:56.320 --> 00:40:01.600
So that's going to be the main cost probably for this whole thing.


00:40:01.600 --> 00:40:02.600
Charles.


00:40:02.600 --> 00:40:09.320
Another quick question, because you mentioned dragons, and I was just thinking to, I don't


00:40:09.320 --> 00:40:17.800
if it fits exactly here or actually if GitHub is sort of related to where you we go with this but


00:40:17.800 --> 00:40:23.240
you know the Microsoft acquiring GitHub is a is a kind of question with a lot of dimensions so I


00:40:23.240 --> 00:40:29.240
don't know if that's a dragon that's relevant but it is it's super relevant and if somebody


00:40:29.240 --> 00:40:32.200
could write down Microsoft someplace on the notes I would really appreciate it.


00:40:34.520 --> 00:40:36.520
I don't want to get too deep into it.


00:40:36.520 --> 00:40:44.240
GitHub was originally kind of a hero of open source.


00:40:44.240 --> 00:40:48.760
It created a lot of the open source collaboration model


00:40:48.760 --> 00:40:50.560
that we have today,


00:40:50.560 --> 00:40:53.640
where people who don't know each other work together.


00:40:53.640 --> 00:40:56.860
It was magical and wonderful.


00:40:56.860 --> 00:41:01.200
20 years later, whatever, it wasn't a perfect thing either.


00:41:01.200 --> 00:41:04.040
There's horror stories about some of the people at GitHub


00:41:04.040 --> 00:41:09.080
stuff like that. But in the main, it was a beautiful and wonderful thing. It was a boon


00:41:09.080 --> 00:41:15.080
to humanity. It actually, like, if you thought about the boost that it gave to productivity


00:41:15.080 --> 00:41:21.080
in software, and then software goes everywhere, kind of, it's huge. It's a big thing. It's a big


00:41:21.080 --> 00:41:28.280
deal. GitHub is awesome. And kind of like Twitter, it ended up being a super big thing. So not only


00:41:28.280 --> 00:41:33.240
was it a cool thing for a few people, it ended up being like a society-wide thing where everybody


00:41:33.240 --> 00:41:36.320
but it was using it day in, day out for a lot of stuff.


00:41:36.320 --> 00:41:40.720
So that's the good news.


00:41:40.720 --> 00:41:44.260
The other news is that Microsoft bought it a few years ago.


00:41:44.260 --> 00:41:49.280
Microsoft has, if you zoom out


00:41:49.280 --> 00:41:53.040
and get a 30,000 foot view of the open source ecosystem,


00:41:53.040 --> 00:41:56.400
Microsoft has been kind of like cherry picking parts


00:41:56.400 --> 00:41:59.360
of the ecosystem and acquiring it


00:41:59.360 --> 00:42:03.000
and then improving it, improving that little part


00:42:03.000 --> 00:42:05.800
in a way that you go, oh, well,


00:42:05.800 --> 00:42:07.940
I could use the clunky, you know, open source version.


00:42:07.940 --> 00:42:10.120
I could use the open source version


00:42:10.120 --> 00:42:11.900
that Microsoft is supporting.


00:42:11.900 --> 00:42:13.300
That would be a beautiful, wonderful thing


00:42:13.300 --> 00:42:15.500
because there's more capability.


00:42:15.500 --> 00:42:18.840
And everybody has been getting hypnotized


00:42:18.840 --> 00:42:22.080
into using the Microsoft version of open source


00:42:22.080 --> 00:42:25.280
rather than the open version of open source.


00:42:25.280 --> 00:42:30.280
So if you look the right way,


00:42:30.280 --> 00:42:33.480
Microsoft isn't fighting open source,


00:42:33.480 --> 00:42:36.760
but they're embracing it and smothering it kind of.


00:42:36.760 --> 00:42:41.120
Smothering it is a strong word.


00:42:41.120 --> 00:42:42.440
They're not killing it,


00:42:42.440 --> 00:42:46.000
but they are definitely bending it to their direction


00:42:46.000 --> 00:42:52.000
in a big way and in massive ecosystem ways, not unlike,


00:42:52.000 --> 00:42:57.240
it's the Twitter, the Microsoft takeover of GitHub


00:42:57.360 --> 00:43:00.800
is kind of like the Elon takeover of Twitter.


00:43:00.800 --> 00:43:05.680
It changed it from a community commons to a--


00:43:05.680 --> 00:43:07.840
it's owned by interesting people.


00:43:07.840 --> 00:43:14.200
And so because it's such a centralized location


00:43:14.200 --> 00:43:19.440
for all of open source, it is hard to move away from.


00:43:19.440 --> 00:43:25.400
And Microsoft isn't being quite so nasty as Elon is--


00:43:25.400 --> 00:43:28.440
or crazy maybe is a different way to say it.


00:43:28.440 --> 00:43:32.240
But there's definitely warning signs.


00:43:32.240 --> 00:43:39.280
And long story short, there are a couple more open source


00:43:39.280 --> 00:43:40.800
Gitforges.


00:43:40.800 --> 00:43:43.000
There's one called--


00:43:43.000 --> 00:43:44.120
I think actually if--


00:43:44.120 --> 00:43:45.720
I'm going to skip ahead in the slides.


00:43:45.720 --> 00:43:48.440
Yeah.


00:43:48.440 --> 00:43:49.600
There are other forges.


00:43:49.600 --> 00:43:50.840
There's one called Codeburg.


00:43:50.840 --> 00:43:53.320
There's one called GitLab.


00:43:53.320 --> 00:43:55.320
Those are both very open source friendly.


00:43:55.320 --> 00:44:00.520
There's another one called Sourcehut.


00:44:00.520 --> 00:44:06.520
Sourcehut is aggressively kind of open source


00:44:06.520 --> 00:44:09.080
in a very opinionated way.


00:44:09.080 --> 00:44:11.080
Sourcehut is an amazing and wonderful thing.


00:44:11.080 --> 00:44:13.000
I'm sorry they didn't put it in this list here.


00:44:13.000 --> 00:44:14.760
I'll add that.


00:44:14.760 --> 00:44:18.800
But it's so opinionated that it can be hard to use.


00:44:18.800 --> 00:44:22.080
Codeberg is kind of, I think, the best replacement for it.


00:44:22.080 --> 00:44:25.960
Codeburg is using software called Forgeo.


00:44:25.960 --> 00:44:29.840
Forgeo is a fork of Gitty.


00:44:29.840 --> 00:44:35.080
So you can actually run your own Gitty or Forgeo instance.


00:44:35.080 --> 00:44:37.000
You can even use a tiny little thing called


00:44:37.000 --> 00:44:41.760
Git, which has no admin interface except a Git


00:44:41.760 --> 00:44:43.840
repository.


00:44:43.840 --> 00:44:46.040
What's that repository also?


00:44:46.040 --> 00:44:50.480
A repository in Git is the set of all the files


00:44:50.480 --> 00:44:51.200
you're working on.


00:44:51.200 --> 00:44:57.180
So for a book, it would be all of the chapters and probably also some additional, you know,


00:44:57.180 --> 00:45:02.240
like materials that you're using, notes, notes to yourselves, research things and stuff like


00:45:02.240 --> 00:45:03.240
that.


00:45:03.240 --> 00:45:04.240
That's a repository.


00:45:04.240 --> 00:45:08.200
You can have lots of repositories, but you kind of cluster, you know, all your files


00:45:08.200 --> 00:45:14.400
together into a repository.


00:45:14.400 --> 00:45:16.640
We're running out of time.


00:45:16.640 --> 00:45:21.120
I still want to cover one more thing real quick.


00:45:21.120 --> 00:45:27.520
So this is kind of the pearl of this meeting.


00:45:27.520 --> 00:45:33.960
It's an example that I have from an open source project


00:45:33.960 --> 00:45:37.920
that I wrote a couple years ago called Obsidian Settings


00:45:37.920 --> 00:45:39.800
Manager.


00:45:39.800 --> 00:45:41.360
It happens to be for Obsidian.


00:45:41.360 --> 00:45:42.840
That's not why I picked this.


00:45:42.840 --> 00:45:46.240
I picked it because something really cool happened.


00:45:46.240 --> 00:45:48.400
I wrote this code a couple of years ago.


00:45:48.400 --> 00:45:53.400
And in July, this guy named Doug Phillips,


00:45:53.400 --> 00:45:59.000
sorry, I didn't get what I wanted.


00:45:59.000 --> 00:46:02.840
Doug Phillips kind of whizzed by on GitHub and he said,


00:46:02.840 --> 00:46:05.560
"Huh, this is a software that I wanna use,


00:46:05.560 --> 00:46:07.840
"except it doesn't quite work the way I want it,


00:46:07.840 --> 00:46:12.580
"but it's on GitHub, so I can pull it down.


00:46:12.580 --> 00:46:13.420
"I can clone it."


00:46:13.420 --> 00:46:16.260
It's actually, cloning is grabbing everything,


00:46:16.260 --> 00:46:18.080
a fresh version of everything.


00:46:18.080 --> 00:46:21.620
I can clone it, I can make changes to it.


00:46:21.620 --> 00:46:25.480
And then I can suggest those changes back to Pete.


00:46:25.480 --> 00:46:34.960
So this uses a GitHub concept called the pull request.


00:46:34.960 --> 00:46:37.440
And other forges do this now too.


00:46:37.440 --> 00:46:39.440
They call it different things sometimes.


00:46:39.440 --> 00:46:46.760
But what Doug did was he changed the way it worked.


00:46:46.760 --> 00:46:49.880
And then he sent me a message through GitHub,


00:46:49.880 --> 00:46:51.600
which is all kind of automated.


00:46:51.600 --> 00:46:55.040
You can click this button, New Poll Request.


00:46:55.040 --> 00:46:58.120
He did this thing where he said--


00:46:58.120 --> 00:46:59.520
let me show it to you, actually.


00:46:59.520 --> 00:47:05.960
Hi, Peter, I found your repo.


00:47:05.960 --> 00:47:06.920
I'm on Linux.


00:47:06.920 --> 00:47:07.600
I'm on Mac.


00:47:07.600 --> 00:47:12.640
I needed to make some changes.


00:47:12.640 --> 00:47:15.040
So he didn't even send me an email.


00:47:15.040 --> 00:47:18.560
He sent me this to the GitHub collaboration mechanism.


00:47:18.560 --> 00:47:21.120
So I get this message and I look at it


00:47:21.120 --> 00:47:26.120
and he's got this whole set of changes that he's made.


00:47:26.120 --> 00:47:29.920
So I can look at each of these changes


00:47:29.920 --> 00:47:34.020
and I think it's reverse chronological.


00:47:34.020 --> 00:47:36.540
So for each of these changes,


00:47:36.540 --> 00:47:38.760
I can look at the changes he's made.


00:47:38.760 --> 00:47:42.660
He's deleted things in red and added stuff in green.


00:47:43.560 --> 00:47:48.560
And I can step through the various changes he made.


00:47:48.560 --> 00:47:51.440
Doug is a careful software developer.


00:47:51.440 --> 00:47:56.240
So he collapsed or when he made changes,


00:47:56.240 --> 00:48:00.120
he made just an atomic change kind of,


00:48:00.120 --> 00:48:03.440
and then said, I'm going to commit this.


00:48:03.440 --> 00:48:06.640
All of those commits ended up being a bundle.


00:48:06.640 --> 00:48:11.320
And that, sorry, it's a little bit hard


00:48:11.320 --> 00:48:12.280
to talk and think here,


00:48:12.280 --> 00:48:22.480
bit. That all ended up being one pull request. I can look at the pull request altogether.


00:48:22.480 --> 00:48:28.680
This is actually just one file in this one. Let me get back to kind of where we were looking


00:48:28.680 --> 00:48:35.080
at pull requests. You can see there's one open pull request, 10 closed. The process


00:48:35.080 --> 00:48:42.280
of this is he makes a pull request, I look at it, make some comments, and I can either


00:48:42.280 --> 00:48:49.280
comment on everything or I can comment on specific changes. Let me see if we can see


00:48:49.280 --> 00:49:00.320
a more specific change. Yeah, I don't know. So here is bolded the exact part of this line


00:49:00.320 --> 00:49:05.600
that's changed. This is not something that Git does, but GitHub has a fancy version of the


00:49:05.600 --> 00:49:15.760
differences thing. I can go here and I can say, you know, "What the heck are you doing?"


00:49:15.760 --> 00:49:26.240
or whatever, right? So literally line by line, I can go through and comment on changes. I can


00:49:28.320 --> 00:49:30.320
you know, look at this whole thing and say,


00:49:30.320 --> 00:49:31.740
this all looks great.


00:49:31.740 --> 00:49:36.980
This looks, it's really common to say, looks good to me.


00:49:36.980 --> 00:49:44.580
And you can, this ends up being in a,


00:49:44.580 --> 00:49:46.440
kind of a threaded discussion


00:49:46.440 --> 00:49:48.480
around all the different files.


00:49:48.480 --> 00:49:52.800
This is pull request number four.


00:49:52.800 --> 00:49:55.520
Here's me saying, looks good to me.


00:49:55.520 --> 00:49:56.800
Here's me merging it.


00:49:56.800 --> 00:50:04.900
There's with a little bit more prep, I could have taken a better tour through this.


00:50:04.900 --> 00:50:07.160
There are places where we're going back and forth.


00:50:07.160 --> 00:50:10.620
You know, that part looks good, except that you need to do it a little bit different way.


00:50:10.620 --> 00:50:13.460
Or I'm going to take this part.


00:50:13.460 --> 00:50:14.460
This looks great.


00:50:14.460 --> 00:50:18.440
But let's work on this part because it's not quite right yet at all.


00:50:18.440 --> 00:50:22.960
So you can bounce parts of the pull request out for later.


00:50:22.960 --> 00:50:25.040
You can take parts of them and save them.


00:50:25.040 --> 00:50:28.040
you can merge them all and do wonderful things.


00:50:28.040 --> 00:50:31.520
So not that this was a very good demo of it,


00:50:31.520 --> 00:50:34.400
but this is kind of where I'm hoping


00:50:34.400 --> 00:50:35.860
at least some of us get to go


00:50:35.860 --> 00:50:40.200
into a place where we're collaborating like that.


00:50:40.200 --> 00:50:44.840
And real quick, let's hit tools.


00:50:44.840 --> 00:50:49.200
The tools that you need are Git,


00:50:49.200 --> 00:50:50.940
which I didn't even make this list,


00:50:50.940 --> 00:50:52.400
your favorite text editor.


00:50:52.400 --> 00:50:54.520
You don't really need a markdown editor,


00:50:54.520 --> 00:50:56.640
but you can use other tools to get fancier


00:50:56.640 --> 00:50:58.640
and stuff like that.


00:50:58.640 --> 00:51:00.380
So that's where we are.


00:51:00.380 --> 00:51:05.320
Let me stop sharing my screen


00:51:05.320 --> 00:51:07.780
and I apologize for going over time a little bit.


00:51:07.780 --> 00:51:13.780
Where should we go next?


00:51:13.780 --> 00:51:16.120
Do we wanna do this again in a week?


00:51:16.120 --> 00:51:18.480
Do we wanna do it again with Pete presenting,


00:51:18.480 --> 00:51:20.400
talking head style and going through stuff?


00:51:20.400 --> 00:51:22.080
Maybe a little bit more prep.


00:51:22.080 --> 00:51:26.000
Do we want to slow down and do kind of a collaborative work


00:51:26.000 --> 00:51:26.800
session?


00:51:26.800 --> 00:51:27.520
What should we do?


00:51:27.520 --> 00:51:32.840
Anything quick to say about the writing


00:51:32.840 --> 00:51:35.800
compared to the software stuff?


00:51:35.800 --> 00:51:38.200
Yeah, it's a great question.


00:51:38.200 --> 00:51:42.560
Software is just another language, basically.


00:51:42.560 --> 00:51:45.960
So it has lines of text.


00:51:45.960 --> 00:51:48.160
It kind of has things like paragraphs.


00:51:48.160 --> 00:51:51.540
It has things like chapters, and chapters are modules.


00:51:51.540 --> 00:51:56.720
If you don't mind stepping back from Microsoft Word


00:51:56.720 --> 00:52:00.420
or Google Docs a little bit into plain text


00:52:00.420 --> 00:52:02.880
and making sure that you do things online


00:52:02.880 --> 00:52:06.240
so that Git can do its automatic merging magic,


00:52:06.240 --> 00:52:08.000
they're essentially the same thing.


00:52:08.000 --> 00:52:13.980
Even down to software developers have a bunch of conventions


00:52:14.120 --> 00:52:17.320
around noting problems, you know,


00:52:17.320 --> 00:52:20.800
or bundling up sets of changes, you know,


00:52:20.800 --> 00:52:22.680
here's a bunch of changes to chapter one.


00:52:22.680 --> 00:52:26.040
And I also needed to change some wording in chapter three


00:52:26.040 --> 00:52:28.760
and five to go along with the changes in chapter one.


00:52:28.760 --> 00:52:31.760
All of that stuff that writers do,


00:52:31.760 --> 00:52:34.920
software developers have figured out and systematized.


00:52:34.920 --> 00:52:38.140
So I think it's a match made in heaven.


00:52:43.760 --> 00:52:44.600
Bill?


00:52:44.600 --> 00:52:50.140
- Sometimes I learn better by doing.


00:52:50.140 --> 00:52:54.480
Once, you know, I like to have the kind


00:52:54.480 --> 00:52:55.640
of the comprehensive view


00:52:55.640 --> 00:52:57.440
of what is really gonna happen here.


00:52:57.440 --> 00:53:01.320
But if we had a little short kind of an exercise


00:53:01.320 --> 00:53:04.520
we could all participate in together,


00:53:04.520 --> 00:53:07.960
maybe that would be an efficient way to get a feel for it


00:53:07.960 --> 00:53:09.560
and would raise other questions.


00:53:09.560 --> 00:53:11.480
But just a thought. - Yeah, that's brilliant.


00:53:11.480 --> 00:53:12.320
Yeah.


00:53:13.560 --> 00:53:14.060
>> Great.


00:53:14.060 --> 00:53:20.280
>> So I want to say again, thank you very much.


00:53:20.280 --> 00:53:26.600
Like I have sort of a vision that I had in mind of my personal motivation


00:53:26.600 --> 00:53:30.960
when I saw that you wanted to do this for saying, great, let's do it.


00:53:30.960 --> 00:53:37.760
And it is to, just as you said, to actually be able to facilitate


00:53:37.760 --> 00:53:43.640
collaborative writing with exactly the same flows as developers use.


00:53:43.640 --> 00:53:49.720
So you didn't say that explicitly when you were like waiting into


00:53:49.720 --> 00:53:53.240
the project that you had on GitHub which somebody forked and


00:53:53.240 --> 00:53:56.480
then started to make changes and gave you a pull request.


00:53:56.480 --> 00:53:58.000
>> Yep. >> But I think it's important for


00:53:58.000 --> 00:54:01.200
everyone to imagine being able to do exactly the same sort of thing,


00:54:01.200 --> 00:54:06.560
to work together in an organized way on a document.


00:54:06.560 --> 00:54:08.280
It could be an academic paper,


00:54:08.280 --> 00:54:11.960
it could be a white paper for a project,


00:54:11.960 --> 00:54:15.760
and really systematize that process


00:54:15.760 --> 00:54:19.200
to efficiently work together to create something better


00:54:19.200 --> 00:54:23.920
than one person might be able to do on their own.


00:54:23.920 --> 00:54:27.800
And that's beautiful, both for the output


00:54:27.800 --> 00:54:30.720
that can come from it, but also as a way


00:54:30.720 --> 00:54:35.720
for people to learn to function well together as a team.


00:54:36.480 --> 00:54:39.280
And that's what I think is really awesome about this.


00:54:39.280 --> 00:54:41.440
- Yeah, I totally agree.


00:54:41.440 --> 00:54:43.520
That's the dream.


00:54:43.520 --> 00:54:45.600
That's the dream for me too.


00:54:45.600 --> 00:54:46.440
Bill?


00:54:46.440 --> 00:54:50.880
- Yeah, I just wanna support Bill Larson's idea


00:54:50.880 --> 00:54:52.280
and maybe Ray, I think,


00:54:52.280 --> 00:54:57.240
why don't we actually put together a document


00:54:57.240 --> 00:55:00.360
that perhaps outlines what we're trying to get out of this,


00:55:00.360 --> 00:55:02.040
where we think we might go.


00:55:02.040 --> 00:55:04.080
We could comment on each other's things.


00:55:04.080 --> 00:55:09.080
we could try and use what the affordances of Git


00:55:09.080 --> 00:55:14.760
to just see how that works,


00:55:14.760 --> 00:55:16.960
what kind of breakdowns we have,


00:55:16.960 --> 00:55:18.400
because I agree with you.


00:55:18.400 --> 00:55:22.360
I think there's a little bit of a learning curve,


00:55:22.360 --> 00:55:24.200
but it's not that big to get to,


00:55:24.200 --> 00:55:26.560
and we could, doing it ourselves,


00:55:26.560 --> 00:55:28.400
learn how to help other people do it.


00:55:28.400 --> 00:55:32.220
- Charles?


00:55:32.220 --> 00:55:34.620
Great idea, Bill, by the way.


00:55:34.620 --> 00:55:35.780
We should write that.


00:55:35.780 --> 00:55:39.260
In fact, maybe everybody should write something


00:55:39.260 --> 00:55:42.660
about what it is exactly that they want


00:55:42.660 --> 00:55:44.100
to get out of this.


00:55:44.100 --> 00:55:45.780
That would be really useful.


00:55:45.780 --> 00:55:52.500
- That would be a great thing to do on the HackMD.


00:55:52.500 --> 00:55:54.100
And you could either make your own section


00:55:54.100 --> 00:55:55.900
or follow along in another section.


00:55:55.900 --> 00:55:58.400
Sorry, Charles, go ahead.


00:55:58.400 --> 00:55:59.780
- Oh, no worries.


00:55:59.780 --> 00:56:00.620
This is great.


00:56:00.620 --> 00:56:09.900
probably go shortly as many of us probably. So Bill noted to add fork to the list, so I thought,


00:56:09.900 --> 00:56:14.860
you know, if there's something 20-30 seconds to say about forking, and then I don't know if this


00:56:14.860 --> 00:56:21.020
is like too much to pile in, but I haven't actually heard any details about MassiveWiki in a long


00:56:21.020 --> 00:56:26.940
time, but I was around, more or less around the inception time, and I know you and Bill,


00:56:29.180 --> 00:56:31.180
Anderson and others


00:56:31.180 --> 00:56:35.260
You know have been doing it relates and it overlaps, but it's not the same


00:56:35.260 --> 00:56:38.820
but it probably relates more to the forking part, so I don't know just


00:56:38.820 --> 00:56:42.900
Jumbling in my awareness of it here. Yeah, thanks


00:56:42.900 --> 00:56:50.140
For folks who need to go at the top of the hour, it's the top of the hour. Thanks for thanks for everything


00:56:50.140 --> 00:56:52.220
Let's get together again


00:56:52.220 --> 00:56:57.240
Maybe I the easiest way for me to do that is to coordinate through that community thing


00:56:57.620 --> 00:56:59.620
So you should have that link.


00:56:59.620 --> 00:57:01.860
If you don't, send me an email.


00:57:01.860 --> 00:57:05.060
If you don't want to join the community, you can kind of follow along.


00:57:05.060 --> 00:57:07.940
I'll keep you in the loop.


00:57:07.940 --> 00:57:11.700
So thanks for anybody who has to leave at that hour.


00:57:11.700 --> 00:57:16.900
So Charles, real quick, you talked about massive wiki and then the thing before that is forking.


00:57:16.900 --> 00:57:24.180
So let's cover those both real quick.


00:57:24.180 --> 00:57:27.980
A caveat that I don't give to most people


00:57:27.980 --> 00:57:32.980
is that there's actually two meanings for the word fork.


00:57:32.980 --> 00:57:36.820
There's like a big fork, capital F fork,


00:57:36.820 --> 00:57:38.820
and then there's little fork, capital,


00:57:38.820 --> 00:57:40.420
or small, small F fork.


00:57:40.420 --> 00:57:44.140
The fork terminology, I think,


00:57:44.140 --> 00:57:46.660
comes from an old thing that used to happen


00:57:46.660 --> 00:57:49.580
in software communities pre GitHub,


00:57:49.580 --> 00:57:51.500
where you'd have the community going along


00:57:51.500 --> 00:57:52.620
and everything was wonderful.


00:57:52.620 --> 00:57:56.580
And then at some point there would be some leadership conflict.


00:57:56.580 --> 00:57:59.060
Somebody would say, well, I think we should do it this way.


00:57:59.060 --> 00:58:02.580
And leadership says, we're not going to do it that way. It's stupid.


00:58:02.580 --> 00:58:08.060
So the, uh, you hit a fork in the road and the community splits in the two,


00:58:08.060 --> 00:58:12.500
um, the, uh, the Protestants and the whatever's, um,


00:58:12.500 --> 00:58:17.020
the conservatives and the, you know, uh, heretics. So, um,


00:58:17.020 --> 00:58:21.780
uh, often that will kill a community. Um, sometimes, uh, the,


00:58:21.940 --> 00:58:25.660
the, you know, there's a lot of pressure


00:58:25.660 --> 00:58:28.500
to not do that kind of split


00:58:28.500 --> 00:58:30.140
because you don't wanna split your resources


00:58:30.140 --> 00:58:31.140
and stuff like that.


00:58:31.140 --> 00:58:35.660
But sometimes it happens.


00:58:35.660 --> 00:58:37.300
Sometimes the act of doing that


00:58:37.300 --> 00:58:38.500
kind of relieves the pressure.


00:58:38.500 --> 00:58:41.500
Everybody can like take a year to kind of like develop along


00:58:41.500 --> 00:58:43.140
and then say, "Hey, we're doing the same thing anyway.


00:58:43.140 --> 00:58:44.820
"Let's get back together."


00:58:44.820 --> 00:58:46.540
So that's a big F fork.


00:58:46.540 --> 00:58:47.580
It's a big deal.


00:58:47.580 --> 00:58:50.420
GitHub used that language.


00:58:50.420 --> 00:58:52.180
And I think it's a good thing that they did.


00:58:52.180 --> 00:58:55.340
They use that language to mean something


00:58:55.340 --> 00:58:56.920
conceptually very similar.


00:58:56.920 --> 00:59:01.100
I wanna take all of your code the way that Doug did.


00:59:01.100 --> 00:59:03.780
I wanna take all your code and make a copy of it for myself


00:59:03.780 --> 00:59:05.580
and then make changes.


00:59:05.580 --> 00:59:08.000
So now I've got this fork.


00:59:08.000 --> 00:59:10.400
These two versions are, you know,


00:59:10.400 --> 00:59:12.980
they could continue to evolve separately.


00:59:12.980 --> 00:59:16.780
And on GitHub, it's very common for not just Doug to fork it


00:59:16.780 --> 00:59:18.980
but it's very common for 10 people to fork something


00:59:18.980 --> 00:59:20.220
or a hundred people.


00:59:20.220 --> 00:59:23.180
So now you've got a hundred different copies of this thing.


00:59:23.180 --> 00:59:26.740
They're all like, they're not even like arguments.


00:59:26.740 --> 00:59:28.380
And they're not even disagreements, right?


00:59:28.380 --> 00:59:30.220
Doug just had a different way of doing things


00:59:30.220 --> 00:59:32.300
or needed some extra stuff added.


00:59:32.300 --> 00:59:37.660
So at some point Doug can say, well, I've got my fork,


00:59:37.660 --> 00:59:40.580
but it's, you know, I really want, you know,


00:59:40.580 --> 00:59:42.900
to contribute to the thing with everybody in it,


00:59:42.900 --> 00:59:47.240
not just me doing my stuff on a fork of everything.


00:59:47.240 --> 00:59:51.300
So I'll make a pull request and the fork merges back.


00:59:51.300 --> 00:59:55.100
So that fork is just the process of making a,


00:59:55.100 --> 00:59:59.440
usually very temporary copy of the whole thing,


00:59:59.440 --> 01:00:04.440
changing it so that it's all cohesive in itself


01:00:04.440 --> 01:00:10.080
and then probably putting it back together.


01:00:10.080 --> 01:00:13.500
So forks and pull requests go together.

