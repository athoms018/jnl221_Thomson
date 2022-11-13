<!-- Complete this worksheet in html and css. Instructions are as comments; you may use reference_sheet.html and the internet to jog your memory on html tags and css. -->

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Basic HTML</title>
        <link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,400,300,600,700&subset=latin,latin-ext' rel='stylesheet' type='text/css'>
        
        <style>
        
        p {
            color: #5A5A5A;
            font-size: 16px;
            font-family: 'Open Sans', serif;
            width: 50%;
        }
        #quote {
            color: magenta;
            font-style: italic;
            border: solid lightskyblue 2px;
    
        }

        #book {
            border: 1px gray;
        }


        #bargraph {
            border: 1px solid gray;
            padding-left: 10px;
            padding-bottom: 10px;
            width: 25%;
        }
        .bar_label {
            color: red;
        }
        #longest {
            width: 3px;
            height: 10px;
            background: gray;
            border: 1px solid red;
        }
        #longer {
            height: 5px;
            background: gray;
            border: 1px solid red;
        }
        #long {
            height: 100px;
            background: gray;
            border: 1px solid red;
        }

        </style>
    </head>
    
    <body>

    <h1>A little bit about me!</h1>
    
    <h2>My intro</h2>
    <p> 
    <strong>  
    <i>   
        My name is Adam Thomson and I am from Cazenovia New York. I am studying Broadcast and Digital Journalism and for fun I like to listen to music. My family is my parents and my brother.
    </strong> 
    </p>
    </i>
    <!-- Include: a brief intro to yourself -- where you're from, what you like to do for fun, what you're studying, and who your community or family is. -->
    <!-- Tags to use: <p>, <strong>, <i> -->
    

    <h2>My handles</h2>
    <p>
    <a>
        Instagram: adam_.thomson
        Snapchat: a_thomson78
    </a>
    </p>

           <!-- Include: at least two handles for your social media accounts -->
    <!-- Tags to use: <p>, <a> -->

    
    <h2> ~ Challenge: Why is my text maroon? ~</h2>
    <!-- Challenge! The text in your p tags is currently maroon. Figure out why and make it dark gray, using a hex code. (Hint: use google to find a hex code for a dark gray) -->

    <p>My text is maroon.</p>
   
    <h2>My favorite meme</h2>
    <img src="large_wink.png"></img>

    <!-- Include: "large_wink.png" as an image -->
    <!-- Tags to use: <img> -->
    <!-- Hint! Use 'reference_sheet.html', which you downloaded with this file, to remember how to include an image. -->
 
    
    <h2>Why I'm a great student</h2>
    <ul>
    <li>
        <strong>
          <ul>
             I have good study habits.  
          </ul> 
          <ul>
              I do my homework on time. 
          </ul>  
        
          <ul>I am a strong writer. </ul> 
           
            <ul>I am good at analyzing text.</ul>

          <ul>I am creative. </ul>   
        </strong>

    </li>
    <!-- Include: an unordered list -->
    <!-- Tags to use: <ul>, <li>, <strong> -->

    
    <h2>Top 3 most famous people from my hometown</h2>
    <ol>
        <li>
            <a>
                Anne Burrell </ol> 
              <ol>  Beezie Madden </ol>
             <ol>   Sarah Brown   </ol>

            </a>
        </li>
    <!-- Include: an ordered list -->
    <!-- Tags to use: <ol>, <li>, <a> -->


    <h2> ~ Challenge: Read my poetry ~</h2>
    <br>
        <p>
            Amazing
           <br> Diligent </br>
            Awesome
           <br> Marvelous </br>
        </p>
    </br>


    </br>
    <!-- Challenge! Use the internet to figure out what a <br> tag is. Write a short poem about your college experience so far. -->
    <!-- Tags to use: <p>, at least two <br> tags -->
        

    
    <h2>This is one of my favorite quotes</h2>
    <h3>J Cole</h3>
    <p>
    <i>
        "We aint picture perfect but we worth the picture still"
    </i>
    </p>

    <!-- Include: a quote from a book -- quote should be in italics and gray, title of source should be in an <h3> tag -->
    <!-- Tags to use: <h3>, <p> with an id named 'quote' that is styled in the <style> section -->


 <h2> These are more of my favorite books</h2>
   
  
    <ul>
        <li>
          <ul> Pet Semetary </ul>
          <ul>  Diary of a Wimpy Kid </ul>
      <ul>      Rich Dad Poor Dad </ul>
        </li>

    </ul>
    
    <!-- Include: an unordered list of at least three books, list items should have a border -->
    <!-- Tags to use: <ul>, <li> with classes named 'book' that is styled in the <style> section -->


    <h3>~ Challenge: A very simple bar graph ~</h3>
    <!-- Challenge! Add CSS styles to '#longer' and '#long' to make the bar graph look like it's ordered from longest to shortest. You may also change the h4 text and the p text to make this simple bar chart reflect real (or fake) data. -->

    <div id="bargraph">
        <h4>Length of bars</h4>
        <p class="bar_label">Long</p>
        <div id="longest"></div>
        <p class="bar_label">Longer</p>
        <div id="longer"></div>
        <p class="bar_label">Longest</p>
        <div id="long"></div>
    </div>
     
    </body>
</html>
