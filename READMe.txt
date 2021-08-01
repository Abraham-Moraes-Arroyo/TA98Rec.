This is the layout of the web page that allows the user 
to click on the div tags instead of having to make different 
html files that will only slow us down. 

Home=home page
Form= post a job
Data=Recruiting Services
Map= Diversity Practice 
About= Events  
Bird = About Us
Sketcher = Contact us

Get the photo for the home page, we are going for a black and white look so take one from their web page
*I got the photo*

This is the code for the search bar, I am going to get the card template from bootstrap and then center it:

<div class="input-group rounded">
  <input type="search" class="form-control rounded" placeholder="Search" aria-label="Search"
    aria-describedby="search-addon" />
  <span class="input-group-text border-0" id="search-addon">
    <i class="fas fa-search"></i>
  </span>
</div>

* I already got the search bar working*

Now I am going to get to the part where I need to make "blog" where I can post a job entry.
I still have the coloumns where I can individually enter a post. I also need to have an about us tag at the 
far right where text will be placed. 


This is for the login 

https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_login_form_modal


Code for the sign up 


<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <div class="form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>

