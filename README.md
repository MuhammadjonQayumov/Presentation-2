# Lecture 6

>1)DOM
>
>2)BOM
>
>3)EVENTS
>
>4)DOM METHODS

# Window

>Объект window представляет собой окно, содержащее
>DOM документ; свойство document указывает на DOM 
>document (en-US), загруженный в данном окне. Окно 
>текущего документа может быть получено с помощью 
>свойства

![](/window1.png)

# What is DOM in JavaScript?

#### WHAT IS THE DOM ?

>The Document Object Model (DOM) is a programming >interface for web documents. It represents the page >so that programs can change the document structure, >style, and content. The DOM represents the document >as nodes and objects; that way, programming >languages can interact with the page.

#### The dom tree structure

![](/dom1.webp)

#### DOM

>The Document Object Model (DOM) connects web pages >to scripts or programming languages by representing >the structure of a document—such as the HTML >representing a web page—in memory. Usually it >refers to JavaScript, even though modeling HTML, >SVG, or XML documents as objects are not part of >the core JavaScript language.
>
>The DOM represents a document with a logical tree. >Each branch of the tree ends in a node, and each >node contains objects. DOM methods allow >programmatic access to the tree. With them, you can >change the document's structure, style, or content.
>
>Nodes can also have event handlers attached to >them. Once an event is triggered, the event >handlers get executed.