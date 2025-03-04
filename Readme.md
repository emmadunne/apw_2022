# README

Currently built at [https://fau-paleo.github.io/apw_2022/](https://fau-paleo.github.io/apw_2022/). 

## About Jekyll

The page is built with jekyll, a neet ruby program which translates markdown documents to html and builds these into static websites. It is insanely powerful. The building process itself is exectued by GitHub itself, you make the changes, commit and push them to the repository and in 1 minute they should be visible - given that everything you have done is ok. If you want to learn more about this, check out [this page](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll). 


If you have Jekyll installed on your computer, you can also render and check out how the page looks like offline - but the page is so simple that this is not necessary.  

## For Instructors 

*You are expected to edit the module-specific pages*, which are in the `_posts` directory. These pages have a front matter (before the dashes), don't worry about those - except for the title, which you are more than welcome to change.

| file                                 | correspondent(s) |
|--------------------------------------|------------------|
| 2022-08-01-toolset.md                | Adam/Nuss        |
| 2022-08-02-paleostats.md             | Emma/Wolfgang    |
| 2022-08-03-morphometrics.md          | Manuel           |
| 2022-08-04-gis.md                    | Adam             |
| 2022-08-05-global-diversity.md       | Adam/Emma/Carl   |
| 2022-08-06-div-cmr-abiotic-biotic.md | Lee Hsiang       |
| 2022-08-07-phylogenetics.md          | Rachel/Laura     |
| 2022-08-08-niches.md                 | Erin             |

- For novice git users: to avoid chaos please only edit the page that you are responsible for and use the GitHub interface. If all of this feels overwhelming, don't worry. I (Adam) is more than happy to put material on for you if you'd like!

- I have included examples on every one of these to 1. include links to external files 2. links to downloadable files and 3. images. You can copy these and modify them to include all the material you want to share. You are also welcome to explore! 

- The data files should be put in the `data` directory, then the format `{{site.baseurl}}/data/<your directory path>/filename.ext` is used to create the link to the file. They need to be committed to the git repo. GitHub has a file size limit, if you want to share files that are bigger than 100MB, please use an external hosting service and provide the download links. I (Adam) can also put up big files here. Do not share sensitive files here. 

- The dates of the posts control when they are visible, future posts are not visible, hence the past dates

- I will make the links to the material in the schedule table available on the fly. To help you explore, they are all live at the moment. Even though the links will not work (not to disorient the students), the URLs will be live. It is a good idea therefore to save the URL of the page that you are editing. 


## Markdown

You can find a cheat sheet [here](https://www.markdownguide.org/cheat-sheet/).
