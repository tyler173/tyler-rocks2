<html>
  <head>
<link href="//netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//netdna.bootstrapcdn.com/bootstrap/3.0.0/js/bootstrap.min.js"></script>
<script src="//code.jquery.com/jquery-1.11.1.min.js"></script>
  </head>
<!------ Include the above in your HEAD tag ---------->
  <body>
    <h1 class = "container">Programming Fansite:</h1>
    <div class="container">
        <div class="row">
            <div class="col-xs-12 col-sm-12 col-md-4 well well-sm">
                <legend><a href="http://www.jquery2dotnet.com"><i class="glyphicon glyphicon-globe"></i></a> Sign up!</legend>
                <form action="#" method="post" class="form" role="form">
                <div class="row">
                    <div class="col-xs-6 col-md-6">
                        <input class="form-control" name="firstname" placeholder="First Name" type="text"
                            required autofocus />
                    </div>
                    <div class="col-xs-6 col-md-6">
                        <input class="form-control" name="lastname" placeholder="Last Name" type="text" required />
                    </div>
                </div>
                <input class="form-control" name="youremail" placeholder="Your Email" type="email" />
                <input class="form-control" name="password" placeholder="Your Password" type="password" />
                <input class="form-control" name="reenteremail" placeholder="Re-enter Password" type="password" />
                
                <label for="">
                    Birth Date</label>
                <div class="row">
                    <div class="col-xs-4 col-md-4">
                        <select class="form-control">
                            <option value="Month">Month</option>
                            <option value="Month">01</option>
                            <option value="Month">02</option>
                            <option value="Month">03</option>
                            <option value="Month">04</option>
                            <option value="Month">05</option>
                            <option value="Month">06</option>
                            <option value="Month">07</option>
                            <option value="Month">08</option>
                            <option value="Month">09</option>
                            <option value="Month">10</option>
                            <option value="Month">11</option>
                            <option value="Month">12</option>
                        </select>
                    </div>
                    <div class="col-xs-4 col-md-4"> 
                        <select class="form-control">
                            <option value="Day">Day</option>
                            <option value="Day">01</option>
                            <option value="Day">02</option>
                            <option value="Day">03</option>
                            <option value="Day">04</option>
                            <option value="Day">05</option>
                            <option value="Day">06</option>
                            <option value="Day">07</option>
                            <option value="Day">08</option>
                            <option value="Day">09</option>
                            <option value="Day">10</option>
                            <option value="Day">12</option>
                            <option value="Day">13</option>
                            <option value="Day">14</option>
                            <option value="Day">15</option>
                            <option value="Day">16</option>
                            <option value="Day">17</option>
                            <option value="Day">18</option>
                            <option value="Day">19</option>
                            <option value="Day">20</option>
                            <option value="Day">21</option>
                            <option value="Day">22</option>
                            <option value="Day">23</option>
                            <option value="Day">24</option>
                            <option value="Day">25</option>
                            <option value="Day">26</option>
                            <option value="Day">27</option>
                            <option value="Day">28</option>
                            <option value="Day">29</option>
                            <option value="Day">30</option>
                            <option value="Day">31</option>
                        </select>
                    </div>
                    <div class="col-xs-4 col-md-4">
                        <select class="form-control">
                            <option value="Year">Year</option>
                            <option value="Year">1967</option>
                            <option value="Year">1968</option>
                            <option value="Year">1969</option>
                            <option value="Year">1970</option>
                            <option value="Year">1971</option>
                            <option value="Year">1972</option>
                            <option value="Year">1973</option>
                            <option value="Year">1974</option>
                            <option value="Year">1975</option>
                            <option value="Year">1976</option>
                            <option value="Year">1977</option>
                            <option value="Year">1978</option>
                            <option value="Year">1979</option>
                            <option value="Year">1980</option>
                            <option value="Year">1981</option>
                            <option value="Year">1982</option>
                            <option value="Year">1983</option>
                            <option value="Year">1984</option>
                            <option value="Year">1985</option>
                            <option value="Year">1986</option>
                            <option value="Year">1987</option>
                            <option value="Year">1988</option>
                            <option value="Year">1989</option>
                            <option value="Year">1990</option>
                            <option value="Year">1991</option>
                            <option value="Year">1992</option>
                            <option value="Year">1993</option>
                            <option value="Year">1994</option>
                            <option value="Year">1995</option>
                            <option value="Year">1996</option>
                            <option value="Year">1997</option>
                            <option value="Year">1998</option>
                            <option value="Year">1999</option>
                            <option value="Year">2000</option>
                            <option value="Year">2001</option>
                            <option value="Year">2002</option>
                            <option value="Year">2003</option>
                            <option value="Year">2004</option>
                            <option value="Year">2005</option>
                            <option value="Year">2006</option>
                            <option value="Year">2007</option>
                            <option value="Year">2008</option>
                            <option value="Year">2009</option>
                            <option value="Year">2010</option>
                            <option value="Year">2011</option>
                            <option value="Year">2012</option>
                            <option value="Year">2013</option>
                            <option value="Year">2014</option>
                            <option value="Year">2015</option>
                            <option value="Year">2016</option>
                            <option value="Year">2017</option>
                            <option value="Year">2018</option>
                            <option value="Year">2019</option>
                        </select>
                    </div>
                </div>  
                <label class="radio-inline">
                    <input type="radio" name="sex" id="inlineCheckbox1" value="male" />
                    Male
                </label>
                <label class="radio-inline">
                    <input type="radio" name="sex" id="inlineCheckbox2" value="female" />
                    Female
                </label>
                <br />
                <br />
                <button class="btn btn-lg btn-primary btn-block" type="submit">
                    Sign up</button>
                </form>
            </div>
        </div>
      </div>
  </body>
</html>
