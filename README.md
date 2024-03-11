# Hosting-an-R-Markdown-HTML-file-on-a-GitHub-page
INTRODUCTION

R Markdown is a great package for RStudio. You can create (or knit) an html file using R Markdown which will let you add text, snippets of code, and plots. Additionally, you can run R code in R Markdown and have the output as part of the html document. 

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/8d5448a1-f714-4cf0-b709-c79fa5386f6a/Figure+-+Example.jpg?format=1500w)

You can also create an html file using R Markdown and host it on a GitHub page. This is a feature of GitHub to allow you to host html files from your GitHub account. 

There is a lot of flexibility with GitHub; consequently, I’ve started to explore using this option to post tutorials I’ve generated in R Markdown on GitHub. In this article, I’ll review how I was able to host my R Markdown html files on my GitHub repository using the GitHub desktop application.

Step 1: Download the GitHub desktop application

You can download the GitHub desktop application from their website. 

 

Step 2: Create a repository in GitHub

Next, you’ll need to create a repository in GitHub. 

Open a browser and go to your GitHub page. Create a new repository. For this tutorial, I’ll create the “R Markdown GitHub Page” repository. This is where I will save my R Markdown html file. 

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/5859dc30-4bfd-40b1-b2c5-8228b9168fbd/Figure+0a+-+Create+GitHub+Repository.jpg?format=1500w)


Step 3: Open GitHub Desktop Application

Once you’ve downloaded the app, open it. You should see the “Let’s get started” message. We’ll clone the repository that was created in GitHub (“R Markdown GitHub Page”. Search for this repository and then click on “Clone” 

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/b6612f08-e1d2-4778-8bbb-629fac764257/Figure+2.jpg?format=1500w)

Next, you’ll see a window pop up prompting you to select the location on your computer to clone your repository. Chose a location on your computer where you can easily remember and access. 



![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/e9c23c87-2c19-461c-a84c-b45193a205d3/Figure+3.jpg?format=1500w)

Once you’ve done that, the GitHub application will open to your repository. You can view the files in the folder where you’ve cloned your repository. Click on “Show in Explorer” and a window will appear with a couple of files. Note: When you create your repository, you can elect to have a README file generated. If you did so, then you will see the “README.md” file in this folder. You can ignore the “.git” folder since this is a hidden folder. 


![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/8f63191f-7893-4acc-8222-3bfac0e47513/Figure+4.jpg?format=1500w)

Next, create a folder called “docs” in this cloned repository folder. This is where we will save our R Markdown and html files.


![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/d90a7558-ff56-4f86-908d-3904a214584d/Figure+4a.jpg?format=1500w)

Step 4: Setup the GitHub pages features

Now, return to your GitHub repository that is open in your browser. You will need to setup the GitHub pages features. In the GitHub repository, click on the “Settings” tab. Then click on “Pages” in the “Code and automation” tab. This will allow you to set the GitHub Pages to the main branch and the “docs” folder. 

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/8f14afd7-90e0-43f1-b00c-2ef3c836af2f/Figure+5a.jpg?format=1500w)
![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/fee7410b-d2cf-441c-91db-ec89de8f53e0/Figure+5b.jpg?format=1500w)

Make sure to click “Save” after selecting the “main” branch and the “docs” folder. 

GitHub will generate a url where you can host your R Markdown html file. This may take a few minutes to go live, so click on refresh every few minutes. Once the url has been generated, you will see it on this page.

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/8e643f71-6b37-4dde-9554-0ea43962e377/Figure+5c.jpg?format=1500w)

Step 5: Create R Markdown html

Once you’ve setup your GitHub Pages and activated your url, start RStudio and create a new R Markdown file. 

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/58071643-1c35-4b27-a5c3-33184aa2c768/Figure+6a.jpg?format=1500w)

This will generate an R Markdown default template that we will use for our html example. 

Next you want to click on “Knit” and select “Knit to HTML.” You will be asked to save the HTML file. Navigate to your “docs” folder and save the HTML file as “index.” This will save your HTML file as “index.html” in the “docs” folder. Next, save your R Markdown file as “index.Rmd” in the “docs” folder. You should have two files in the “docs” folder: “index.html” and “index.Rmd”

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/56107378-8d45-47f7-90d1-f988b9501497/Figure+6b.jpg?format=1500w)

Step 6: Push the changes to the main branch

After saving your R Markdown file and html file in the “docs” folder, you will need to push these changes to the main branch. Return to your GitHub application and review the changes that are being made. We have two changes that reflect the addition of two files into the “docs” folder. 

Every time you make a change to the main branch, you have to enter a short note. I entered “Build R Markdown HTML page” for the title of my short note, and then I include a short description of that change. 

Next, I click on “Commit to main” to make the changes to the GitHub application. You will receive a message to push these changes to the main branch. Make sure to select “Push origin” to finalize the changes to the main branch.

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/ceb03ff2-9771-4a65-9a1b-544b6688fb20/Figure+6c.jpg?format=1500w)

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/fe86a612-57c0-4b36-b94d-d3d3f392984c/Figure+6d.jpg?format=1500w)

Step 7: View your R Markdown html file on your GitHub url link

After you push your final changes to the main branch, the R Markdown html file will be hosted on the GitHub url link that you generated. 

![](https://images.squarespace-cdn.com/content/v1/58cde3fcdb29d633eb688e9e/ac90ed98-7d21-434d-9a99-534eb6ec7548/Figure+7.jpg?format=1500w)

CONCLUSIONS

R Markdown is a great way to generate html pages on your R code and output. You can share these files using GitHub Pages in addition to the GitHub application. Additionally, you can work with other folks to make edits and leverage the GitHub applications to push these changes easily to the main branch

This is a work in progress, and I anticipate updating this article as I discover new and innovative ways to improve upon this tutorial.

REFERENCES

[mark bounthavong Blog Post](https://mbounthavong.com/blog/2022/7/30/hosting-a-r-markdown-html-file-on-a-github-page)
