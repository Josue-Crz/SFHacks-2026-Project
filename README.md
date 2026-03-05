# SFHacks-2026-Project
<h2>🌡️ GreenSense 🌱 </h2>
<h3>  IoT full stack application that provides real time temperature & humidity data, providing Artificial Intelligence suggestions about how to save energy for user's HVAC systems with the goal of reducing costs and spreading environmental awareness. </h3>

<h2> The Problem </h2>
Most users when they own a house view their HVAC systems as a black box, essentially seeing it as something outside of their understanding letting the professionals. But for homeowners at the end of the month once the utility bills arrive see the bill and question why is it so high? How could I understand the metrics without stepping out of the couch?

<h2> The Solution </h2>
During the 2026 SFHacks Hackathon our team prototyped GreenSense, a full stack Internet of Things application that solve client issues of understanding how an HVAC system runs the meter bills up, meanwhile promoting environment sustainability of unnecssary HVAC use. 

This is achieved by monitoring surrounding weather data, as well including inside temperature and humidity data through hardware implementations. Providing AI suggestions to the client on how to interpret collected data in order to understand why an HVAC system had been potentially overused.

<h2> Technology Stack </h2>

<h3>Frontend</h3>
<h4>React.js</h4>
Responsive client dashboard for real-time monitoring and AI-driven energy insights.

<h3>Backend</h3>
<h4>Python(Flask/FastAPI)</h4>
Managed data processing, integration of the LLM and served as the handler for sensor data

<h3>Middleware</h3>
<h4>Ngrok</h4>
Utilizing platform integration as a secure tunneling service to expose the local backend to the web, enabling data transmission endpoints.

<h3>Hardware</h3>
<h4>Arduino Uno R3 (Elegoo)</h4>
Using the Elegoo distribution of the Arduino microcontroller in order to implement environmental sensors. Elegoo distribution chosen for budgeting toward the initial prototype.

<h3>Sensors</h3>
<h4>DHT11</h4>
Capturing indoor temperatue and humidity for relative telemtry data to be parsed. 

<h3>Communication</h3>
<h4>PySerial Library</h4>
Implemented serial data parsing to bridge the full stack integration among the hardware-level sensor readings to the Python backend layer. 

<h3>Physical Prototype during SFHacks presentation</h3>

![physical-prototype](/static/Physical-Prototype.jpeg)

<h3>Wire Diagram using Fritzing to promote organized hardware layout for initial prototyping</h3>

![fritzing-diagram](/static/wireDiagramGreenSenseDevice.png)




<h2> Long Term Plans Post Hackathon </h2>

- [ ] Refactor, organize submodules into different branches of prototype phasing and long-term fixes to resolve bugs.
- [ ] Integration of a database in the backend to handle GET requests from client
- [ ] Creating a webhook and exploring other options as opposed to standard REST standards
- [ ] Integration of Artificial Intelligence in dashboard for real time parsing data and feedback for users on eco safety based on the weather around themselves


 
<h3>Other Goals</h3>

- [ ] Refactor Greensense using the RaspberryPi 4 Model B for ease WiFi/Networking capabilities as opposed to parsing Serial Py information and sending it to the client outside of a localhost network.

<br>
<h2>Co-Contributors:</h2>

[@LuisGon4](https://github.com/LuisGon4) -> Frontend implementation & Artificial Intelligence Implementation
<br>
[@Negarghni](https://github.com/Negarghni) -> Frontend/Product design & contributor
<br>
[@Josue-Crz](https://github.com/Josue-Crz) -> Backend implementation & Hardward Architect 
<br>
[@WaiLwinO](https://github.com/WaiLwinO) -> Product design & backend contributor

Slideshow made during SF Hacks initiated by [@WaiLwinO](https://github.com/WaiLwinO)
<br>
[Slideshow Presentation](https://www.canva.com/design/DAHBVCWiJZw/kZGviSNUuthjVmJBRI87bw/edit)


