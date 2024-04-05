<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="container">
        <h1>Survey Form</h1>
        <form id="survey-form">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" required>
            </div>
            <div class="form-group">
                <label for="gender">Gender:</label>
                <select id="gender" name="gender" required>
                    <option value="">Select</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>
            </div>
            <div class="form-group">
                <label for="feedback">Feedback:</label>
                <textarea id="feedback" name="feedback" rows="4" cols="50"></textarea>
            </div>
            <div class="form-group">
                <label>How did you hear about us?</label><br>
                <input type="radio" id="hear-website" name="hear" value="website">
                <label for="hear-website">Website</label><br>
                <input type="radio" id="hear-friend" name="hear" value="friend">
                <label for="hear-friend">Friend</label><br>
                <input type="radio" id="hear-advertisement" name="hear" value="advertisement">
                <label for="hear-advertisement">Advertisement</label>
            </div>
            <div class="form-group">
                <label>What services are you interested in?</label><br>
                <input type="checkbox" id="service-webdev" name="services" value="webdev">
                <label for="service-webdev">Web Development</label><br>
                <input type="checkbox" id="service-mobiledev" name="services" value="mobiledev">
                <label for="service-mobiledev">Mobile App Development</label><br>
                <input type="checkbox" id="service-design" name="services" value="design">
                <label for="service-design">Design Services</label>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>


