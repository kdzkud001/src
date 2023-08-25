# Club Simulation Program Guide

Welcome to My project! This README provides step-by-step instructions on how to compile and run the club simulation program.

## Prerequisites

Please ensure you have `make` installed on your machine. You can verify this by typing the following command in your terminal:

```bash
make --version
```

# Step 1: Navigate to the Project Directory
First, open your terminal. Navigate to the project directory using the cd command followed by the path to the 'club simulation' directory:
``` bash
cd <path_to_clubsimulation_directory>
```

Replace `<path_to_clubsimulation_directory>` with the actual path where your 'parallel' directory is located.

## Step 2: Compile the Files

After navigating to the 'parallel' directory, use the `make` command to compile the necessary files:

```bash
make
```

This command will automatically locate the Makefile in the directory and compile the files as specified.

## Step 3: Run the Program

Now, you are ready to run the program. Use the following `make` command:
```bash
make run ARGS="<noClubgoers> <gridX> <gridY> <max>"
```
Replace `<noClubgoers> <gridX> <gridY> <max>` with your desired values. Here's an example:
```bash
make run ARGS="20 10 10 5"
```

In this example, this will run the simulation with:
- 20 total people to enter the room.
- 10 X grid cells.
- 10 Y grid cells.
- A maximum of 5 people allowed in the club at once.

## Step 4: Cleaning Up
To remove compiled classes and clean up the bin directory, use the following command:

```bash
make clean
```

## Note
This README assumes you have the Java Development Kit (JDK) installed, along with the javac and java commands.




