---
title : Nelson Kiyoshi Kossuga
---

Nice to meet you! I am a games programmer with a deep interest in computer geometry, shader coding, openGL and other graphics-related topics.

## About my work experience:

I worked for a little over a year in Double Dash Studios, an indie studio from Rio de Janeiro - I improved my understanding of programming at a fast pace during my days there thanks to the great training and tutoring from my coworkers. I later enrolled into Futuregames (FG 21 fall-term) and I will be graduating in the spring of 2023.

With my prior experience I can comfortably work with Agile/Scrum teams, I also know how to work with git GUI's, including using gitflow for branching and merging - but I am by far not a master in version control.

I have 3+ years of experience with Unity-C# - both 2D and 3D, as well as 2 years of shaderlab experience, both within shadergraph and HLSL - while I am more used to the legacy render pipeline, I can work just as comfortably with URP. I have worked on procedural mesh generation and in basic development tools with Unity-C#, such as object placement and custom inspector windows. I usually connect my scripts through event-driven architectures for their simplicity and flexibility in Unity's editor.

I have around 1 year of C++ experience, which recently became my main language and the one I'm using to study openGL, a journey which I started around march of 2022. I aim to have a simple 3D game which runs with my graphics library before the end of this year (2022).

I have also worked with Unreal Engine (both UE 4 and 5) for little less than a year, using both the Material Editor's shader nodes and Niagara Systems for technical art assets, with the support of the Blueprint System. I currently consider myself slower at handling C++ code made for Unreal due to my inexperience with the engine's features - but I can also produce C++ code.

Below you'll find links and visual references for some of the projects I have worked on.

## Unity

