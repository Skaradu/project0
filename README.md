<!DOCTYPE html>
<html>
    <head>
        <title>My Webpage</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">
        <link rel="stylesheet" href="nesting.css">
        <link rel="stylesheet" href="inheritance.css">

        <style>
            table {
               border: 2px solid black;
               border-collapse: collapse;
               width: 30px
        }
            th, td {
               border: 1px solid black;
               padding: 5px;
               text-align: left;
        }
            th {
               background-color: lightgray;
        }

        div.box {
          text-align: left;
        }
        p {
          line-height: 1em;
        }
        @media (min-width: 500px) {
               body {
                   background-color: inherit;
                }
             }

             @media (max-width: 499px) {
                body {
                    background-color: magenta;
                 }
              }

        .row > div {
          padding: 5px;
          background-color: lightblue;
          border: 2px solid black;
          }

          p1::selection {
              color: red;
              background-color: yellow;
          }

        </style>
    </head>
   <body>
    <div class="container">
     <h1>My Webpage</h1>
       <div class="box">
           <img src="swot4.jpg" height="35%" width="30%">
       </div>

     <h2>Introduction</h2>

      <p1>Creating a Personal SWOT Analysis for Your Career
        When you need to assess a particular subject or decide how to overcome a challenge,
        it can be helpful to visualize all aspects of the situation.
        Learning how to use a SWOT analysis may help you form logical conclusions as you handle different decisions in your career.
        In this article, we will discuss the components of a SWOT analysis, why it is a useful tool and how to create a personal SWOT analysis.
      </p1>

    <h3>Profile</h3>
      <table>
           <tr>
               <th>Strengths</th>
               <th>Weaknesses</th>
               <th>Opportunities</th>
               <th>Threats</th>
           </tr>
           <tr>
               <td>List of your relevant strengths. </td>
               <td>Review your relevant weaknesses. </td>
               <td>Define any opportunities available to you. </td>
               <td>Understand any potential threats. </td>
            </tr>
          </table>

     <h4></h4>
          <div class="container">
            <div class="row">
             <div class="col-lg-3 col-sm-6">
              Strengths are your skills, abilities and qualifications.
             </div>
             <div class="col-lg-3 col-sm-6">
              Weaknesses; You can create an effective analysis.
             </div>
             <div class="col-lg-3 col-sm-6">
              Opportunities are external factors that can improve your situation.
             </div>
             <div class="col-lg-3 col-sm-6">
              Threats; Consider external factors that put you at a disadvantage, a small job market.
            </div>
         </div>

      <div>
          <p>These are strenghs list.</p>
          Strengths:
       <ul>
          <li>Bachelor's degree in computer science</li>
          <li>CS50 profesional certicate online training</li>
          <li>college internship with a LAN and WAN Database Center</li>
       </ul>
     </div>

     <div>
       <p>These are weaknesses list.</p>
          Weaknesses:
       <ol>
          <li>Difficulty developping training</li>
          <li>Finds it challenging to compete plans for clients</li>
          <li>Marketing experience</li>
       </ol>
     </div>

          <h5>Links</h5>
          <ul>
              <li><a href="http://www.cs50.harvard.edu/web/notes/1/">cs50 harvard education</a></li>
              <li><a href="http://www.edx.org/courses/">EdX courses</a></li>
              <li><a href="http://www.google.com">google</a></li>
              <li><a href="http://www.facebook.com">facebook</a></li>
          </ul>
        </div>

      <div class="success">This is a way to success.</div>

      <div class="warning">Passion and Inclusion lead to success.</div>

      <div class="error">I'm still learning.</div>

   </body>
</html>
