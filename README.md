# HEX Lab Website

This is the code for the public website of HEX Lab at TU Munich, Klinikum rechts der Isar.


## I want to edit!

If you want to change what you see on the website, edit the markdown files in this repository. Most interesting things are inside the `content` folder. You can drop images that you want to reference in the `images` folder. While the files are markdown, inline html is supported for more creativity.

After you have made changes, commit them and push to the repository. An automated github action will pick up the change and update the website after a few secons (see *Actions* tab in the Github menu bar).

## Common tasks

See below to achieve some common tasks. Also see the reference for the template and website builder used here: https://docs.hugoblox.com/

**Add a post**

Go to `content/post`. Create a new folder, preferrably with the timestamp as name, and place an `index.md` file with content and a `featured.jpg` teaser image. The `index.md` file should contain the post, consisting of at least title, content and date. Feel free to add more metadata and shotcode elements to the posts, see https://docs.hugoblox.com/reference/markdown/ and https://docs.hugoblox.com/reference/page-features/.


**Add / edit a team member**

Team members are in the `content/authors` folder. Each team member is in it's own folder, with the information in the `_index.md` file. This file is commented with the different options. To create a new team member, create a new folder and file plus image. The `user_groups` property in this file determines where in the `people` segment on the home page the person will show up. 

*Note:*

This website is based on the Hugo Blox Research Group theme, see below for more information.

---


# [Hugo Research Group Theme](https://github.com/wowchemy/starter-hugo-research-group)

[![Screenshot](./preview.png)](https://hugoblox.com/hugo-themes/)

The **Research Group Template** empowers your research group to easily create a beautiful website with a stunning homepage, news, academic publications, events, team profiles, and a contact form.

️**Trusted by 250,000+ researchers, educators, and students.** Highly customizable via the integrated **no-code, widget-based Wowchemy page builder**, making every site truly personalized ⭐⭐⭐⭐⭐

[![Get Started](https://img.shields.io/badge/-Get%20started-ff4655?style=for-the-badge)](https://hugoblox.com/hugo-themes/)
[![Discord](https://img.shields.io/discord/722225264733716590?style=for-the-badge)](https://discord.com/channels/722225264733716590/742892432458252370/742895548159492138)  
[![Twitter Follow](https://img.shields.io/twitter/follow/GetResearchDev?label=Follow%20on%20Twitter)](https://twitter.com/wowchemy)

Easily write technical content with plain text Markdown, LaTeX math, diagrams, RMarkdown, or Jupyter, and import publications from BibTeX.

[Check out the latest demo](https://research-group.netlify.app/) of what you'll get in less than 60 seconds, or [view the showcase](https://hugoblox.com/creators/).

The integrated [**Wowchemy**](https://hugoblox.com) website builder and CMS makes it easy to create a beautiful website for free. Edit your site in the CMS (or your favorite editor), generate it with [Hugo](https://github.com/gohugoio/hugo), and deploy with GitHub or Netlify. Customize anything on your site with widgets, light/dark themes, and language packs.

- 👉 [**Get Started**](https://hugoblox.com/hugo-themes/)
- 📚 [View the **documentation**](https://docs.hugoblox.com/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- ⬇️ **Automatically import citations from BibTeX** with the [Hugo Academic CLI](https://github.com/GetRD/academic-file-converter)
- 🐦 Share your new site with the community: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- 🗳 [Take the survey and help us improve #OpenSource](https://forms.gle/NioD9VhUg7PNmdCAA)
- 🚀 [Contribute improvements](https://github.com/HugoBlox/hugo-blox-builder/blob/main/CONTRIBUTING.md) or [suggest improvements](https://github.com/HugoBlox/hugo-blox-builder/issues)
- ⬆️ **Updating?** View the [Update Guide](https://docs.hugoblox.com/hugo-tutorials/update/) and [Release Notes](https://github.com/HugoBlox/hugo-blox-builder/releases)

## We ask you, humbly, to support this open source movement

Today we ask you to defend the open source independence of the Wowchemy website builder and themes 🐧

We're an open source movement that depends on your support to stay online and thriving, but 99.9% of our creators don't give; they simply look the other way.

### [❤️ Click here to become a GitHub Sponsor, unlocking awesome perks such as _exclusive academic templates and widgets_](https://github.com/sponsors/gcushen)

## Demo credits

Please replace the demo images with your own.

- [Female scientist](https://unsplash.com/photos/uVnRa6mOLOM)
- [2 Coders](https://unsplash.com/photos/kwzWjTnDPLk)
- [Cafe](https://unsplash.com/photos/RnDGGnMEOao)
- Blog posts
  - https://unsplash.com/photos/AndE50aaHn4
  - https://unsplash.com/photos/OYzbqk2y26c
- Avatars
  - https://unsplash.com/photos/5yENNRbbat4
  - https://unsplash.com/photos/WNoLnJo7tS8