[Here](https://github.com/5Daydreams/SnakeGameAlgorithms) is a solo project I tinkered with during my time in Futuregames - it is a 3D snake game with flying movement, the objective being to survive as long as possible while avoiding the ever increasing asteroids in a closed arena.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170142710-bb71570c-5081-42a3-af78-a6a87559a019.gif" alt="animated" />
</p>

[This](https://github.com/5Daydreams/SudokuSolver) was a really fun research project I did to try and understand how the Wave-Function-Collapse Algorithm works. I ended up very satisfied with just being able to generate the Sudoku boards, and couldn't find a more creative use for my implementation of the algorithm.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170132395-fedd9b14-0df2-4d29-8ee5-fd47592033d1.gif" alt="animated" />
</p>

[And this was a project from back in 2021](https://github.com/5Daydreams/GridMaze) where I was studying procedural generation for mazes. At the time I was relatively inexperienced, but this was one of the first games I managed to work on from start to finish.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/175815851-821c93df-2880-4279-9e76-b3481158dd87.gif" alt="animated" />
</p>

[Here](https://github.com/5Daydreams/ProceduralGeometryUnity) are some of my studies on Procedural Geometry with Unity. 
I really enjoy working on these objects, but I have never used them in my games. I really appreciate how closely related this type of code is to graphics programming "from scratch", but it is usually an overly complicated method to getting symmetrical art assets.


<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170142698-15fc08ef-180b-4ed7-9849-2e5125c997e1.gif" alt="animated" />
</p>

This was a study on volumetric rendering of primitive shapes with raymarching:

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170143940-43665fe4-840a-4760-9147-b8d14f7c5537.gif" alt="animated" />
</p>

Here is a block with a few Stencil Buffer windows, this was partially inspired by Antichamber, where each face of the cube has a different object inside:

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170146562-b57bb666-3558-4517-a35e-7998d4cc5be6.gif" alt="animated" />
</p>

This was a "swirl" animation for uv's, the idea was to have this behind the glass of washing machines. 
This effect was made in HLSL with some uv-remapping in fragment shader:

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170147009-4c1fd5b6-f61f-4926-817a-c410cbf3ceb3.gif" alt="animated" />
</p>

A disco dance floor with flashing lights. 
The pixel-art assets were produced by my artist teammates for a two-week game project during my time in Futuregames. 
During gameplay, the color of the dancefloor's lights indicated if you hit the dance move on the correct beat or not:

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170147717-a75e5591-5332-4380-9387-f4b23e0fe91b.gif" alt="animated" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170147769-d4baf960-cb71-491a-8766-4efb068b6217.gif" alt="animated" />
</p>

During my early experiments with Vertex shading I was able to get this wave effect - in the GIF I'm actually moving a handle:

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170147287-a5860508-e343-4b3a-84cf-c8279e0c59f7.gif" alt="animated" />
</p>

## Studies on low-level rendering with OpenGL and C++

[This](https://github.com/5Daydreams/StudiesOpenGL) is what I am currently experimenting with my rendering and openGL studies. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170142724-68b3aaed-7181-4514-a576-395abde7de5d.gif" alt="animated" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/175815899-4f59c818-ce84-47ff-a28f-44938e94b6cd.png" alt="animated" />
</p>


## Unreal Engine

This is from my 3rd group project in Futuregames, I worked on both the water heightmap and shaders to have the player move along the waves with custom water physics. While I did not implement the physics system directly, I did help with the math and calculations for said system.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180613671-05b1983d-801d-4660-a94e-8ad2efbe2b49.gif" alt="animated" />
</p>

I also worked on these caustics, which are triplanar mapped and applied into the bottom of our game's seabed with a decal.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180613749-dd91e9cf-82bf-459b-940a-0293619d33e8.gif" alt="animated" />
</p>

And this is an earlier version of the water, before implementing proper transparency and foam.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180613858-ca9d798b-0728-43bf-936b-18a2e12c18ca.gif" alt="animated" />
</p>

The wave shapes which you see are not Gerstner waves, I had to do some approximations to get the same vertical motion of the Gerstner waves but without the horizontal displacement, because we couldn't figure out a proper way to read the heightmap with the horizontal displacement from the Gerstner Waves. 

[This is the math I came up with](https://www.desmos.com/calculator/tht7i3rugm) for our game. I don't know if it has a proper mathematical name, but I coined these as "Lorentzian Waves" since it uses a pattern similar to the Lorentzian distribution (it looks like a Gaussian distribution, minus the fancy properties).

Now these are some personal side-projects I made when I started learning Unreal: 

These Galaxies and bubbles are made from Niagara Systems, I also made the shaders for the particles by myself.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180614197-7816c345-f9f3-4a09-936d-190d47dd1fb8.gif" alt="animated" />
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180614204-cc14141a-330b-4ffe-abe7-687684e35433.gif" alt="animated" />
</p>

I was also very curious and played a little bit with the refraction option from Unreal's material editor to achieve this "magic fog wall". 

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180614214-78d3c0d0-b70a-4edd-8d0f-b3ca36b9cb3a.gif" alt="animated" />
</p>

I then worked on spawning a "particle" as the distortion when you try to go through the wall

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180614438-f9982998-17a1-4c72-97de-136bc287cb06.gif" alt="animated" />
</p>

I also worked a little on some tutorials on applying raindrops, water ripples and moisture for static objects.

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/180614222-5763f2fe-8145-43fb-b4b6-45c7a217b617.gif" alt="animated" />
</p>


## Miscellaneous

[Here are some of the things I made with Processing](https://github.com/5Daydreams/processing-procedural):
As a hobby, I also like to make some simple generative art, I believe this is a great exercise for computer-mathematics, and is how I got started with programming. It is also very fun to prototype movement scripts and custom physics equations!

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170142857-6b2b9317-999f-44aa-9349-42689db8b683.gif" alt="animated" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170142964-5fbb75a9-f205-49d3-8806-524e23b2a470.gif" alt="animated" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/49330163/170143337-5c874873-5725-423a-a8a2-fa2a6a5020fa.gif" alt="animated" />
</p>
