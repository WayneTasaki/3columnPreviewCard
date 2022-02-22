<img src="https://github.com/WayneTasaki/3columnPreviewCard/blob/main/design/desktop-preview.jpg"></img>
<h1 align="center">NFT preview card component</h1>

<div align="center">
  <h3>
    <a href="https://waynetasaki.github.io/3columnPreviewCard/">🌐 Live Site </a>  |  
    <a href="https://www.frontendmentor.io/solutions/3column-preview-card-component-WP-ewiTpa"> Solution </a> | 
    <a href="https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-"> Challenge </a> 
  </h3>
</div>
<div align="center">
   Solution for a challenge from  <a href="https://www.frontendmentor.io/" target="_blank">frontendmentor.io</a>.
</div>
<br>
<br>

## About This Project

<p>This challenge is perfect if you're just getting started. The shift between the layouts will be a nice test if you're new to building responsive projects.
The challenge is to build out this 3-column preview card component and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.
<br>
<br>
Your users should be able to:
<br>
1. View the optimal layout depending on their device's screen size
<br>
2. See hover states for interactive elements</p>
<br>
<br>




## Built with 
HTML, CSS
- 

## What I learned
One thing that tripped me up was the button hover state. I had the button styled with no border, but when I added the hover state, I set the background to none, and added a .15rem(2.4px) border. Unfortunately this kept pushing the other content and breaking the design. My first solution was to make the button slightly smaller during the hover state and then the added border would make up the difference. I believe this could have worked, but I instead searched Google for a more elegant solution. I found a GENIUS idea <a href="https://stackoverflow.com/questions/18887058/css-hover-creating-border-but-pushing-content"> here on Stack Overflow</a>. They suggested adding the border on the button but set the color to transparent, then on the hover state you can just change "transparent" to whichever color is needed. What a much better solution than my first idea!