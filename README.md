# Ex-06-Book-Cover-Design

NAME : P.KEERTHANA

REFERENCE NUMBER : 23011895

DEPARTMENT : AIML

AIM :
To design a book cover page using HTML and CSS.

PROCEDURE :
STEP 1 : HTML Structure
Ensure proper HTML structure with , , and tags.

STEP 2 : Container Styling
Style .bookpage with fixed dimensions, centered margins, and a background image.

STEP 4 : Book Title
Center and style book title with padding and flexbox.

STEP 5 : Author Section
Style author text (author) with appropriate font size and indentation. Add a bottom orange horizontal line (bottomhr) below author information.

STEP 6 : Image Styling
Style author image (img) with fixed width, height, and margin.

STEP 7 : End the HTML structure
Run the code.

CODE :
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Book Coverpage</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("Background.jpg");
             background-position: center;
             background-color: black;
             background-repeat: no-repeat;
         }
         .toptext{
             color:white;
             padding-left: 5px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;
             
         }
         .tophr{
             color: orange;
              width: 180px;
         }
         hr{
             color: orange;
            
         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
             align-items: center;
             justify-content: center;
             margin-right: 10px;
             margin-left: 10px;
             font-size: 20px;
             line-height:normal;
         }
         .author{
             color:white;
             display:inline;
             position:relative;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             line-height: 5px;
              
             
         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

            
            
  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }
  
.footer {
    color:orange;
    padding-top:180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    margin-right: px;
}
.bottomhr { 
    color: red;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align:bottom;
}
.edition {
    color:orange;
             font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    line-height: bottom;
 
}


        </style>
        </head>
            <body>
                <div class="bookpage">
                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXPERT INSIGHT</div>
                    <div class="tophr"><hr></div> 
               <div class="booktitle"><h1> Responsive Web Design with HTML5 and CSS </h1></div>
               <h3 class="sub-text">&nbsp;&nbsp;&nbsp;Develop future-proof responsive websites</h3>
                    <h3 class="sub-text">&nbsp;&nbsp;&nbsp;using the latest HTML5 and CSS designs</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;Third Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="author.png"></h2>              
                      
                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Ben Frain &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Packt></h3></div>
                    
                </div>
                </div> 
                
            </body>
        
    
</html>

OUTPUT :
Alt text

RESULT :
The book cover design has been successfully created using HTML and CSS.