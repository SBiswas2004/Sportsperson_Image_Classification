<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>

  <!-- Header Image -->
  <img src="your-image.jpg" alt="Sportsperson Classification Demo" class="header-image" />

  <h1>🏅 Sportsperson Image Classification</h1>

  <h2>Project Description</h2>
  <p>
    This project is a machine learning-based web application that identifies specific sportspersons from uploaded facial images. 
    It uses classical image processing techniques along with a trained classification model to recognize individual athletes 
    such as cricketers, footballers, and tennis players. The system extracts facial features using wavelet transformation, 
    combines them with raw pixel data, and uses a pre-trained model to predict the name of the sportsperson.
  </p>

  <h2>How to Run the Project</h2>
  <ol>
    <li>Make sure you have Python 3.8+ installed on your system.</li>
    <li>Install the required dependencies using the command:
      <pre>pip install -r requirements.txt</pre>
    </li>
    <li>Start the Flask backend by running:
      <pre>python server.py</pre>
    </li>
    <li>Open the <code>app.html</code> file in your web browser to access the user interface.</li>
    <li>Upload an image of a sportsperson and view the predicted result on the page.</li>
  </ol>

</body>
</html>
