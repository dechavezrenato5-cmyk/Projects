<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Survey Form</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <main>
    <h1 id="title">Community Feedback Survey</h1>
    <p id="description">We value your feedback! Please take a minute to fill out this survey.</p>

    <form id="survey-form">
      <!-- Name -->
      <label id="name-label" for="name">Name</label>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required>

      <!-- Email -->
      <label id="email-label" for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Enter your email address" required>

      <!-- Number -->
      <label id="number-label" for="number">Age</label>
      <input type="number" id="number" name="age" min="10" max="100" placeholder="Enter your age">

      <!-- Dropdown -->
      <label for="dropdown">Which option best describes you?</label>
      <select id="dropdown" name="role" required>
        <option disabled selected value="">Select one</option>
        <option value="student">Student</option>
        <option value="professional">Professional</option>
        <option value="other">Other</option>
      </select>

      <!-- Radio buttons -->
      <p>Would you recommend us to a friend?</p>
      <label><input type="radio" name="recommend" value="yes" required> Yes</label>
      <label><input type="radio" name="recommend" value="no"> No</label>

      <!-- Checkboxes -->
      <p>What features do you like? (Select all that apply)</p>
      <label><input type="checkbox" name="features" value="design"> Design</label>
      <label><input type="checkbox" name="features" value="usability"> Usability</label>
      <label><input type="checkbox" name="features" value="performance"> Performance</label>

      <!-- Textarea -->
      <label for="comments">Additional Comments</label>
      <textarea id="comments" name="comments" rows="4" placeholder="Enter your comments here..."></textarea>

      <!-- Submit Button -->
      <button type="submit" id="submit">Submit</button>
    </form>
  </main>
</body>
</html> 
