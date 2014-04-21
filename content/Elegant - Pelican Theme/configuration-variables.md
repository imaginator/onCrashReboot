Title: List of Configuration Variables and Metadata
Tags: pelican-theme
Category: Elegant - Pelican Theme
Date: 2014-04-20 15:49
Slug: complete-list-of-file-metadata-that-elegant-uses
Disqus_identifier: iado0cf-complete-list-of-file-metadata-that-elegant-uses
Subtitle: 
Summary: List of all the metadata that you can use in your articles and pages with Elegant
Keywords: 

[TOC]

## Pelican Configuration

These are the settings that will help you get the most out of Elegant

    :::python
    PLUGINS = ['sitemap', 'extract_toc', 'tipue_search', 'neighbors', 'assets', 'share_post']
    MD_EXTENSIONS = ['codehilite(css_class=highlight)', 'extra', 'headerid', 'toc(permalink=true)']
    DIRECT_TEMPLATES = (('index', 'tags', 'categories','archives', 'search', '404'))
    STATIC_PATHS = ['theme/images', 'images']
    TAG_SAVE_AS = ''
    CATEGORY_SAVE_AS = ''
    AUTHOR_SAVE_AS = ''

## Configuration Variables

These are the optional configuration variables that you can define

1. `USE_FAVICON` used for [Favicon](how-to-set-favicons-and-speed-dial-icon-of-your-blog)
1. `SITE_LICENSE`
1. `SITESUBTITLE`
1. `SITE_DESCRIPTION`
1. `RECENT_ARTICLES_COUNT`
1. `COMMENTS_INTRO` used 

1. `LANDING_PAGE_ABOUT`
1. `PROJECTS`

These are the variables used for [Mailchimp](http://mailchimp.com/) subscriber form in the sidebar,

1. `MAILCHIMP_FORM_ACTION` is mandatory. Set it to your Mailchimp form action URL
1. `SUBSCRIBE_BUTTON_TITLE`
1. `EMAIL_FIELD_PLACEHOLDER`
1. `EMAIL_SUBSCRIPTION_LABEL`

These are the variables used with different Pelican plugins,

1. `SERIES_TITLE` used with [`multi_part` plugin](how-to-use-multi-part-plugin)
1. `SHARE_POST_INTRO` used with [`share_post` plugin](how-to-use-social-sharing-plugin)
1. `RELATED_POSTS_LABEL` used with [`related_posts` plugin](https://github.com/getpelican/pelican-plugins/tree/master/related_posts) 
1. `SOCIAL_PROFILE_LABEL` used with [social media profiles widget](how-to-display-your-social-media-profiles)

These are the variables used for [Social Media Optimization](search-engine-and-social-media-optimization),

1. `TWITTER_USERNAME`
1. `GOOGLE_PLUS_PROFILE_URL` 
1. `FEATURED_IMAGE`

## Metadata

Pelican uses [file
metadata](http://docs.getpelican.com/en/latest/getting_started.html#file-metadata)
from your articles and pages text files to get information about your posts,
like tags, authors etc.

On top of *"official"* metadata, Elegant uses some optional metadata that you
can use in your articles and pages.

1. `status`
1. `summary`
1. `keywords`
1. `modified`
1. `subtitle`
1. `series_title`
1. `featured_image`
1. `comments_intro`
1. `share_post_intro`
1. `disqus_identifier`

Blog [`onCrash=Reboot();`](http://oncrashreboot.com) uses Elegant theme. You can see its configuration files at [Github](https://github.com/talha131/onCrashReboot) for inspiration.

