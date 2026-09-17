---
layout: page
title : Apprenticeship at Inria
subtitle: This page presents the project I had the opportunity to work on during my two years as a Research Engineer at Inria
---

# Presentation

My work at Inria started in 2023 with a 3-months internship during my Bachelor degree that later turned into a 2-years apprenticeship supervised by [Stephane Ducasse](http://stephane.ducasse.free.fr/), research director of the [Evref team](https://www.inria.fr/fr/evref)

# Context

Evref is responsible for developping and maintaining [Pharo](https://pharo.org/), an object-oriented programming language but also a powerful environment. When I started working with the team they introduced me [Bloc](https://github.com/pharo-graphics/Bloc), a new low-level graphical library for Pharo. At the time, Bloc was in development (and still is today) and so the team asked me to create projects in order to explore Bloc's possibilities. 

*All the following projects were made using Bloc for Pharo*



# Projects 



## Myg 

[Myg](https://github.com/Ducasse/Myg) is a library for Pharo that contains games and provides tools to create yours, I implemented 5 games with classics such as MineSweeper or Sokoban and you can check those games to learn and create your own, like the "SameGame" that was originally created by students using Myg.

<p>
<img src="{{ 'assets/img/myg.png' | relative_url }}" alt="Myg" />
</p>



## Labyrinth 

[Labyrinth](https://github.com/Enzo-Demeulenaere/Labyrinth) is an implementation of the Labyrinth board game for Pharo for 2 to 4 local players. This project was made in 3 weeks in order to be presented at [ESUG](https://esug.org/) 2024, you can find the video of my presentation [here](https://www.youtube.com/watch?v=X5ifOzHkASw&list=PLJ5nSnWzQXi89jwnBCmGPh9xG6shuvuwb&index=10)

<p>
<img src="{{ 'assets/img/labyrinth.png' | relative_url }}" alt="labyrinth" />
</p>



## Bloc Demo Browser

The Demo Browser is a tool integrated to Bloc that searches snippets of executable code in the Bloc files (although **everything** is executable in Pharo), then it displays those snippets to try to understand existing examples by seeing their implementation, the visuals they return, but also their location in the files if you want to look deeper.

<p>
<img src="{{ 'assets/img/demobrowser.png' | relative_url }}" alt="demobrowser" />
</p>

## Color Picker 

The Color Picker is another tool integrated to Bloc that works as a basic Color Picker where you can toy with the Color Map, Hue and Alpha sliders in order to have the right Color for you to copy-paste into your code with the right RGB and/or HEX values

<p>
<img src="{{ 'assets/img/colorpicker.png' | relative_url }}" alt="colorpicker" />
</p>

## CoypuIDE 

I had the opportunity to work with [lucretio](https://linktr.ee/lucretiomsp) a DJ who wanted to experiment new things for his shows by connecting visuals to his actions so that spectators may experience differently the performance. We worked in collaboration in order to bring [CoypuIDE](https://github.com/pharo-graphics/CoypuIDE), a framework that provides visual tools to help him during his performances. I implemented new knobs, sliders and other visuals for him to work with.

<p>
<img src="{{ 'assets/img/coypu.png' | relative_url }}" alt="coypu" />
</p>

## Drag and Drop 

This sections shows various projects that allowed us to experiment with Drag and Drop implementation in Bloc 

### Flaps 

The flaps were the first steps towards a new Drag and Drop implementation. A "flap" is a widget that acts like a drawer ; you could store components of your environment by dragging them inside, then close the flap so it stays in a corner of your environment and then open it later to drag components back into your environment. Trying to create such a widget highlighted the need for a new Drag and Drop implementation.

<p>
<img src="{{ 'assets/img/flaps.png' | relative_url }}" alt="flaps" />
</p>

### Experimentations

We then started to experiment the available implementation of Drag and Drop to understand it and then build a new one with the pros and without the cons. The following picture shows different results of snippets we built *(from top to bottom, left to right )*:
- Select multiple elements by creating a "lasso" selection tool
- Sort elements in a list when dragging them in the right place
- Make an element react whenever another is dragged above
- A sorting game mixing newly found knowledge on drag and drop, animations and layouts

<p>
<img src="{{ 'assets/img/experimentations.png' | relative_url }}" alt="experimentations" />
</p>
  
### Letters Sorter

The Letters Sorter is an example mixing all we learned and implemented for the Drag and Drop, this simply shows how an element can react depending on where we are dragging and/or dropping it. This example was linked to a written tutorial in the documentation on how understand the implementation and recreate such an example.

<p>
<img src="{{ 'assets/img/letterssorter.png' | relative_url }}" alt="letterssorter" />
</p>

## Toplo 

Toplo is another graphical framework that works on top of the Bloc layer that provides widgets and tools to create your own widgets. For Toplo, my work was to create some widgets such as the "Tree" or the "Collapse" widgets below, but I also brought implementations for parts of widgets like new sliders of different kinds privoding multiple options.


<p>
<img src="{{ 'assets/img/widgets.png' | relative_url }}" alt="widgets" />
<img src="{{ 'assets/img/sliders.png' | relative_url }}" alt="sliders" />
</p>
