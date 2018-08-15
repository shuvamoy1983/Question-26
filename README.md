# Question-26


@Test
public void parkingIsEmpty() {
boolean ans = true;
assertEquals(ans,isEmpty());
}

@Test
public void getRowNumber() {
//*test row number
int[] expectedOutput={2,4,5}
assertArrayEquals(expectedOutput, getRow);
}

@Test
public void getSpotNumber() {
//*test spot number
String[] expectedOutput={2A,4B,5C}
assertArrayEquals(expectedOutput, getSpotNumber());
}

@Test
public void canFitInTheSpot() {
//*test to check whether a car fit in the spot or not
boolean ans = true;
assertEquals(ans, canFitInSpot("Autonomouscar"));
}

@Test
public void isVehicleRemove() {
//*to test whether a vehile is removed or not after parking
boolean ans = true;
assertEquals(ans, removeVehicle("Autonomouscar"));
}
