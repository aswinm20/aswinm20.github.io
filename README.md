# Hosting a Markdown Resume on GitHub Pages

## Purpose

After going through this README, it will have served two purposes: 

1. To provide a detailed guide on the practical steps for hosting and formatting a Markdown resume on GitHub Pages.

2. To draw connections between the above practical steps and the principles of modern technical writing described by Andrew Etter in his book, "Modern Technical Writing".

## Prerequisites

>Ensure you have a resume in Markdown format.


~~~
In his book "Modern Technical Writing", Andrew Etter emphasizes the use of lightweight markup languages,
such as Markdown ,due to its simplicity and readability. By using Markdown for your resume, you make
it accessible and easily editable across different plaforms. 

Markdown's easy to understand syntax improves readability according to Andrew Etter. He mentions in his
book that content should be easily understandable in its raw or original form, and by using Markdown we
are mirroring this principle. 
~~~


## Instructions

**1. Create A GitHub Account**
> 1. Visit [github.com](github.com) and click on Sign Up 
> 2. After creating your account, you should end up with a page that looks similar to this
>    
> ![Screenshot 2024-03-07 081546](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/74059718-40b7-42a3-8eab-8e5a508e8ee0)

```
In his book "Modern Technical Writing", Andrew Etter emphasizes the advantage of distributed version 
control systems such as Git. By applying distributed version control system into documentation, 
it ensures performance, offline capabilities, and streamlined collaboration. By hosting your markdown resume 
on GitHub, which is a distributed version control system platform, you take advantage of an environment that 
supports efficient version control and collaboration.
```


<br>

**2. Create a new Repository on your GitHub account**
> 1. Click on the "Create Repository" button that is located on the top left of your current page.
>    
> ![Screenshot 2024-03-07 083415](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/07690590-9bbd-4627-9d27-524b9975db4c)
>
> 2. Enter your GitHub user name along with ".github.io" in the "Repository Name* input box.
>    ***For example**: if my GitHub user name is aswinm20 , then I will name my repository, "aswinm20.github.io".*
>
> ![Screenshot 2024-03-07 084251](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/9e3dd4eb-1346-4e99-8d6a-1a89755eaab4)
>
> After you have created your new repository, you will end up with a page like this.
>
> ![Screenshot 2024-03-07 085127](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/d033f4e0-bf23-47cf-8e6a-d5639c4db7f1)

<br>

**3. Upload your resume to the repository**
> 1. Click on "creating a new file" on your repository page
>
> ![Screenshot 2024-03-07 085505](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/803848de-c067-4c9c-96d6-967984606451)
>
> 2. Name your file "index.md" and copy paste your resume into the box
>
> ![Screenshot 2024-03-07 090118](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/3d5a3e33-873e-4b49-a13e-20b9cd74a58f)
>
> 3. Click on "Commit changes..." to finish uploading the file.
>
> After you have followed the above steps you will end up with a page like this.
>
> ![Screenshot 2024-03-07 085819](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/990ff441-26fb-48cb-ae46-99b6d898b039)

<br>

