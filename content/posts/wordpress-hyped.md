---
title: "WordPress is not worth the Hype"
date: 2021-06-23T13:16:03+05:30
draft: false
cover: 
    image: pexels-pixabay-265667.jpg
    alt: 'Wordpress backend running on a laptop'
    caption: ''
---

WordPress is probably the reason many aspiring Bloggers had given up. Search for the term "How to start a Blog" and WordPress will be the first term parroted to you. For those uninitiated, here is my description of WordPress: 'It is a piece of software that you install on your web hosting provider to serve your blog content.'

According to [W3Tech](https://w3techs.com/technologies/details/cm-wordpress), WordPress is currently used on 41.9% of all websites but this statistic is absolutely deceiving to a novice user. Just consider the fact that the vast majority of websites on the Internet don't serve any meaningful purpose.

Now, let's consider the Pros of setting up your Website on WordPress:


## **A Blogging Centric Platform**

At a time when the web is being converted to this gentrified garden with a few monolith corporations controlling a vast majority of human interactions; WordPress goes against the grain and contains minimal code that is dependent on the mothership. The only feature at its core that depends on an external service to serve content is probably the "Gravatar" feature. Everything else is fiercely independent with minimal external dependencies. _At its core, WordPress is a terrific platform to start blogging._


## **A Metric Tonne of Documentation with a Big Community of Users**

This is probably the biggest reason why you can consider WordPress if your requirements are constantly changing and you constantly need to add features to your website. The amount of documentation available is miles ahead of the competition. Additionally, if you are technically proficient in web development; the ability to reach out on [StackOverflow](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/stackoverflow.com) and the WordPress forums is huge support due to Wordpresses' large community of users.


## **The Plugin Library**

Owing to its popularity it probably has a plugin for every conceivable use case scenario you can think ok. "No coding required".


# **The End of your Honeymoon and Why WordPress isn't worth the hype.**


## **The Confused Child**

WordPress started as a Blogging Platform and still serves its purpose as a blogging platform to an extent. However, over time, the core developers decided to turn it into a full-fledged CMS at a point and they did an absolute half-assed job in this regard. Most WordPress idiosyncrasies and hair-pulling frustrations stem from this basic fact. A complete rewrite of WordPress was needed at the point it was decided to turn into a full-fledged CMS, but holding off this radical decision in the interest of maintaining backward compatibility it turned a perfectly functioning piece of software into a horror house of a CMS.

It is now a hornet's nest of spaghetti code with potential pitfalls at every turn. The relative ease with which you can enable a plugin deceives the heartburn you'll feel in your journey. Even a simple update of a Plugin has the potential to break your site.

Hell even hiding the Page title will make you download a theme builder where this particular option will be hidden in a very specific spot inside the six layers of UI of the newly downloaded theme builder. Doesn't it make sense for a full-fledged CMS to build the option to hide your page title in with a simple checkbox? WordPress doesn't think so.


## **WordPress has no SEO Capabilities**

Contrary to popular rhetoric WordPress is not inherently better for SEO. If you want to get mileage out of SEO, you'll need to download another plugin like Yoast SEO! Yoast in itself is a terrific plugin but it sorely sticks out like a sore thumb in the overall scheme of things. It is a big oversight to delegate the core SEO functionality to another Plugin. Imagine having to download a file explorer after you install Windows!

[ghost](https://ghost.org/vs/wordpress/) provides a good template on how SEO can be seamlessly handled inside a CMS.


## **Theme Builders / Page Builders are Messy and Stupid**

Visual Theme builders promise to craft every aspect of your website without the tedium of learning web development. But it only serves to further complicate matters than it solves.

WordPress is a free piece of software, but all theme builders for WordPress are based on the freemium model which seems good in theory but in essence, is a terrible idea. Providing the theme builder for free makes no sense if you have to buy the paid version to change something basic. For example, by changing the header of a webpage or adding social share icons you need to buy the Pro version of Elementor. This creates an additional layer of confusion as certain fixes for your layout problems in the documentation might only work with a paid version of the theme builder, making the user run in a circle for no apparent reason.

Additionally many theme builders for WordPress overlook all conventions of WordPress and God forbid if you change the theme builder; your layouts will break with junk characters and layout code strewn across your website in plain sight. WP Bakery is the finest example.


## **UI is a nightmare and Things break oftern**

The WordPress dashboard after installing a few plugins looks akin to Internet Explorer overloaded with toolbars. Need I say more.


# **What is the solution?**

Rather than going for a one size fits all solution, consider your use case. Avoid WordPress like a Plague if another solution has to serve your needs


## **If you want to just put content out there and have zero technical chops**

Choose a platform like [Medium](https://medium.com/). It might not be the most friendly in terms of giving authors ownership of their content but is hard to beat in terms of ease of use. Other notable alternatives include [Substack](https://substack.com/).


## **If you have an Inclination to Host the Site Yourself and Have a Bit of Technical Knowledge**

Go with a [ghost](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/ghost.org). This is the solution I am using to host the blog you are currently reading. It is a terrific solution if your content is blog-centric and you want the ability to host your own website. Most premium themes are quite affordable too. It [integrates seamlessly with many online services](https://ghost.org/integrations/) in a much more graceful manner than what WordPress Plugins offer. The interface is clean and minimal with built-in SEO and Social Sharing and Payment through Stripe currently supported. Their official documentation is pretty minimal but straightforward.

The only major drawback with ghost currently is that it is built upon NodeJS which is not supported by many hosting providers like Bluehost and Siteground. I am currently using [Digital Ocean](https://digitalocean.com/) as my hosting provider while utilizing the smallest droplet which costs around $5 per month. One notable problem I encountered with my setup is that initially my Digital Ocean virtual server (called a Droplet in DO terminology) ran out of memory for MySQL frequently and required a hard power cycle every few days. But I was able to [quickly resolve this issue by setting up a swap as mentioned in this article.](https://www.digitalocean.com/community/tutorials/how-to-add-swap-on-ubuntu-14-04)


## **If you want eCommerce functionality**

Go with [Shopify](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/shopify.com). It seems a much more pricy option than say WooCommerce or Magento. But I have found that it is actually viable to set up a much better and polished looking website without hiring a  developer. Also, if you are planning to sell while Blogging(Content Marketing), go with Shopify and setup your blog inside your shopify store. It is much easier administering a Blog inside shopify than integrating a shopping cart inside a blog platform.

TL:DR Shopify seems pricy due to its per transaction free but you save precious amounts of time and effort from not spending time administering and developing your site.


## **Want Content under your Own Domain Name but have Minimal Technical Knowledge**

This is admittedly a niche I have never explored but the usual supects like [Squarespace](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/squarespace.com), [Wix](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/wix.com), [Weebly](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/weebly.com), come to mind. I have never used those platforms but have heard good things from people using those platforms. Don't write off these platforms by thinking all the cool kids use Wordpress. Trust me, if you are not inclined to be a full tie web developer, it is not worth it to continuously keep administering your website. Just choose your platform, get shit done and move on.


## **For those with the Required Technical Knowledge of Web Developement but still itching to kick the Bucket on WordPress**

Consider [webflow.](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/webflow.com)


## **For Photographers and Designers as a Portfolio Site**

Consider [koken](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/koken.me) , Adobe Portfolio and 500px. Personal Experience : As a photographer I used [koken](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/koken.me) extensively in the past due to its ability to post directly to web through a Lightroom Plugin.


# **When Wordpress might Still be right for You**

Despite my Angry Rant, I still believe WordPress has a place for certain use cases. It becomes problematic when it is bastardised beyond its usual use cases like for setting up a static one-page website. For these specialized use cases get one of the options mentioned above.

It will still remain a dominant CMS in the foreseeable future, hence finding developers familiar with the platform is not going to be a problem.

It still remains an excellent choice for multilingual sites due to its extensive list of supported languages. Wordpress especially shines in creating content for much more niche languages like Assamese, which are not supported officially on other platforms.


# **If you have decided to go with Wordpress you can take these steps to mitigate some of the potential problems**


## **Never Choose Wordpress just because you consider it to be the Cheapest option**

_It costs money and especially your time to administer a Wordpress site effectively._ Factor in the cost of hiring a developer if you can. It is a much better approach than downloading a bunh of free themes and plugins and praying for the best, if you value your own time.

Also, factor in the cost of getting a decent theme with the subsciption cost of a theme builder if you go the DIY route to build a competent website while comparing your costs to a platform like squarespace. The wordpress option might start looking much less enticing.


## **Get a Managed Hosting Provider like WPEngine or Flywheel**

A lot of frustrations with WordPress stems from using sleazy hosting providers like[ GoDaddy](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/godaddy.com), to host your site. Go instead with a Managed hosting provider exclusively specializing in Wordpress like [Flywheel](https://santanushekhar.com/why-wordpress-is-not-worth-the-hype/getflywheel.com) & [WPEngine](https://wpengine.com/plans/). They are a bit pricey but offer excellent support for WordPress centric sites. The [Tiny Plan by Flywheel](https://getflywheel.com/pricing/) is quite affordable too.


## **Avoid Buying Cheap, Prebuilt Themes like the Ones from Themeforest**

Instead get a general theme like OceanWP, or Hello Elementor with the paid version of the required theme builder and customize according to your requirement. Most specialized prebuilt themes are junk and are not worth the hassle.

WordPress does a half-assed job as a CMS as it is time to consider other options as well. Don't get carried by the WordPress hype.