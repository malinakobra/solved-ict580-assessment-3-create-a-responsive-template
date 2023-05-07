Download Link: https://assignmentchef.com/product/solved-ict580-assessment-3-create-a-responsive-template
<br>
Assessment 3

This assignment will test your understanding of CSS, HTML, specifically how to use CSS media queries, flexible layouts, and flexible images to create a responsive web design. If you have any questions or

For this assignment, you will be redesigning a blog template. You will not be creating an HTML file for this assignment. The HTML file will be provided for you by the instructor in D2L under Content and Dropbox sections. You will find a model/folder named “assignment_3”. Within this model are the files for this assignment. The first file is the HTML file. You may modify the contents of this file if you would like, but it is not required for this assignment. Additionally, you will find a folder named ‘css’ which contains a CSS file named ‘style.css’ and an ‘imgs’ directory containing all images for this assignment.

The existing template was created using a ‘mobile first’ approach. However, the previous designer only tested the website using an iPhone in landscape mode (480px × 320px). While the site works well when viewed on devices with these dimensions, it does not look right when viewed on tablets, desktop computers, or mobile devices in portrait mode.

Your job is to create a completed responsive layout design for this template. Again, you may modify the contents of the HTML file if you would like, but it is not required to complete this assignment.

&#x25fc; Requirement

Using what we have learned in class, you are to create a responsive design that meets the following criteria:

<ul>

 <li>The HTML file should include one or more&lt;link&gt; elements for your CSS file(s) related to your responsive design. You may include all of your responsive designs in a single file</li>

</ul>

<table width="0">

 <tbody>

  <tr>

   <td colspan="2" width="70">(using</td>

   <td colspan="2" width="55">@media</td>

   <td width="537"> media queries) or using multiple CSS files (with the media queries specified in</td>

  </tr>

  <tr>

   <td width="49">the</td>

   <td colspan="2" width="41">media</td>

   <td colspan="2" width="571"> attribute of your &lt;link&gt; element. Your design should support the following breakpoints:</td>

  </tr>

  <tr>

   <td width="49"> </td>

   <td colspan="4" width="612">o    Screens with a maximum width of 480px</td>

  </tr>

  <tr>

   <td width="49"></td>

   <td width="21"></td>

   <td width="20"></td>

   <td width="34"></td>

   <td width="537"></td>

  </tr>

 </tbody>

</table>

o    Screens with a minimum width of 481px and a maximum width of 768px o       Screens with a minimum width of 769px

<ul>

 <li><strong>Less than 481px wide</strong></li>

</ul>

The rules in the CSS file applied to screens with a maximum width of 480px should result in the following:

<ol>

 <li>The page navigation should be displayed as a list of horizontal links across the top of the page. These links can span more than one line if necessary.</li>

 <li>The logo should be displayed centred on the page and below the page navigation.</li>

 <li>The list of recent articles should be displayed in a single column.</li>

 <li>All images should fit on the screen and should have a small amount of white space on either side of them.</li>

 <li>Social networking links should be displayed in one column at the bottom of the screen (Icons should be under each other).</li>

 <li>The page footer should be centred across the bottom of the screen</li>

</ol>

<ul>

 <li><strong>Between 481px and 768px wide</strong></li>

</ul>

The rules in the CSS file applied to screens with a minimum width of 481px and a maximum width of 768px should result in the following:

<ol>

 <li>The logo should be displayed in the upper left-hand corner of the screen.</li>

 <li>The page navigation should be displayed as a list of vertical links to the right of the logo.</li>

 <li>The main image should not have anything to the left or right of it.</li>

 <li>The recent articles should be displayed in two columns of equal width. <strong>Images should not extend beyond the borders of its column.</strong></li>

 <li>Social networking links should be displayed in two horizontal rows below the recent articles.</li>

 <li>The page footer should be centred across the bottom of the screen.</li>

</ol>

<ul>

 <li><strong>Greater than or equal 769px wide:</strong></li>

</ul>

The rules in the CSS file applied to screens with a minimum width of 769px and a maximum width of 1024px should result in the following:

<ol>

 <li>The logo should be displayed in the upper left-hand corner of the screen.</li>

 <li>The page navigation should be displayed as a list of horizontal links to the right of the logo.</li>

 <li>The main image should not have anything to the left or right of it.</li>

 <li>The recent articles should be displayed in four columns of equal width. <strong>Images should not extend beyond the borders of its column.</strong></li>

 <li>Social networking links should be displayed in a single horizontal row below the recent articles.</li>

 <li>The page footer should be centred across the bottom of the screen.</li>

</ol>

<ul>

 <li>Images should never extend beyond the edge of their parent element. Be sure to take the necessary measures to ensure that this doesn’t happen.</li>

 <li>(1 point) The following elements should not be displayed on the printed page (Hit</li>

 <li>Submit (Only submit a single .zip file)</li>

</ul>

<strong>          </strong> Tips (optional)

<ul>

 <li>Review the CSS code, closely identifying any CSS code that refers to the width. Please note that the viewport meta tag has been not added in the head section.</li>

 <li>Use this concept to convert your widths from pixels to percentages:</li>

</ul>

o Target ÷ Context = Result shows how to change a layout from pixels to percentages.

<ul>

 <li>Modify all pixel-based selectors that refer to the width. That includes margin and padding, but please review the information on the introduction to guide you in finding the correct target and context.</li>

 <li>Add your comment to show the math for each selector you change.</li>

 <li>Start with the first media query, @media (max-width: <strong>481px</strong>) and then adjust each selector in the other media queries. If they do not display properly for a media query, do not move to another media query. Keep working on it until you meet the media query requirements.</li>

 <li>Remember! If a selector in the main CSS uses a float and the media queries do not need one, you need to add: float: none; This applies to any selector that may inherit a property that the smaller screens do not need.</li>

 <li>Convert selectors with width properties from pixel to percent.</li>

 <li>Adjust images to display at 100% in the container that they are placed.</li>

 <li>Create media queries to adjust the properties to meet the various screen sizes.</li>

</ul>