<!-- 
Registration Form HTML/CSS
This repository contains a simple registration form created using HTML and CSS. The form collects basic information such as name, email, mobile number, date of birth, gender, and address.

Once you have the form open in your web browser, you can:

Fill in your details in the respective fields.
Ensure all required fields are filled before submitting the form.
Click on the "Submit" button to submit the form (Note: The form does not have any backend functionality in this example).
Contributing
 -->
<!-- main container -->
    <div class="container">
    <!-- heading of registration from -->
        <div class="text">
            Registration Form
        </div>
<!-- here we had use the form tag to take input from the client or user   ............
here method is post because when ever we not declare the any method in the form it get method is as the all the input are getted load to a url but by using the post method data not render to url -->
        <form action="#" method="post" class="ff">
            <div class="input">
            <!-- input here mainly use to take the input  and placeholder is type of temporary value by the user can understand what they have to fill and it is type attribute of input tag-->
                <input type="text" name="" id="" 
                placeholder="Enter Your Name" required>
            </div>

            <div class="input">
                <input type="email" name="" id="" placeholder="Enter Your Email" required>
                <!-- required - it is also attribute of the input tag which generaly to indicate the user that perticilar feild is important -->
            </div>
            <div class="input">
                <input type="number" pattern="[0-9]{10}" name="" id="" placeholder="Mobile" required>
            </div>
            <div class="input">
                <input type="date" class="in" id="" placeholder="Enter Your DOB" required>
            </div>
            <div class="input">
            <!-- label we use mainly to give name relaed to the input feild -->
                <label for="gender">
                    <p>Gender : </p>
                    Male : <input type="radio" name="gender" id="" required class="ww">
                    Female : <input type="radio" name="gender" id="" required class="ww">
                </label>
            </div>
            <div class="input">
                <textarea name="" id="" cols="30" rows="1" placeholder="Enter Your Address"></textarea>
                <!-- <input type="textarea" name="" id="" placeholder="Enter Your DOB" required> -->
            </div>
</form>
            <!-- button tag mainly generate the button by which user can submit there form and couild we redirected to the page -->
                <button type="submit"><a href="#">Submit</a></button>
           




    </div>