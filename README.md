# FIFO Scheduling Algorithm

This repository contains a simple implementation of the **First-In-First-Out (FIFO)** scheduling algorithm in C. The program takes process details from the user (such as Process ID and Burst Time) and schedules the processes using the FIFO approach.

## Features
- Input validation for process details.
- User-friendly prompts for entering process data.
- Implements the FIFO scheduling algorithm.

## Prerequisites
To compile and run this program, you need:

- A C compiler (e.g., GCC)
- Alpine Linux or any Linux-based environment (or other platforms with minor modifications)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/fifo-scheduling.git
    cd fifo-scheduling
    ```

2. Compile the code:
    ```bash
    gcc -o fifo_scheduling main.c queue.c
    ```

## Usage
Run the program using the following command:
```bash
./fifo_scheduling
```

### Example Execution
1. Start the program:
    ```
    ./fifo_scheduling
    ```
2. Input the number of processes:
    ```
    Enter Number of Processes: 3
    ```
3. Input process details (Process ID and Burst Time) for each process:
    ```
    Enter Process ID for Process 1: 101
    Enter Burst Time for Process 1: 5
    Enter Process ID for Process 2: 102
    Enter Burst Time for Process 2: 8
    Enter Process ID for Process 3: 103
    Enter Burst Time for Process 3: 2
    ```
4. The program will process the input and execute the FIFO scheduling logic.

### Sample Output
```
Enter Number of Processes: 3
Enter Process ID for Process 1: 101
Enter Burst Time for Process 1: 5
Enter Process ID for Process 2: 102
Enter Burst Time for Process 2: 8
Enter Process ID for Process 3: 103
Enter Burst Time for Process 3: 2

Scheduled Processes:
PID     Burst Time
101     5
102     8
103     2
```

## Files
- `main.c`: Contains the main logic for user input and scheduling.
- `queue.c`: Implements a queue to store and manage process data.
- `queue.h`: Header file for `queue.c`.

## Known Issues
- Ensure valid inputs for Process ID and Burst Time (numeric values only).
- The program might hang if invalid inputs are provided. Input validation is implemented but needs careful attention from the user.

## Future Improvements
- Add support for other scheduling algorithms (e.g., Round Robin, SJF).
- Enhance input validation for better error handling.
- Include graphical or textual visualization of scheduling.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or suggestions, please contact:
- **Ahmed Soliman**: [ahmedsoliman202@gmail.com](mailto:ahmedsoliman202@gmail.com)
