# Math Quiz Game

A console-based interactive math quiz game written in C++ that tests your arithmetic skills with customizable difficulty levels and operations.

## Description

This educational game generates random math questions based on your chosen difficulty level and operation type. Test your mental math abilities with addition, subtraction, multiplication, and division problems, and receive instant feedback with visual color cues.

## Features

- **Multiple Difficulty Levels**: Choose from Easy, Medium, Hard, or Mixed difficulty
- **Various Operations**: Practice Addition, Subtraction, Multiplication, Division, or Mixed operations
- **Customizable Quiz Length**: Answer between 1 to 100 questions per session
- **Instant Feedback**: Get immediate responses on whether your answer is correct or wrong
- **Visual Feedback**: Screen changes color (green for correct, red for incorrect) with audio alerts
- **Performance Summary**: View detailed results including pass/fail status and score breakdown
- **Replay Option**: Play multiple rounds without restarting the program

## Difficulty Levels

- **Easy**: Numbers range from 1 to 10
- **Medium**: Numbers range from 10 to 50
- **Hard**: Numbers range from 50 to 100
- **Mix**: Randomly selects from Easy, Medium, or Hard for each question

## Operation Types

- **Add (+)**: Addition problems
- **Sub (-)**: Subtraction problems
- **Multi (×)**: Multiplication problems
- **Div (÷)**: Division problems (integer division)
- **Mix**: Randomly selects from all operation types

## How to Compile

### Using g++
```bash
g++ -o math_quiz math_quiz.cpp
```

### Using Visual Studio
1. Create a new C++ Console Application project
2. Copy the code into the main source file
3. Build the solution (F7)

### Using Code::Blocks or Dev-C++
1. Create a new project
2. Add the source file
3. Build and run

## How to Run

After compilation, run the executable:

```bash
./math_quiz
```

On Windows:
```bash
math_quiz.exe
```

## How to Play

1. **Start the game**: Run the executable
2. **Enter number of questions**: Type a number between 1 and 100
3. **Select difficulty level**: 
   - Press 1 for Easy
   - Press 2 for Medium
   - Press 3 for Hard
   - Press 4 for Mix
4. **Choose operation type**:
   - Press 1 for Addition
   - Press 2 for Subtraction
   - Press 3 for Multiplication
   - Press 4 for Division
   - Press 5 for Mix
5. **Answer questions**: Type your answer and press Enter
6. **View results**: See your score and whether you passed
7. **Play again**: Press Y to play another round or N to exit

## Scoring System

- Each correct answer increases your right answer count
- Each incorrect answer increases your wrong answer count
- **Pass Condition**: Right answers ≥ Wrong answers
- The game displays the correct answer when you answer incorrectly

## Example Gameplay

```
How Many Questions Do You Want To Answer: 5

Enter The Level Of Question: [1] Easy, [2] Mid, [3] Hard, [4] Mix ? 1

Enter Operation Type: [1] Add, [2] Sub, [3] Multi, [4] Div, [5] Mix ? 1

Question [1/5]

7
3 +
_____________
10
Right Answer :-)

...

Final Results is PASS :-)
_______________________________________

Number of Questions: 5
Questions Level    : Easy
OpType             : +
Number Of Right Answers: 4
Number Of Wrong Answers: 1
_______________________________________

Do You Want To Play Again? Y/N?
```

## System Requirements

- C++ compiler (C++11 or later recommended)
- Windows OS (for color commands) or compatible terminal emulator
- Console/Terminal window

## Technical Details

- Language: C++
- Standard Libraries: iostream, cstdlib, ctime
- Platform-specific features: Uses Windows system commands for screen color changes

## Notes

- Division operations use integer division (results are truncated)
- Division by zero is prevented automatically
- Screen color changes work best on Windows Command Prompt
- Audio alert (beep) plays on incorrect answers

## Future Enhancements

Potential improvements could include:
- Decimal/floating-point division support
- Timed challenges
- High score tracking
- Save/load game statistics
- Cross-platform color support
- Difficulty progression mode

## License

This project is open source and available for educational purposes.

## Author

Math Quiz Game - An educational C++ project for practicing arithmetic skills.