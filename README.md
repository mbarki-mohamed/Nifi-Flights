# Nifi Flights Dashboard
An Apache NiFi data pipeline that extracts flight data from flights APIs, dump data into a warehouse (SnowFlake) and constructs a PowerBi dashboard on top of this.

## Overview  
Apache Nifi is an easy to use and reliable data ingestion tool that connects to a wide range of connectors allowing seamless data flow between different components.
Data will be collected from a rest API :  the Amadeus Travel API which provides extensive end-points to integrate flight data, and also has a generous free plan.
