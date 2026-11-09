# CMD Learning Project

A Python project designed for learning command-line interface concepts and mathematical property examples. It demonstrates different properties through interactive prompts.

## Features
- Modular property system
- Example demonstrations for each property
- Easy-to-extend structure

## Requirements
- Python 3.x

## How to Run
```bash
python main.py
```

## User Manual

### Starting the Program
1. Open a terminal/command prompt.
2. Navigate to the project folder.
3. Run: `python main.py`
4. You will see a prompt (`> `).

### Available Commands / Properties
Type the property name exactly and press Enter.

| Command | Description |
|---------|-------------|
| `Property 1` | Shows Property 1 and waits for the next input. |
| `Property 2` | Shows Property 2 and waits for the next input. |
| `Property 3` | Shows Property 3 and waits for the next input. |
| `Property 4` | Shows Property 4 and waits for the next input. |
| `Example` | (After selecting a property) Displays a worked example for that property. |

### How It Works
1. The program shows a prompt.
2. Type one of the property names (`Property 1`, `Property 2`, etc.).
3. The program prints information about that property.
4. Type `Example` to see a concrete numerical example.
5. Any other input shows "Invalid input".
6. The program loops so you can try another property.

### Example Session
```
> Property 1
[Property 1 information is displayed]
> Example
a = 5
b = 3
Now the formula is: a x b = ab integer
Answer: ab =
15

> Property 2
[Property 2 information is displayed]
> Example
Number one = 4
Number Two = 7
...
```

### Tips
- Property names are case-sensitive. Type them exactly as shown.
- After viewing an example, the program returns to the main prompt so you can explore another property.
- This is an educational project — the properties are hardcoded examples for learning.

## Project Structure
- `main.py` - Entry point
- `laws.py` - Core logic for each property
- `settings.py` - Configuration and example values

## License
MIT
