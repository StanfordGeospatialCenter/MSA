# **MSA**
A repository for the maintenance and distribution of the Mass Shootings in America Database.

#### Contents

**Data folder** contains the most updated MSA dataset as an .xlsx. GeoJSON coming soon..

**Methodology folder** contains the rules for how events are included into the dataset and how it is organized.

**Documents folder** contains reference material.

# Project background
The Stanford Mass Shootings of America (MSA) data project was begun in 2012 in reaction to the mass shooting in Sandy Hook, CT. In our initial attempts to map this phenomena it was determined that no comprehensive collection of these incidents existed online. The Stanford Geospatial Center set out to create, as best we could, a single point repository for as many mass shooting events as could be collected via online media. The result was the Stanford MSA.

### What the Stanford MSA is
The Stanford MSA is a data aggregation effort. It is a curated set of spatial and temporal data about mass shootings in America, taken from online media sources. It is an attempt to facilitate research on gun violence in the US by making raw data more accessible.

### What the Stanford MSA is not
The Stanford MSA is not a comprehensive, longitudinal research project. The data collected in the MSA are not investigated past the initial assessment for inclusion in the database. The MSA is not an attempt to answer specific questions about gun violence or gun laws.

The Stanford Geospatial Center does not provide analysis or commentary on the contents of this database or any derivatives produced with it.

### Data collection methodology
The information collected for the Stanford MSA is limited to online resources. An initial intensive investigation was completed looking back over existing online reports to fill in the historic record going back to 1966.  Contemporary records come in as new events occur and are cross referenced against a number of online reporting sources.  In general a minimum of three corroborating sources are required to add the full record into the MSA (as many as 6 or 7 sources may have been consulted in many cases). All sources for each event are listed in the database.

Due to the time involved in vetting the details of any new incident, there is often a 2 to 4 week lag between a mass shooting event and its inclusion in the public release database.

It is important to note the records in the Stanford MSA span a time from well before the advent of online media reporting, through its infancy, to the modern era of web based news and information resources. Researchers using this database need to be aware of the reporting bias these changes in technology present.  A spike in incidents for recent years is likely due to increased online reporting and not necessarily indicative of the rate of mass shootings alone.  Researchers should look at this database as a curated collection of quality checked data regarding mass shootings, and not an exhaustive research data set itself. Independent verification and analysis will be required to use this data in examining trends in mass shootings over time.

### Definition of Mass Shooting
The definition of mass shooting used for the Stanford database is 3 or more shooting victims (not necessarily fatalities), not including the shooter. The shooting must not be identifiably gang or drug related. The motive typically appears to be indiscriminate killing.

#### Why limit the type of incidents added to the Stanford MSA?
The goal of the Stanford MSA is to track the particular phenomena of mass shootings in the U.S. and not gun violence as a whole. While all gun violence is tragic, it is the seemingly spontaneous eruption of public mass murder for no easily discernable reason that is often the most confounding when looking for answers after the fact.

#### Differences between the Stanford MSA and other mass shooting data projects
The key difference between the Stanford MSA and other similar projects is the scope of definition and the focus on mass shooting incidents versus mass murder.  Instead of limiting our data collection to incidents in which 4 or more fatalities occurred (the FBI definition for Mass Murder), we instead collect incidents of 3 or more shooting victims (not necessarily fatalities). The focus is the act of indiscriminate shooting, with an assumed intent to kill.  All mass shooting definitions are arbitrary in that there is no natural way to quantify such an event. In setting up our threshold we wanted to focus on the shootings over the outcomes.

#### How to compare the Stanford MSA totals to other project totals for 'Mass Shootings'
There are a number of other databases tracking shootings in the U.S. each with their own criteria and incident tally. Extreme differences between datasets are likely an indication of different thresholds for inclusion (1, 2, 3 or 4 victims), the type of outcome (fatalities only versus fatalities and injuries), and the type of incidents captured (all gun violence, gang related, domestic, terroristic, etc.).

