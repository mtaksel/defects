# Character Unlock Screen Text Message Not Fit On Screen
<!-- standardized-defect-report -->

| Field | Value |
| --- | --- |
| Defect ID | DEF-SV-003 |
| Status | Documented |
| Type | UI/UX |
| Severity | Low |
| Priority | Not recorded |
| Reproducibility | Not recorded |
| Platform | PC Game |
| Evidence | Included in the report |

[Back to Software Defect Portfolio](../../README.md)

## Description
- When a new character is unlocked as a reward, the name of the character and the message confirming the unlock do not fit properly on the screen.

## Preconditions
- Complete the relevant task or challenge to unlock a character reward.

## Steps
1. Launch Steam Client.
2. Start Supervive.
3. Go Queue to find the game.
4. Wait for the game to find a match.
5. Select a character and complete the game by gaining XP.
6. Upon earning enough XP, unlock a new character with rewards.
7. Navigates to character unlock animation scene.
## Screenshots
![](/supervive-game-defects/media/char-unlock-message-inconsistency-1.png)
![](/supervive-game-defects/media/char-unlock-message-inconsistency-2.png)

## Expected Result
- The character’s name and the confirmation message should fit neatly within the designated space on the screen.

## Actual Result
- Both the character name and the unlock message overflow the screen space, making it difficult to read.

## Severity
- Level: Low
- Minor UI Issue: This bug does not affect gameplay functionality but impacts the overall user experience and readability.

## Test Environment
*Device: Intel i9-10850K - NVIDIA GeForce RTX 3070 - 16GB RAM

*OS Version: Windows 11 23H2, Build 22631.4037

*Display Resolution: 1920x1080

*Platform details: PC

*Steam Client Version: 1726604483

*Supervive version: release0.15.snf-100829-shipping

*Issue Reproduction Time: 19.10.2024, 21:11

## Impact

Not formally assessed in the original test session.

## Workaround

No workaround was documented during the original test session.
