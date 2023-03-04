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

Based on these requirements, I built my website. I put all my content on one page. See sample homepage in pictures below. 

In the first section of the page, called "Home", I have a heater, menu, title, and a photo of his art. To navigate the page, I used **sticky header(position: sticky;)** where I added a menu using the **list element`(<li>)`**. To get the menu button to work, I used the **HTML anchors**, also known as **`(<a>)`** element and **HTML links**. These anchors are intra-page targets for other links on that page. I link to them by putting the **ID(id="home")** in the **href(`<a href="#home"></a>`)** attribute of another link. They make it easy to navigate around the intra-page.

In the second section of the page,  called "About", I have a photo of the artist, and a short biography. I have also included a link to another website in this section, which was one of the requirements. I add picture with **image tag(`<img>`)**, usin a **external resource attribute(src="")** and **alternate text(alt="")**.


![image](https://user-images.githubusercontent.com/117119598/222925017-92e005e6-e020-4565-8363-e36336c28df6.png)
![image](https://user-images.githubusercontent.com/117119598/222925253-dff33459-4a9d-4174-b0a6-0343b1803478.png)
![image](https://user-images.githubusercontent.com/117119598/222925266-eda90ca7-a684-4bb7-ad42-e3c0730a2e6a.png)
![image](https://user-images.githubusercontent.com/117119598/222925300-2d7ffcbc-0c0d-4c4a-8d65-abe48e53b245.png)



---

## References

