Sugarizer GSOC2020 projects
=====

## Sugarizer game activity pack

**Prerequisites**

- Experience with JavaScript/HTML5 development
- Experience with Vue.js framework development

**Description**

The objective of this project is to develop new Sugarizer activities requested by teachers from [Sugarizer deployment in Saint-Ouen](https://wiki.sugarlabs.org/go/Sugarizer_Saint-Ouen_deployment).

Specifically, the objective of this project is to develop two new games:

- A Mind Math activity
- A Tangram activity

*Mind Math Activity*

The Mind Math activity will be a game to practice mathematic in a different way. More precisely, the goal is to arrive at a chosen number using the four basic arithmetic operations (+, -, ×, ÷) applied to five numbers chosen randomly.

Two levels of difficulty will be proposed:

- an easy level with a chosen number between 10 and 69
- a medium level with a chosen number between 0 and 99

The difficulty level could also be increased by asking for mandatory operations.

The user will have five random numbers (one between 1-4, one between 1-6, one between 1-8, one between 1-12 and one between 1-20) and 4 slots to find the chosen number. The user will be able to undo an operation.

![](images/mindmath.png)

The score will depend of:

- Number of slots used (more is better)
- Bonus when all four arithmetic operations are used
- Bonus depending of time to solve the challenge

The game could be played alone or against other users on the network. In one player mode, a solver should be integrated to help the user and show the best result at end. In multiple player mode a leader board will be displayed.

The detailed game play will be discussed with the project mentor but the inspiration of this game came from [Mathador](https://www.mathador.fr/).

*Tangram Activity*

The Tangram activity will be an activity to play to the traditional [Tangram game](https://en.wikipedia.org/wiki/Tangram).

The Tangram activity will present to the right of the screen a set of Tangram pieces and to the left of the screen a canvas where the user should form a specific shape using these pieces.

![](images/tangram.png)

Two levels of difficulty could be proposed:

- an easy level where the user know where each piece should be set on the shape and just have to move/rotate the right piece to the right place
- a medium level where the user should guess where each piece should be set and move/rotate it to the right place

The difficulty level could also be related to the complexity of the shape.

The detailed game play will be discussed with the project mentor but following is a non-exhaustive list of inspiration:

- [http://activities.sugarlabs.org/en/sugar/addon/4186](http://activities.sugarlabs.org/en/sugar/addon/4186)
- [https://freegames.org/tangrams/](https://freegames.org/tangrams/)
- [https://www.abcya.com/games/tangrams](https://www.abcya.com/games/tangrams)
- [https://www.giochi.it/gioco/kids-tangram](https://www.giochi.it/gioco/kids-tangram)
- [https://www.tangram-channel.com/](https://www.tangram-channel.com/)

**Project Tasks**

These new activities should provide unique Sugarizer features:

- Sugarizer look & feel: use of Sugar toolbar and palette
- Sugarizer storage: load/save content into the Journal
- Network integration: integrate Sugarizer presence to share the activity on the network so multiple users could play together
- Responsive: content should adapt to any screen size, a fullscreen button should allow to mask the toolbar for smaller screens
- Multi-device support: should work on any browser (Chrome, Firefox, Safari) and any platform (Android, iOS, Windows, Linux, MacOS) supported by Sugarizer
- Tutorial: an integrated documentation should be integrated to explain each feature of the activity

As with other Sugarizer activities, the new activities should be written using JavaScript and Sugar-Web library. We recommand also to use the Vue.js framework.

**First steps to start:**

- Complete the [Sugarizer activity development tutorial](https://github.com/llaske/sugarizer/blob/dev/docs/tutorial.md)
- Explore the list of inspiration provided above
- Study the [source code](https://github.com/llaske/ExerciserReact) of the Calligra activity, a Sugarizer activity developped with the Vue.js framework
- Learn about [Vue.js](https://vuejs.org) framework and complete the Vue.js tutorial
- Propose a game play for these activities

------------

## Sugarizer knowledge activity pack

**Prerequisites**

- Experience with JavaScript/HTML5 development
- Experience with Vue.js framework development

**Description**

The objective of this project is to develop new Sugarizer activities requested by teachers from [Sugarizer deployment in Saint-Ouen](https://wiki.sugarlabs.org/go/Sugarizer_Saint-Ouen_deployment).

Specifically, the objective of this project is to develop two new activities:

- A Curriculum activity
- A Vote activity

*Curriculum Activity*

The Curriculum activity will be a way for a student to self check its skill in a set of knowledge and provide multimedia element to demonstrate these skills.

The Curriculum activity will display a hierarchical set of skills grouped by categories then let the user explore the tree. On each skill the user should be able to validate (i.e. skill acquired) and provide multimedia elements (pictures or sounds coming from Journal) to demonstrate the skill.

![](images/curriculum.jpg)

The Curriculum activity will provide a settings mode to edit the set of skills: Create/Update/Delete/Sort skills or categories. A category should have a title and a color, a skill should have a title and an image.
It should be possible to generate a Word/ODT document with all skills and dated multimedia elements.
It should be possible to share its skills on the network.

The detailed features will be discussed with the project mentor but the inspiration of this activity came from [JeValide](http://classetice.fr/spip.php?article437) application.

*Vote Activity*

The Vote activity will allow easily to build a poll system. The user create a poll (yes/no, choose a value in a list, enter a value) then share it on the network so any user could vote in real time. At the end of the vote, a screen will sum up results of the vote: stats, who vote for what, who vote first, ...

The design of the Vote activity could be inspired by the Exerciser activity:

- A home screen allow to quickly choose a poll template and run the vote
- A setting screen allow user to create new poll or customize a poll

A poll is a label (question) and could integrate a multimedia element (image, audio, video, speech to text).

![](images/vote.jpg)

The detailed features for this activity will be discussed with the project mentor but following is a non-exhaustive list of inspiration:

- [https://www.speechi.net/en/home/assess/free-interactive-voting-system-mobile-application/](https://www.speechi.net/en/home/assess/free-interactive-voting-system-mobile-application/)
- [https://www.voxvote.com/](https://www.voxvote.com/)

**Project Task**

These new activities should provide unique Sugarizer features:

- Sugarizer look & feel: use of Sugar toolbar and palette
- Sugarizer storage: load/save content into the Journal
- Network integration: integrate Sugarizer presence to share the activity on the network so multiple users could play together
- Responsive: content should adapt to any screen size, a fullscreen button should allow to mask the toolbar for smaller screens
- Multi-device support: should work on any browser (Chrome, Firefox, Safari) and any platform (Android, iOS, Windows, Linux, MacOS) supported by Sugarizer
- Tutorial: an integrated documentation should be integrated to explain each feature of the activity

As with other Sugarizer activities, the new activities should be written using JavaScript and Sugar-Web library. We recommand also to use the Vue.js framework.

**Fist step to start:**

- Complete the [Sugarizer activity development tutorial](https://github.com/llaske/sugarizer/blob/dev/docs/tutorial.md)
- Explore the list of inspiration provided above
- Study the [source code](https://github.com/llaske/ExerciserReact) of the Calligra activity, a Sugarizer activity developped with the Vue.js framework
- Learn about [Vue.js](https://vuejs.org) framework and complete the Vue.js tutorial
- Propose a game play for these activities

------------

## Sugarizer School Portal

**Prerequisites**

- Experience with JavaScript/HTML5 development
- Experience with node.js and EJS framework
- Experience with Docker and Kubernetes

**Description**

Sugarizer School Portal is a new tool in the Sugarizer family to provide a way, for schools interested by Sugarizer, to host and manage themselves their Sugarizer deployment. More precisely, the idea is to provide an on-demand Sugarizer Server deployment tool. So, every school will be able in few clicks to create a Sugarizer Server to host its own deployment without any technical skill.

![](images/docker.png)

Under the hood, Sugarizer School Portal will be a Kubernetes server that should be able to create/manage on demand new Sugarizer Server docker instances.
A web interface will be also created to let users ask for a new deployment. Finally, a dashboard will be created to let super administrator follow number of deployments and usage of each deployment to be able to resize the infrastructure if need.

**Project Task**

- Create a Kubernetes infrastructure that could deploy on demand Sugarizer Server instance
- Create a set of scripts to handle deployment/removal of a new Docker instance
- Create a set of scripts to extract stats usage of Sugarizer Server
- Create a web interface to let users ask for a new deployment
- Create a web dashboard to let super administrator manage instances deployment and usage

Some other features could be added to this list depending of feedbacks on the field.

**Fist step to start:**

- Complete the [Sugarizer activity development tutorial](https://github.com/llaske/sugarizer/blob/dev/docs/tutorial.md) to understand how Sugarizer work
- Install [Sugarizer Server](https://github.com/llaske/sugarizer-server/tree/dev) and dashboard using Docker and explore the Docker compose file provided with Sugarizer Server
- Create different Sugarizer users and see how the dashboard trace activities and usage works
- Study the [source code](https://github.com/llaske/sugarizer-server/tree/dev/dashboard) of dashboard
- Learn about [Kubernetes](https://kubernetes.io/) and complete the [Kubernetes tutorial](https://kubernetes.io/docs/tutorials/)

------------
