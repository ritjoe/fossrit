# Thu Oct 17 15:43:27 EDT 2019

## a note on notes.md use

I'm going to adopt one of my documentation practices, of writing a
blog-ordered text file as a sort of running developer diary.

By "blog-ordered" I mean most-recent entries at the top.

I've only more recently begun to use light markup, usually Markdown, in this
sort of file.

Sometimes I'll revise an earlier entry. While revision control can reveal
those sorts of edits, I like also explicitly note having done so within the
document itself as a subheading to the entry.

## a note on *this* note.md

Below is the text from each of three issue comments I've made in the past
about an organization-wide meta-reposiotry like this. I may add full links
to the comments as hosted by GitHub, but one of my ongoing aims is to make
our content agnostic to the hosting software or platform, so I'm including
them here. Above, I expect I'll make loosely structured entries as I
continue trying to pull items in.




# 2019-10-17

from ritjoe/fossrit
 
This picks up where https://github.com/FOSSRIT/fossrit/issues/1 left off.

I see for instance https://github.com/FOSSRIT/tasks hasn't been touched since February.

Our attention continues to be scattered across that, https://fossrit.github.io and its associated repository https://github.com/FOSSRIT/fossrit.github.io, https://github.com/FOSSRIT/infrastructure, https://github.com/FOSSRIT/foss-profiles, institutional Google Docs, email, https://fossrit.community, IRC and its bridged services, and probably other thngs.  

Beyond currently used resources, there is a body of things that have been lost to memory, forgotten or neglected. The chaos of everyday life tends to push things from the former category of currently-used resources into the latter category of derelicts. 

Some of this is understandable, inevitable, or even appropriate. 

Even so, the current resources do not serve the function I've been looking for here. None are conceptualized as having the scope to track our fleet of resources as they pass in and out of harbor, or as they begin to drift, to succumb to the doldrums of limited time and attention. 

My point is not to impugn any of those resources, but to explain as best I can what I do want that they don't provide:  A more functional and flexible entry point to our GitHub presence than what the ability to pin repositories provides, a point from which we can *also* point outwards to other resources, a point that is hosted *within* GitHub, but which consists primarily of static content*. 

Rather than burn people's attention and goodwill by arguing the point, though, I'm just going to sit here and scratch this itch out of the way, within my account.

Perhaps as I use this, others can infer better the purpose I was not able convincingly to convey through https://github.com/FOSSRIT/fossrit/issues/1#issue-365890025

* "static" as is so often used in the context of static-site builders is anything but. It's static content so far as the server is concerned, sure, but it almost always contains more than a little JavaScript that is quite active on the client side. Maybe the contemporary term that best fits what I'm talking about is "assets" if Markdown or reStructuredText files can be considered assets alongside images and other files. 



# 2019-10-17

from FOSSRIT/fossrit


I'm going to jump back to this and begin opening issues and putting things together in the way I had in mind for this repo. Instead pushing this into the FOSSRIT github organization I'll do it through my own account. If what I'm doing and the way I'm doing it there gains any support for bringing that over to the FOSSRIT organization then we can try to make that happen later.

See https://github.com/ritjoe/fossrit





# 2018-10-02

from FOSSRIT/fossrit



**The problem**

The FOSSRIT GitHub organization is **difficult to navigate**, including as it does--at the time of this writing--194 repositories going back more than 6 years, having been created, used, or maintained--and in many cases, abandoned--by several generations of participants. This can be particularly **difficult for newcomers** browsing the organization and not accustomed to using GitHub search features nor aware of keywords to use relevant to the organization. The default repository listing sorts by most-recently active at the top and buries key but only periodically-updated repositories in the middle of the pack.

There are also a number of **difficulties for more-experienced participants**. 

* The criteria for including a repository in the organization is poorly defined. 
* Some repositories are native to the organization, but some are forks. If and how to bring a repository or fork into the organization is not well defined. 
* What's more, whether to keep a repository in the organization is not well defined.

**Proposed solution**

