# Routing And Nested Resources

## Objectives

1. Understand the value of nested routes
2. Create nested routes
3. Understand how nested resource URL helpers are named

## Lesson

### URL As Data

###


## Outline

Back to the blog example. Author has any posts

  * Sometime we want to show users a little bit about how the relationships work. Want users to realize that these posts belong to this user.
  * Also we want our URLs to be shareable and almost "english-y". We want our URLs to be descriptive. Also allow for more discovery. 
  * Create route manually, no nested stuff for `/authors/1/posts`. and `/authors/1/posts/2`. Just the reading resources.
  * Modify the controller to work with the new filters
  * So annoying, muddies up your routes
  * Show how to do nested routes properly. use the `[:only]` stuff so that they don't go on to the `/new` and `/edit` just yet.
  * Show the url helpers. (put them in the views)
  * rake routes tip
  * Explain to never nest more then one level deep.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/routing-nested-resources-reading' title='Objectives'>Objectives</a> on Learn.co and start learning to code for free.</p>
