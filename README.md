# Bitmex Order Book Assginment
<h3> Running Version </h3>

- JAVA 8 SDK
- Maven 3.6.0

<h3> Remarks </h3>

- This order book only supports one instrument
- For simplicity, the code does not support order recovery on restart
- Validation has been added for below scenario
  - No negative or non-numeric price
  - No negative or non-numeric size
  - No duplicate orders
  - No malform order input 
  - No malform order side


<h3> User guide </h3>
Running Manually

- cd to project root folder
- run: mvn clean package
- Create a terminal and run: mvn exec:java -Dexec.mainClass="bitmex.interview.exchange.Exchange"
- Input request in terminal, e.g. "1,B,10,20"


Running embedded Test
- cd to project root folder
- run: mvn clean verify
- check test result

