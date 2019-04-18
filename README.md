# smart-store
The Store Management Project comprises of several ways of handling the availability of the items which are empty and can be refilled automatically. Few goods should be refilled manually.  A store consists of infinite racks where products are displayed and these racks are manually checked for the availability of the goods. In order to reduce manpower, automatic instructions are sent to the staff member through a buzzer, also these instructions are displayed on the LCD screen with the full details of the rack that needs stock replenishment. By looking at these notifications on the LCD screen, the staff member refills the items in that particular row. The ultrasonic sensor is used to detect whether the row is empty or not. The second module is on the basis of a container box. LDR is placed inside the container box at the top edge and a light base is situated at the bottom of the container box. When the items get empty, the light from the light base reflects on the LDR, which further detects the light and operates the servo motor. The Servo motor opens the cap for a minimum amount of time, that has to be set so that the container gets re-filled automatically. The container gets connected to the automatic crate system where the left stock is placed and the servo motor closes after a given amount of time. Therefore, in this operation, the store doesn't require any manpower to refill the items. However, in the last module, loose product items are measured by the product weight. The load cell is used to measure the product weight and triggers the buzzer to ring when the product weight decreases by the set weight on that basket, also an instruction stating that the basket needs refilling, is displayed on the LCD screen. 

BASIC COMPONENTS:

ARDUINO UNO 
Buzzer
16x2 LCD 
Breadboard
Ultrasonic sensor
LDR sensor
Servo motor
Light base
Load cell
HX711 Load cell amplifier
USB cable
Connecting Wires
Nut Bolts, Frame and base
Potentiometer
button

In the first module, whenever the rack is empty of a particular product in a particular row of the store, the ultrasonic sensor is used to detect the presence of the goods and sends an indication to the staff member by ringing a buzzer and also displays the row number details on the LCD screen. The second module is based on the container box items when the stock becomes empty, it re-filled automatically by using a crate system connected to the container box and opens the cap by using a servo motor. In this module, servo motor runs on the basis of the sensor named LDR (light dependent resistor). The LDR detects when the container box becomes empty, and receives the light from the base that is placed at the bottom of the container. The third module is on the basis of loose product items. These items can be weighed by using a load cell and HX711 load cell amplifier.  The weight limit has to be set to the basket, whenever the basket reaches the limit where a notification is sent to the staff member, stating that the basket has to be replenished with the items.

