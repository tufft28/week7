# week7
Evaluating data, GitHub Pages, and telling stories with maps

## Story Mapping: *because no one has thought of a narrative approach to mapping until now apparently?*

In the last several years, story mapping has emerged as a way to bring a "guided tour" feel to interactive maps. Below are (in my mind at least) the biggest players.

### Esri's approach
https://storymaps.arcgis.com  
https://esri.github.io/#Storytelling  
[example](http://storymaps.esri.com/stories/2015/refugee-crisis/)  

##### Pros
- Esri integration
- Easy to include photos/videos from other website
- Ease of use

##### Cons
- Can be a little on the ugly side
- Limited to Esri map embedding

### Odyssey.js (from CartoDB team)
http://umn-gis-5574.github.io/odyssey.js/
http://www.azavea.com/blogs/atlas/2015/02/using-odysseyjs-sandbox/
[example](http://clhenrick.github.io/BushwickCommunityMap/)

##### Pros
- Very powerful
- Integrates Torque as a unique viewing option
- Easy to connect to a CartoDB layer

##### Cons
- Documentation is a bit spotty, making the learning curve a bit trickier than the others
- Looking forward, it's not clear if it's going to see much improvement 

##### Other
- Great way to start writing in Markdown, as it's an integral aspect of Odyssey

### StoryMapJS from Knight Lab
https://storymap.knightlab.com/  
[example](http://www.minnpost.com/stroll/2014/06/hockey-hip-hop-and-other-green-line-highlights)  
[another example](https://storymap.knightlab.com/examples/aryas-journey/)  

### Neatline
http://neatline.org/  
Runs on top of [Omeka](http://omeka.org/)  

## Intro to [GitHub Pages](https://pages.github.com)
Two choices
- *user or organization site*, useful for portfolio type sites.  
- *project site*, for projects(!)

This week's assignment is to fork the week7 repo and create your own project site, what you need to do is:
1. Fork the week7 repo
2. Clone your fork
3. Create a new branch and call it **gh-pages**
4. Create an `index.html` file
5. Add the following boilerplate

```html
<!DOCTYPE html>
<html>
<head>
	<title>GIS 5574 - My story map</title>
	<meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
  </style>
</head>
<body>
<h1> Look at my story map!</h1>
<!-- Your embed code goes in here -->

<p>What did you think?</p>
</body>
</html>
```

6. Add the iframe embed code for your story map into the `index.html` file
7. Commit and sync your file
8. In a few minutes go to `<your Github account>.github.io/week7` and you should see your work! (for example, since my username is `krdyke` I would go to `krdyke.github.io/week7`
9. Create a pull request so I can see that you're done.
