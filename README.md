# StarWarsAPI-Angular
<h3>Overview</h3>
This project was submitted for my no-server project at DevMountain. The project was fun in nature and utilized the <a href="https://swapi.co/" target="new">Star Wars API</a>.

The biggest challenge in this project was the implementation of Angular Chart to plot the ship statistics on a radar graph. I ended up having to use a nested array from the parsed reponse in order to input the data into the Angular Charts required format. You can see this approach in the Ships Controller and Service.

You may notice that there is a lot going on in the Controllers of the ships and planets. Since the API was void of information I wanted, and this was a no-server project, I decided to inject my own data (planet images and summaries) into the object for Angular extraction. In a real world scenario this would be handled on the back-end.

One fun addition I made to this website was Angular Audio. You will notice a sound plays when you click on the links at the top of each page. This effect uses Angular Audio.

Overall this project solidified my understanding of Angular using routing, custom directives, and configuring controllers and services to GET data from a live API.

<h3>Lessons Learned</h3>
If I had to create this webapp again I would have established a more flexible file structure early on. I started this project early and realized I needed to create the ships page after I already began. As a result I had to do some re-arranging of index files, controllers, and services. This was unneccessary and could have been prevented with a more efficient file structure from the beginning. This was the biggest lesson learned on this project that I will take with me in to my future projects. Lastly, I would have made this website responsive if I had to do it again.

<h3>Screenshots</h3>
<a href="http://i.imgur.com/OULbZys.png" target="new">Splash Page</a>
<br>
<a href="http://i.imgur.com/Rfsg4Zj.jpg" target="new">Planets ScreenShot</a>
<br>
<a href="http://i.imgur.com/GlBZx2V.png" target="new">Ships Radar Graph</a>


<h3>Libraries/Frameworks/Resources Used</h3>
<a href="https://swapi.co/" target="new">Star Wars API</a>
<br>
<a href="https://necolas.github.io/normalize.css/" target="new">Normalize.css</a>
<br>
<a href="https://angularjs.org/" target="new">AngularJS</a>
<br>
<a href="http://cdnjs.com/libraries/angular.js/" target="new">Angular Routes</a>
<br>
<a href="http://jtblin.github.io/angular-chart.js/" target="new">Angular Chart</a>
<br>
<a href="https://github.com/danielstern/ngAudio" target="new">Angular Audio</a>
