javac -cp $EDGENT/samples/lib/'*':$PI4J_LIB/'*' -d bin/ *.java
sudo java -cp $EDGENT/samples/lib/'*':$PI4J_LIB/'*':bin/ TempSensorApplication

