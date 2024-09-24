Project Structure:

src/main/java: Contains the main application code, including the following files:

App.java: entry point

CarRunner.java: Runs different vehicle types and compares their efficiencies.

ElectricInterface.java: interface for electric vehicles.

GasolineInterface.java: interface for gasoline-powered vehicles.

Hybrid.java: Implements specific to hybrid vehicles.

HybridVehicle.java: Class that models the hybrid vehicle, integrating features from electric and gasoline vehicles.

src/test/java: Contains unit tests for the application.

AppTest.java: Unit tests for the overall application logic.

HybridTest.java: Unit tests for the Hybrid class to ensure proper functionality of the hybrid vehicle model.

How to Build and Run:
1) Clone the repository.
1) run these cmds (outside of all directories):
  mvn compile

  mvn clean test

