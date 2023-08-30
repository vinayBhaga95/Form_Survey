# Form_Survey
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Survey Form </title>
    <style>
        body {
            font-family: sans-serif;
        }
        th, td {
            padding: 10px;
        }
        label {
            margin-right: 20px;
        }
        button {
            margin: 2px;
        }
    </style>
</head>
<body>
    <h1> Food Preferences - Survey Form  </h1>
    <h5> please fill out and submit the survey form at the earliest</h5>
    <hr/> 
    <form action="" method="post">
        <table>
            <tr>
                <td>1. Name </td>
                <td><input type="text" name="user"></td>
            </tr>
            <tr>
                <td>2. Age </td>
                <td><input type="number" number="Age" min="13" max="100"></td>
            </tr>
            <tr>
                <td>3. Where do you eat most often ? </td>
                <td>
                    <input type="radio" id="home" name="location" value="home"/>
                    <label for="home"> at home </label>

                    <input type="radio" id="at work or school" name="location" value="at work or school"/>
                    <label for="at work or school"> at work or school </label>

                    <input type="radio" id="Restaurant" name="location" value="Restaurant"/>
                    <label for="Restaurant"> at Restaurant </label>

                </td>
            </tr>
            <tr>
                <td colspan="2">4. Specify, how often </td>
            </tr>
            <tr>
                 <td colspan="2">
                    <table style="border: 1px solid;">
                        <thead>
                            <th></th>
                            <th>every day </th>
                            <th>few times a week </th>
                            <th>once a week</th>
                            <th>several times a month</th>
                            <th>once a month</th>
                            <th>less often than a month</th>
                        </thead>
                        <tbody>
                            <tr>
                                <td>you prepare your own meals</td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="every_day"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="few times a week" /> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="once a week"/></td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="several times a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="once a month"/> </td> 
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="less oftet than a month"/> </td> 
                            </tr>

                            <tr>
                                <td>you eat out  </td>
                                <td style="text-align: center;"><input type="radio" name="you eat out" value="every_day"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you eat out" value="few times a week" /> </td>
                                <td style="text-align: center;"><input type="radio" name="you eat out" value="once a week"/></td>
                                <td style="text-align: center;"><input type="radio" name="you_eat out" value="several times a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_eat out" value="once a month"/> </td> 
                                <td style="text-align: center;"><input type="radio" name="you_eat out" value="less oftet than a month"/> </td> 
                            </tr>

                            <tr>
                                <td>you order food for home  </td>
                                <td style="text-align: center;"><input type="radio" name="you order food for home" value="every_day"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you order food for home" value="few times a week" /> </td>
                                <td style="text-align: center;"><input type="radio" name="you order food for home" value="once a week"/></td>
                                <td style="text-align: center;"><input type="radio" name="you order food for home" value="several times a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you order food for home" value="once a month"/> </td> 
                                <td style="text-align: center;"><input type="radio" name="you order food for home" value="less oftet than a month"/> </td> 
                            </tr>

                        </tbody>
                    </table>
                </td>
            </tr>
            <tr>
                <td colspan="2">5. The most common places you visit are Restaurant serving food of origin </td>
            </tr>
            <tr>
                <td colspan="2">
                    <table> 
                        <tr>
                             <td>
                                <input type="checkbox" id="polish" name="Food_origin_preference" value="polish"/>
                                <label for="polish">polish</label>

                             </td>
                             <td>
                                <input type="checkbox" id="Indian" name="Food_origin_preference" value="Indian"/>
                                <label for="Indian">Indian</label> 
                            </td>
                            <tr>
                                <td>
                                   <input type="checkbox" id="Itanlian" name="Food_origin_preference" value="Itanlian"/>
                                   <label for="Itanlian">Itanlian</label>
   
                                </td>
                                <td>
                                   <input type="checkbox" id="Spanish" name="Food_origin_preference" value="Spanish"/>
                                   <label for="Spanish">Spanish</label> 
                               </td>
                               <tr>
                                <td>
                                   <input type="checkbox" id="Asian" name="Food_origin_preference" value="Asian"/>
                                   <label for="Asian">Asian</label>
   
                                </td>
                                <td>
                                   <input type="checkbox" id="Chinese" name="Food_origin_preference" value="Chinese"/>
                                   <label for="Chinese">Chinese</label> 
                               </td>
                               <tr>
                                <td>
                                   <input type="checkbox" id="American" name="Food_origin_preference" value="American"/>
                                   <label for="American">American</label>
   
                                </td>
                                <td>
                                   <input type="checkbox" id="Others" name="Food_origin_preference" value="Others"/>
                                   <label for="Others">Others</label> 
                               </td>
                    </table>
                </td>
            </tr>
            <tr>
                <td>6. Given an option, would you go Vegan</td>
                <td> <input type="radio" name="Vegan" id="sure" value="sure"/><label for="sure ">sure</label>
                    <input type="radio" name="Vegan" id="NO" value="NO"/><label for="NO ">no </label>
                </td>
            </tr>
            <tr>
                <td><button>submit</button><button type="reset">reset </button></td>
            </tr>
        </table>
    </form>
       
</body>
</html>