A meta-repository like this one [FOSSRIT/fossrit](https://github.com/FOSSRIT/fossrit) :smile:

This is similar to, but more flexible and more expansive than, the pinned repositories feature.

This approach of having one navigational meta-repository is used by a number of other GitHub organizations. A prominent one that most easily comes to mind is that of [Travis-CI](https://github.com/travis-ci/travis-ci) but there are others.

The list of top-level directory objects will be kept short so that the README is not too far down the main repository page. The README, then, will be maintained as an easy-to-browse single page for navigational information, with links both to key GitHub-hosted FOSSRIT repositories as well as to web and community resources found elsewhere. The preferred form for links in documents hosted elsewhere pointing to this organization should be https://github.com/FOSSRIT/fossrit while deprecating ~~https://github.com/FOSSRIT/~~ .

The issues and, possibly, wiki associated with this primary [FOSSRIT/fossrit](https://github.com/FOSSRIT/fossrit) meta repository can serve as **unambiguous first stops** for any journey into the organization. Any query, discussion topic, or document can find a home here, first, if no other location is immediately apparent. Discussions or document need not remain in this top-level repository and can be moved to or continued in more specific repositories later. 

Any discussions starting at this meta level, but which discussion is relevant to the organization as a whole regarding policies and procedures can remain. Issues originating in other repositories that turn out to have a wider, organization-wide aspect can be moved to or continued in this top-level repository.

This repository would either become one of the pinned repositories or, perhaps better to funnel participation through it, would be the only pinned repository.

**Alternatives**

Maintaining more of our documentation and navigational aids within the vast suite of **institutionally-maintained and promoted software-as-a-service** is one clear alternative: Learning management systems, student organization systems, internal-only repository hosting, institutional wikis, etc. To those less invested in FOSS collaboration methodologies these may seem like the best, obvious choice.

However, these are generally not so portable beyond the institution that hosts them and represent even worse lock-in than GitHub does, and moves the documentation for our code hosting away from the code hosting itself.

Going in the other direction, perhaps we should set up our primary entry-funnel meta-repository at a repository **hosting site whose server software is itself FOSS**: [Pagure](https://pagure.io), [GitLab](https://gitlab.com), [Gogs](https://gogs.io)/[Gitea](https://gitea.io)/[notabug](https://notabug.org), [Framagit](https://framagit.org), etc.

It might seem that the effort to maintain a less participatory, top-level web site like a Wordpress instance or the fossrit.github.io page obviates the need for something like this.  However, these serve the needs of the community more broadly, rather than those of the code-hosting and development aspects in particular: For most of the community, they remain a read-only medium, with a narrow channel for onboarding maintainers and contributors.

Also, as we've seen in recent years, maintenance of such infrastructure carries its own challenges idiosyncratic to the software used and the way each is hosted which require effort to learn and maintain. When they are working, they are, in a sense, complementary to a code-hosting organization meta-repository: Each clearly should contain links to the other, but they do not substitute one for the other. 

**Additional context**

It will be important to keep what shows up on the main page of the repository fairly clean and navigable. It might become lengthy, but if we do reasonably well in categorizing and prioritizing the page layout in "inverted pyramid" form, keeping the most relevant information at the top of the README, it will serve us well.

Deeper into the document tree we can put other organization-wide documents like polices, procedures, HOWTOs, etc. 

Pages further down may be included which incorporate alternate views into the repository, including embedded links to searches, eg

* [hfoss](https://github.com/FOSSRIT?q=hfoss)
* (minor)[https://github.com/FOSSRIT?q=minor]
* [POSSE](https://github.com/FOSSRIT?q=posse)
* [monroe](https://github.com/FOSSRIT?q=monroe)
* [election](https://github.com/FOSSRIT?q=election)

These can serve directly to aid navigation through browsing, but can also serve as models for the use of the search features and of keywords particularly useful within the organization. Many features of these documents will largely be portable, useful beyond GitHub and any GitHub-specific organizational features like tags.

Special-purpose managerial meta-repositories like:

* [tasks](https://github.com/FOSSRIT/tasks)
* [infrastructure](https://github.comFOSSRIT/infrastructure)
* [brand](https://github.comFOSSRIT/brand)

probably wouldn't be replaced by this [FOSSRIT/fossrit](https://github.com/FOSSRIT/fossrit) meta-repository. We would link to them from it. There might be some duplication between it and them, but with judicious use of crosslinks amongst them all that might turn out OK, or even well.

