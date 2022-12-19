# Habitat For Humanity Website Reviews

## Website
[leewardhabitat.org](https://leewardhabitat.org/)

---

## Review date | Reviewer

</br>

#### 12/15/2022 | Kurt
- `'/'` home page looks okay
- `'/mission'` has a broken image in the left sidebar that links to '/?page_id=34'
- `'/advocacy'` the `<h2>` "Cost of Home", should that be "_Cost of a Home_"? (same applies to the first sentence of the paragraph) 
  - _scratch that_ they use it as a hashtag #CostofHome (still don't like it 😆)
- `'/staff-board'` a few things here:
  - image sizes are inconsistent
  - A few of the titles overflow to a new line under the image. There's media queries setting a max width for various screen sizes and it's causing the titles to wrap to a new line. 
    - fix would be move the titles under the image
    - putting `<img>`'s in `<p>` tags is a new one for me
  - nit: they could really use some new/better staff images, especially Jo's
- `'/build_site_volunteers'` the max width set on the container is breaking the layout on larger screens (especially the top `<strong>` tag)
  - nit: the feature-image is taking up a lot of prime real estate above the fold
    - idk if the layout on this page is intentional cuz it's super weird when inspecting with dev tools
- `'/partners'` idk...nothing is really broken here but imo the layout is wonky af
- `'/home-ownership'` pretty aight 
  - _future consideration: could use a table for the "Income Guidelines" fam size and ygi_
- `'/home-repairs-rehab'` pretty aight
- `'/shop-the-restore'` the "Visit Us Today!" section is not scaling well in the medium sized screen range
  - font size and color for "Tuesday" in the store hours under "COVID=19 Safety Updates" does not match the other days
  - the code for Monday and Tuesday are not the same as each other, or the other days wtf
  - the `<a data-number="+phone-number">` text in the "Interested in volunteering at the Restore?" section includes more than just the phone number turning the last sentence into a link
- `'/events/golfclassic'` the `<h3>` is all over the place when scaling screen size. Text is wrapping under the image a few times between large and small
- `'/events/women-build'` last two `<div>`'s before the footer, think they are supposed to be image galleries for the 2018 & 2019 events buuuuut they are not working
  - `[mk_gallery title=”2019 Women Build” images=”1599,1600,1601,1596,1597,1598″ image_size=”large”]`
  - `[mk_gallery title=”2018 Women Build” images=”1448,1447,1446,1445,1444,1443″ column=”6″]` 
    - ⬆️ is what is being shown on the page
  - nit: the column layout on the "2021 Women Build" section looks like poop on anything larger than 768px wide screen size. The image should be full container width above the `<h1>` making one column (same as it is on mobile)
  - there's a random period `"."` in a `<p>` tag after the `text-content` `<ul>`. Thought it was something on my screen at first 🤣
- `'/donate/online-donations'` goes to the paypal page to donate, and works as expected
  - nit: the link to the donate page is buried away in the "menu more" of the header. Adding a "donate with paypal" button to most of the pages would be a "nice to have" 
- `'/donate'` as with most of the other pages, the layout is doo doo on anything 768px wide or larger
- `'/sponsorship'` layout, again. See first and second `<p>` tags in the `<div class="entry-content">` section  
  - An `<img>` inside of a `<strong>` tag inside of a `<p>` tag? **Wut**? (_this seems to be a site wide thing, not just this page_)    
- `'/give/golfclassicsponsorship'` layout layout layout
  - the top `<p>` tag that has two `<img>`'s inside of it and the second `<p>` with the text...why? 🤔
    - the text in not moving to below the image until it's like one or two letters next to the image. I'm probably describing it badly, but the image sizing the way the text is wrapping is causing problems. 
  - could use some padding between the golfclassic.jpg image and the text below it
  - could use some margin (or padding, idk which is preffered) above the `<h3>`

-----

</br>

## Summary 

- **Overall:** There's only a few truely broken items, but there's a lot of layout issues and screen size scaling issues. Idk if the layout and scaling is a Wordpress thing, a theme thing, or the way the creator put it together, but it doesn't look good, it's not a great user experience and could use some work. I'll check out the theme to see where it can be fixed. 
- **Proposed fixes:** The items that are actually broken or non-functional are straight forward to fix. Make them work. Done. The layout and scaling, if deemed necessary to fix, imo using a one column layout for all screen sizes would be a good and easy to implement solution. It's simple, easy to read, and easy to navigate. 
Once this site is vaporized and we're working with a modern tech stack + new content, a more robust, dynamic and modern layout can be implemented.
- **Next Steps:** Take the final list of items deemed "broken" to Jo. I'll walk her through them on the site so she can see what exactly each item is and the proposed "fixes" for each. 

-----

### kmal's To-Do List
- **Todo:** 
  - [ ] Create a master list of items that are "broken", non-functional, or deemed worthy of fixing at this juncture.
  - [ ] Schedule a meeting with Jo 
    - [ ] Show, explain, and propose fixes/changes for "project-lipstick"
    - [ ] Request shell access to the hostmonster server (if it's not already available)
    - [ ] Discuss next steps (_once project lipstick is complete_)
  - [ ] Configure Git Version Control, whether that's done with the hostmonster integration or elsewhere
    - [ ] Get the files to repo
    - [ ] Create a new [EPIC] issue for this project phase and [TASK] issues for each item on the master list
  - [ ] WIP 🏗

-----
                          
                   



