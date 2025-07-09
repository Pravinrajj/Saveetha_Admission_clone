# Saveetha_Admission_clone
## Date:

## Objective:
To design a landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS. This activity reinforces skills in layout design, form creation, user input handling, responsive structure, and visual styling based on a real-world example.

## Tasks:
#### 1. Analyze the Landing Page Layout:
Observe the split-screen layout with a promotional section on the left and a form on the right.

Note the use of background images, text styling, and branding elements.

#### 2. Create the HTML Structure:
Use semantic tags like ```<section>, <header>, <form>, and <footer>``` to organize content.

Structure the form with input fields such as name, email, phone, password, city, state, course, specialization, captcha, and checkbox.

#### 3. Add Form Functionality:
Include appropriate input types (text, email, tel, password, select, etc.) with placeholders and labels.

Use the <button> element for the "APPLY NOW" action.

#### 4. Apply CSS Styling:
Implement a split layout using flexbox or grid.

Style the form elements with padding, shadows, background colors, and rounded borders.

Include hover effects and button transitions to match the original look.

#### 5. Incorporate Images and Branding:
Add the institution logo and use matching fonts and colors.

Place a background image or blurred overlay behind the form content if needed.

#### 6. Ensure Responsiveness:
Make sure the page adapts to different screen sizes using media queries.

Maintain readability and layout integrity on both desktop and mobile.

## HTML Code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Saveetha Engineering College</title>
</head>
<body>
    <div class="content">
        <div class="container">
            <div class="admform">
                <h1>Admissions Open 2025</h1>
                    <div class="form">
                        <form>
                            <div class="form-group">
                                <label for="name"></label>
                                <input id="name" type="text" placeholder="Enter Name *">
                            </div>
            
                            <div class="form-group">
                                <label for="email"></label>
                                <input id="email" type="email" placeholder="Enter Email Address *">
                            </div>
                            <div class="phone">
                                <div class="form-g">
                                    <label for="std"></label>
                                    <select id="std">
                                        <option>+91</option>
                                        <option>+12</option>
                                    </select>
                                </div>
                
                                <div class="form-g">
                                    <label for="phone"></label>
                                    <input id="phone" type="number" placeholder="Enter Mobile Number *">
                                </div>
                            </div>
            
                            <div class="form-group">
                                <label for="pass"></label>
                                <input id="pass" type="password" placeholder="Any Password of Your Choice *">
                            </div>
                            <div class="add">
                                <div class="form-group">
                                    <label for="state"></label>
                                    <select id="state">
                                        <option>State *</option>
                                        <option>Tamil Nadu</option>
                                    </select>
                                </div>
                
                                <div class="form-group">
                                    <label for="city"></label>
                                    <select id="city">
                                        <option>City *</option>
                                        <option>Chennai</option>
                                        <option>Madurai</option>
                                        <option>Theni</option>
                                    </select>
                                </div>
                            </div>
            
                            <div class="form-group">
                                <label for="course"></label>
                                <select id="course">
                                    <option>Course *</option>
                                    <option>B.E</option>
                                    <option>B.Tech</option>
                                </select>
                            </div>
            
                            <div class="form-group">
                                <label for="dept"></label>
                                <select id="dept">
                                <option>Specialization *</option>
                                <option>CSE</option>
                                <option>AIML</option>
                                <option>AIDS</option>
                                </select>
                            </div>
            
                            <div class="form-group checkbox">
                                <input type="checkbox" id="check">
                                <label for="check">I accept terms & conditions *</label>
                            </div>
            
                            <button type="button">Apply</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
```
## CSS Code:
```css
    body{
    margin: 0;
    color: whitesmoke;
    background-image: url(bgimg.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size:cover;
}

.content{
    width:100%;
    height: 650px;
    object-fit: cover;
}

.container {
    display: flex;
    justify-content: end;
}

.form-group {
    display: flex;
    flex-direction: column;
    margin-bottom: 15px;
}

.form-g {
    width: 100%;
}

.add {
    width: 100%;
    display: flex;
    justify-content: space-between;
}

#city {
    width: 200%;
}

#state {
    width: 200%;
}

.phone {
    display: flex;
    flex-direction: row;
    margin-bottom: 15px;
}

.admform{
    margin: 1px 20px 0px 0px;
    background-color: rgba(0, 0, 0, 0.6);
    padding: 10px 50px;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    width: 220px;
    height: 625px;
}

.form{
    height: 800px;
    width: 100%;
}

h1{
    text-align: center;
    font-size: 24px;
    margin-bottom: 20px;
}

input,select{
    margin: 0 -20px;
    padding:10px;
    border:none;
    border-radius: 5px;
    font-size: 14px;
}

:placeholder-shown{
    color: rgba(0, 0, 0, 0.1);
}

input[type="checkbox"] {
    width: auto;
    margin-right: 10px;
}

.checkbox {
    display: flex;
    align-items: center;
}

button {
    padding: 12px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}
```
## Output:
![image](https://github.com/user-attachments/assets/127d6e3c-4fb5-4f7c-b3a7-a66015c24f32)

## Result:
A landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS is designed successfully.
