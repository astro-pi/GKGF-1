# GKGF-1
<b>European Astro-Pi challenge 2016-2017</b> <br>
<b>Team name:</b> GKGF-1 - Gymnasium of Kanithos (Chalkida) Greece <br>
<b>Reference about challenge:</b> <br>
http://blogs.sch.gr/gymkanith (in Greek language) <br>
https://astro-pi.org/past-missions/ <br>
http://www.esa.int/Education/AstroPI/European_Astro_Pi_Challenge_Code_your_ISS_experiment_-_more_details2 <br>
http://www.esa.int/Education/AstroPI/1st_European_Astro_Pi_Challenge_Timeline <br>
http://www.esa.int/Education/AstroPI/Meet_the_sense_hat_-_teach_with_space_T05.2http://www.esa.int/Education/AstroPI/Meet_the_sense_hat_-_teach_with_space_T05.2 <br>
http://www.esa.int/Education/AstroPI/Getting_started_with_Astro_Pi_-_teach_with_space_T05.1 <br>
http://www.esa.int/Education/AstroPI/How_to_collect_data_from_the_Astro_Pi_-_teach_with_space_T05.3 <br>
http://www.esa.int/Education/AstroPI/Phase_2_of_the_European_Astro_Pi_challenge_begins <br>
http://www.esa.int/Education/Teachers_Corner/European_Astro_Pi_Challenge_Phase_2_update <br>
http://www.esa.int/Education/AstroPI/2016_-_2017_European_Astro_Pi_Challenge_winners_announced <br>
http://www.esa.int/Education/AstroPI/2016_17_European_Astro_Pi_Challenge_Winners <br>

<b>Our missions: </b> <br>
<i>Primary: </i> <br>
- Receiving measurements from all SenseHAT sensors per 10secs (temperature from humidity,
temperature from pressure, relative humidity, pressure, orientation (in radians and degrees),
accelerometer (raw and degrees), compass (direction of North and raw), gyroscope (raw and
degrees) and CPU temperature at Raspberry PI3 model B). <br>
- Timestamp for each measurement (in format: dd/mm/yyyy and hh:mm:ss). <br>
- Monitoring living conditions of the ISS crew per 10 sec. Living conditions on ISS are: temperature
(min 18.3 o C – max 26.6 o C), relative humidity (min 50% - max 70%), pressure (min 979.0559 mbar –
max 1027.2769 mbar). Displaying of notifying messages on the 8x8 led display of SenseHAT if the
measurements of the sensors (temperature, humidity, pressure) are above or below the allowed
limit. <br>
- For monitoring temperature we use the average measurement of temperature from the humidity
sensor and temperature from the pressure sensor. <br>
- All our programme is conducted in 3 hours (10800 sec). <br>
- If there is a slight variation of temperature/humidity in the original measurements which will be
received after commencing the programme (approximately 60 sec) we assume that somebody will
be in proximity to Astro-Pi and a greeting message (Hi!) will be displayed in the 8x8 led display. <br>

<b>Reference about our missions:</b> <br>
www.celestrak.com/NORAD/elements/stations.txt <br>
wsn.spaceflight.esa.int/docs/Factsheets/30%20ECLSS%20LR.pdf <br>
http://pep8online.com <br>
pypi.python.org/pypi/pep8 <br>
www.faa.gov/other_visit/aviation_industry/designees_delegations/designee_types/ame/media/Section%20III.1.2%20Cabin%20Environment%20and%20EVA%20Environment.doc <br>
www.weather.gov/media/epz/wxcalc/pressureConversion.pdf <br>
www.weather.gov/media/epz/wxcalc/tempConvert.pdf <br>
UNIVERSITY PHYSICS WITH MODERN PHYSICS - 13TH EDITION - HUGH D. YOUNG - ROGER A. FREEDMAN
Physics (Student Book) from Greek Public High School-ISBN 978-960-06-4827-0 (in Greek language)

<b>Files description: </b> <br>
GKGF_1.py - the Python programm running on ISS <br>
GKGF-1_GKGF_1_Greece_20170501_115603.csv - Data from ISS (from 01/05/2017,11:56:03 until 01/05/2017,14:55:51) - All mesurments from all sensors of SenseHat <br>
GKGF-1_GKGF_1_Greece_calc_20170501_115603.csv - Data from ISS (from 01/05/2017,11:56:03 until 01/05/2017,14:55:51) - Position of ISS (latitude , longitude , altitude) <br>

<b>Many thanks to: </b> <br>
a) my students (Paraskevas, Nikos, Pavlos, Constantinos and Anastasia) <br>
b) Mr Tsamouris Tasos - Physics Teacher at 4th Lyceum of Chalkida for his scientific support <br>
c) Mrs Pappa Korina - English Teacher at Gymnasium of Kanithos her translating assistance from Greek to English. <br>
  
  
