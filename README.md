# EX01 Developing a Simple Webserver
## Date:
29.03.2024
## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="background-image: url(676781.png); background-size: cover ; background-repeat: no-repeat;" >
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <div style="display: flex; margin: 10px;">
    <div class="card" style="width: 18rem;">
        <img src="Once_Upon_a_Time_in_Hollywood_poster.png" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Once Upon a Time In Hollywood...</h5>
          <p class="card-text">Rick, a washed-out actor, and Cliff, his stunt double, struggle to recapture fame and success in 1960s Los Angeles. In their mission, they must tackle several twists and turns</p>
          <a href="https://www.primevideo.com/dp/amzn1.dv.gti.7c70c507-10a0-4f83-85dc-e31a12f15a5b?autoplay=0&ref_=atv_cf_strg_wb" class="btn btn-primary">Click to Watch</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="inception.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Inception</h5>
          <p class="card-text">Cobb steals information from his targets by entering their dreams. He is wanted for his alleged role in his wife's murder and his only chance at redemption is to perform a nearly impossible task.</p>
          <a href="https://www.primevideo.com/dp/amzn1.dv.gti.4eb1c578-2d81-f757-917d-e4c16fbbfebe?autoplay=0&ref_=atv_cf_strg_wb" class="btn btn-primary">Click to Watch</a>
        </div>
      </div>

        <div class="card" style="width: 18rem;">
            <img src="The_Aviator_(2004).png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">The Aviator</h5>
              <p class="card-text">After Howard Hughes' film becomes a success, he pursues the growing aviation industry. However, a mental health illness threatens his aspirations.</p>
              <a href="https://www.primevideo.com/dp/amzn1.dv.gti.72b868f7-30f6-1fd2-0def-bc26dc4d9265?autoplay=0&ref_=atv_cf_strg_wb"btn btn-primary">Click to Watch</a>
            </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="CmIFUCAN.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Catch me if you can</h5>
          <p class="card-text">Frank Abagnale Jr, a con man, poses as a pilot, doctor and a lawyer and cashes forged cheques worth millions before his 21st birthday, despite being constantly chased by FBI agent Carl Hanratty.</p>
          <a href="https://www.primevideo.com/dp/amzn1.dv.gti.76b3ec7c-f05c-d306-0677-6faf3231e2c8?autoplay=0&ref_=atv_cf_strg_wb"btn btn-primary">Click to Watch</a>
        </div>
    </div>
    <div class="card" style="width: 18rem;">
        <img src="Departed234.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">The Departed</h5>
          <p class="card-text">An undercover agent and a spy constantly try to counter-attack each other in order to save themselves from being exposed in front of the authorities. Meanwhile, both try to infiltrate an Irish gang.</p>
          <a href="https://www.primevideo.com/dp/amzn1.dv.gti.2cb54975-53dc-c440-2479-089f5cf66ec3?autoplay=0&ref_=atv_cf_strg_wb"btn btn-primary">Click to Watch</a>
        </div>
    </div>
</body>
</html>

## OUTPUT:
![alt text](snmp/output.png)

## RESULT:
The program for implementing simple webserver is executed successfully.
