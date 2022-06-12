# duxda-21106332

<h2>Accessibility</h2>

<h3>Skip links</h3>
<ul>
  <li>Follows WCAG guideline G1 - <a href="https://www.w3.org/TR/WCAG20-TECHS/G1.html">Click here to view guidance</a></li>
  <li> Allows screenreader users to skip to main content of page</li>
</ul> 
 
 <h3>Font</h3>
 <ul>
  <li>Atkinson Hyperlegible font was selected due to its legibility and readability for low vision users</li>
  <ul>
    <li>Developed by <a href="https://brailleinstitute.org/freefont">Braille Institute</a></li>
  </ul>
 </ul>
 
 <h3>Copy</h3>
 <ul>
  <li>A max width was set in ch to help with readability</li>
 </ul>
 
 <h2>Structure</h2>
 
 <h3>Classes and ids</h3>
 <ul>
  <li>Due to the simplicity of the webpage, applying CSS to semantic tags was deemed sufficient</li>
  <li>Classes have been added only when there’s a need to differentiate within a semantic element</li>
 </ul>
 
 <h3>:root</h3>
 <ul>
  <li>This was used as it is the highest parent element available</li>
  <li>Means that if you change one variable, it is carried out across any class it is attributed. 
    This makes it quicker and more efficient to make changes.</li>
 </ul>
 
 <h3>Comments</h3>
 <ul>
  <li>Used across both html and css to help organise the content within the files</li>
  <li>Makes it easier to go back and edit later</li>
 </ul>
  
 <h3>Media queries</h3>
  <ul>
    <li>Used to specify changes to specific elements when the screen goes below a certain size</li>
    <li>Placed at the bottom of the css file to make it easier when going back and making changes</li>
  </ul>
  
  <h2>Form</h2>
  
<h3>Hints and placeholder</h3>
  <ul>
    <li>Hints were used instead of placeholder text as it allows users to reference back rather than placeholder text which disappears once a user enters something in the field</li>
  </ul>
  
  <h3>Hidden fields</h3>
  <ul>
  <li>Users are asked to select a preferred contact method</li>
  <li>To make completing the form easier, only the preferred method input field will be shown</li>
  </ul>
  
  <h3>Autocomplete</h3>
  <ul>
  <li>Used to make it quicker for users to complete the form</li>
  </ul>
  
  <h3>Chosen fields</h3>
  <ul>
    <li>Only 2 fields are required - email or phone number and message</li>
    <ul>
      <li>This is the only information that would be required to respond to a query about the content on the site</li>
     </ul
    <li>Users given the option to include their name should they want to</li>
