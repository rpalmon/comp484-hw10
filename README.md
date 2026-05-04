"# comp484-hw10

HW Link:

https://rpalmon.github.io/comp484-hw10/

## Console Methods Used

### Log Info
Used in the following functions:
- `persistPets()` - logs when pets are persisted to localStorage, including the active pet's name

### Log Warning
Used in the following functions:
- `clickedTreatButton()` - warns if no active pet is found when trying to give a treat
- `clickedPlayButton()` - warns if no active pet is found when trying to play, and warns if trying to play when weight is already at 0
- `clickedExerciseButton()` - warns if no active pet is found when trying to exercise, and warns if trying to exercise when weight is already at 0

### Log Error
Used in the following functions:
- Reserved for future error handling

### Log Table
Used in the following functions:
- `persistPets()` - displays the current pets array in a table format in the console for easier debugging

### Log Group
Used in the following functions:
- `setActivePet()` - groups logs related to changing the active pet, including the new active pet's name
- `createPetFromTabs()` - groups logs related to creating a new pet from the tab interface, including a styled log message when starting the creation process

### Log Custom
Used in the following functions:
- `persistPets()` - logs a custom message with styles when pets are persisted to localStorage

## Messages Logged by Browser

- Cause 404 network error
- Cause TypeError
- Cause Violation" 
