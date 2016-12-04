# [DRAFT] Release parties
_This recommendation is a DRAFT for consideration of the MODX Advisory Board._

Editor: Gauke Pieter Sietzema
First published draft: To be determined.

## Versions
- Oct 18, 2016 - Initial draft
- Oct 20, 2016 - Rewrite based on new findings (semver/modx releases how they are now)
- Oct 24, 2016 - Finished draft, should be reviewed. Input welcome regarding direction and feasibility.
- Nov 17, 2016 - Moved to Github-repo + implemented comments from Drive file

## Goal of Recommendation
The goal of Release Parties is more (community|pr) engagement during releases. This requires minor and major releases to contain more compelling features for a wider audience.

Right now, the user (the content manager) isn't given enough feature-love and won't be excited about future releases. Because of this, they will not share anything in their network. This needs to change, because it is the biggest part of our user base.

## Relevant Recommendations
n/a

## Recommendation
**Preface**
Jay Gilmore and Ryan Thrash are doing a great job announcing the MODX releases. A great example, with images, is the 2.5 release blog article. The best part of this release are the preview images of the UI-changes, which will appeal to users who want to use non-desktop browsers for their manager experience.

This document focusses on two types of releases: minor and major releases (for now: release). Every release should contain something for everyone to keep everybody engaged. To do this, we need to determine the type of users we have:
1. Developers
1.1. Implementers who change a static site to a MODX manageable website)
1.2. Developers who write new code for MODX or MODX extras
1.3. Site maintainers / Support employees / Sysadmins

2. Users / Content managers who use MODX to manage their site
2.1. Power users who use it everyday
2.2. Occasional updates to a site

Every release should contain something good for every type of user (developer or user). To accomplish this, we need a roadmap. Not necessarily a multiple-year roadmap, but we should be able to create a 12-month release schedule.

**The recommendation**
A new release schedule should be implemented. The current roadmap can be found on docs.modx.com, but it only contains a short term minor release and the next big thing(s): 3 & Next. There's a lot in between.

**A new minor release should happen every 3 months.** The release features should be determined by the MAB, project leadership and the integrators. We should keep in mind that both developers and users should be addressed in each release.
To get more community members involved, a voting system should be incorporated. Community members can vote on ideas, which are recommendations from the MAB. These votes can be used as an indication of what the community deems important for a next release. This helps the creators of the schedule to prioritise. Voting can be done on Github.

**Major releases should happen every year.** Officially, a major release should contain breaking changes, which means no backwards compatibility (BC), but we should also keep in mind that new major versions give MODX more exposure. Therefore the **requirement of breaking changes should be let go**, or a BC should be specified in a way which makes it easier to call something a BC. The requirement for a new version should be a major feature, not necessarily breaking BC.


## To summarise this recommendation:
- A release must address the needs of both users and developers;
- Minor release every 3 months;
- Major release every year;
- Breaking BC is no longer a requirement for a major release;
- Community members can vote on recommendations to help us prioritise;

## Expected results
- More clarity regarding release scheduling and content
- Make press announcements better to organise and write
- More compelling features for both users and developers
- More PR about MODX
- More structure for integrators and possibly more work

## Relevant sources
- [Drupal.org - Article about versioning](https://www.drupal.org/blog/the-transformation-of-drupal-8-for-continuous-innovation)
- [WordPress.org - Roadmap](https://wordpress.org/about/roadmap/)
- [Semver.org - Semantic Versioning spec](http://semver.org/)
- [MODX.com - Roadmap and versioning](https://docs.modx.com/revolution/2.x/getting-started/an-overview-of-modx/roadmap)





—
The semver spec calls the different types of releases patch, minor and major, and while these make sense to developers it doesn't always make sense to other users what those mean.

At modmore we recently started referring to the releases by bugfix or bug-fix (instead of patch), feature (instead of minor) and breaking (instead of major). These terms should be easier for people to understand, and still communicates what semver communicates in the exact same way.

Perhaps this is something to consider for the MODX project as well, which would require buy-in from core integrators and contributors, documentation updates, perhaps tweaks on the site.

I know @gpsietzema mentioned something about version numbering at the last meeting so I'm curious to hear his thoughts on that, but wanted to dump this idea somewhere before I forget it again.