<img src="https://user-images.githubusercontent.com/68516952/223836189-4e899747-2f5e-4632-a33a-102f4641e1b6.png" title="Yordevs Duck" width="350">

# Yordevs Quiz Night 2023  

We bid you welcome to the final Yordevs event of the term, where you'll put your programming and web development skills to the test for a chance to win a voucher!

As a quiz participant you will get free pizza! Please fill out the Google Form [here](https://quiz.yordevs.com), if you haven't already.
The Yordevs AGM will also follow this event! You can nominate yourself beforehand [here](https://nominations.yordevs.com).  

You can work individually or in a group. You have half an hour to answer these questions. If you are following the quiz out of person, please email yordevs@yusu.org your answers by 6:35pm to qualify for the prizes! Answers will be revealed at 6:35pm. Prizes will be awarded to one nominated member of the winning teams via email following the event, and it will be their responsibility to split the prize amongst the team.  

If you're _really_ stuck, ask us for a quick nudge.[^1] Good luck!

[^1]: **Hint:** you may find inspecting [the Yordevs website](https://yordevs.com) and [the Yordevs Links page](https://links.yordevs.com/), scouring [Yordevs GitHub](https://github.com/yordevs) or utilising [CodePen](https://codepen.io) useful for some of these questions.  

## Part 1: HTML and CSS    

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

[^1]: **Hint:** They were crafted using _only_ CSS!

   - <img src="https://user-images.githubusercontent.com/68516952/223913883-74d9cec4-6452-4db5-a092-941ee906cdf2.png" title="Yordevs Ancient Logo 1" width="350">
   + <img src="https://user-images.githubusercontent.com/68516952/223913881-25d96dc9-d305-400a-9609-bbb02e4bdbce.png" title="Yordevs Ancient Logo 2" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/223914406-3e7dcd31-9244-4911-8681-10e510aa7b66.png" title="Yordevs Ancient Logo 3" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/223913884-b44ea022-e5a2-4d47-b391-7494d3e51781.png" title="Yordevs Ancient Logo 4" width="350">

## Part 2: JavaScript  

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

1. How many ducks are present on the Yordevs Links page?[^1]  

   + 170
   - 180
   - 200
   - 150

[^1]: **Hint:** Investigate the Yordevs Links page or repo...

1. No

   ```javascript
   var s = "JavaScript syntax highlighting";
   alert(s);
   ```

1. rickrollhttp regex

