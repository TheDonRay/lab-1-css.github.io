<!-- Reflection MD file --> 

# Question 1: Describe the path an HTTP Request takes from a browser to your GitHub Pages site 

- The path an HTTP request takes from the browser to my Github pages site is that first it goes through the DNS phase. DNS is Domain Name system where our computer basically asks a name server to translate our github page which ends in .io to convert into a specific unique IP address. From there it goes into a couple of Site security measures including a TCP handshake, and from there our site takes in a HTTP request such as a GET request over our secure link asking for a specific file which in this case is the index.html file.  

# Question 2: If you used GenAI (ChatGPT, Claude, etc.) to help write code, you must include the prompt you used and explain one logic error the AI made that you had to fix manually. 

- The prompt that I used for prompting to chat gpt is " Adjust the css to the specific margins that are acceptable for my class elements". One logic error that the AI made was it went ahead and chose to make almost every element blue for some reason and I had to go and change the edited colors to my specific liking. So I kept the blue where it was needed whereas the rest I just kept it white.
  
<!-- Reflection Homework 2 --> 

# Question 1: Explain the difference between flex-direction: row and flex-direction: column.
- The difference between flex-direction: row and flex-direction: column is simply their direction. Specifically wheter you want your elements to be set vertically or horizontally and we can apply that css property to specific childe elements of a larger div and such. 


# Question 2: Why is it important to use relative units (like %, vh, or rem) instead of fixed pixels (px) for responsive design
- It’s important because relative units help your website fit different screen sizes, while fixed pixels do not adjust as well.

# Question 3: AI Attribution: List the prompt you used if you consulted GenAI. Identify one specific piece of CSS code the AI provided that you had to modify to make it work for your layout 
- The specific prompt I used was, “Did I correctly update the nav bar and its list elements inside the nav-bar div?” I used this because I wanted to double-check how the nav bar was positioned and whether the order of the elements mattered. One specific piece of CSS code the AI provided was the following, check below. I ended up changing some of the `vh` and `rem` values to see how they affected the UI text and spacing across mobile and desktop, so I had to play around with the values a bit.
body {
    font-size: 1rem;
    line-height: 1.7;             
  }

  .logo {
    font-size: 1.4rem;
  }

  #site-header h1 {              
    font-size: 1.75rem;
  }

  .tagline {
    font-size: 0.95rem;
  }

  h2 {
    font-size: 1.4rem;
  }

  .project-card h3 {
    font-size: 1.2rem;
  }