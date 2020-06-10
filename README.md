# UE4 Functional test demo

This demo was made and tested on UE 4.25.1

The goal was to create a simple hit detection test with auto fire for the basic "First person shooter template" found in UE.

- Single test and its assets can be found under Content/FirstPersonBP/Tests

- We add a simple cube with basic hit detection, we use two cubes to check one has been hit and other has not been hit

- We modify the FirstPersonCharacter BP to include a “MockFiring” event handler to be able to fire the weapon in the tests

- We copy the entire scene and add these testing pieces to FTEST_ShootingTest. This test can then be run from the Session Front end window (found under Project tests)