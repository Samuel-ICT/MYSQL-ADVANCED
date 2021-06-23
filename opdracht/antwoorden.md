# Antwoorden Eindopdracht

1. Copy paste je gemaakte SQL query hieronder
   SELECT races.name AS races_name, circuits.name AS circuit_name FROM races JOIN circuits ON circuits.circuitId = races.circuitId WHERE year = 2009; 

2. Copy paste je gemaakte SQL query hieronder
   SELECT races.name, drivers.surname, driver_standing.points FROM races JOIN driver_standing ON driver_standing.raceId = races.raceId JOIN drivers ON drivers.driverId = driver_standing.driverId WHERE points = 10 AND year = 2017; 

3. Copy paste je gemaakte SQL query hieronder
   SELECT drivers.forename, drivers.surname, pitstops.duration FROM drivers JOIN pitstops ON pitstops.driverId = drivers.driverId WHERE duration < 25; 

4. Copy paste je gemaakte SQL query hieronder
   SELECT constructors.name, races.name AS GrandPrix FROM races JOIN constructor_standing ON races.raceId = constructor_standing.raceId JOIN constructors ON constructors.constructorId = constructor_standing.constructorId WHERE constructor_standing.constructorId = 1 AND year = 2010; 
   
5. Copy paste je gemaakte SQL query hieronder
   SELECT circuits.name AS circuit, circuits.country AS country, races.name AS GrandPrix, drivers.surname FROM drivers JOIN driver_standing ON driver_standing.driverId = drivers.driverId JOIN races ON races.raceId = driver_standing.raceId JOIN circuits ON circuits.circuitId = races.circuitId WHERE drivers.surname LIKE "f%" AND year = 1950; 
   
