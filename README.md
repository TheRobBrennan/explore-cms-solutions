This repo will explore several Content Management Systems (CMS).

# Content Management System (CMS) shoot-out

## Initial impressions

### Craft CMS

Craft CMS immediately caught my eye as one of the most visually appealing CMS solutions I have seen.

The user interface for creating content is extremely friendly:

![https://craftcms-com.imgix.net/home-features-03/live-preview.jpg?dpr=2&fp-x=0.5&fp-y=0.5&h=684&ixlib=php-2.1.1&mode=fit&w=1200&s=8e2313c9b87ace9dcee9f8deb3dce52c](https://craftcms-com.imgix.net/home-features-03/live-preview.jpg?dpr=2&fp-x=0.5&fp-y=0.5&h=684&ixlib=php-2.1.1&mode=fit&w=1200&s=8e2313c9b87ace9dcee9f8deb3dce52c)

I'm a fan of the live preview capability:
![https://craftcms-com.imgix.net/why-content-creators-02.png?dpr=1.5&fm=jpg&fp-x=0.5&fp-y=0.5&ixlib=php-2.1.1&mode=fit&q=60&w=1000&s=24f50ca1861788539db8f93dd692876c](https://craftcms-com.imgix.net/why-content-creators-02.png?dpr=1.5&fm=jpg&fp-x=0.5&fp-y=0.5&ixlib=php-2.1.1&mode=fit&q=60&w=1000&s=24f50ca1861788539db8f93dd692876c)

You can view your own two-day Craft demo site by signing up at [https://demo.craftcms.com/](https://demo.craftcms.com/). Alternatively, you can download and install Craft CMS from the [GitHub repo](https://github.com/craftcms/demo).

[Craft CMS](https://craftcms.com/) is a PHP 7 application that uses your choice of MySQL, MariaDB, or PostgreSQL on the back-end.

A complete list of [technical requirements](https://craftcms.com/docs/3.x/requirements.html#minimum-system-specs) can be viewed [here](https://craftcms.com/docs/3.x/requirements.html#minimum-system-specs)

Out of the box, the front-end is a PHP application that uses [Twig](https://twig.symfony.com/) - a templating engine for PHP.

You can also run Craft CMS in headless mode - allowing it to be the back-end for front-end applications of your choice (React, Gatsby, Angular, Vue, etc.).

> Whether the system should run in Headless Mode, which optimizes the system and control panel for headless CMS implementations.

> When this is enabled, the following changes will take place:

> - Template settings for sections and category groups will be hidden.
> - Template route management will be hidden.
> - Front-end routing will skip checks for element and template requests.
> - Front-end responses will be JSON-formatted rather than HTML by default.
> - Twig will be configured to escape unsafe strings for JavaScript/JSON rather than HTML by default for front-end requests.
> - The `loginPath`, `logoutPath`, `setPasswordPath`, and `verifyEmailPath` settings will be ignored.

> With Headless Mode enabled, users may only set passwords and verify email addresses via the control panel or controller actions. Be sure to grant "Access the control panel" permission to content editors and administrators that should be able to log into the control panel unless you're providing your own auth forms.

I would give [Craft CMS](https://craftcms.com/) serious consideration. Whether used out of the box or as a headless CMS, [Craft CMS](https://craftcms.com/) has some enticing features and functionality that are worth exploring.

My only hesitation in giving this a full out recommendation is that you must host the application yourself. While [pricing](https://craftcms.com/pricing) for [Craft CMS](https://craftcms.com/) is more than reasonable to me (free forever as a solo project; professional plans start at $299 per project for the first year and then $59/year after for updates), **you will need to plan your hosting and infrastructure** accordingly. If the thought of hosting an application is intimidating, [Craft CMS](https://craftcms.com/) does have [preferred hosting providers](https://craftcms.com/hosting).

### Sanity

[Sanity](https://www.sanity.io/)

### Storyblok

[Storyblok](https://www.storyblok.com/)
