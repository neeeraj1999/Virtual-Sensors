<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>IoT Assignment 3</h1>
    </header>
    
  <section>
      <h2>By</h2>
      <p>Neeraj Patil</p>
      <p>SUID: 404910861</p>
  </section>
  
  <section>
      <h2>Overview</h2>
      <p>This involves setting up a simulated IoT environment using ESP32 with MicroPython on Wokwi and publishing sensor data to ThingSpeak. The simulation includes virtual sensors for monitoring temperature, humidity, and CO2 levels.</p>
  </section>
  
  <section>
      <h2>Pre-requisites</h2>
      <ul>
          <li>Wokwi account for ESP32 simulation.</li>
          <li>ThingSpeak account for data visualization.</li>
      </ul>
  </section>
  
  <section>
      <h2>Setup Instructions</h2>
      <h3>1. Wokwi Setup</h3>
      <ol>
          <li>Sign up or log in to Wokwi.</li>
          <li>Create a new ESP32 MicroPython project.</li>
          <li>Include a DHT22 sensor and LEDs in your diagram if needed.</li>
      </ol>

  <h3>2. ThingSpeak Channel Creation</h3>
  <ol>
      <li>Log into ThingSpeak and create a new channel.</li>
      <li>Add fields for Temperature, Humidity, and CO2.</li>
      <li>Note down the channel ID and other credentials.</li>
  </ol>

  <h3>3. MQTT Configuration</h3>
  <p>Use Python to configure MQTT clients and ensure proper authentication using the umqtt library.</p>

  <h3>4. Code Configuration</h3>
  <p>Insert your ThingSpeak and Wi-Fi credentials into the provided code.</p>

  <h3>5. Simulation Execution</h3>
  <p>Paste the code into Wokwi's editor and run it. The simulation will output sensor data every 20 seconds.</p>

  <h3>6. ThingSpeak Visualization</h3>
  <p>Access your ThingSpeak channel to view the data and utilize ThingSpeak's tools for further data analysis.</p>
  </section>
  
</body>
</html>