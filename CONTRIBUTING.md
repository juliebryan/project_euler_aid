# Contributing to project-euler-utils

Thank you for considering contributing to this package. The focus is on inncreasing the efficiency of functions
using **NumPy** and building  the test coverage.

## How to Contribute

### 1. **Fork the Repository**
   - Fork the repository by clicking on the **Fork** button at the top-right of the repository page.

### 2. **Clone Your Fork**
   - Clone your forked repository to your local machine:
     ```
     git clone https://github.com/juliebryan/project_euler_aid.git
     cd your-repo-name
     ```

### 3. **Create a New Branch**
   - Create a new branch for your changes:
     ```bash
     git checkout -b improve-efficiency
     ```

### 4. **Make Changes**

   - **Improve efficiency**: Use **NumPy** to optimize any parts of the code that are computationally expensive.
   - **Add tests**: Write tests for the new or existing functions. 
   
   I currently do not have pytest as a dependency but recommend using pytest for developing tests.
     - Tests should be added in the `tests/` directory.
     - Make sure all tests pass before submitting the pull request

### 5. **Run Tests**
   - Before submitting, make sure all tests pass:
     ```bash
     pytest
     ```

### 6. **Commit Changes**
   - Add and commit your changes:
     ```bash
     git add .
     git commit -m "Optimized function using NumPy and added tests"
     ```

### 7. **Push Changes**
   - Push your changes to your fork:
     ```bash
     git push origin improve-efficiency
     ```

### 8. **Open a Pull Request**
   - Go to the original repository and open a **pull request** from your fork's `improve-efficiency` branch to `main`.
   - In the pull request description, explain what you did and the impact it will have.


Appreciate your contributions to make this package better!

Email - juliebryan998@gmail.com