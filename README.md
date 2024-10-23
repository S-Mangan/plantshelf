# HTML notes:
* `<a href="..." target="_blank"></a>`

___

# 🌿PlantShelf  
PlantShelf is a webpage which shows image/information cards for different plants. You can [see the full version (with the card flip extension) running here](https://s-mangan.github.io/plantshelf/).  

In these 2 lessons, you will:  
* Explore and modify the structure (HTML) and style (CSS) of PlantShelf.  
* Learn to use GitHub and git to back up and version-control your code.  

![Plant image cards on the PlantShelf webpage](/documentation/plantshelf.png "Plant image cards (left), and the image cards again with one flipped to show the back (right)")   
*LEFT: Plant image cards*  
*RIGHT: Plant image cards, with one flipped to show the back*

<br/><br/><br/><br/>

## **⯈Part A** GitHub and HTML
### GitHub │ Forking a repository
GitHub is a website which stores files—all their past versions. The files for the PlantShelf webpage (including this README!) are stored in a folder (or *repository*) on GitHub. Your first step is to make your own copy (or *fork*) of this folder on GitHub.

- [x] Go to [GitHub.com](https://github.com/signup) and create a free account (or login if you already have one).  
![Screenshot of signup](/documentation/github_signup.png "Screenshot of signup")

- [ ] Go to [the PlantShelf repository](https://github.com/S-Mangan/plantshelf), click Fork, and accept all the defaults.  
![Screenshot of making a fork](/documentation/github_fork.png "Screenshot of making a fork")

- [ ] Now that you have your own copy, try making a small change to its README:  
![Screenshot of editing the README](/documentation/github_edit.png "Screenshot of editing the README")   

- [ ] When you click Commit Changes, you can write a short message about your change. Make it something descriptive that will help you remember what you changed later (e.g. "added my name to README heading")

- [ ] Now check that see your change in the README on the main page of your fork.

### Visual Studio Code | Making a local copy
The fork you created is a *remote* copy of the original repository. *Remote* means that it doesn't live on your computer---in this case it lives on GitHub's servers.

It will be easier to make changes to the website if you have a *local* copy on Windows. For now, we'll just manually download the code—we'll learn a better way later.

- [ ] Download a zip of your fork and save it in your home folder  
![Screenshot of downloading a zip](/documentation/download.png "Screenshot of downloading a zip")   

- [ ] Unzip the folder

- [ ] Open Visual Studio Code and then open the unzipped folder (File > Open Folder)  

### Visual Studio Code | Modifying the HTML  
Find the index.html file in the tree folder (View > Open View... Folders), and then:
   - [ ] Click and drag the index.html into a browser window to see PlantShelf website. Try hovering over the cards—they should change colour. Note that in this version, the cards don't flip.  
   - [ ] Double click index.html to see the HTML. Notice that the content has 3 main sections:  the header, the main content, and the footer.

Modify the HTML and refresh your browser to see how the website changes:  
   - [ ] Update the GitHub link in the footer to point to your fork.  
   - [ ] Replace some of the card images (see the images folder), and update the card headings to match.  
   - [ ] Change the main website heading

<br/><br/><br/><br/>

## **⯈Part B** git (via GitHub desktop) and CSS
- [ ] CSS variables  
- [ ] Responsive typography and the rem unit  
- [ ] flex layouts: flex-direction (column vs row)   
- [ ] grid layouts: gap, grid-template-columns  
- [ ] psuedo classes and transitions  

## [optional] Card flipping extension
* In  index.html, uncomment all the `<div class="back side">` sections.  
* Also in index.html, link the additional `flip_extension.css` stylesheet.  
* What happens now when you hover over a card?  
* Investigate the TODOs in `flip_extension.css` and try to make the cards flip.  

## [optional] Further information and useful tools
#### Visual Studio Code │ Live Server extensio  * Search and install the Live Server extension (View > Open View... Extensions).  
* Inside your index.html, right click and select "Open with Live Server". A new browser tab should open with your page, and will automatically reload whenever you save a change to the html or css (so you no longer have to refresh!)

* #### Visual Studio Code │ Live Server extension
* Search and install the Live Server extension (View > Open View... Extensions).  
* Inside your index.html, right click and select "Open with Live Server". A new browser tab should open with your page, and will automatically reload whenever you save a change to the html or css (so you no longer have to refresh!)  
