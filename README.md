<hr>
<img src="title.svg" width="470" height="80" alt="css-in-readme">

★ &nbsp;DEV [Profile](https://dev.to/nilostolte)\
★ &nbsp;Discord: ID nilostolte#1728, [Channel](https://discord.gg/ZZGWnZBups)

## Summary
★ &nbsp;[**Open Letter**](https://github.com/nilostolte/Projects-Presentations/blob/main/OpenLetter.pdf): this letter is a foreword to the work I have been doing lately in terms of research and development.

★ &nbsp;[**Introduction**](https://github.com/nilostolte#introduction_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [Vector graphics as a portable solution for GUIs](https://github.com/nilostolte#vg_guis_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [Graphics designers as vector graphics GUI creators.](https://github.com/nilostolte#graphics_designers_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [Future high resolution screens](https://github.com/nilostolte#hd_screens_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [Google did it: Dart and Flutter](https://github.com/nilostolte#dart_flutter_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [FLutter is just Skia disguised behind the scenes. Could Dart survive?](https://github.com/nilostolte#flutter_skia_html_anchor)
    
★ &nbsp;[**Activities**](https://github.com/nilostolte#activities_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [**Current Activities**](https://github.com/nilostolte#current_activities_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [𝝅 desktop calculator](https://github.com/nilostolte#current_activity_1_html_anchor)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [**Future Activities**](https://github.com/nilostolte#future_activities_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [thinking about it](https://github.com/nilostolte#future_activity_1_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [**Previous Activities**](https://github.com/nilostolte#previous_activities_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Examples of vector graphics in Java](https://github.com/nilostolte#previous_activity_1_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Functionalities using PDFBox](https://github.com/nilostolte#previous_activity_2_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Functionalities using FreeHEP](https://github.com/nilostolte#previous_activity_3_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Major recent projects](https://github.com/nilostolte#previous_activity_4_html_anchor)
  
★ &nbsp;[**Hints and programming hacks**](https://github.com/nilostolte#hints_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [Java `Graphics2D`: you don't need double buffering](https://github.com/nilostolte#hint_1_html_anchor)\
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▻ [UTF-8 the ultimate standard for UNICODE texts](https://github.com/nilostolte#hint_2_html_anchor) <a name="introduction_html_anchor"></a>
  
★ &nbsp;[**Meme**](https://github.com/nilostolte#meme_html_anchor)
<hr>

## Introduction

Citizen of Canada and France, I am creative, autonomous, experienced, self-motivated, and after an entire career of **software engineer**, **researcher in Computer Science**, and **university professor**, having extensive experience in **C++** and **Java** programming (desktop and Android), in enterprise management, and in research, I am nowadays focusing in innovative graphics user interfaces (GUIs) using **vector graphics** in Java desktop applications as well as in Android, with impressive results in appearance, performance and display independence. This work has a tremendous reach in terms of longevity as well as in reduction of costs of graphics user interfaces. The vector graphics paradigm is almost universal and has been available in some languages and it has been recently migrating to hardware in the form of standard APIs.<a name="vg_guis_html_anchor"></a><br>

### Vector graphics as a portable solution for GUIs

Since [vector graphics paths](https://github.com/nilostolte/ClockWidget/blob/main/README.md#path-commands) are very high level abstractions, although able to define complex low level shapes, they can also be seen as part of a **generic metalanguage** which is platform, operating system and language independent. In other words, one can define GUIs using vector graphics primitives which are at the same time efficient (since we are actually dealing with the lowest level layer of vector graphics pipeline) and portable, since these primitives are practically universal, having only tiny differences between different languages and platforms. 
This means that it is theoretically very easy to port a vector graphics GUI from one language to another, or from a platform to another, or an operating system to another. Not only that but the automatization of this trasnformations is not at all rocket science and actually not very complex. These **transcompilers**, though, may be quite labor intensive depending on the level of details of their implementation.<a name="graphics_designers_html_anchor"></a>

### Graphics designers as vector graphics GUI creators.

The main advantage of using vector graphics primitives for GUI contruction on the other hand, are neither one cited above. The actual quite important consequence of such choice is to be able to use vector graphics art conceaved by **graphics designers** to define the GUI shapes and their appearence. For a long time GUIs were exclusively designed by programmers, not artists, and had terrible appearences and no appeal. Not only that but **frameworks** for GUI construction, which are basically designed by programmers, are extremely standardized, difficult to be customized and complex to learn and use. With the possibility to use **artwork from graphics designers** this whole perspective radically changes. In addition to that graphics designers are much cheaper and more creative than programmers. It looks obvious that vector graphics is definitely the solution for modern and fancy GUIs.<a name="hd_screens_html_anchor"></a>

### Future high resolution screens

But these are not the only advantages of using vector graphics for GUI creation. Its known intrinsic characteristic is of being **insensitive to the screen resolution**. One can for example zoom any part of the interface [without any loss of quality](https://github.com/nilostolte/Projects-Presentations/blob/main/%CF%80%20Vector%20GUI%20for%20Java%20and%20Android.md#basic-definitions). This not only means that one can design far different GUIs having **zooming** as part of its interactive process but also that the same interface can run in a variety of different screen resolutions. With the advent of **4K** and **8K** monitors and panels, and maybe even higher resolutions in the future, this is a fundamental feature for the **portability** of the same interface in different screen resolutions. With screen technology growing faster than the hardware to display the information, vector graphics can be seen as the graal for solving this kind of problem. What's amazing is that barely no one is using it nowadays, and we will eventually have a problem where all applications will need to migrate to vector GUIs anyway.<a name="dart_flutter_html_anchor"></a>

### Google did it: Dart and Flutter

Not everybody ignored all the vector graphics advantages in GUI contruction. **Google** didn't. That's the reason Google created **Flutter** and the language **Dart**. Dart can be seen as an enhanced revamped version of a vector graphics programming language and Flutter is its graphics environment. Dart and Flutter seem to be the solution for constructing GUIs and GUI-based appplications. Despite its growing popularity, **Dart and Flutter have caveats**. The main one is the fact of that they return the creative aspect back to programmers. As we have seen previously that is a mistake. Only a small amount of graphics designers would be interested in doing **design and programming**, and few will have both skills at reasonable level. In average one side could be good but the other sacrified. We have already forced artists to learn vector graphics production. Even though interactive tools make this task easier to them, artists had to adapt to all idiosyncrasies of vector graphics, particularly using **Bezier curves**. All mathematical aspects of Bezier curves are hidden to them, but some practical aspects are often missed, like setting control points touching the curve in minimal and maximal points. 
These aspects come as an **option**, and they generally only improve with the experience. But now Google is trying to convince artists that **programming is easy**. We have already seen this before with web programming and **JavaScript**. Artists had already a hard time to adapt to **Illustrator**, but now we are telling them to go a step further and submit to a totally **abstract way** of producing their art.

But it is also possible that Google is just another victim falling in the **trap of imposing a framework** desguised behind a language instead of offering a complete vector graphics language, or offering both side by side. The declarative nature of Dart doesn't actually promote the use of vector graphics primitives. The whole **marketing** behind Flutter seems to actually hide that and rather stress how easy it is to produce applications. Therefore the whole thing seems rather just like a framework. 
We have already seen that frameworks are **complex** as well as **difficult to customize** and to learn. Thus, the intention here seems to be not only to hide vector graphics primitives but also to hide the limitations of an underlying framework-like environment. Maybe the intention is to integrate in the language new ways to do interfaces as they appear. But if they can't appear in Dart we are assuming it is appearing somewhere else and this means that it is maybe an approach of staying one step behind, never being a vector of change.<a name="flutter_skia_html_anchor"></a>

### FLutter is just Skia disguised behind the scenes. Could Dart survive?

What is behind Flutter is **Skia**, a vector graphics library for **C++**. It is a quite complex and heavy library but it can be seen as a very good alternative for building vector graphics GUIs in C++ instead of **Qt**, since Qt is just a framework. This bring us to the fundamental limitation of Flutter and Dart for this score. It is designed to generate **machine language**, not **high level** and **portable** building blocks like vector graphics primitives.

This also brings us to the ultimate conclusion that there is probably no way to escape from **vector graphics primitives** to produce applications that have really portable GUIs. Does that mean that **Dart is a dead end?** Not necessarily. We know Flutter and Dart are **open source**. If Dart doesn't limit any vector graphics primitives for being accessed directly there is a chance to shortcircuit the compiler to accept only these constructions and to use it as a transcompiler. If it does limit them, direct access to these primitives must be added, but a new language would be created, since it is not actually Dart. In this way, in the case of a compiled language the normal compilation would take place to generate machine language. In the case one wishes to use a language having acces to its own vector graphics primitives, the compiler would generate high level code in that language, thus totally bypassing Skia.<a name="activities_html_anchor"></a>

<hr>

## Activities <a name="current_activities_html_anchor"></a>

<a name="current_activity_1_html_anchor"></a>
### Current Activities
- 𝝅 **desktop calculator**: a revamping of my [previous multi-precision scientific calculator](https://github.com/nilostolte/Projects-Presentations/blob/main/%CF%80%20Vector%20GUI%20for%20Java%20and%20Android.md#origins-of-the-system) for Android known as MaxCalc. This version is a desktop version that is a much more flexible application, not only integrating new features such as complex numbers, parenthesis prioritized operations, new computation calculus libraries, copy-pasting of values, etc., but it also implements a GUI entirely based on vector graphics primitives (previously it used a homemade framework library of widgets as explained [here](https://github.com/nilostolte/Projects-Presentations/blob/main/%CF%80%20Vector%20GUI%20for%20Java%20and%20Android.md#origins-of-the-system)), uses a much 
more flexible and extensible approach for function implementations using lambda expressions, variable sized and zoomable window,etc. This application is going to be offered as an open source software on GitHub once it is completed. The main idea is to use it as a demo for vector graphics GUI.<a name="future_activities_html_anchor"></a>

<a name="future_activity_1_html_anchor"></a>
### Future Activities
- thinking about it <a name="previous_activities_html_anchor"></a>

<a name="previous_activity_1_html_anchor"></a>
### Previous Activities
- **Examples of vector graphics in Java**
  -  [**ClockWidget**](https://github.com/nilostolte/ClockWidget): analog vector graphics clock in Java that gives the real time on a desktop (wholly developped in Java, but the design was inspired by a vector clock from freepik)
  -  [**ExclamationIcon**](https://github.com/nilostolte/PostScript/tree/main/Examples/Convertion%20to%20Java): static icon used as an error warning (automatically converted to Java from PostScript - [process described here](https://github.com/nilostolte/PostScript/tree/main/Examples/Convertion%20to%20Java/ExclamationIcon)).
  -  [**Java Vector GUI**](https://github.com/nilostolte/Java-Vector-GUI)
     -  [MenuInfographics6](https://github.com/nilostolte/Java-Vector-GUI/tree/main/MenuInfographics6): example of a complete menu wholly developed in Java inspired from a vector design from freepik. <a name="previous_activity_2_html_anchor"></a>The example contains menu items with an original shape, vector texts and exclusive vector icons, also providing interactions by clicking and rolling mouse wheel.
- [**Functionalities using PDFBox**](https://github.com/nilostolte/PDFBox)
  - [PDFBoxCompact](https://github.com/nilostolte/PDFBox/tree/main/PDFBoxCompact): <a name="previous_activity_3_html_anchor"></a>
    - [ShowJustifiedFormattedBook](https://github.com/nilostolte/PDFBox/blob/main/PDFBoxCompact/src/org/apache/pdfbox/examples/pdmodel/ShowJustifiedFormattedBook.java): example that generates automatic documentation from text file using a Latex-like simple language.
- [**Functionalities using FreeHEP**]()
  - [Java2PPT](https://github.com/nilostolte/Java2PPT): Java vector information shown on the screen, such as a Graphics User interface, is automatically converted to PowerPoint by using an intermediate language, MicroVBA. <a name="previous_activity_4_html_anchor"></a>
  - [MicroVBA-PowerPoint](https://github.com/nilostolte/MicroVBA-PowerPoint): VBA interpreter written in VBA to be used in PowerPoint in order to be able to import large vector graphics files, notably Java vector information from Java2PPT.
- [**Major recent projects**](https://github.com/nilostolte/Projects-Presentations)
  - [π Vector GUI for Java and Android](https://github.com/nilostolte/Projects-Presentations/blob/main/%CF%80%20Vector%20GUI%20for%20Java%20and%20Android.md#%CF%80-vector-gui-for-java-and-android): This project is about the development of a system for creating Graphics User Interfaces (GUI) for Java applications on Windows, Linux or Android using vector primitives and vectorized fonts.
  - [Automatic Vector Fonts Generator Project – Glyphs, their widths and kerning pairs](https://github.com/nilostolte/Projects-Presentations/blob/main/Automatic%20Vector%20Fonts%20Generator%20Project.md#automatic-vector-fonts-generator-project--glyphs-their-widths-and-kerning-pairs): This project is about the development of a tool to transform Truetype and Opentype fonts to an embedded proprietary compact font format in Java.
  - [String Vectorizer Project](https://github.com/nilostolte/Projects-Presentations/blob/main/String%20Vectorizer.md#string-vectorizer-project): This project is about a program that vectorizes strings into Java Path2D.Float paths.
  - [BreakIntoLines](https://github.com/nilostolte/Projects-Presentations/blob/main/BreakIntoLines.md#breakintolines): This project is about a Java program that vectorizes a string into Java Path2D.Float paths, breaking it into lines and right justifying the text.
  - [Converting PostScript to Java](https://github.com/nilostolte/PostScript/tree/main/Examples/Convertion%20to%20Java/ExclamationIcon#exclamationicon): This project shows how to convert PostScript files into Java classes semi-automatically.
  - [Java Vector GUI](https://github.com/nilostolte/Java-Vector-GUI/tree/main/MenuInfographics6#menuinfographics6): This project shows how a vector GUI can be coded. This code has been used for other projects like in MicroVBA.<a name="hints_html_anchor"></a>
<hr>

## Hints and programming hacks <a name="hint_1_html_anchor"></a>

### Java `Graphics2D`: you don't need double buffering

If you are into Java programming this might sound to you as a big surprise and almost as a huge heresy. No, you just don't need a `JPanel` and you definitely don't need double buffering.

What you need is just a `JFrame` and buffering with a `BufferedImage`, where you save your `Graphics2D` using `createImage`. You then use `drawImage` to display the saved buffer whenever you need to refresh the whole `JFrame`. Never redisplay your whole `JFrame` with `Graphics2D` primitives, but only with the `BufferedImage`. You can redisplay only parts of the `JFrame`. In this case your `JFrame` "paint" method must know what part to update by selective painting (like highlighting a button when clicked).

This is far much faster than double buffering and you will never see any flickering. Thus you will have the best performance with the same result as using a `JPanel` and double buffering.

But that is not the only advantage. It also allows easily zooming your entire window (by using `setSize` method) because you are dealing with the `JFrame` directly. Every time your window changes size (for example, by clicking on a magnifier lens with "+" or "-" icon) you create a new `BufferedImage` for the redisplay. This concept is a desirable feature when you are dealing with vector graphics interfaces (basically using `Shape` and `Graphics2D`), as zooming can become part of the interface.

It might sound weird to talk about vector graphics and a pixelized `BufferedImage` at the same time. However, a `Shape` is first scan-converted before being displayed and an `Area` is nothing more than a bitmap representation. By using a buffer you are just anticipating and cutting down scan-conversion time. This is extremely useful in complex vector graphics interfaces. It is a know fact that what is deterring the generalized use of vector graphics in GUIs, either in embedded applications, either on the web, is that it is quite time consuming.

This will likely change in the near future when hyper high resolution screens will appear and programs will have to deal with a wide range of screen resolutions. Vector graphics will then be the most elegant solution to this problem. Using lots of photos and images in your web sites? If they are only for decoration you will probably be in trouble when this arrives. <a name="hint_2_html_anchor"></a>


### UTF-8 the ultimate standard for UNICODE texts

[This project](https://github.com/nilostolte/UTF-8) allows to read UTF-8 encoded UNICODE files. It implements an infinite buffer file reader where one can recover the text word by word, which is converted from UTF-8, skipping blanks. The blanks can be recovered since they are all counted (feature used in the test program). By skipping blanks the reader is able to identify the start and the end of the words because they are different than blank. The fact that the text is encoded is totally transparent to the reader. The test program reads an UTF-8 testing file and prints it over the console. A batch file is provided to help running the jar. The source files are also given and they are all for free with no license of any kind. <a name="meme_html_anchor")></a>\

## Meme

<p align="left">
  <img src="https://user-images.githubusercontent.com/80269251/156929643-db1e72e8-c622-4a80-8f8a-6c57d1b6d42d.jpg" width="414" height="453">
</p>

