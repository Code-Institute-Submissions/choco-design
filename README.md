# Choco - Design Website

[Click for live website demo](https://bencheee.github.io/choco-design/)

This website is part of my 1st milestone project in Coding Institute's Full Stack Software Development Course. This is website for imaginary company called 'Choco-Design'. This company is making unique chocolate products and selling them to other businesses such as hotels, bars, restaurants, shops, etc. Website is made to be fully responsive on range of devices to provide great browsing experience for existining partners and potential new customers.

![Mockup image of responsive website](/mockup.JPG)


## User Experience (UX)

### User stories

#### 1. First Time Visitor Goals

* As a First Time Visitor, I want to easily understand the main purpose of the site and what is company's main objective.
* As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
* As a First Time Visitor, I want to find out more about the products which are for sale.
* As a First Time Visitor, I want to find out more about the company and also I want to locate their social media links to see their followings and to determine how trusted and known they are.

#### 2. Returning Visitor Goals

* As a Returning Visitor, I want to find photo gallery with all products offered by company.
* As a Returning Visitor, I want to find the best way to get in contact with the the company with any enquiries I may have.

#### 3. Frequent User Goals

* As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.


## Wireframes

* [Mobile view](wireframes/wireframes-mobile.pdf)
* [Tablet view](wireframes/wireframes-tablet.pdf)
* [Desktop view](wireframes/wireframes-desktop.pdf)


## Design

### Colour Scheme

The two main colours used are dark chocolate brown (#2b1e18) and creamy beige (#ffdcbb).

### Imagery

The large, banner images are showing different types of chocolate products with colors matching site's colour scheme. Purpose of images is to give clear idea of the purpose of the site and to also make it visually attractive.

### Typography

The Thasadith font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. On some of the headings there is combination of Commissioner and Euphoria Script fonts with Sans Serif as the fallback font.


## Features

* Responsive on all device sizes
* Interactive elements


## Technologies Used

### Languages Used

* HTML5
* CSS3 

### Frameworks, Libraries & Programs Used

* Gitpod

Gitpod was used to write all the HTML and CSS code for the website.

* Git

Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

* GitHub

GitHub is used to store the projects code after being pushed from Git.

* Hatchful logo maker

Hatchful is free online logo generator which was used to create logo for the company which is used on the website.

* Balsamiq

Balsamiq was used to create the wireframes during the design process.

* Photopea.com

Photopea is free online photo editor which was used to resize and optimize logo and photos for the website.

* Font Awesome

Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

* Google Fonts

Google fonts were used to import the 'Thasadith', 'Commissioner' and 'Euphoria Script' fonts into the style.css file which is used on all pages throughout the project.


## Testing

### Testing User Stories from User Experience (UX) Section

#### 1. First Time Visitor Goals

* As a First Time Visitor, I want to easily understand the main purpose of the site and what is company's main objective.
  * On every page of the website there is a big banner with chocolate photo and company logo which clearly suggests the theme of the website.
  * On the left side of the banner there is a welcoming title with brief marketing text which tells main purpose of website and every page. *(On mobile and tablet version title section is above banner)*
  * Below banner on the main page there is main content area which contains more details on types of business that owner of the company identified as key partners.

* As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
  * The site has been designed to be responsive on mobile, tablet and desktop sizes. At the top of each page there is a clean navigation bar. Each link clearly describes to which page user will be redirected.
  * Layout of the website is consistent with navigation bar, banner section, content section and footer on every page.
  * At the bottom of every page there is a link to bring the user to the top of the page.
  * On gallery page in desktop view there are thumbnail images that act as links to each gallery podsection.
  * At the end of each gallery podsection in desktop view there is a link which brings user back to the main gallery menu.

* As a First Time Visitor, I want to find out more about the products which are for sale.
  * On main gallery page products are organized in categories with clear text description for every podsection.
  * In desktop view user has the option to click on image thumbnails to access the gallery with more images of the same product type.
  * In mobile and tablet views there are no thumbnail links, and in mobile version there are only two photos per each section.

* As a First Time Visitor, I want to find out more about the company and also I want to locate their social media links to see their followings and to determine how trusted and known they are.
  * 'Contact' page of the website provides the user with all relevant information about the company and it's owner Betty Miller in 'About Us' section.
  * In the footer area throughout the website there are icons linking to company's profiles on various social media accounts. Links are opening in new tabs with intention of keeping user on our website after checking social media sites.

#### 2. Returning Visitor Goals

* As a Returning Visitor, I want to find photo updated gallery with all products offered by company.
  * Gallery section has 'new' badge feature added to photos to clearly shows which products are newest in company's portfolio.

* As a Returning Visitor, I want to find the best way to get in contact with the the company with any enquiries I may have.
  * On every page in the website there is a call to action button which invites the user to enquire about products. Click on this button will redirect the user directly to contact form.
  * On the navigation bar  throughout the website there is a link to 'Contact' page. There user can fill out the provided form and send the message directly to the company email. Alternatively user can contact the company via one of the social media links provided in the footer.
  * The footer contains links to the company's Facebook, Instagram, Pinterest and Youtube profiles as well as the email link. Each link will be opened in new tab to ensure that user can easily get back to the website. Email link will open default email app and autofill email address in to recepient field.

#### 3. Frequent User Goals

* As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.
  * On 'Contact' page there is a form which allows user to sign up to the newsletter.

### Further Testing

#### Known Bugs

* None

#### Previous bugs (fixed)

* Content boxes on the main page in desktop view are not centered properly.
  * This was caused by following CSS code:

  ```CSS
    .content p:last-of-type {
        margin-top: 50px;  
    }
  ```


## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps:

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps:

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the GitHub Repository
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.
```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
7. Press Enter. Your local clone will be created.
```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```


## Credits

### Media 

* All banner images and image of random woman (used for Betty Miller's profile) are licence free and downloaded from [Unsplash.com](https://unsplash.com/)
* Photos used in gallery section are property of Marina Prijatelj and were used with author's permission. Photos are downloaded from website [cokolada.hr](http://www.cokolada.hr/)

### Content

* All content was written by Sandro Bencinic (developer).
* Betty Miller's character is fictional and was made up by developer.

### Readme

* Code Institute's readme file template was used to create this readme file. Content of this file was modified by developer to match properties of the website.

### Acknowledgements

* My mentor Aaron Sinnott for continuous helpful feedback.
* Tutor support at Code Institute for their support.