# A Non-Blind Reviewing Proposal for *ACL

## Background

The current [*ACL arXiv and reviewing policy](https://www.aclweb.org/adminwiki/index.php?title=ACL_Policies_for_Submission,_Review_and_Citation) can be characterized as follows: we know there are implicit biases, so the intervention is to hide the signals (features) that could lead to implicit biases.

See above link for details, but one important provision is that posting to any non-blind preprint server one month before the conference deadline is prohibited.
I am indeed on record as calling this policy "idiotic".
There are many reasons why authors would post on arXiv (and equally many reasons why some think it's a bad idea), but those motivations are orthogonal.
I'm happy to discuss but that's a separate issue.

My entire argument is that this policy is **ineffective**. Explained as follows:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">And as I&#39;ve pointed out several times: the *ACL policy only works for the initial creation of the paper. If a paper is rejected, the authors will naturally post on arXiv, so blind review is defeated the next conference cycle. We just delayed our impact for no good reason.</p>&mdash; Jimmy Lin (@lintool) <a href="https://twitter.com/lintool/status/999099753286615040?ref_src=twsrc%5Etfw">May 23, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

And:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Hypothesis that new arXiv policy for *ACL simply pushes deadlines one month earlier. Look at the spike in arXiv cs.CL submissions last week, one month before NAACL 2018 long paper deadlines. Thanks to <a href="https://twitter.com/tuzhucheng?ref_src=twsrc%5Etfw">@tuzhucheng</a> for analysis! <a href="https://twitter.com/hashtag/NLProc?src=hash&amp;ref_src=twsrc%5Etfw">#NLProc</a> <a href="https://t.co/l18zHuI59k">pic.twitter.com/l18zHuI59k</a></p>&mdash; Jimmy Lin (@lintool) <a href="https://twitter.com/lintool/status/932729551326793730?ref_src=twsrc%5Etfw">November 20, 2017</a></blockquote>

To which Chris Manning explained:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">The <a href="https://twitter.com/ACL_NLP?ref_src=twsrc%5Etfw">@ACL_NLP</a> policy relies on 2 human failings: procrastination and forgetfulness. Everyone could finish papers 35 days before a deadline but few do. Some genuine preprints or previously rejected papers will be broadly available but people are less likely to remember authors. 7/</p>&mdash; Christopher Manning (@chrmanning) <a href="https://twitter.com/chrmanning/status/1000528110276624384?ref_src=twsrc%5Etfw">May 27, 2018</a></blockquote>

This, IMO, is not sound evidence-based policy making.
As far as I'm aware, these "two human failings" are unverified assumptions.
People will search while reviewing and unwittingly unblind papers.
And no, you simply *cannot* prescribe how reviewers conduct their reviews (i.e., "try not to search..."). It's enforceable.

## My Proposal

Given that background, I've clearly stated:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I think everyone is misunderstanding me: I&#39;m not opposed to blind review. It has advantages but it is by no means perfect. What annoys me is the attitude that everyone treats blind review as sacrosanct, the sole source of truth in an axiomatic, inviolable manner.</p>&mdash; Jimmy Lin (@lintool) <a href="https://twitter.com/lintool/status/1000812604904824832?ref_src=twsrc%5Etfw">May 27, 2018</a></blockquote>

Now, in the spirit of being constructive, I'll propose a completely opposite approach: let's give up on blind review and be explicit about the signals that may lead to implicit bias, and then explicitly correct for them.
This approach is predicated on there being substantial research on implicit biases and how to combat then.

Under this proposal, a conference would do something like this:

+ All conference officers (PC chairs, SPC, etc.) must take mandatory training that discusses diversity, inclusivity, implicit bias, etc.
+ Conference officers are empowered during mandatory in-person SPC meetings to correct for any biases they encounter, based on the above training.
+ The paper submission system *explicitly* gathers all features that we might imagine to be relevant to diversity, inclusivity, implicit bias, etc. (e.g., h-index, gender, L2 vs. L1).
+ We make available for decision making, accumulated over time, analyses that are pertinent to decision making, like the [WSDM experiment](http://www.pnas.org/content/114/48/12708).

Under this proposal, there are absolutely no restrictions against arXiv submission, flag-planting, shameless self-promotion on social media, etc.
There will, however, be consequences.

## How This Would Work

Reviewing would proceed normally as most conferences are run today. Reviewers remain blind to authors, but they must be revealed to the SPC (or track chairs, or whatever).
The major change happens at the *in-person* PC meeting (and I believe the *in-person*-ness is absolutely critical).
The SPC members examine all papers and make adjustments to combat implicit bias:

+ Based on the diversity, inclusivity, implicit bias, etc. training they have received.
+ Based on the accumulated evidence on effective strategies to handle diversity, inclusivity, implicit bias, etc. issues. This means the techniques will be refined and improved over time.

In other words, we empower the SPC members (or PC chairs, etc.) to _override_ reviews based on their training and judgment.
Or even stronger: we _expect_ the SPC members to correct for implicit and hold them accountable.

Let's, for the sake of concreteness, assume that the SPC uses the "checklist approach" (although there are other effective techniques as well). The checklist approach attempts to make explicit the decision-making process so as to ensure that decisions are made equitably (for whatever definition of equity the community decides to adopt).

Let's again, for concreteness, assume that under the checklist approach we wish to guard against the implicit biases associated with fame, gender, and L2 vs. L1-ness.
(The community can converge through some process on what these characteristics are.)
Then I'd imagine that discussions at the in-person meeting might include the following:

+ Paper 342 was reviewed by two second-year Ph.D. students who don't seem to have a solid command of the literature, and as a result we believe there is a "famous author" effect at work here. Despite the high scores, we're going to reject the paper.
* Paper 1934 has a review that exhibits sexist undertones regarding the topic of study. This is inappropriate and so we are going to discount the negative review and accept the paper.
+ Paper 908 has one review that isn't substantive, and is critical based solely on relatively superficial grammatical mistakes. We're going to recommend a native-speaker editing pass, but otherwise accept the paper because we think the underlying ideas are solid. (Even better, if the conference has a shepherding process, then we make the copyediting mandatory).
+ Paper 85 makes exaggerated novelty claims that went unchallenged because the paper came from a prestigious institution, but in our opinion, the methodology is shoddy. Despite the high scores, we're going to reject.

Note that under this model authors can shamelessly flag-plant all they want on arXiv, but they will be held accountable if they do shoddy science.

## Objections

**It's a lot of work!**

And we're trying to combat a pernicious problem... your point is?

**It puts a lot of power in hands of the SPC members.**

So? We already do.
Now we're just giving them a clear mandate and a methodology for redress.
If we can't select a handful of members from the community we trust doing this, then I think the community has more serious issues...

**What about the possibility of retaliation?** Won't an SPC member who is an assistant professor worry about axing a paper from a famous author?
What about the possibility of retaliation for tenure reviews, for example?

I concede that this is a concern.
It can perhaps be mitigated by SPC members where we'd pair someone very senior (full professors) to provide "cover" for junior faculty.

**In-person PC meetings are untenable.**

No they're not.
Last time I checked, SIGIR and WWW still do this.
Many conferences have split into tracks now, so less desirable, but still adequate, are track-specific in-person meetings.
As a bonus, we also rotate these meetings to different parts of the globe to further promote diversity.

**This plan biases against people with restrictions on traveling, such as parents with young children.**

Agreed. I have no response to this.
This actually happened to me recently.