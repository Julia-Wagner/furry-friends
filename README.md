# **Furry Friends Shelter**
[Link to live project](https://julia-wagner.github.io/furry-friends/)

The Furry Friends Shelter is an imagined dog shelter. This static website was created for educational purposes. As described below in the planning phase I considered possible goals a real-world dog shelter and its visitors could have. The website has four pages helping to reach these goals.

![Am I Responsive Screenshot](docs/screenshots/am_i_responsive.png)

## **Table of contents**
- [**Planning**](#planning)
    - [**External user goals**](#external-user-goals)
    - [**Site owner goals**](#site-owner-goals)
    - [**User Stories**](#user-stories)
    - [**Features to achieve the goals**](#features-to-achieve-the-goals)
    - [**Wireframes**](#wireframes)
        - [**Mobile Wireframes**](#mobile-wireframes)
        - [**Tablet Wireframes**](#tablet-wireframes)
        - [**Desktop Wireframes**](#desktop-wireframes)
    - [**Color Scheme**](#color-scheme)
    - [**Fonts**](#fonts)
    - [**Logo and Images**](#logo-and-images)
    - [**Features**](#features)
        - [**Header**](#header)
        - [**Footer**](#footer)
        - [**Our Dogs Page**](#our-dogs-page)
        - [**Contact Page**](#contact-page)
        - [**Found a Friend Page**](#found-a-friend-page)
    - [**Future Enhancements**](#future-enhancements)
    - [**Testing**](#testing)
        - [**Manual Testing**](#manual-testing)
        - [**Issues**](#issues)
        - [**Validation**](#validation)
            - [**HTML**](#html)
            - [**CSS**](#css)
        - [**Lighthouse Testing**](#lighthouse-testing)
        - [**Accessibility Testing**](#accessibility-testing)
        - [**User Story Testing**](#user-story-testing)
    - [**Deployment**](#deployment)
    - [**Credits**](#credits)
        - [**Content**](#content)
        - [**Media and Design**](#media-and-design)

## **Planning**
### **External user goals**
- Adopt a dog
- Support the shelter
- Look at cute pictures of dogs

### **Site owner goals**
- Find a new home for the dogs
- Get donations

### **User Stories**
- As a user, I want to navigate the website using multiple devices.
- As a user, I want to find general information about the shelter
- As a user, I want to find out which dogs are available for adoption.
- As a user, I want to apply for a dog.
- As a user, I want to support the shelter.
- As a user, I want to see pictures of dogs.

- As the site owner, I want to find a loving home for the dogs.
- As the site owner, I want to get donations.

### **Features to achieve the goals**
- The website will be built with a mobile-first approach, to ensure it is responsive. I will also test it on various devices and screen sizes.
- General information about the shelter like the opening hours and address will be included in the footer.
- The dogs that are available for adoption will be presented on a separate page (*Our Dogs*) with a picture and description of the dog.
- An application form with relevant information will be included on a separate page (*Contact*).
- On a separate page (*Found a Friend*) pictures and a video will be included to show the dogs that are already adopted with their new owners.

- Call-to-action buttons will be used throughout the website to get donations. (As the shelter is only imaginative the *Donate* links link to the [PayPal Donations](https://www.paypal.com/donate/buttons/partner) information site and not a real organisation.)

### **Wireframes**
I created wireframes to visualize my ideas using [Balsamiq](https://balsamiq.com/). As I want to stick to the mobile-first approach I created wireframes for mobile, tablet and desktop screen sizes.

#### **Mobile Wireframes**
- [Home](docs/wireframes/wireframe_mobile_home.png)
- [Our Dogs](docs/wireframes/wireframe_mobile_our_dogs.png)
- [Contact](docs/wireframes/wireframe_mobile_contact.png)
- [Found a Friend](docs/wireframes/wireframe_mobile_found_a_friend.png)
    
#### **Tablet Wireframes**
- [Home](docs/wireframes/wireframe_tablet_home.png)
- [Our Dogs](docs/wireframes/wireframe_tablet_our_dogs.png)
- [Contact](docs/wireframes/wireframe_tablet_contact.png)
- [Found a Friend](docs/wireframes/wireframe_tablet_found_a_friend.png)

#### **Desktop Wireframes**
- [Home](docs/wireframes/wireframe_desktop_home.png)
- [Our Dogs](docs/wireframes/wireframe_desktop_our_dogs.png)
- [Contact](docs/wireframes/wireframe_desktop_contact.png)
- [Found a Friend](docs/wireframes/wireframe_desktop_found_a_friend.png)
    
### **Color Scheme**
To create the color scheme I looked at various pictures of dogs I might use as hero images. I quickly decided to go for green as my main color and picked `#83A603` to be one of my main colors. Then I used [coolors.co](https://coolors.co/) to find matching colors for my scheme. After picking out my five main colors I used [contrast-grid.eightshapes.com](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%2383a603%0D%0A%231b4001%0D%0A%23f0deb4%0D%0A%23f6f7eb%0D%0A%23001e1d&es-color-form__tile-size=regular&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) to check the contrast and possible color combinations.

![Color contrast](docs/screenshots/color_contrast.png)

### **Fonts**
I used [fontpair.co](https://www.fontpair.co/) to get some inspiration for possible font pairings. I wanted to use [Google Fonts](https://fonts.google.com/) and decided to use **Nunito** for my headings and **PT Sans** for my text. These two fonts seem to pair nicely and I like the rounded, playful shape of Nunito for the topic of this website.

### **Logo and Images**
After choosing my colors and fonts I wanted to make a simple Logo for my website, as the *Furry Friends Shelter* does not exist in the real world. I used my colors and fonts for the creation of the Logo. The paw prints I used are my own dogs' paws.

![Furry Friends logo](docs/screenshots/logo.png)

## **Features**
### **Header**
To follow my mobile-first approach I started by looking at tutorials on how to implement a hamburger menu without JavaScript. I found a video with the according [Codepen](https://codepen.io/kevinpowell/pen/jxppmr) from Kevin Powell. I used the information from the video and example code in the Codepen for my navigation.
To improve accessibility I added **Menu** as a text alternative and used `aria-hidden` on the hamburger icon.

![Mobile header](docs/screenshots/header_mobile.png)

The navigation header is sticky to improve UX. This way the user can easily navigate the website and click on another page from anywhere. The navigation links have a `:hover` effect that is also used for the active page, as shown in the screenshot below.

![Dekstop header](docs/screenshots/header_desktop.png)

Below my navigation, I have a hero image on each page. On the homepage, the hero is bigger than on the other pages. I added an overlay on top of the hero images to make sure that the text is readable.

![Hero index](docs/screenshots/hero_index.png)

### **Footer**
The footer includes the shelter´s opening hours, a Google Maps screenshot and links to the site´s pages. The Facebook and Instagram pages are also linked in the Footer.
At the bottom of the footer, I have the copyright information. This includes the disclaimer, that the website was only made for educational purposes and that the images and icons were taken from Unsplash and Icons8.

![Desktop footer](docs/screenshots/footer_desktop.png)

To create a minimum viable product without JavaScript I only included a screenshot of Google Maps. To further improve the website after this course I would use the [Google Maps API](https://developers.google.com/maps) to add a usable map to the footer.

On bigger screen sizes the footer is organized in three columns using CSS grid. On smaller screens, the elements are presented in one column.

![Mobile footer](docs/screenshots/footer_mobile.png)

### **Home Page**
The *Home* page is presented in different sections. First I have a heading and a short description text of the shelter. Next, there is an image with some text asking for donations. Then I have a full-width banner with a statistic of the shelter. At the bottom of the *Home* page, there are two decorative images with links to the *Our Dogs* page and the PayPal donation site.

![Home Page](docs/screenshots/home.png)

### **Our Dogs Page**
After a heading and some information about the adoption process, all the dogs available for adoption are presented on this page. Each dog is presented as a card with a picture of the dog, their name, facts about them and a short description of their character. 

For the fictional shelter, I created eight dogs available for adoption. On big screen sizes, they are presented in three columns, on smaller sizes there are two columns and for mobile sizes one column.

![Our Dogs Page](docs/screenshots/our_dogs.png)

### **Contact Page**
On the *Contact* page, the website user finds an application form to apply for one of the shelter´s dogs. The user has to fill out their contact details (required fields are marked with a * and checked using the `required` attribute) and can give additional information.

![Contact Page](docs/screenshots/contact.png)

For this static website, the form uses the `GET` action instead of `POST`. This is just to improve UX to give clear feedback to the user after submitting the form. Below the feedback text, I reused the section from the *Home* page linking to *Our Dogs* and the donation site. This fills the feedback page and links to the most important sites of the shelter again.

![Contact sent Page](docs/screenshots/contact_sent.png)

### **Found a Friend Page**
The *Found a Friend* page shows a gallery of former shelter dogs with their new owners. A video is also included in the gallery. Autoplay is turned off for the video to ensure user control. As the shelter is fictional I used a [placeholder video from YouTube](https://www.youtube.com/watch?v=B7yOO4oKMVc&source_ve_path=OTY3MTQ&feature=emb_imp_woyt) that shows a dog being adopted. 

To display the gallery I used CSS grid with column-spans for horizontal content.

![Found a Friend Page](docs/screenshots/found_a_friend.png)

## **Future Enhancements**
I believe I added all the necessary features to create a minimum viable product that is ready to be used as a real-life website. However, there is room for improvement and further features. Here are some enhancements I would like to make in the future and to adapt this project for a real-world shelter.

- The form on the *Contact* page uses a `GET` parameter at the moment to simulate submitting the form. I would change this to a `POST` request to make the form fully function. The form data would be sent to the shelter´s office mail address.

- I would use the [Google Maps API](https://developers.google.com/maps) to add a usable map to the footer instead of the screenshot that is placed there at the moment.

- To better present the dogs of a real shelter I would add a details page for each dog. On this page, there would be more text, pictures and maybe even videos of the according dog. For easier maintainability, a CMS like WordPress could be used to make the website dynamic.

## **Testing**
### **Manual Testing**
I deployed the first version of my project after finishing the header. From this moment on I made sure to always test my live website. While implementing new features I had the website open in **Google Chrome**, resizing the browser using *Dev Tools*. I also opened the website on my phone after pushing new features. I think you get a better feeling for the mobile version of a website when opening it on a real phone, instead of a smaller browser window. Furthermore, I have **Microsoft Edge** and **Firefox** installed and made sure to open my deployed website there frequently.

To test **Safari** and **iOS** devices I signed up for a free trial on [BrowserStack](https://www.browserstack.com/) as I made a really good experience using this tool before. 

### **Issues**
While coding some issues kept me thinking for longer than others. Below is a list of issues that took me a while to fix.

1. Having a full-width counter section on the *Home* page.
    - The issue I found while adapting the counter section to desktop screen sizes was that it wasn´t full width on bigger screens.

    ![Issue with counter section](docs/screenshots/issue_counter.png)
    - This issue appeared because I limited the width of my `main` to `1600px`. I tried fixing this by using `position: absolute;`. However, this led me to another problem as it removed the element from the document flow. So I decided to use `width: 100vw` instead. To then move it to the left side of the screen without positioning it I used a negative margin with `calc()` to calculate it. \
    I then noticed a horizontal scrollbar that apparently can appear depending on browser settings when `100vw` is used. So after some more thinking and looking for other hacky solutions I eventually went with the most obvious solution of just removing the `max-width` from my `main`. I decided to use a `.container` class on all the smaller sections instead.

    ![Issue with counter section](docs/screenshots/issue_counter_fixed.png)
    - **Lesson learned** - I´ll think twice before using `100vw` from now on and try to think of obvious solutions instead of hacky ones.
2. Getting a better performance on Lighthouse testing.
    - When I first ran the Lighthouse test my values for *Accessibility*, *Best Practices* and *SEO* were between 90 and 100 for all pages. But for *Performance* they were between 70 and 80, for the mobile version of my *Home* page it was even down to 51.

    ![Initial Mobile Home Performance](docs/testing/mobile_home_initial.png)
    - Trying to get this up was probably one of the hardest challenges for me during this project as I was already familiar with HTML and CSS, but not so much with performance optimization. \
    First I tried compressing the images again, but that didn´t change much. Then I converted them to the *.webp* format and changed the image size. As I had downloaded the images from Unsplash in their original size I was able to really size down my images this way. \
    The big problem that remained was FontAwesome. I only needed four icons so creating a Subset would have been a good solution. However, this is only possible with a paid plan so I tried hosting the files within the project instead of loading the CDN, but that didn´t change anything for the *Performance* value. \
    So I decided to not use FontAwesome and just download the icons and use them as images. I downloaded them from [Icons8](https://icons8.com/) and added a credit link in the footer. This significantly increased my *Performance* score. To further improve the mobile score I resized my hero images and used these smaller images for mobile-sized screens. This way I was able to score 100 at the *Performance* value too.

    ![Mobile Home Performance](docs/testing/mobile_home_score.png)

### **Validation**
#### **HTML**
#### **CSS**
I used the [Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjulia-wagner.github.io%2Ffurry-friends%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css) to validate my CSS. The validation came back with no errors or warnings. I first validated the CSS by direct input and had a warning saying that some parts of the CSS can only be validated by URI. So I validated my deployed *Home* page too, to make sure there are no errors.

![CSS Validator](docs/testing/css_validator.png)

The full validation result can be found [here](docs/testing/css_validator_results.pdf).

### **Lighthouse Testing**
As described before in the [Issues](#issues) section, getting the *Performance* score on Lighthouse to a high level was probably the biggest challenge for me in this project. \
I followed the recommendations I got in the Lighthouse tab and made some performance improvements that I already described. This way I managed to get my score for *Accessibility*, *Best Practices* and *SEO* to 100 for all mobile and desktop pages. The score for *Performance* varies between 95 and 100 depending on the page, size and when I run the test. Only the score for my *Found a Friend* page is 92 because it includes many pictures and an embedded video.

![Lighthouse Score Our Dogs](docs/testing/desktop_dogs_score.png)
![Lighthouse Score Contact](docs/testing/mobile_contact_score.png)
![Lighthouse Score Home](docs/testing/mobile_home_score.png)
![Lighthouse Score Home Desktop](docs/testing/desktop_home_score.png)
![Lighthouse Score Found a Friend](docs/testing/mobile_friend_score.png)

### **Accessibility Testing**
In addition to the Lighthouse Accessibility score I tested my website using the [WAVE Tool](https://wave.webaim.org/) which returned no errors.

### **User Story Testing**

## **Deployment**
I followed my mentor's tip and deployed my website early, after implementing the header. The steps to deploying a website on GitHub pages are:
1. Open the [repository](https://github.com/Julia-Wagner/furry-friends) and go to the **Settings** tab.
2. Navigate to the **Pages** tab in the left menu.
3. Choose **Deploy from a branch** and select the according branch, *main* in my case.
4. Click save. The link to the deployed website can then be found in the [repository](https://github.com/Julia-Wagner/furry-friends) on the right menu under **Environments**.

The link to my live site is: [Furry Friends Shelter](https://julia-wagner.github.io/furry-friends/)

## **Credits**
Thanks to my Code Institute Mentor David Bowers for giving me valuable feedback and tips during this project.

### **Content**
- The content was written by myself and the images on the *Found a Friend* page as well as the first three dogs on the *Our Dogs* page are my own.
- I adapted my hamburger menu from a video with the according [Codepen](https://codepen.io/kevinpowell/pen/jxppmr) from Kevin Powell. 
- To test my website I signed up for a free trial on [BrowserStack](https://www.browserstack.com/).
- To test accessibility on my website I used to [WAVE Tool](https://wave.webaim.org/).

### **Media and Design**
- The images used for the website are taken from [unsplash.com](https://unsplash.com/) and compressed using [tinypng.com](https://tinypng.com/). Some images of dogs are my own pictures.
- [Convertio](https://convertio.co/) was used to convert images to the *.webp* format.
- I used [Balsamiq](https://balsamiq.com/) to create Wireframes.
- With [coolors.co](https://coolors.co/) I created a color scheme and used [contrast-grid.eightshapes.com](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%2383a603%0D%0A%231b4001%0D%0A%23f0deb4%0D%0A%23f6f7eb%0D%0A%23001e1d&es-color-form__tile-size=regular&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) to check the contrast and possible color combinations.
- [fontpair.co](https://www.fontpair.co/) was used to get inspiration for font pairings, the fonts were downloaded from [Google Fonts](https://fonts.google.com/).
- The icons for the hamburger menu and footer were taken from [Icons8](https://icons8.com).
- The screenshot at the top of this document was taken from [Am I Responsive?](https://ui.dev/amiresponsive?url=https://julia-wagner.github.io/furry-friends/).