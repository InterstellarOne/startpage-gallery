# Startpage Gallery
A static community gallery showcasing startpages (New Tab pages) from across the internet. Pages can be submitted through GitHub issues, which automatically will open a pull-request with the startpage's information.

https://startpage.gallery

\
![](https://raw.githubusercontent.com/InterstellarOne/startpage-gallery/refs/heads/master/public/gallery-cover.png)

## How to contribute

### Submitting a new startpage
Visit the [Submission issue page](https://github.com/InterstellarOne/startpage-gallery/issues/new?template=submit-startpage.yml
) and follow the instructions there to submit a startpage. You do not have to be affiliated with the startpage to submit it, but you must at least like the startpage. 

**Things to keep in mind:**
- Make sure the image you upload is 16:10 and large enough to look decent at the scale of the card.
- Only .png, .jpg, and .jpeg are accepted file formats. 
- You can upload edited images, but they must showcase an actual screenshot of the project.
- Github will allow you to upload multiple images, but please only upload one. If you do upload multiple, only the first one uploaded will actually be added to the repository, and the rest won't be easily accessible.
- When adding tags, please use existing ones when possible, rather than adding new tags that could represent the same thing. (e.g. use "Clock" instead of "Time")
- If the startpage is just named "startpage" or "New Tab", I will append the author name in brackets after the startpage, e.g. "startpage (InterstellarOne)".

### Editing an existing startpage
Edit requests are not guaranteed to be accepted. If there is a typo or a link that is incorrect, I will accept it, but if you are making significant changes you may want to provide some information on your affiliation to the project to have a better chance of having your edit accepted. To submit an edit request, there are two possible methods.
1. **Pull Request** - If you are comfortable creating a pull request, you may do so. Please provide a description of what you changed, and justify why you think the change is beneficial.
The data for each startpage is stored in json files in [src/content/startpages/](https://github.com/InterstellarOne/startpage-gallery/tree/master/src/content/startpages), and screenshots are stored in [public/screenshots/](https://github.com/InterstellarOne/startpage-gallery/tree/master/public/screenshots). If you replace the image, please keep the filename the same. Remember that you may have a maximum of eight tags.
2. **Edit Issue** - Create a new [Edit existing issue](https://github.com/InterstellarOne/startpage-gallery/issues/new?template=edit_existing.md) and follow the instructions there.

### Feature requests / Bugs
Please submit enhancements and bugs to the issues tag! I will do my best with my limited time to respond and add things that will improve the site. This is my first time making a website, so while the code is all mine, it may be messy.

## Credits
- Icons courtesy of [Lucide](https://lucide.dev/), [Tabler Icons](https://tabler.io/icons), [Font Awesome](https://fontawesome.com/), and [Simple Icons](https://simpleicons.org/)
- Site built using [Astro](https://astro.build/)
- Inspired by https://firefoxcss-store.github.io/
- Thank you to [this course](https://webdevsimplified.github.io/fem-getting-started-with-javascript/) for teaching me basic JavaScript.
- I am using [Issue Form Parser - GitHub Action](https://github.com/onmax/issue-form-parser) by onmax for automatic parsing of GitHub issues.
- [Chrome Stats API](https://chrome-stats.com/docs/api) is used for chrome extension data.

## AI Usage Disclosure
I used Gemini as a source of information for this project, mainly when working with Astro and when trying to understand REST APIs for different services, as the documentation was often lackluster or missing important details. I did my best to use Startpage (the search engine!)/Stack Overflow when possible when searching for information so I was not reliant on Gemini when creating the website. I have a background in C, so while I am new to JavaScript, most of the syntax is the same so programming the backend was fairly straightforward.