##### Known issues
- Data for the Stanford MSA are collected and maintained with the help of student assistants, interns, or temporary staff. The database may be left untended for short periods between staff hires during which events may go unrecorded and remain unremediated when work on the MSA resumes.

- Locations in the MSA are generally given as City/State. When using some online mapping services to geocode locations by City/State some locations may be misplaced due to the repetition of common city names between multiple states. This is an issue with the mapping service, not the database. Double check any maps created with this data to be sure your chosen service is placing locations correctly.

- Sources for the MSA come solely from online reports. Increases in records over time can not simply be assumed to be a reflection of increased events as online reporting trends and outlets have increased tremendously over the span of time covered by the Stanford MSA.

##### A note to researchers and journalists using the MSA
It is the user's responsibility to perform their own rigorous data quality assessment before using the MSA in their work.  Please read the data dictionary completely when looking for incident breakdown information. Please refer to the Known Issues and Methodology sections above for information on other issues that may affect trends in the data. Graphing the raw data for commentary without adjsuting for the various known issues and methedology (see above sections) may not provide insightful information.

##### How to cite the MSA
The Stanford MSA is released under a Creative Commons Attribution 4.0 international license. Please cite the MSA as “Stanford Mass Shootings in America, courtesy of the Stanford Geospatial Center and Stanford Libraries”.

##### Status of the database
The Stanford MSA is an ongoing project that involves the careful aggregation of data on a topic that receives numerous new records under the search term “Mass Shooting” on a weekly basis. Updating the database involves checking and corroborating both new and historical stories and is a time consuming process.  Our goal is to release a new update at least once a month or more frequently depending on the number of new records.

##### Access
Please fill out the form linked here to obtain a copy of the latest MSA release and data dictionary. Current release copy is December 8th, 2015.






# Dillinger

Dillinger is a cloud-enabled, mobile-ready, offline-storage, AngularJS powered HTML5 Markdown editor.

  - Type some Markdown on the left
  - See HTML in the right
  - Magic

You can also:
  - Import and save files from GitHub, Dropbox, Google Drive and One Drive
  - Drag and drop files into Dillinger
  - Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions that people naturally use in email.  As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually* written in Markdown! To get a feel for Markdown's syntax, type some text into the left window and watch the results in the right.

### Version
3.2.7

### Tech

Dillinger uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [markdown-it] - Markdown parser done right. Fast and easy to extend.
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [keymaster.js] - awesome keyboard handler lib by [@thomasfuchs]
* [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

You need Gulp installed globally:

```sh
$ npm i -g gulp
```

```sh
$ git clone [git-repo-url] dillinger
$ cd dillinger
$ npm i -d
$ NODE_ENV=production node app
```

### Plugins

Dillinger is currently extended with the following plugins

* Dropbox
* Github
* Google Drive
* OneDrive

Readmes, how to use them in your own application can be found here:

* [plugins/dropbox/README.md] [PlDb]
* [plugins/github/README.md] [PlGh]
* [plugins/googledrive/README.md] [PlGd]
* [plugins/onedrive/README.md] [PlOd]

### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma start
```

### Docker
Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 80, so change this within the Dockerfile if necessary. When ready, simply use the Dockerfile to build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:latest .
```
This will create the dillinger image and pull in the necessary dependencies. Once done, run the Docker and map the port to whatever you wish on your host. In this example, we simply map port 80 of the host to port 80 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 80:80 --restart="always" <youruser>/dillinger:latest
```

Verify the deployment by navigating to your server address in your preferred browser.

### N|Solid and NGINX

More details coming soon.

#### docker-compose.yml

Change the path for the nginx conf mounting path to your full path, not mine!

### Todos

 - Write Tests
 - Rethink Github Save
 - Add Code Comments
 - Add Night Mode

License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [@thomasfuchs]: <http://twitter.com/thomasfuchs>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [keymaster.js]: <https://github.com/madrobby/keymaster>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]:  <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
