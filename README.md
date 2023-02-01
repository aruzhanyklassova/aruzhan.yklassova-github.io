<!DOCTYPE html>[lab3.zip](https://github.com/aruzhanyklassova/aruzhan.yklassova-github.io/files/10558367/lab3.zip)

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="main.css">
  <title>CSS Design</title>[lab3.zip](https://github.com/aruzhanyklassova/aruzhan.yklassova-github.io/files/10558370/lab3.zip)

<div style="background-color:beige;padding:20px;">
      <style>
        img {display: block;
margin-left: auto;
margin-right: auto;
border: 2px double hotpink}
 .red {color:red;}
 .purple {color:hotpink;}
 .blue {color:skyblue;}
  #style {font-style:italic;}
    
a:link {
  color: violet;
}

a:visited {
  color: blueviolet;
}

a:hover {
  color: darkviolet;
}

a:active {
  color: mediumvioletred;
}
  }
  h2 [name] {color: green}
  }
body{background-color:beige}
h1 {text-align: center;
font-family: Arial;
font-size:50px}

</style>
</head>
<body>
  <!-- HEADER -->
  <header>
    <div class="banner">Web Programming...</div>
  </header>

  <!-- Navbar -->
  <nav>
      <a class="logo" href="#">
        <img src="nu_logo.png" alt="logo" width="80px" height="80px">
      </a>

      <ul class="menu">
        <li><a class="active" href="#task">Task</a></li>
        <li><a href="#requirements">Requirements</a></li>
        <li><a href="#submission">Submission</a></li>
        <li><a href="#grading">Grading</a></li>
        <li><a href="#deadline">Deadline</a></li>
        <li><a href="#">SignIn</a></li>
      </ul>
  </nav>

  <!-- Main Content -->
  <section class="main_content">
    <h1 id="main-heading" class="topic">
      Lab 4 - Designing with CSS 
    </h1>
    <hr>
    <article id="task">
      <h2 >Task</h2>
      <p>
        <img src="cs.jpg" alt="" width="300px" height="210">
        As you have alredy learned in the last lecture, 
        CSS is about the presentation of the documents
        like HTML or XML.
        You need to apply
        CSS styling rules to make this template HTML file look
        beautiful and interesting.  
      </p>
      <p>
        There are no 
        limits to what techniques you use and how you 
        ultimately solve this task. 
        However, there are some minimal requirements
        which are explained in the next section below.
        <a href="#requirements">Next...</a>
      </p>
    </article>
    <article id="requirements" class = "red">
      <h2 >Requirements</h2>
      <p>
        
        The main requirement for this task is to 
        style this HTML document without any 
        changes (including adding new and deleting the existing elements) to itself except for these cases: 
        <ul>
          <li>
            You can add <strong>id</strong>
            and <strong>class</strong> 
            attributes to the ncessary elements. 
            </li>
            <li>
            You can replace the 
            images in the defined elements within this document with your
            own ones. 
            </li><li>
            Notice that there is a place for a 
            large banner on the top of the page,
            you <strong>must</strong> place an image there only using CSS.
            </li>
            <li>
              You <strong>must</strong> write your names in the specified fields below.
            </li>
            <li>You can change the location
              of in the map below or replace it with the image.
            </li>
        </ul>
      </p>
      <p>
        In your stylesheet you <strong>must</strong>
         use these selectors:
        <ul>
          <li>Element selectors;</li>
          <li>Class selectors;</li>
          <li>Attribute selectors;</li>
          <li>ID selectors.</li>
          <li>Pseudo-class selectors.</li>
        </ul>
      </p>
      <p>
        Also, you <strong>must</strong> 
        use the necessary CSS properties
        and demonstrate the following changes
        of the elements:
        <ul>
          <li>font and background colors;</li>
          <li>font family and size;</li>
          <li>margin, padding and borders;</li>
          <li>image sizes (width and height);</li>
          <li>text alignment (horizontal and vertical);</li>
        </ul>
        Additionally, a special focus <strong>must</strong> 
        be done to the menu links.        
        They need to change their status appropriately 
        (active, hover, visited)
        as well as be placed in a natural way,
        i.e. horizontally or vertically. 
        <a href="#submission">Next...</a>
      </p>
    </article>
    <article id="submission" class = "purple" id="size"> 
      <h2>Submission</h2>
      <p>
       As usual, you <strong>must</strong> submit 
       your work via Github. All the files and images need to go to 
       your <strong> <i>username.github.io</i> </strong>repository. 
       Also, this page must be available 
       through this domain name.
      </p>
      <h3>Info</h3>
      <p>
         Insert an image of yourself here.
         <img src="ya.jpg" alt="" width="240px" height="270">

        <ul>
          <li>Aruzhan Yklassova </li>
          <li> <a href="https://instagram.com/aruzhany22?igshid=YmMyMTA2M2Y="> My instagram page </a></li>
        </ul>
      </p>
    </article>
    <article id="grading"class = "blue">
      <h2>Grading</h2>
      For this assignment you will get 
      <strong>70 points</strong>  in total.
      The final score is the sum of the points 
      for each of the criteria below.
      <table>
        <tr>
          <th>Criteria</th>
          <th>Points</th>
        </tr>
        <tr>
          <td>CSS file is linked to the document</td>
          <td>5 pts</td>
        </tr>
        <tr>
          <td>Banner image is present</td>
          <td>5 pts</td>
        </tr>
        <tr>
          <td>Menu is styles appropriately</td>
          <td>5 pts</td>
        </tr>
        
        <tr>
          <td>Photo is present </td>
          <td>5 pts</td>
        </tr>
         <tr>
          <td>HTML file is unchanged</td>
          <td>5 pts</td>
        </tr>
        <tr>
          <td>Required selectors are used</td>
          <td>10 pts</td>
        </tr>
        <tr>
          <td>Required CSS properties are used</td>
          <td>10 pts</td>
        </tr>
        <tr>
          <td>Website is available online</td>
          <td>10 pts</td>
        </tr>
        <tr>
          <td>Website looks nice and not broken</td>
          <td>10 pts</td>
        </tr>
        <tr>
          <td>Extra cool stuff is used</td>
          <td>5 pts</td>
        </tr>
        </tr>
      </table>
    </article>
  </section>

  <!-- Aside Information -->
  <aside>
    <h3>Important</h3>
    <section class="aside_content">
      <article id="deadline">
        <h4>Deadlines:</h4>
        <ul>
          <li>Soft deadline: Jan. 31, 2023, 23:59</li>
          <li>Hard deadline: Feb. 2, 2023, 23:59</li>
        </ul>
        <p>
        <a href="#">More...</a>
      </article>
      </section>
     
        <h3>Some Dummy Content</h3>
       <section>
        <article>
        <h4>Article 1</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, 
          adipisicing elit. Odit, fugiat eveniet! 
          Optio quia perspiciatis earum ipsa dicta 
          porro dolorum facere laudantium repellat 
          ad necessitatibus asperiores dolor, molestias 
          officiis corrupti iusto.
          <a href="#">More...</a>
        </p>
      </article>
      <article>
        <h4>Article 2</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, 
          adipisicing elit. Odit, fugiat eveniet! 
          Optio quia perspiciatis earum ipsa dicta 
          porro dolorum facere laudantium repellat 
          ad necessitatibus asperiores dolor, molestias 
          officiis corrupti iusto.
          <a href="#">More...</a>
        </p>
      </article>
      <article>
        <h4>Article 3</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, 
          adipisicing elit. Odit, fugiat eveniet! 
          Optio quia perspiciatis earum ipsa dicta 
          porro dolorum facere laudantium repellat 
          ad necessitatibus asperiores dolor, molestias 
          officiis corrupti iusto.
          <a href="#">More...</a>
        </p>
      </article>
    </section>
  </aside>

  <!-- FOOTER -->
  <footer id="style">
    <div class="contacts">
      <div >
        <h5>Contacts</h5>
        <p>
          Nazarbayev University <br>
          53 Kabanbay Batyr ave. <br>
          Block 7, Room 7.422 <br>
          Ph.: +7-7172-123-4567 <br>
          <a href="mailto:info@naturallyinspired.com" class="email">
            info@naturallyinspired.com
          </a>
        </p>
      </div>
      <div class="map">
          <iframe src="https://maps.google.com/maps?q=Nazarbayev%20university,%20Nur-Sultan&t=&z=13&ie=UTF8&iwloc=&output=embed" 
                  frameborder="0" scrolling="no" marginheight="0" marginwidth="0">
          </iframe>
      </div>
    </div>
    <div class="categories">
      <h5>Top 10 Categories</h5>
      <ul>
        <li><a href="#">Category 1</a></li>
        <li><a href="#">Category 2</a></li>
        <li><a href="#">Category 3</a></li>
        <li><a href="#">Category 4</a></li>
        <li><a href="#">Category 5</a></li>
        <li><a href="#">Category 6</a></li>
        <li><a href="#">Category 7</a></li>
        <li><a href="#">Category 8</a></li>
        <li><a href="#">Category 9</a></li>
        <li><a href="#">Category 10</a></li>
      </ul>
    </div>
    <div class="quick_links">
      <h5>Quick Links</h5>
      <ul>
        <li><a href="#">Item1</a></li>
        <li><a href="#">Item2</a></li>
        <li><a href="#">Item3</a></li>
        <li><a href="#">Item4</a></li>
        <li><a href="#">Item5</a></li>
        <li><a href="#">Item6</a></li>
      </ul>
    </div>
  </footer>
</body>
</html>
