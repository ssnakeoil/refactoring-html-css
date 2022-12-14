# Horiseon Site Refactoring

[>> Link to Deployed Site! <<](https://ssnakeoil.github.io/refactoring-html-css/)

## Screenshot of deployed site:

![site screenshot](./assets/images/refactor-html-css-live-site-screenshot.png)

## Description

This project was completed with the intention to better understand HTML, CSS and git through refactoring. Some features were non-functioning and just needed some polishing up. A lot of things were learned along the way!

## Notes

1. nav h1 selector was used to float "Horiseon" text to the left, but if any additional text was added to the nav using h1 it would float that as well - probably important to note that this worked this time but shouldn't be used for a section containing a lot of text.
2. align-items: center centered items on the y axis but uses line-height to determine a reference point for centering - because of this it became easier to remove padding styles in favor of setting the bar to a specific height and then setting the line height to the same size.
3. In hindsight, could have unified search-engine-optimization + online-reputation-management + social-media-marketing attributes into one attribute.
4. align-items: center items on the y axis but uses line-height to determine a reference point for centering - because of this it became easier to remove padding styles in favor of setting the bar to a specific height and then setting the line height to the same size.
5. These elements are similar: `<div> <header>` but the latter is an example of a semantic element and can provide more information about a section than the former. This may also affect the priority that your browser may see the section contents. More about that [here](https://www.w3schools.com/html/html5_semantic_elements.asp).
6. messing with the ul/li styles changed the order of the list items as well, did not notice until writing up this readme.

 Further notes can be found in comments on commit notes [here](https://github.com/ssnakeoil/refactoring-html-css/commit/e83a6b30a91059a13b5212e23189b82ebe4d6873#commitcomment-86926023) and [here](https://github.com/ssnakeoil/refactoring-html-css/commit/12df748ee21d7816b80e5cd51aa91f6651848674#commitcomment-86925974)

## Credits

- [How to horizontally align (header) elements](https://stackoverflow.com/questions/20887702/horizontal-align-html-header-elements)
- [How to vertically align elements](https://stackoverflow.com/questions/79461/how-can-i-vertically-align-elements-in-a-div)
- [Finding problems in file in VSCode](https://stackoverflow.com/questions/58017905/how-to-find-out-problems-in-this-file-errors-in-vs-code)
- [Branch synchronization](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/keeping-your-local-repository-in-sync-with-github/syncing-your-branch)
- [Pro README guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)
- [Equivalent of alt attribute for div elements](https://thewebdev.info/2021/08/21/what-is-the-equivalent-of-the-alt-attribute-for-div-elements/#:~:text=for%20div%20Elements-,To%20add%20the%20equivalent%20of%20the%20???alt???%20attribute%20for%20div,alt%20attribute%20to%20the%20div.)
