# Ready, set, go!

It's time to make our hands dirty with Luna! The first thing we're going to do is to create a simple data flow graph, which will create two numbers and then add them together!

Place your mouse over the Luna Visual Editor and press the <kbd>tab</kbd> key. A Node Searcher should appear on the screen <span class="uiref">1</span>. It allows you to filter available functions and libraries by their names.

![](/assets/placeholder.jpg)

---

Type `7` or any other lucky number and press <kbd>enter</kbd> to confirm your choice. A blue circle appears on the screen <span class="uiref">1</span>. It is called a "node". You will learn more about both the Node Searcher and nodes in the following chapters. For now just remember that node is a function, that you feed with data from the left side and outputs result from the right side. A number does not need any input, it just returns itself as a result, thus we do not need to connect anything to it's left side. It's color indicates the type of data it processes. Numbers are blue. Simple, isn't it? 

![](/assets/placeholder.jpg)

---

Next press the <kbd>tab</kbd> key again and type `13` or any other unlucky number. Press the <kbd>enter</kbd> key. You should see 2 circles on the screen. You can press and drag them to arrange them freely in the space. Let's arrange them vertically! 

Select the node with lucky number and press the <kbd>tab</kbd> key again. If a node is selected when Node Searcher opens, it tries to search for associated functions first. As you can see, a lot of mathematical functions are displayed now. Type `+` and press <kbd>enter</kbd>. A new node appears <span class="uiref">1</span>. This time however, it is connected to our lucky node. The connection <span class="uiref">2</span> indicates the flow of data. It just means that the number `7` flows from its creator into the `+` node. To connect the second number, hover over it's output port <span class="uiref">3</span> and either drag it to input port of `+` node <span class="uiref">4</span> or click on each port respectively.

![](/assets/placeholder.jpg)

--

As you can see, each node displays it's results below it's visual representation 
<span class="uiref">1</span>. An important thing to note here is that Luna works in a reactive way, so keeps all results always up to date. Let's click on the lucky number node and press <kbd>enter</kbd> key. The node will expand from its minimal representation to a full one <span class="uiref">2</span> giving you access to interactive controls - a number slider in this example. Change the slider and observe how the results update on the fly!