**4. Add a theme to your resume**
> 1. Click on "Add file" button and select "Create new file".
>
> ![Screenshot 2024-03-07 092249](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/40e72863-0e38-44ce-904f-a242b078ecf8)
>
> 2. Name your file "_config.yml".
> 3. Write "remote_theme: daattali/beautiful-jekyll" in the input box. <br>
> 
> ![Screenshot 2024-03-07 094153](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/3ff82899-522a-4e67-97e1-bee040d4be53)
>
> 4. And finally, click "Commit Changes..." on the top right to finish adding your theme.
>
> After doing the above steps, you will notice how there is a orange dot in your repository page
>
> ![Screenshot 2024-03-07 094547](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/7dde3509-0e72-46e8-b35a-95e2358b5140)
>
> 5. Wait for this dot to turn green and into a check mark like so.
>
> ![Screenshot 2024-03-07 095648](https://github.com/Aswin-Manoj/Aswin-Manoj.github.io/assets/131378919/0e329ea5-1583-4fdb-9b27-2bf2c5315192)
>

```
According to Andrew Etter in his book, "Modern Technical Writing", for a unique and eye catching website, 
customization of themes is crucial. In our example, we used a theme to add some style and structure to   
our hosted resume. This customization is essential for differentiating content between pages and websites, 
which aligns with Etter's idea on creating visually appealing websites.
```

<br>


**5. Open your hosted resume using a url link.**
> 1. Search the url "[your GitHub username].github.io" to view your hosted resume. <br>
>    ***For example**: If my GitHub username is aswinm20 , then I will search the url, aswinm20.github.io*
>    
> When you open the link, your Markdown resume should look similar to this.
> 
>![ezgif com-animated-gif-maker](https://github.com/aswinm20/aswinm20.github.io/assets/162495676/b2002a12-b467-434c-aae6-3f0c9c47cf73)


```
In his book "Modern Technical Writing", Andrew Etter emphasizes the use of static websites because of 
its ability to take lightweight markup(such as Markdown) and processing them into a functional website. 
He also mentioned that, by utilizing a static site generator, any changes that have be to made to the website 
(in our case, the hosted resume) becomes a simple task of changing the content. This is exactly why we chose 
GitHub Pages due to its ability to host static websites.
```

## More Resources

- Visit this [link](https://www.markdownguide.org/getting-started/) to have a general understanding of Markdown.

- Visit this [link](https://www.markdowntutorial.com/) for an quick and easy tutorial on the basics of Markdown.

- Since, we will be focussing on hosting a Markdown formatted resume on Github Pages, here is a [link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to some useful syntax on GitHub Flavoured Markdown.

-  Themes make your Websites have style and structure. Here, we used the theme "daattali/beautiful-jekyll", but you are not limited to just this one option. Visit this [link](https://pages.github.com/themes/) to explore more themes.

- Visit the [GitHub Pages Documentation](https://docs.github.com/en/pages) to gain a deeper understanding of its features for hosting static websites.

- Visit the [Jekyll Official Documentation](https://jekyllrb.com/docs/) to gain a deeper understanding of Jekyll, the static site generator used by GitHub Pages.


## Author and Acknowledgments
 I want to thank

- Andrew Etter for insights on DVCS, static web pages, and markup languages from his book, "Modern Technical Writing".

- Daattali for their beautiful-jekyll theme, enhancing the aesthetics of the hosted resume.

- Shaun Paraplammoottil Cheiryan and Zack Wiebe for their valuable feedback on this README.

- And finally, professor Stewart for guidance and support throughout the development of this README. 

## FAQs

Q1) Why is Markdown better than a word processor?
> Markdown is preferred over a word processor for several reasons:
>
> - According to Andrew Etter in his book, "Modern Technical Writing" , he mentions how markup languages like Markdown uses straightforward and simple syntax which is easy to read. This helps to focuss on the content rather than worry about the formatting.
>
> - He also mentions in his book that Markdown files are platform-independent due it being primarly text-based. According to Andrew, a word processor will be useful for resumes, but unsuitable for technical documentation because, it does not work well with version control and HTML export. However, according to him, this is not the case with Markdown as it can handle the two latter conditions.

Q2) Why is my resume not showing up?
> If your hosted resume is not appearing, consider the following troubleshooting steps:
>
> - ***Resume File Name***: Ensure your resume file name is "index.md" as this crucial for GitHub Pages to identify it as the main page. <br> 
> - ***Theme Settings*** : Ensure the file that specfies your theme has the name "_config.yml" and also check that there are no spelling mistakes in your theme selection. <br>
> - ***Wait for Changes*** : Any changes made to the content of your resume will take time to reflect on the url. Give it some time and refresh the page.
> - ***Markdown Syntax Errors*** : Ensure that your Markdown resume has proper syntax.
