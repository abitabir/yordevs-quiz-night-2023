<img src="https://user-images.githubusercontent.com/68516952/223836189-4e899747-2f5e-4632-a33a-102f4641e1b6.png" title="Yordevs Duck" width="350">

# Yordevs Quiz Night 2023  

We bid you welcome to the final Yordevs event of the term, where you'll put your web development and programming skills to the test for a chance to win a voucher!

As a quiz participant you will get free pizza! Please fill out the Google Form [here](https://quiz.yordevs.com), if you haven't already.
The Yordevs AGM will also follow this event! You can nominate yourself beforehand [here](https://nominations.yordevs.com).  

You can work individually or in a group. Choose one of the four answers for every question. You have half an hour to answer these questions. Email your answers to yordevs@yusu.org by 6:35pm to qualify for the prizes! Answers will be revealed at 6:35pm. Prizes will be awarded to one chosen member of the winning teams via email following the event, and it will be their responsibility to split the prize amongst the team.  

If you're _really_ stuck, ask us for a quick nudge.[^1] Good luck!

[^1]: **Hint:** you may find inspecting [the Yordevs website](https://yordevs.com) and [the Yordevs Links page](https://links.yordevs.com/), scouring [Yordevs GitHub](https://github.com/yordevs) or utilising [CodePen](https://codepen.io) useful for some of these questions.  

## Questions  

1. Which is a valid HTML tag?

   - `<h0>`
   - `<h10>`
   + `<h6>`
   - `<heading>`

1. What is the correct HTML tag for inserting a line break element?

   + `<br>`
   - `<break>`
   - `<lb>`
   - `\n`

1. Why does the logo on the YUSU website blur when you zoom in a bit too much?
   
   <img src="https://user-images.githubusercontent.com/68516952/224081684-bd8990ce-56b8-4f08-a006-fb61fe3454d6.png" title="YUSU Logo" width="350">

   - The width and height properties were set too high in the `<img>`.
   - The logo is in an XML-based vector graphic of an SVG format.
   + The logo is in a PNG image format.
   - The `style="max-width: 200px"` shouldn't make that possible!

1. Using a screenreader for accessibility testing (e.g [Pericles](https://chrome.google.com/webstore/detail/pericles-text-to-speech-s/oacindbdmlbdeidohafnfocfckkhjlbg)), upon which icon in the Yordevs Website's footer does the screenreader stop working properly?

   <img src="https://user-images.githubusercontent.com/68516952/224089167-b4403383-702f-4cad-b836-d7f8d673ee58.png" title="Yordevs Footer" width="350">

   - Twitter
   - GitHub
   - Discord
   + Instagram

1. Why does the LinkedIn icon come up as an `Unknown Social Media Icon` when styling is stripped from the Yordevs website?

   <img src="https://user-images.githubusercontent.com/68516952/224126229-21afdd69-788f-4178-8e7c-c37c7173b640.png" title="Yordevs Footer Unstylinged" width="350">

   - `iconName="Link to Yordevs LinkedIn"` isn't present
   + `iconName="Link to Yordevs LinkedIn"` is misplaced
   - `icon={<FaLinkedin/>}` isn't present
   - `icon={<FaLinkedin/>}` is misplaced

1. The following ASCII art is accompanied by which Yordevs welcome in Dev Tools on the Yordevs Website?

   <img src="https://user-images.githubusercontent.com/68516952/224125507-bfc8676b-558b-4cac-8a46-c0d8f3b703fa.png" title="ASCII Longboi Welcome" width="350">
   
   - "Hi from Longboi, and the Yordevs team!"
   - "Hello from the Yordevs team, and Longboi!"
   - "Hi from the Yordevs team, and Longboi!"
   + "Hello from Longboi, and the Yordevs team!"

1. WCAG (Web Content Accessibility Guidelines) are guidelines published by the Web Accessibility Initiative of the World Wide Web Consortium, the main international standards organization for the Internet. Which of the following is the correct WCAG 2.0 guideline on contrast ratios?

   + WCAG 2.0 Level AA requires text or images of text to have a contrast ratio of at least 4.5:1 (or 3:1 for large text).
   - WCAG 2.0 Level A requires text or images of text to have a contrast ratio of at least 7:1 (or 4.5:1 for large text).
   - WCAG 2.0 Level AAA requires text or images of text to have a contrast ratio of at least 4.5:1 (or 3:1 for large text).
   - WCAG 2.0 Level AAAA requires text or images of text to have a contrast ratio of at least 7:1 (or 4.5:1 for large text).

1. Using an accessibility testing tool (e.g [WAVE](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)), you can check if any contrast errors are present on a website. Thankfully, there are none on the Yordevs Website - but there is one error. Which of the following WCAG guidelines, is this error not compliant with?

   <img src="https://user-images.githubusercontent.com/68516952/224108335-afccb587-1563-4fa0-be4a-76e687e4d949.png" title="Yordevs WAVE Test" width="350">  
   <img src="https://user-images.githubusercontent.com/68516952/224112554-93600b69-2100-404c-9703-5f7234a4f685.png" title="Yordevs WAVE Error" width="350">

   - [4.1.2 Name, Role, Value (Level A)](https://webaim.org/standards/wcag/checklist#sc4.1.2) 
   - [1.1.1 Non-text Content (Level A)](https://webaim.org/standards/wcag/checklist#sc1.1.1) 
   + [3.1.1 Language of Page (Level A)](https://webaim.org/standards/wcag/checklist#sc3.1.1)
   - [2.4.4 Link Purpose (In Context) (Level A)](https://webaim.org/standards/wcag/checklist#sc2.4.4)

1. Which of these hex codes is part of the Yordevs branding?
   
   + #AA211A
   - #2B434C
   - #DED45B
   - #9D140D

1. Meet the Yordevs duck's distant cousin. In the following HTML code block containing internal CSS, what hex code represents the colour of the body class?

   ```HTML
   <!DOCTYPE html>
   <html>
   <head>
      <style>
         body {
           padding: 0;
           margin: 0;
           background: #FFFFFF;
         }
         .circle {
           position: relative;
           display: block;
           width: 500px;
           height: 500px;
           background: #284049;
           margin: 0 auto;
           border-radius: 50%;
         }
         .beak {
           position: absolute;
           border-top: 100px solid #E85454;
           border-right: 50px solid transparent;
           border-left: 25px solid transparent;
           margin-left: 30px;
           margin-top: 150px;
           transform: rotate(90deg);
         }
         .head {
           position: absolute;
           left: 75px;
           top: 80px;
           background: #F7ED74;
           border-radius: 50%;
           width: 180px;
           height: 180px;
         }
         .body {
           position: absolute;
           left: 75px;
           top: 240px;
           background-color: #F7ED74;
           width: 400px;
           height: 230px;
           border-radius: 30% 70% 50% 30% / 50% 0 100% 50%;
         }
         .wing {
           display: none;
         }
         .red-wing {
           position: absolute;
           border-top: 140px solid #9D140D;
           border-right: 80px solid transparent;
           border-left: 80px solid transparent;
           transform: rotate(150deg);
           margin-left: 150px;
           margin-top: 270px;
         }
         .yellow-wing {
           position: absolute;
           border-top: 140px solid #F7ED74;
           border-right: 80px solid transparent;
           border-left: 80px solid transparent;
           transform: scale(0.75) rotate(150deg);
           margin-left: 140px;
           margin-top: 275px;
         }
         .cursor {
           position: absolute;
           border-top: 30px solid #9D140D;
           border-right: 15px solid transparent;
           border-left: 10px solid transparent;
           transform: rotate(155deg);
           margin-left: 110px;
           margin-top: 130px;
         }
         .cursor-tail {
           position: absolute;
           background-color: #9D140D;
           height: 10px;
           width: 10px;
           transform: rotate(65deg);
           margin-left: 125px;
           margin-top: 155px;
         }
      </style>
   </head>
   <body>
      <div class="circle">
        <div class="duck">
          <div class="body"></div>
          <div class="beak"></div>
          <div class="head"></div>
          <div class="eye">
            <div class="cursor"></div>
            <div class="cursor-tail"></div>
          </div>
          <div class="wing">
            <div class="red-wing"></div>
            <div class="yellow-wing"></div>
          </div>
        </div>
      </div>
   </body>
   </html>
   ```

   - #E85454
   - #284049
   + #F7ED74
   - #FFFFFF

1. Using the same HTML code as the previous question, you may have noticed that our distant cousin is wingless. Which is the smallest _change_ in the code that wings the poor duck?

   - Remove `display: none;` from the `wing` class styling
   + Replace `wing` by `wings` in the internal CSS
   - Replace `red-wing` by `red-wings` in the HTML document body
   - Add `display: block !important;` to both `red-wing` and `yellow-wing` class stylings

1. Going up the Yordevs family tree for a quick history lesson. Who of the following is the oldest of the long lost Yordevs ancestors?[^1]
   
   - <img src="https://user-images.githubusercontent.com/68516952/223913883-74d9cec4-6452-4db5-a092-941ee906cdf2.png" title="Yordevs Ancient Logo 1" width="350">
   + <img src="https://user-images.githubusercontent.com/68516952/223913881-25d96dc9-d305-400a-9609-bbb02e4bdbce.png" title="Yordevs Ancient Logo 2" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/223914406-3e7dcd31-9244-4911-8681-10e510aa7b66.png" title="Yordevs Ancient Logo 3" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/223913884-b44ea022-e5a2-4d47-b391-7494d3e51781.png" title="Yordevs Ancient Logo 4" width="350">

   [^1]: **Hint:** They were crafted using _only_ CSS!  

1. Which HTML tag formats elements as a numbered list?

   + `<ol>`
   - `<list>`
   - `<dl>`
   - `<ul>`

1. Which is the correct HTML hyperlink?

   - `<a url="http://www.yordevs.com">Yordevs</a> <!-- This one is -->`
   - `<a name="http://www.yordevs.com">Yordevs</a> <!-- No, that one is -->`
   - `<a>http://www.yordevs.com</a> <!-- Yes, this one is! -->`
   + `<a href="http://www.yordevs.com">Yordevs</a> <!-- No, this is -->`

1. What message is displayed on the Yordevs Links page if the source is specified as a QR code?[^1]  

   + "If you can scan a qr code you can make a website, why not use these links to find out more about us"
   - "You've come from a qr code? Why not join us and find out how we knew!"
   - "You clicked our link on a qr code? I didn't even know you could do that!"
   - "This link was shared via a qr code? Good job I wrote the code for this message then!"

   [^1]: **Hint:** Check out URL query strings and parameters!

1. What backend does this Contact Us form on the Yordevs Website use?  
   
   <img src="https://user-images.githubusercontent.com/68516952/223878998-f14bb974-159b-4ced-9fcd-233d3c774751.png" title="Yordevs Contact Us" width="350">
   
   - Formbold
   - Formcake
   + Formspree
   - Formspark

1. Which HTML opens a link in a new browser window?

   - `<a href="url" new>`
   + `<a href="url" target="_blank">` 
   - `<a href="url" target="new">`
   - `<a href="url" target="new">`

1. How many ducks are present on the Yordevs Links page?[^1]  

   + 170
   - 180
   - 200
   - 150

   [^1]: **Hint:** Investigate the Yordevs Links page or repo...

1. What HTTP request method gets you rick rolled on the Yordle Server?  

   - DELETE
   - POST
   - PUT
   + GET

1. What HTTP status code (although slightly misleading) is accompanied by [this response](https://raw.githubusercontent.com/yordevs/yordle-server/master/resources/forbiddenResponse.txt) on the Yordle Server upon an POST request with an invalid body?  

   + 403
   - 200
   - 400
   - 402

1. Which is the correct HTML tag to enclose important text

   - `<important>`
   + `<strong>`
   - `<b>`
   - `<i>`

1. Which of these are valid HTML?

    - ```HTML
      <h1> Yordevs Quiz Night 2023
      <h2> Questions
      ```
    - ```HTML
      </h1> Yordevs Quiz Night 2023<h1>
      </h2> Questions<h1>
      ```
    + ```HTML
      <h1>Yordevs Quiz Night 2023</h1>
      <h2>Questions</h2>
      ```
    - ```HTML
      <h1>Yordevs Quiz Night 2023<h1>
      <h2>Questions<h2>
      ```
      
1. What is the correct HTML for making a checkbox?

   - `<check>`
   - `<checkbox>`
   - `<input type="check">`
   + `<input type="checkbox">`

1. This is the Yordevs website's nav bar. What HTML tag should enclose the elements of the nav bar?  
   
   <img src="https://user-images.githubusercontent.com/68516952/224137068-d8fd525d-9484-4d24-b125-db44894da117.png" title="Yordevs Nav Bar" width="350">  

   - `<navbar>`
   - `<section>`
   - None, as they are enclosed by `<header>`
   + `<nav>`

1. When you hover over an item on the Yordevs nav bar, the change is very visual. Which of the following is not a valid reason, according to the WCAG 2.0 guidelines, for this?

   <img src="https://user-images.githubusercontent.com/68516952/224136816-5166bd30-07d8-4682-b962-b77d03828aaa.png" title="Yordevs Nav Bar on Hover" width="350">
   
   - A change in text decoration (usually an underline) upon mouse hover and keyboard focus is sufficient enough to indicate a hyperlink, as users are accustomed to seeing links underlined.
   + A change in colour upon mouse hover and keyboard focus is sufficient enough to indicate a hyperlink, even if some users have low vision, color deficiency, or page color overrides.
   - Links should look like links, and nothing else should.
   - Alternative visual mouse hover effects (such as background glows, drop shadows, color changes) for navigation links can help users know that an element is clickable.

1. Keyboard users utilise the tab and shift-tab keys to navigate through interactive web page elements. Visual indication of the element with current keyboard focus, called a focus indicator, is thus useful for sighted keyboard users. An example of a focus indicator on the button link to the Yordevs Website from the Yordevs Links page is shown. To ensure the same visual presentation is available upon both mouse hover or keyboard focus, any time `a:hover` is adjusted in CSS, `a:focus` should be too. Which of the following elements on the Yordevs website does not provide focus indication?

   <img src="https://user-images.githubusercontent.com/68516952/224175831-19a09136-62c8-48d1-8fa0-e84fac90d621.png" title="Links Focus Indicator Example" width="350">  

   - <img src="https://user-images.githubusercontent.com/68516952/224176408-a180579e-004e-4153-8277-cab3b1aeab54.png" title="Focus Indicator 1" width="350">
   + <img src="https://user-images.githubusercontent.com/68516952/224176797-474487cc-4db1-4c3b-99de-cd424ea6314d.png" title="Focus Indicator 2" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/224177236-0191861c-05f6-4d75-81ee-053bf9c2d60c.png" title="Focus Indicator 3" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/224176940-4b7e5170-3039-4f4a-85d4-2fe6348b7e57.png" title="Focus Indicator 4" width="350">

1. Which of these is the biggest setback for keyboard users when navigating the Yordevs website when zoomed in at 125%+ or on a smaller viewport?

   <img src="https://user-images.githubusercontent.com/68516952/224178311-6d3e5a75-8c9b-4ce3-aac4-15593eacf9aa.png" title="Smaller Viewport" width="350">
   
   + The burger menu is not keyboard focusable.
   - There is no focus indicator on the Yordevs logo.
   - There is no focus indicator on the `Blogs` navigation link.
   - The tab order is awesome!

1. Which HTML attribute is used to specify that an form element input field has to be filled out?

   - formvalidate
   - validate
   + required
   - placeholder

1. Which of these are valid JavaScript?

   ```javascript
   var s = "JavaScript syntax highlighting";
   alert(s);
   ```

1. regex

