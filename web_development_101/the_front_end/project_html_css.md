### Introduction

For this mini-project, you'll deconstruct an existing web page and rebuild it. Don't worry if the links don't go anywhere and the search box doesn't do anything when you submit it. The goal is to start thinking about how elements get placed on the page and roughly how they get styled and aligned. For some of you, this may be the first time you've actually tried to "build" something in HTML (very exciting!).

Using the browser's developer tools (right-clicking something on the page and clicking "inspect element" will get you there) will be your best friend. Build the page in a .html text file and open it in your browser to check it out (or try using [CodePen](http://codepen.io/pen/) or [jsfiddle.net](http://www.jsfiddle.net)).

### Try These Before Starting

These skills will be helpful for you when you start building. Either try them yourself or at least make sure you know how to do it:

1. Two ways to move a div around on the page
1. Stick a div onto the bottom or top of the page
1. Identify the background color of an existing webpage
1. Grab the URL for an image from an existing webpage
1. Center an element horizontally
1. Identify three ways you can include your CSS styles in a page
1. Understand how to use classes and ids to target CSS at specific elements on the page
1. Build a very basic form (even if it doesn't "go" anywhere)

### Setting Up Your Project's GitHub Repository (optional)

As mentioned in the [introduction to Git](/courses/web-development-101/lessons/introduction-to-git), you'll want to organize all your projects like a portfolio and link them to GitHub so it can be seen by others.

If you do not know how to set up a repository, follow the instructions found in [Project: Git Basics](/courses/web-development-101/lessons/practicing-git-basics) to learn how.

1. If you haven't already, create a folder on your computer called `the_odin_project` and `cd` into it. This folder will house all the projects you do at Odin.
2. Create a new repo for this project on GitHub.com and call it `google-homepage` (instead of `git-test`).
3. Then move that repository onto your local machine. The command should look like: `git clone git@github.com:username/google-homepage.git` (use SSH)

- [Setting up SSH on GitHub](/courses/web-development-101/lessons/setting-up-git#step-2-configure-git-and-github).

4. Now `cd` into the `google-homepage` project directory that is now on your local machine; set up your `README.md` file and write a brief introduction for what the current project is and what skills you have demonstrated once you have completed it. (You can do this as a self-reflection at the end of the project which is a good way to review what you have learned.)
5. If you want to share your solution, include a link in the markdown file included at the top of the Student Solutions section.

If you are having trouble:

- Ensure you followed the steps [here on Step 2.3](/courses/web-development-101/lessons/setting-up-git#step-2-configure-git-and-github) to clone from GitHub with SSH.
- Refer to the [cheat sheet](/courses/web-development-101/lessons/git-basics) in the Git Basics Lesson.
- Review the [workflow](/courses/web-development-101/lessons/practicing-git-basics) in the Git Basics Project.

Note: All Git commands need to be run from inside your project's folder (did you forget to `cd` into the `google-homepage` folder?)

_When you're building your project, you will probably end up doing several `git add` + `git commit` cycles before being ready to push it up to GitHub with `git push origin master`._

If you have entered `git push origin master` and typed out your username and password, if you refresh your GitHub page, you should see new files added onto GitHub.

Okay, that's enough Git for the moment -- time to actually build stuff!

### Assignment

#### Easy Version: Build the [Google.com](http://www.google.com) homepage

(the simple one with just a search box).

Inside your project folder, create your index.html file

1. Tips:
   - DON'T BE A PERFECTIONIST! You're just trying to make it _look_ like google.com, not actually function like it and it doesn't have to be spaced exactly the same way to the pixel. Any dropdown menus or form submissions or hover-highlighting should be ignored.
   - USE GOOGLE! You'll probably run into roadblocks where you can't figure out how to do something so do what all good devs do... Google it!
   - Now is a good time to [set up the live server extension](https://youtu.be/mGORIVStWWc) in VSCode, if you haven't already.
   - If you're frustrated with trying to get buttons or inputs to style the way you want (for instance, they seem to just not respond to any styles), look into the CSS property `-webkit-appearance: none;` or `-moz-appearance` if you're using Firefox.
   - [Here's a link to the Google Logo just in case they temporarily replace it with a Doodle!](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)
   - [Here's a cached page of the Google home page for reference in case the original logo is not there.](https://web.archive.org/web/20191130234759/https://www.google.com/)
2. Start with just putting the main elements on the page (the logo image and search form), then get them placed horizontally. You can either download the Google logo or link directly to its URL on the web in your `<img>` tag.
3. Next do the navbar across the top, first building the content and then trying to position it. Check out [how to build a horizontal CSS navbar](http://www.w3schools.com/css/css_navbar.asp) if you're lost.
4. Finally, put in the footer, which should be very similar to the top navbar.
5. In general, do as much on your own as you can before relying on the developer tools (or viewing the page's source code) to help you along.
6. Push your project to GitHub using the instructions above!

#### Difficult Version (optional): Build the [Google.com search results page](https://www.google.com/search?q=build+this+webpage)

You should be able to reuse much of your code from before if you started with that project. Again, don't worry about links to nowhere and forms that won't submit and hard coding the search results (which you'll have to do of course), just focus on placement and order of items on the page.

Note: All the classes and id's and names of elements that you inspect on Google's home page are nonsensical strings (like `<div class='srg'>`). This is because the code was **Minified** ([see the Wikipedia entry here](<http://en.wikipedia.org/wiki/Minification_(programming)>)), which removes or shortens unnecessary characters and names to help the page load faster. The HTML (or JavaScript or CSS) file will be smaller but the browser can still read it just fine.

### Viewing your project on the web

If you want to show your work (the project) to others, or submit a solution below, you will need to publish your site so that others can access it from the web, rather than just on your local machine. The good news is that if you have your project on GitHub (as described above) doing this is incredibly simple.

GitHub allows you to publish web projects directly from a GitHub repository. Doing this will allow you to access your project from `your-github-username.github.io/your-github-repo-name`

There are a couple of ways to go about doing this, but the simplest is this:

- make sure that the main HTML file of your project is called `index.html`. If it is not, you will need to rename it.
- go to your GitHub repo on the web and click the **Settings** button
- scroll down until you find the **GitHub Pages** section
- change the **Source** from _none_ to _master branch_ and click Save.
- it may take a few minutes (the GitHub website says up to 10) but your project should be accessible over the web from `your-github-username.github.io/your-github-repo-name` (obviously substituting your own details in the link)

### Student Solutions

Submit a pull request with a link to your solution in this [file](https://github.com/TheOdinProject/curriculum/blob/master/web_development_101/the_front_end/project_html_css.md) when your project is complete. See the section on [Contributing](http://github.com/TheOdinProject/curriculum/blob/master/contributing.md) for how.

<details markdown="block">
  <summary> Show Student Solutions </summary>

* Add your solution below this line!
* [DomilsonFirmino Solution (Easy)](https://github.com/DomilsonFirmino/google-homepage) - [View in Browser](https://domilsonfirmino.github.io/google-homepage/)
* [25mm's Solution (Easy)](https://github.com/25mm/google-homepage) - [View in Browser](https://25mm.github.io/google-homepage/)
* [elaol93's Solution (Easy)](https://github.com/elaol93/google-homepage) - [View in Browser](https://elaol93.github.io/google-homepage/)
* [dronevil's Solution (Easy)](https://github.com/dronevil/google-homepage) - [View in Browser](https://dronevil.github.io/google-homepage/)
* [Ollie2304's Solution (Easy)](https://github.com/Ollie2304/TOP-Google-Homepage-Assignment) - [View in Browser](https://ollie2304.github.io/TOP-Google-Homepage-Assignment/)
* [Cendevs' Solution (Easy)](https://github.com/Cendevs/google-homepage-) - [View in Browser](https://cendevs.github.io/google-homepage-/)
* [Hugh9's Solution (Easy)](https://github.com/Hugh9/google_homepage) - [View in Browser](https://hugh9.github.io/google_homepage)
* [cabtdesigns' Solution (Easy)](https://github.com/cabtdesigns/google-homepage) - [View in Browser](https://cabtdesigns.github.io/google-homepage//)
* [virto' Solution (Easy)](https://github.com/virto/google-homepage) - [View in Browser](https://virto.github.io/google-homepage/)
* [carloscodes' Solution (Easy)](https://github.com/carloschancodes/google-homepage) - [View in Browser](https://carloschancodes.github.io/google-homepage/)
* [Abordan Peter's Solution (Easy)](https://github.com/Pety99/google_homepage) - [View in Browser](https://pety99.github.io/google_homepage/)
* [berghdavid's Solution (Easy)](https://github.com/berghdavid/Google-lookalike) - [View in Browser](https://berghdavid.github.io/Google-lookalike/)
* [lrwthns's Solution (Easy)](https://github.com/lrwthns/google-homepage) - [View in Browser](https://lrwthns.github.io/google-homepage/)
* [dd301's Solution (Easy)](https://github.com/dd301/google-homepage) - [View in Browser](https://dd301.github.io/google-homepage/)
* [Christine's Solution (Easy)](https://github.com/galleryofplaces/google-homepage) - [View in Browser](https://galleryofplaces.github.io/google-homepage/)
* [FranekB's Solution (Easy)](https://github.com/FranekB/google-homepage) - [View in Browser](https://franekb.github.io/google-homepage/)
* [RyanzpLee's Solution (Easy)](https://github.com/RyanzpLee/google-homepage) - [View in Browser](https://ryanzplee.github.io/google-homepage/)
* [CaptianCustard's Solution (Easy)](https://github.com/CaptianCustard/google_homepage) - [View in Browser](https://captiancustard.github.io/google_homepage/)
* [reinimax's Solution (Easy)](https://github.com/reinimax/google-homepage) - [View in Browser](https://reinimax.github.io/google-homepage/)
* [ASentientTomato's Solution (Easy)](https://asentienttomato.github.io/google-homepage/) - [View in Browser](https://asentienttomato.github.io/google-homepage/)
* [Eric M. Todd's Solution (Easy)](https://github.com/EricMTodd/google-homepage) - [View in Browser](https://ericmtodd.github.io/google-homepage/)
* [Tendai Makina's Solution (Easy)](https://github.com/keenah27/google-homepage) - [View in Browser](https://keenah27.github.io/google-homepage/)
* [kloba1004's Solution (Easy)](https://github.com/kloba1004/google-homepage) - [View in Browser](https://kloba1004.github.io/google-homepage/)
* [TJ647's Solution (Easy)](https://github.com/tj647.github.io/google-homepage/) - [View in Browser](https://tj647.github.io/google-homepage/)
* [unotreal's Solution (Easy)](https://github.com/unotreal/google-homepage) - [View in Browser](https://unotreal.github.io/google-homepage/)
* [diogofcr's Solution (Easy)](https://github.com/diogofcr/google-homepage) - [View in Browser](https://diogofcr.github.io/google-homepage/)
* [Sabrina's Solution (Easy)](https://github.com/SabrinaWi/google-homepage) - [View in Browser](https://sabrinawi.github.io/google-homepage/)
* [yosraemad's Solution (Difficult)](https://github.com/yosraemad/google-homepage-clone) - [View in Browser](https://yosraemad.github.io/google-homepage-clone/)
* [rhiannonthompson's Solution (Easy)](https://github.com/rhiannonthompson/google-homepage) - [View in Browser](https://rhiannonthompson.github.io/google-homepage/)
* [Jacob's Solution (Easy)](https://github.com/JacobGiordano/google-homepage) - [View in Browser](https://jacobgiordano.github.io/google-homepage/)
* [Emmanuel Effi's Solution (Easy)](https://github.com/EmmanuelEffi/google-homepage) - [View in Browser](http://effisgoogle.ml/)
* [ChrisJGuard's Solution (Easy)](https://github.com/ChrisJGuard/google-homepage) - [View in Browser](https://chrisjguard.github.io/google-homepage/)
* [mmjordan11's Solution (Easy)](https://github.com/mmjordan11/google-homepage) - [View in Browser](https://mmjordan11.github.io/google-homepage/)
* [Vinu's Solution (Easy)](https://github.com/Vinu-Devaraj/google-homepage) - [View in Browser](https://vinu-devaraj.github.io/google-homepage/)
* [JesseN619's Solution (Easy)](https://github.com/JesseN619/google-homepage) - [View in Browser](https://jessen619.github.io/google-homepage/)
* [tranesid's Solution (Easy)](https://github.com/tranesid/google-homepage) - [View in Browser](https://tranesid.github.io/google-homepage/)
* [Vedant Wankhade's Solution (Easy)](https://github.com/VedantWankhade/google-homepage) - [View in Browser](https://vedantwankhade.github.io/google-homepage/)
* [Cramer99's Solution (Easy)](https://github.com/Cramer99/google-homepage) - [View in Browser](https://cramer99.github.io/google-homepage/)
* [kbhvrs's Solution (Easy)](https://github.com/kbhvrs/google-homepage) - [View in Browser](https://kbhvrs.github.io/google-homepage/)
* [Kaynec's Solution (Easy)](https://github.com/Kaynec/kaynec.github.io) - [View in Browser](https://https://kaynec.github.io/)
* [Jane Agim's Solution (Easy)](https://github.com/janeagim/google-homepage) - [View in Browser](https://janeagim.github.io/google-homepage/)
* [khanzzyyy1's Solution (Easy)](https://github.com/khanzzyyy1/google-homepage) - [View in Browser](https://khanzzyyy1.github.io/google-homepage/)
* [JatraMaya's Solution (Easy)](https://github.com/JatraMaya/google-homepage) - [View in Browser](https://jatramaya.github.io/google-homepage/)
* [Reize00's Solution (Easy)](https://github.com/Reize00/google-homepage) - [View in Browser](https://reize00.github.io/google-homepage/)
* [aderose's Solution (Difficult)](https://github.com/aderose/google-search-page/) - [View in Browser](https://aderose.github.io/google-search-page/)
* [aderose's Solution (Easy)](https://github.com/aderose/google-homepage) - [View in Browser](https://aderose.github.io/google-homepage/)
* [Christopher Mendez's Solution (Easy)](https://github.com/cmendez20/google-homepage) - [View in Browser](https://cmendez20.github.io/google-homepage/)
* [Koalatree's Solution (Easy)](https://github.com/koalatree/google-homepage) - [View in Browser](https://koalatree.github.io/google-homepage/)
* [@theghos1980 - Saturno Mangieri (Easy)](https://github.com/theghost1980/google-homepage) - [View in Browser](https://theghost1980.github.io/google-homepage/google-search-easy.html)
* [Siddharth Sahoo's Solution (Easy)](https://github.com/sidd-oo/google-homepage) - [View in Browser](https://sidd-oo.github.io/google-homepage/)
* [Anna's Solution (Easy)](https://github.com/annatake/google-homepage-project) - [View in Browser](https://annatake.github.io/google-homepage-project/)
* [Zahir's Solution (Easy)](https://zahnieb.github.io/google-homepage/) - [View in Browser](https://zahnieb.github.io/google-homepage/)
* [Nick's Solution (Difficult)](https://github.com/nmccooey/google-search-page) - [View in Browser](https://nmccooey.github.io/google-search-page/)
* [Diogo Costa's Solution (Easy)](https://github.com/drscosta/google-home) - [View in Browser](https://drscosta.github.io/google-home/)
* [Tom's Solution (Easy)](https://github.com/thomasokc/google-homepage) - [View in Browser](https://thomasokc.github.io/google-homepage/)
* [JustinL's Solution (Easy)](https://github.com/JustinL404/google-home-page) - [View in Browser](https://justinl404.github.io/google-home-page/)
* [Cherry Danish's Solution (Easy)](https://github.com/CherryDanish/odinproject-google-homepage) - [View in Browser](https://
