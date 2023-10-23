# Bikes For Refugees

Fun fact, [Bikes For Refugees](https://www.bikesforrefugees.scot/) is a real project, and CYF grads have worked on apps for it for their Final Projects.

## Set up

1. **Clone** [this repository](https://github.com/CodeYourFuture/bikes-for-refugees/) onto your machine. You can use this [video guide](https://www.youtube.com/watch?v=ILJ4dfOL7zs) to refresh your memory if you're stuck.
1. Open up the repository you just cloned using VSCode.
1. Make a new branch for your work in the form `cohort/name`. For example: `NW7/GermanBencci`

You're now ready to code!

## Exercise

The aim of the exercise is for your webpage to look like the following screenshot:

![Bike For Refugees: final design](https://github.com/CodeYourFuture/bikes-for-refugees/blob/main/bikes-for-refugees_final-design.png)

Open the `index.html` file in your browser, and compare it to the image of the final result. What's different?

### Exercise 1) Use semantic markup

Open up Devtools and [choose the Accessibility tab](https://stackoverflow.com/questions/58988357/accessing-the-accessibility-tree-of-a-website) next to Layout (or behind the >> chevrons). Now start to replace the `<div>`s with semantic HTML tags. The visual render looks the same, but the API interprets the semantic HTML totally differently. Semantic HTML does stuff!

### Exercise 2) Fix the broken images

Some of the links to images are broken. The images you need are in the `images` folder - please replace any broken image links with the correct paths. 
It's also good practice to include a description of the image in the `alt` attribute. 

Make sure to add some CSS to make the images look like the design.

### Exercise 3) Style buttons

There are 3 buttons on the page: can you style them like the design?
**Remember**, re-use styles as much as possible by using CSS classes.

### Exercise 4) Add spacing

- Add more space **inside** the hero section so that more of the image is visible. 
- Add more space **below** the hero section to move the 'Learn more' section down.
- Use the `padding` property to add some more horizontal space between the navigation links in the header.

### Exercise 5) Fix the positioning

Compare what you can see in your browser with the design provided. Can you spot the differences in layout? Use CSS Flexbox or Grid to move elements around so they are positioned correctly.

Also add borders and spacing if required to match the design. 

### Bonus: hover effects

Add a hover effect using CSS, so that:
  1) The links in the top menu navigation become orange on hover
  2) The colours of the buttons are inverted on hover

## Submit your work

Once you've finished, **open a pull request**.

As always, you can use this guide if you need to refresh your memory 👉 https://curriculum.codeyourfuture.io/guides/create-a-pull-request/
