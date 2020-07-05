# Introduction

This repository(folder) contains all the files for the website and is also the medium through which it is deployed on the internet using [GitHub Pages](https://pages.github.com/).

Each [commit](https://help.github.com/en/desktop/contributing-to-projects/committing-and-reviewing-changes-to-your-project) updates the website that are shown on the main website page https://cetbwh.org a few minutes later. 

Most parts of the website are developed in-house and use different elements from all over the internet so the source-code might feel like it is all over the place. We have tried our best to make the code readable and follow all the guidelines. 

If there are any issues with the deployment of the website or any other errors/issues with the process that are not specified in this document then do let us know anytime and we'll try to get back at the earliest. 



## Adding Content to the Website

### For General Users

Navigate to the `.html` files directly from the website, double-click on the `.html` file and click on `edit`, make the changes, write a commit message such as "Added new member info" and click on commit. 

To add photos, go to `images/team/` and go inside the required folder to add the photo of new members. The photos can be uploaded directly on the GitHub website. 

Whenever a change is committed, the website is deployed on the internet again with the new changes and they show up on the website a few minutes later. 

## Adding New Members

Each category of members has its own `.html` file in the folder. For example, `phd_students.html` contains all the information of all the phD students for the website. 

Now, let us look at the lines of code that deals with the information of PhD Students (lines can be found[ here](https://github.com/Center-For-Engineered-Therapeutics/Center-For-Engineered-Therapeutics.github.io/blob/6ccefb27c4703e30c6d13c3bbfd4ae7a73af1fbc/phd_students.html#L176) (176-189)):

*Each `<tag>` in html closes with a `</tag>` .*

![](/images/code_example.png)

Copy the above piece of code [here](https://github.com/Center-For-Engineered-Therapeutics/Center-For-Engineered-Therapeutics.github.io/blob/6ccefb27c4703e30c6d13c3bbfd4ae7a73af1fbc/phd_students.html#L256) (add more members below the last member `</div>` tag) with the following changes:

- To add a new member
  
  - Change the name at the `<h3>` tag.
  
  - Add the image destination at `<img>` tag under `src` . 
  
  - Optionally, the LinkedIn of the members can be added under `<a href="#">` tag replacing the hashtag. 

- To edit a member info
  
  - Change the information under the above mentioned tags.

- To delete the member info
  
  - Delete the entire `<div>` tag shown in the image above.



## Adding New Publications

The list of all the publications are under `publications.html` file. The steps to create, update or delete publications is similar to the steps performed above. 

![](/images/pub_example.png)

Copy the above piece of code [here](https://github.com/Center-For-Engineered-Therapeutics/Center-For-Engineered-Therapeutics.github.io/blob/6ccefb27c4703e30c6d13c3bbfd4ae7a73af1fbc/publications.html#L2797) with the following changes:

- To add a new publication
  
  - Change the names under the `<p>` tags following the authors and journal names. 
  
  - Google Scholar and/or PubMed links can be added under the `<a href="">` tag. 
  
  - Remove the entire `<td>` tag if the link is not available. 
    
- To edit a member info
      
  - Change the information under the above mentioned tags.
    
- To delete the member info
    
  - Delete the entire `&lt;div&gt;` tag shown in the image above.


