# HackerrankCSS

1️⃣
<style>
div{
	height:50px;
	width:50px;
	background:red;
	border-radius:50%;
}
</style>
<div class="grayBall"></div>
❌ .greyBall:hover {transform: scale(2); animate: 500ms;}
✔️ .greyBall:hover {transform: scale(2); transition: 500ms transform;}
✔️ .greyBall:hover {transform: scale(2); transition: 0.5s;}
❌ .greyBall:focus {transform: scale(2); transition: 0.5s;}

answer_1

2️⃣ CSS Ellipsis
Which of the following are true about CSS property 'object-fit'?
❌ 'object-fit: contain;' does not preserve the aspect ratio of the image; it stretches the image to civer the entry width and height of the container.
✔️ 'object-fit: contain;' preserve the aspect ratio of the image and makes sure no clipping happens to the whole image.
✔️ 'object-fit: cover;' avoids the image getting squeezed, but it could end up clipping the image.
❌ 'object-fit: cover;' avoids clipping the image by sacrificing the aspect ratio.

answer_2

3️⃣ CSS object-fit
If an element extends beyond the allocated width, how do you truncate the sentence with an ellipsis (...) using CSS?
For example, "Hello! I am an element, and my width is larger than the container..."
❌ {white-space: pre-wrap; overflow: ellipsis; }
❌ {text-overflow: ellipsis; white-space: wrap; visibility: hidden;}
✔️ {white-space: nowrap; overflow: hidden; text-overflow:ellipsis}
❌ None of the above

answer_3

4️⃣ CSS Text Coloring
WHich of the following renders the text red?
<p id="tagID">Please color me red</p>
❌ :root{--test-color: red;} p{color:--test-color;}
❌ :root{--test-color: red;} p{color:var(--test-color);}
✔️ #tagId {color: red;}p{color:blue;}
✔️ p{colorLred !important;} #tagId{color:blue;}

answer_4

5️⃣ CSS selection
How do you prevent the user from selecting the text rendered insidethe following element?
<p> should not be selectable</p>
❌ p{cursor-event: none;}
❌ p{pointer-events: none;}
✔️ p{user-select: none;}
❌ None of the above

answer_5

6️⃣ CSS input Placeholder
How do you hide the "placeholder" text of an field?
❌ input::placeholder{visibility:clip;}
✔️ input::placeholder{color: transparent;}
❌ input::placeholder{display: none;}
❌ input::placeholder{visibility:hidden};

answer_6

7️⃣ CSS Centering
Which of the following options can position the div with the class name "child" exactly at the center of the page?
<div class="parent" style="width: 100vw; height: 100vh;">
	<div class="child" style="height: 100px; width: 100px; background: black"></div>
</div>
❌ .parent{display: flex; justify-content: center; align-items: center;}
❌ .parent{display: flex; justify-content: center; align-self: center;}
❌ .parent{position: relative;}.child{position: absolute; top: 50%; ;left: 50%;}
✔️ .parent{position: relative;}.child{position: absolute; top: 50%; ;left: 50%; transform-translate(-50%, -50%);}

answer_7

8️⃣ CSS Vertical-align
Which of the following are true about the CSS property 'vertical-align'?
<p>
	Let's
	<span class="heroWord">Hack</span>
	<img src=""/>
</p>
❌ .heroWord{vertical-align: 25px;} moves the word "Hack" to the bottom, 25px lower then <p> tag.
❌ .heroWord{vertical-align: 25px;} moves the word "Hack" to the top, 25px higher then <p> tag.
✔️ p img{vertical-align: text-bottom;} moves the image to the bottom with respect to the <p> tag.
❌ p img{vertical-align: text-bottom;} has no effect on the <img> tag.

answer_8

