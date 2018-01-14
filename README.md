# parancsok:

Emlékeztető:

  -   az org.junit.Assert osztályt (és/vagy annak műveleteit, pl. assertEquals) kell importálni, valamint a org.junit.Test annotációt
  -   a JUnit futtatása, ha a tesztesetek osztálya a névtelen csomagba tartozó SimpleTest (Windows rendszeren ; az elválasztó):

javac -cp .:junit-4.12.jar:hamcrest-core-1.3.jar SimpleTest.java
java  -cp .:junit-4.12.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore SimpleTest
