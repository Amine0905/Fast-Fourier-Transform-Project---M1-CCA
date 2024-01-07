# Fast Fourier Transform Project

This project implements a Fast Fourier Transform (FFT) algorithm in three different versions: sequential, parallelized with OpenMP, and distributed with MPI.

## Project Structure

The project is organized into three main directories:

- `OMP`: Contains the OpenMP parallelized version of the FFT algorithm.
- `Serial`: Contains the sequential version of the FFT algorithm.
- `MPI`: Contains the MPI distributed version of the FFT algorithm.

Each directory includes its own `Makefile` for compilation and execution.

## Running the Code
You can compile and run each version of the FFT algorithm using the provided Makefiles. For example, to compile and run the OpenMP version:

- `cd OMP`
- `make`
- `make run`

Follow a similar process for the Serial and MPI versions.

The `Makefile` uses sub-makefiles in each directory (`OMP`, `Serial`, `MPI`). The target `all` builds each type of program, and the target `clean` cleans the object and executable files in each directory. You can run `make` at the project root to build all programs and `make clean` to clean the generated files.

Make sure to adjust the compilation parameters in the Makefiles according to your system requirements.

## Contributors

- Amine IDRES `21322043`
- Rania Blibek `21215298`


