# Heart_Rate_Monitor
Records heart rate and analyzes heart rate data.

The Arduino collects measures the users heart rate using a pulse sensor, and sends that data over Serial to the Raspberry Pi. A python program
on the Pi reads from Serial then uploads to a MongoDB database hosted on mLab. On the web application side, we use Apache to serve webpages,
PHP for accessing the database, HTML, CSS, and Javascript for the frontend to display data.
