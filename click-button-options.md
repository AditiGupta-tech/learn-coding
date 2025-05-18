Hey coders!

You must have visited  various sites where the options would remain hidden until you clicked on a button. Ever wondered how? Well let's decode that with this code.

Explanation:
-> <button onclick="showOpts()">Show Options</button> : This line creates a button and associates it with a function which will handle the display of options when button will be clicked.

-> <div id="linkContainer">
   ..
  </div>
  -This part of the code creates a div where our options are contained.

  ->  <script>
    ..
  </script>
-The script tag consists of the javascript code which handles the function of displaying the options. (It is always advised to place the javascript code in a separate file [fileName.js]. However, for the ease of understanding we have placed it in the same html file.)

-> function showOpts() { : Marks the beginning of the function with name showOpts.

-> const container = document.getElementById('linkContainer'); : used to find element in html file with id linkContainer.

-> container.style.display = (container.style.display === 'none' || container.style.display === '') ? 'flex' : 'none';
-This is the main code which controls options display. 
-The css property display has a setting none: where content is not visible.
-Thus, this line says that if the content is not visible (display === 'none'), then on button click make it flex where we will see the options. Or if the options are visible (display === '' : any display setting except none), then on button click hide it by making display none.

I hope this helped you and you learnt something new today.

Use this feature in your websites and make them super amazing.

Looking forward to drop more such practice lessons.

Till then, keep coding and keep growing!