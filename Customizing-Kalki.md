## Customizing Kalki. 

As you can see, it's fairly easy to customize Kalki. A little knowledge of HTML and CSS helps, but isn't essential. You can learn enough HTML to customize the front end quickly. 

Look at this example:

The user will see this on their browser or phone: 

https://codepen.io/Teeke/live/GRqebMB

We can go to codepen and alter the code here: 

https://codepen.io/Teeke/pen/GRqebMB

There are three panes, HTML, CSS and JS. To set Kalki to read any subreddit, you will need to change the subreddit names here: 

    <subreddit name="assistance"></subreddit>
    <subreddit name="nature"></subreddit>
    <subreddit name="gardening"></subreddit>
    
You can set those subreddit names to any subreddit you like. Our new example is set to Aww, DIY and Space. 

https://codepen.io/Teeke/pen/XWKGLBN

## Changing the Header Pic

If you have your own hosted picture, you can change the background-image property in the CSS. look for code like this:

    header {
      background-image: url('https://assets.codepen.io/577362/abstract-house.jpeg');
      background-repeat: no-repeat;
      background-size: 100% auto;
      padding: 100px;
      box-shadow: 0px 0px 9px 3px rgba(41,41,41,.25);
      color: #ddd;
      font-size: 40px;
    }

and put your own hosted pic there. Be careful to leave the quotes and brackets around the pic. ('your-pic-here.jpeg');

Voila:

https://codepen.io/Teeke/pen/abZMgPy

        

