This Java-based application compares the efficiency of different types of vehicles, including hybrid, gasoline, and electric vehicles. It defines interfaces for various vehicle types and tests the functionality of a hybrid vehicle through unit tests.

Project Structure:

src/main/java: Contains the main application code, including the following files:

App.java: Entry point for the application.
CarRunner.java: Runs different vehicle types and compares their efficiencies.
ElectricInterface.java: Defines the interface for electric vehicles.
GasolineInterface.java: Defines the interface for gasoline-powered vehicles.
Hybrid.java: Implements functionality specific to hybrid vehicles.
HybridVehicle.java: Class that models the hybrid vehicle, integrating features from electric and gasoline vehicles.
src/test/java: Contains unit tests for the application.

AppTest.java: Unit tests for the overall application logic.
HybridTest.java: Unit tests for the Hybrid class to ensure proper functionality of the hybrid vehicle model.
How to Build and Run:

Clone the repository.
run these cmds:
  mvn compile
  mvn clean test

