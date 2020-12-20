# Popular Posts
Popular Posts is a Blazor WASM app I created for displaying popular posts (most views) from my [Write.as](https://write.as/) blog.

### Configuration
The app takes two querystring parameters: 
- "alias" points to a Write.as alias.
- "max" determines the number of posts to be returned. To get back the 3 most popular posts from your Write.as blogs, pass in a value of 3 for this. If a value isn't
passed in, the app returns the 10 most popular posts.

### Example

To get the 10 most popular posts from my own Write.as blog, I use the following URL:  
`https://popularposts.dinobansigan.com/?alias=dino`

If I wanted to get just the top 5 posts, I can do this:  
`https://popularposts.dinobansigan.com/?alias=dino&max=5`

To use this app on your Write.as blog/site, you can either use the existing app at `https://popularposts.dinobansigan.com/`, pass in your parameter values and 
embed it in a post via iFrame. Or you can clone this repo, build out the solution and upload the static site app onto your webserver of choice, and use the app from there.
