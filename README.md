<body> 
  <div>
    <h1>📌Description </h1>
    <p>This program demostrate how to insert a node at a sepcific index <mark><b>middle</b></mark> in a Singly LinkedList using java</p>
    <p> The implementation also include :</p>
    <ul>
      <li>Adding a node at the beginning (addFirst)</li>
      <li>Print the LinkedList</li>
    </ul>
  </div>
  <div>
    <h1> 🧱Node Structure</h1>
    <p> >Each node contains : </p>
    <ul>
      <li><b><mark>Data-></mark></b>value of the node</li>
      <li><b><mark>Next-></mark></b>reference to the next node</li>
    </ul>
  </div>
  <div>
    <h1>🧠 Logic : Add In Middle </h1>
    <p>To insert a node at index idx :</p>
    <ol>
      <li> IF <mark><b>idx==o</b></mark>, insert at the beginning using<mark><b> addFirst</b></mark></li>
      <li>Start traversal from <mark><b>head</b></mark></li>
      <li>Move the temporary pointer till <mark><b>idx-1</b></mark></li>
      <li>Create a new node</li>
    </ol>
    <p>Adjust The Links</p>
    <ul>
      <li>Point new node to <mark><b>temp.next</b></mark></li>
      <li>Point <mark><b>temp.next</b></mark> to new node</li>
    </ul>
  </div>
</body> 

