<h1 align="center">Goal</h1>
   <p>The target of this project was build a functionality "read more", "read less" to perfom the actions that name itself suggest. In this project it is possible to visualize 10 lines of paragraphs, but we only show 5. If you click to read more you can see the full content and the suspended content; when you click on read less you will see the closed text and only 5 lines of the paragraph.</p>
<br></br>
    
<h3 align="center">About the code</h3>
    <p>All functionality through Javascript was structured entirely using the DOM (Document Object Model) as you can see in the fragment of the <b>index.js</b> document below:</p>
   
  ```
  const readMoreBtn = document.querySelector(".read-more-btn");
  const text = document.querySelector(".text");
  ```
  <li>In the code above we can see the handling of selectors through the <code>document.querySelector</code>. At this first moment we store in our variables the values of the specified selectors. Learn a little more about <b>.querySelector( )</b> through the <a href="https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector"> mdn.</a></li>
  
   ```
   readMoreBtn.addEventListener("click"...);
   // continuation of above code in index.js document
   if (readMoreBtn.innerText === "Read More") {
     readMoreBtn.innerText = "Read More";
   } else {
     readMoreBtn.innerText = "Read More";
   ```
   <li>Analyzing this other part of the code, it is possible to visualize the use of the "click" event with the <code>addEventListener</code> method that allows functions to be called when a specific event happens, in this case, it is < b>click</b>, this event will be triggered when the user clicks the read more/read less button.</li>
