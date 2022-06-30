## Programming For Beginners: 10 Best HTML Coding Practices You Must Know

HTML…One of the easiest things to learn is programming. Most of the newbies and even kids step into programming picking up HTML. They learn, they build some web pages but a lot of developers even experienced one make some silly mistake while writing the code for frontend. Making these silly mistakes not only annoys other developers (when they need to make some changes) but also hurts your main site and drives the end-user away. We are going to mention some common and best practices which you should follow to write a clean and clear HTML code.  

Following some common practices makes debugging easier and saves a lot of time. It also helps in search engine optimization as well.  


1. Use Proper Document Structure With Doctype
HTML has nature that it will still render your markup correctly even if you forget to mention some elements such as <html>, <head>, <body> and <!DOCTYPE html>. You will see the correct result in your browser as you want but that doesn’t mean you will find the same result in every browser. To avoid this issue it’s a good habit to follow a proper document structure with the correct doctype. Doctype is the first thing to mention in an HTML document.


```
<!DOCTYPE html>
<html>
<head>
	<title>Hello World</title>
</head>
<body>
	<h1>Welcome Programmers</h1>
	
<p>This website is for Learner</p>


</body>
</html>

```

1. Close the Tags
To avoid validation and compatibility issue don’t forget to close all the tags in your code. Today most of the text editors come up with features that close the HTML tags automatically still, it’s a good practice(and definitely for final check) to make sure that you don’t miss any parent or nested tag that is not closed. In HTML5 it’s optional to close HTML tags but according to W3C specification, you should close all the HTML tags to avoid any validation error in the future.


```<div>
<div>
<div>
<p> Hello programmers</p>
<ul>
<li>Array</li>
<li>class</li>
<li>string</li>
</ul>
</div>
</div>
</div>
``` 


3. Write Tags in Lowercase
Make a habit to use lowercase for all the tags, attributes, and values in HTML code. It is an industry-standard practice and it also makes your code much more readable. Capitalizing the tags won’t affect the result in your browser but it’s a good practice to write elements in lowercase. Writing your code in lowercase is easy and it also looks cleaner.


```

<SECTION>
	
<p>This is a paragraph.</p>

</SECTION>


<section>
	
<p>This is a paragraph.</p>

</section>

``` 


4. Add Image Attributes
When you add an image in your HTML code don’t forget to add alt attribute for validation and accessibility reasons. Also, make sure that you choose the right description for the alt attribute. Search engines rank your page lower as a result when you don’t mention alt attributes with an image. It’s also good to mention the height and width of the image. It reduces flickering because the browser can reserve space for the image before loading.


```

<img src="html5.gif">


<img src="html5.gif"><img src="html5.gif" alt="HTML5" style="width:100px;height:100px">

``` 

5. Avoid Using Inline Styles
A lot of newbies make this mistake that they add inline-style in HTML tags. It makes your code complicated and difficult to maintain. Make a habit to keep your styles separate from HTML mark-up. Using inline styles can create so many problems. It makes your code cluttered, unreadable, and hard to update or maintain. Separating HTML with CSS also helps other developers to make changes in code very easily.


```

<p style="color: #393; font-size: 24px;">Thank you!</p>



<p class="alert-success">Thank you!</p>

``` 

6. Use a Meaningful Title and Descriptive Meta Tags
HTML title really matters a lot when it comes to search engine optimization or ranking of your page. Always try to make your title as meaningful as possible. The title of your HTML page appears in the google search engine result page and the indexing of your site relies on it. 
A meta description tells the user what the page is all about, so make it descriptive that clearly specifies the purpose of your website or page. Avoid using repeated words and phrases. When a user types some keyword in the search engine bar that keyword is picked up by the search engine spiders and then it is used to find the relevant page for users based on the matching keyword used in meta tags.


```
<meta charset="UTF-8" />
<meta
name="viewport"
content="width=device-width, initial-scale=1, maximum-scale=1"/>
<meta
name="description"
content="Here is a simple program for a learner."/>
<link
rel="shortcut icon"
href="https://technicalqueries.hashnode.dev/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1648566925340%2Fs8c-P0Zoa.webp%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=1920&q=75"
type="image/x-icon"/>
<link
href="https://technicalqueries.hashnode.dev/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1648566925340%2Fs8c-P0Zoa.webp%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=1920&q=75"
rel="stylesheet"/>
<meta name="theme-color" content="#0f9d58" />

<meta
property="og:image"
content=""/>
<meta property="og:image:type" content="image/png" />
<meta property="og:image:width" content="200" />
<meta property="og:image:height" content="200" />
<script src="paste the link here"></script>
<script src="link here"></script>

<title>TECHNICAL QUERIES</title>

``` 

7. Use Heading Elements Wisely
Heading tags also play a crucial role in making your website search engine-friendly. HTML has 6 different types of heading tags that should be used carefully. Learn to use h1 to h6 elements to denote your HTML’s content hierarchy also make sure that you use only one h1 per page. In W3C specs it is mentioned that your page content should be described by a single tag so you can add your most important text within h1 such as article title or blog post. 

```
<h1>Topmost heading</h1>
<h2>Sub-heading underneath the topmost heading.</h2>
<h3>Sub-heading underneath the h2 heading.</h3>
``` 


8. Always Use Right HTML Elements
A lot of beginners make a common mistake using the wrong HTML elements. They need to learn with time which element should be used where. We recommend you learn about all the HTML elements and use them correctly for a meaningful content structure. For example instead of using (br) between two paragraphs you can use CSS margin and/or padding properties. Learn when to use (em) and when to use (i) (both looks the same), learn when to use (b) and when to use (strong) (both looks the same). It comes with practice and when you keep your eyes on good code written by other developers. Another good example is given below.


```
<span class="heading"><strong>Hello programmer</span></strong>
<br><br>
This is Computer Science .
<br><br>
  

<h1>Hello programmer</h1>
  
  
<p>This is Computer Science.</p>
``` 


9. Proper Use of Indentation
it is important to give proper space or indentation in your HTML code to make it more readable and manageable. Avoid writing everything in one line. It makes your code cluttered and flat. When you use the nested element give proper indentation so that users can identify the beginning and end of the tag. A code that follows proper formatting is easy to change and looks nice to other developers. It’s a good coding practice that reduces development time as well. 


```
<aside>
<h3>Program</h3>
<h5>A computer science Program</h5>
<ul>
<li>Computer Science</li>
<li>Gate</li>
</ul>
</aside>
  

<aside>
  <h3>Program</h3>
  <h5>A computer science</h5>
  <ul>
    <li>Computer Science</li>
    <li>Gate</li>
  </ul>
</aside>
``` 

10. Validate Your Code
Last but not least make a habit to validate your HTML code frequently. Validating your code is a great piece of work and helps in finding difficult issues. You can download the W3C markup validation or Firefox developers toolbar to validate your site by URL. Validators are very helpful in detecting errors and resolving them.


