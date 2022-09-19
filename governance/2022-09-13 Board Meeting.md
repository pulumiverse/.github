# Pulumi Governance Board Meeting

Date: 13 September 2022

Attendees:
* [Ringo De Smet](https://github.com/ringods)
* [Simen A.W. Olsen](https://github.com/cobraz)
* [Kathryn Morgan](https://github.com/usrbinkat)
* [Paul Hicks](https://github.com/tenwit)

Excused:
* [David Flanagan](https://github.com/rawkode)

## Agenda

- Contribution PR #14 (Simen)
- What do we want Pulumiverse to be? (Ringo)
- Call for collaboration (Ringo)
- Use of 1Password subscription (Ringo)
- GitHub repos, co-maintainers & original devs 

## Topics

### Contribution PR #14

Pull request #14 has been outstanding for quite a while. The main point of discussion was the section on conventional commits.
We will take an iterative approach on making this section better. The contribution document is approved as is for now and 
#24 is created as an improvement on it with clarifications.

More research will be done regarding the tools & setup around managing conventional commits if we want to standardise on this.
Simen is willing to do a demo on the use of tools he already uses within bjerk.io.

### What do we want Pulumiverse to be?

The board hadn't spoken to each other for way too long, so it was a good refresher to speak out what we want Pulumiverse to be.

The just cause is to build first and foremost a community of people, who work on technical material around Pulumi.
We still need more people to help out on things like documentation, coding, testing, …
Beyond providers, also the creation of standard Pulumi Packages (MLCs) could find a place in Pulumiverse.

We will plan a community meeting with the board meeting, extended by the core maintainers of the different repositories, 
every other month. We kick-start such a meeting with the board members alone, before the current maintainers join in.

### Call for collaboration

With Ringo becoming part of the Pulumi team, there was a bigger momentum for him to work on Pulumiverse growth.
Over the months, he executed some technical setup on his own, in a way to make progress. He now calls for some
more collaboration on the setup of the community.

The situation was two-fold: Ringo didn't ask for help enough on one end, but in cases where he did, the request
wasn't always responded to (on time). We agreed to create a better backlog as a starting point. Once it is known
what we intend to do, we can discuss, review and execute in a more asynchronous & distributed way.

On the tooling side, does everyone see notifications from Github issues and pull requests coming up? We will
all look what our own setup of being informed without being flooded. One tool which allows to get a clear 
view on Github notifications is [Octobox](https://octobox.io/).

### Use of 1Password subscription

1Password supports Open Source projects with access to a free Teams subscription. We applied for this and were
[granted access](https://github.com/1Password/1password-teams-open-source/pull/547). The board members are granted
admin access on this subscription.

The first action around this is that the master credentials for the different accounts we use for Pulumiverse
should be stored in the 1Password Shared vault of this subscription.

We need to further decide how we want to use 1Password for all the different credentials the different repositories
need for testing & publishing their work.

### GitHub repos, co-maintainers & original devs

If we get a request for someone to join Pulumiverse, it must be clear that that person remains the core contributor
of the work. The board wants to make this explicitely clear, to prevent having the confusion that we, the board
members, would take over the maintenance. Our aim is to search for one or more additional maintainers for the
work which is transferred to this community to prevent the work becoming stale.

All of the setup of our Github organization is managed in the [`infra`](https://github.com/pulumiverse/infra) repository.
When people want to join, with our without an existing codebase, make sure the setup reflects the
actual memberships, repositories, etc.
