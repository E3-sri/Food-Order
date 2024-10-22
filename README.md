<!Doctype html>
<html>
    <head>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    </head>
            <body>
                <div class="bg_image d-flex flex-column justify-content-end">
                    <div class="card">
                        <h1 class="mainheading"> Happy Meals</h1>
                        <p class="para"> Discover the best foods over the 1,000 <br>restaurants</p>
                        <button class="button"> Book Now</button>
                    </div>
                </div>
            </body>
</html>

@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.bg_image
{
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/foodbg.png");
    background-size:cover;
    height:100vh;
    width:100vw;
}
.card
{
   height:200px;
   background-color: #f6c56e; 
   text-align:center;
   padding:5px;
   border-top-left-radius: 5px;
   border-top-right-radius: 5px;
}
.mainheading
{
    text-align:left;
    font-family:Bree Serif ;
    margin-left: 20px;
    color:#323f4b
}
.para
{
    text-align:left;
    font-family: Roboto;
    font-weight: bold;
    color:#323f4b;
    margin:20px;
}
.button
{
    margin:20px;
    padding-left:20px;
    padding-right:20px;
    text-align:center;
    background:white;
    width:120px;
    height:40px;
    border-width: 0px;
    border-color: white;
    border-top-left-radius:5px;
    border-top-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border-bottom-right-radius:5px;
    margin-top:10px;

}
