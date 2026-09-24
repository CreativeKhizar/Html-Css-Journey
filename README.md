[ 24 Sept 2026 ]

-> Today I learned about form tag.

-> Form Tag is used to display registration form to the users.

-> From Form Tag we can collect the data from the user and use it in javascript for 
   any functionality or send the collected data for the backend for storing in the database
   or performing any operation on it.

-> form tag has two attribute i.e., action and method.

-> action attribute in form tells about the page where the form data is being 
   transfered and if there is a page when we will click on the submit button then 
   the page will be redirected to the action attribute page or api.

-> method attribute tells what http verb is used for the transferring of data.

-> http protocol is used for communication over the internet.

-> There are 4 types of http verbs :-

   -> GET ( here data is passed in url in the form of query string )

   -> POST ( here data is passed in the header body )

   -> PUT
   
   -> PATCH

   -> DELETE

-> Normally in form we use two tags

-> label and input tags

-> label tag is used to describe about the data that should be entered into the input tag

-> label tag has for attribute that is used to bind the input tag with keeping for attribute
   value as id for the input tag.

-> there are multiple input type attribute values like below

      -> text 
      -> password
      -> email
      -> radio
      -> checkbox
      -> file
      -> color
      -> date
      -> text area

-> There is another tag i.e., drop down list 
      
      <select name="" id="">
         <option value="value1">value1</option>
         <option value="value2">value2</option>
         <option value="value3">value3</option>
      </select>

-> An Example Program is displayed in the directory 24-09-2026.

-> Thankyou for reading.

[ 23 Sept 2026 ]

-> Today I learned about table tag. 

-> table tag is used to create Table in Html.

-> Just like how a webpage has header, body and footer similarly table has three sections
      
      -> thead ( It tells the name of the columns )

      -> tbody ( It tells about the data present in the table like column data )

      -> tfooter ( just the webpage footer it tells about assurance like why we can trust the above data. )
   
-> There is table attribute like border="n", here n represents the size of border of the table.

-> By default the border is invisible for the table you can use border attribute to give
   border to the table.

-> There are other attributes of table like rowspan and colspan.

-> Sometimes we need two or more rows or columns combined together to display our data
   at this time we use rowspan and colspan.

-> rowspan is used to merge two or more rows of same column.

-> colspan is used to merge two or more columns of same row.

-> Thankyou for reading.

[ 22 Sept 2026 ]

-> Today I learned about links, Images, lists and text formatting tags.

-> Links are used to link to redirect from one webpage to another webpage

-> The syntax to create a link is we use anchor tag.
      <a>Redirect</a>
   
-> I learned that anchor tag has 3 attributes with names href, title, target

   <a href="path to redirecting webpage" title="what sholuld be displayed when hover" target="to open redirected webpage in new tab
   or same tab">Link Name</a>

-> Example : <a href="https://google.co.in" target="_blank" title="Google is the most popular search engine">Google</a>

-> I did an small experiment with the anchor tag.

-> Then I learned about Image tag i.e, <img>

-> Syntax : <img src="path of image" alt="Description of the Image">

-> img tag has two attributes ie., src that tells what image should be displayed in the webpage, alt tells description of the image.

-> alt attribute helps in improving the accessiblity of the image for the eye disability people who uses screen reader.

-> To get free images we can use pexels and unsplash websites.

-> Then, I learned about lists and they are used to list a group of items

-> Lists of three types

   -> Ordered Lists
   -> Unordered Lists
   -> Description Lists

-> Ordered Lists are the type of lists that has some sort of numbering in the form of 1,a,A,i.

   Syntax:-

         <ol type="1">  <!-- Here type we can enter 1, i, I, A, a by default 1 is taken>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
         </ol>
      
-> UnOrdered Lists are the type of lists that has no numbering but has just symbols

   Syntax :-

         <ul style="list-style-type="none">  <!-- we cannot type attribute we should use style attribute here we are applying inline css, we can use circle, none ,etc... -->
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
         </ul>

-> Description Lists are the type of lists that has both title and description

   Syntax :-

         <dl>
            <dt>Guitar</dt>
            <dd>Guitar is a 6 String musical Instrument</dd>

            <dt>Ukulele</dt>
            <dd>Ukulele is a 4 String musical Instrument</dd>
         <dl>

-> I also learned about text formatting html tags like <strong>,<em>,<mark>,<sub>,<sup>

-> Thankyou for reading.


[ 21 Sept 2026 ]

-> Today I learned about useful extensions that help developers

-> Live Server is an extension in vscode that helps developer to live update the webpage
   with change in code without the need to refresh the page.

-> Bracket Pair Color is an extension in vscode that helps developers to keep track of 
   the opening and closing brackets with unique colors without being ambigous. it is really
   helpful.

-> Prettier is an extension in vscode that formats the code into a neat identation.

-> An Exercise is given for today based on yesterday's learnings i will first create 
   mapping using pinta in ubuntu and then code for it.

-> Thankyou for reading.

[ 20 Sept 2026 ]

-> Today I learned about Html Structure

-> Html Structure is below like this

      <!DOCTYPE html>   <!-- This tells the browser that the below code is HTML Code -->
      <html>   <!-- It is the opening tag of html>
         <head>   <!-- It is the opening tag of head, it stores the meta information and external file links -->
         </head>  <!-- closing tag of head -->
         <body>   <!-- It is the opening tag of body, it contains the tags that are rendered by the browser in the webpage -->
         </body>  <!-- It is the closing tag of body -->
      </html>  <!-- It is the closing tag of htmll -->

-> Here Everytime entering the structure from scratch becomes a burden when we try to code everyday in html.

-> So, to fix this issue vscode provides a built-in plugin called emmet, we can just use [!+Enter] or [!+Tab] shortcuts.

-> To document our work in html, we can use html comments like this <!-- This is comment -->

-> In the tags, I learned about 

   -> Heading tags (h1,h2,h3,h4,h5,h6) , they decrease in their font-size from h1 ot h6.
   -> Paragraph tag (p), it is used to write content that is used to read for the users.

-> Sometimes we need bulk dummy data to experiment our code or test our code, for this emmet the built-in plugin 
   provided by vscode gives lorem ipsum.

-> loremn -> here n tells the total number of words after lorem. ( lorem50 -> it generates 50 random words ).

-> In the head tag, there meta tags, that provide information about the webpage.

   -> <meta charset="UTF-8"> normally in programming langagues like c, ASCII is used to represent all the characters
      but ASCII can only store english characters, what about other langauge characters to solve this problem UTF-8 encoding
      is introduced and this meta tag tells that we have access to all the characters in the world of any language.

[ 19 Sept 2026 ]

-> Today I learned about what Html and Css is.

-> Html stands for Hyper Text MarkUp Language, it is a markup language which uses tags to define elements.

-> Html is the skeleton of the Websites, All websites contains Html code.

-> CSS stands for Cascading Style sheets.

-> CSS is responsible for styling the Html webpages.

-> Here Cascading means different styles with different priorites fight with each other and the one with high
   priority will get the chance to apply the style to the Html page.

-> To remove css from a webpage we can use Web Developer Extension.

-> One Important thing i Learned is to keep Html and Css files seperately for better readability.

-> I learned about text editors like notepad, notepad++, bracket, sublime and vscode.

-> I am choosing vscode for this journey.

-> I downloaded and installed vscode in my ubuntu operating system from microsoft website.

-> I created a folder with name HTML_JOURNEY and opened it in vscode.

-> Today I am exploring the Web Developer Extension and Vscode.

-> Thankyou for reading.