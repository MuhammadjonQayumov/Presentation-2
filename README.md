# Lecture 6

>1)DOM
>
>2)BOM
>
>3)EVENTS
>
>4)DOM METHODS

# Window

>Объект window представляет собой окно, содержащее DOM документ; свойство document указывает на DOM  document (en-US), загруженный в данном окне. Окно  текущего документа может быть получено с помощью  свойства

>![](/window1.png)

# What is DOM in JavaScript?

#### WHAT IS THE DOM ?

>The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

#### The dom tree structure

>![](/dom1.webp)

#### DOM

>The Document Object Model (DOM) connects web pages to scripts or programming languages by representing the structure of a document—such as the HTML representing a web page—in memory. Usually it refers to JavaScript, even though modeling HTML, SVG, or XML documents as objects are not part of the core JavaScript language.
>
>The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree. With them, you can change the document's structure, style, or content.
>
>Nodes can also have event handlers attached to them. Once an event is triggered, the event handlers get executed.

#### array methods

>The Style object represents an
>individual style statement.

>innerHTML - Это свойство предоставляет простой способ полностью заменить содержимое элемента.

#### Html events …

>Global Event Attributes
>
>
>
>HTML has the ability to let events trigger actions in a browser, like starting a JavaScript when a user clicks on an element.
>
>To learn more about programming events, please visit our JavaScript tutorial.
>
>Below are the global event attributes that can be added to HTML elements to define event actions.


#### createElement()

>The JavaScript document.createElement() method allows you to create and return a
>new element (an empty Element node) with the specified tag name.

## Html events

>![](/HTML-Event-2.png)


##### HTML DOM Element appendChild()

>Node.appendChild() добавляет узел в конец списка дочерних элементов указанного родительского узла. Если данный дочерний элемент является ссылкой на существующий узел в документе, то функция appendChild() перемещает его из текущей позиции в новую позицию (нет необходимости удалять узел из родительского узла перед добавлением его к какому-либо другому узлу).
>
>![](/be.png)

##### appendChild()

>To create a paragraph with a text.
>•Create a paragraph element
>•Create a text node
>•Append the text node to the paragraph
>•Append the paragraph to the document
>
>![](/b2.png)

##### classlist()

>The Element.classList is a read-only property that returns a live DOMTokenList collection of the class attributes of the element. This can then be used to manipulate the class list.
>
>Using classList is a convenient alternative to accessing an element's list of classes as a space-delimited string via element.className.