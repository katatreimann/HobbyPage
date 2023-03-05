# HobbyPage

In my "Hobby Page" project, I introduce an Estonian graphic artist. As this is the first coding project of my life, I wanted to keep it very simple. However, I also had to stick to the requirements of the task. More details below!

___

### Table of Contents

- [Description](#description)
- [How To Use](#how-to-use)
- [References](#references)
- [License](#license)
- [Author Info](#author-info)

---

## Description

Let me start by telling you about the requirements I had to follow:

* The page has a title which informs the user what the site is about.
* The page has a logical layout and clear structure.
* There are images on the page, with alt-text where appropriate page has a logical layout and clear structure.
* The page is visually interesting, for example with borders or colours.
* A list is visible somewhere on the page.
* A user can click on a link that takes them to another website.
* The page has a header element, and a footer element.
* Somewhere on the page, the user can see today’s date. The date should always be correct. You’ll need to use JavaScript to generate the date, and DOM manipulation to display it.

##### Based on these requirements, I built my website. I added all my content on one page. See sample homepage in pictures below. 

##### In the following, I will give you a brief overview of how I built my **HTML** file, where I stored all the content for this website:

- In the first section of the page, called "Home", I have a **header`(<header>)`**, menu, title, and a photo of artist art. To navigate the page, I used **sticky header(`position: sticky;`)** where I added a menu using the **list element`(<li>)`**. To get the menu button to work, I used the **HTML anchors**, also known as **`(<a>)`** element and **HTML links**. I used a **fragment identifier** also known as **id attribute(`id=""`)**. I link to them by putting the **ID(`id="home"`)** in the **href(`<a href="#home"></a>`)** attribute of another link. They make it easy to navigate around the **intra-page**.

- In the second section of the page,  called "About", I have a photo of the artist, and a short biography. I have also included a link to another website in this section, which was one of the requirements. I add picture with **image tag(`<img>`)**, usin a **external resource attribute(`src=""`)** and **alternate text(`alt=""`)**. For the link I used again a **`<a>`** tag with a **`href=""`** attribute specifies with the URL.

- In the third section of the page,  called "Gallery", there I have pictures with the artist's works. To display the photo on the website I used the **image element(`<img>`)** again, with **`src=""`** and **`alt=""`** attribute. I design it with layout mode called **Flexbox(`display: flex;`)**.

- And in the last section of the page I have a **footer`(<footer>)`**. In the footer I added **JavaScript** with **`<script>`** element. **Script element** contains today’s date.

All elements have their own **"id"** or **"class"**, which I used to style the web page in **CSS**.

![image](https://user-images.githubusercontent.com/117119598/222925017-92e005e6-e020-4565-8363-e36336c28df6.png)
![image](https://user-images.githubusercontent.com/117119598/222925253-dff33459-4a9d-4174-b0a6-0343b1803478.png)
![image](https://user-images.githubusercontent.com/117119598/222925266-eda90ca7-a684-4bb7-ad42-e3c0730a2e6a.png)
![image](https://user-images.githubusercontent.com/117119598/222925300-2d7ffcbc-0c0d-4c4a-8d65-abe48e53b245.png)


---

## References

