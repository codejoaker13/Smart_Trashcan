
This Smart Trashcan code uses an ESP32, an ultrasonic sensor, and a servo motor to create a touchless, automatic lid opening system. Here's how it functions:

  ○    Ultrasonic Sensor: The sensor measures the distance of an object in front of the trashcan (likely a person’s hand). It sends out an ultrasonic pulse and measures the time it takes for the pulse to return.
  
  ○   Distance Calculation: The code calculates the distance based on the pulse duration. If the distance is less than a defined threshold (50 cm), the trashcan assumes someone is nearby.

  ○  Servo Motor Control: When a person is detected, the servo motor rotates to 90 degrees, simulating the trashcan lid opening. After the person leaves (i.e., the distance is greater than the threshold), the servo returns to 0 degrees, closing the lid.

  ○  Serial Output: The distance is printed to the serial monitor for debugging purposes, showing the real-time distance to the detected object.

This system is a simple, effective solution for a touchless smart trashcan, improving hygiene and convenience.
