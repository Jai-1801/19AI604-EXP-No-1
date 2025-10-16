# Experiment 1 – Installation of Rust and Cargo Tool and Setting up Rust in VS Code Environment  

<H3>ENTER YOUR NAME: Jai Surya R</H3>  
<H3>ENTER YOUR REGISTER NO: 212223230084</H3>  
<H3>EX.NO.1</H3>  
<H3>DATE: 16/10/2025</H3>  

<H1 ALIGN =CENTER> Installation of Rust and Cargo Tool and Setting up Rust in VS Code Environment </H1>  

## AIM:  
To install Rust and Cargo tools and set up Rust in Visual Studio Code environment.  

## EQUIPMENTS REQUIRED:  
- Hardware – PCs  
- Software – Visual Studio Code (Version 1.104.0)  
- Rust Installation  
- Cargo Toolchain  

## RELATED THEORETICAL CONCEPT:  

*Rust:*  
Rust is a modern systems programming language focused on safety, speed, and concurrency. It ensures memory safety without a garbage collector and provides powerful features like pattern matching, ownership, and concurrency handling.  

*Cargo:*  
Cargo is Rust’s package manager and build system. It helps in managing dependencies, building packages, testing code, and running projects.  

*Need for Cargo in VS Code:*  
- Smooth integration of Rust projects into VS Code.  
- Simplifies the build, run, and debugging process.  
- Helps in managing dependencies and external crates.  
- Improves developer productivity with extensions.  

## ALGORITHM:  
STEP 1: Install **rustup-init.exe** from [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install) and run the file. <BR>  
STEP 2: Complete the installation process. <BR>  
STEP 3: Update Rust and Cargo to the latest version. <BR>  
STEP 4: Check the version of Rust and Cargo. <BR>  
STEP 5: Install the Build Tools for Visual Studio Code from [https://visualstudio.microsoft.com/downloads/](https://visualstudio.microsoft.com/downloads/) and run the exe file. <BR>  
STEP 6: In the Visual Studio Installer, select **Desktop development with C++** and install. <BR>  
STEP 7: Install all the necessary Rust extensions in Visual Studio Code. <BR>  
STEP 8: Run a simple *Hello World* program to test if Rust works in VS Code. <BR>  

## PROGRAM:  
```use std::io;

fn main() {
    println!("Welcome to Rust Setup Test!");
    println!("Let's do a simple calculation.");

    println!("Enter your name:");
    let mut name = String::new();
    io::stdin()
        .read_line(&mut name)
        .expect("Failed to read input");

    println!("Enter two numbers to add:");

    let mut num1 = String::new();
    io::stdin()
        .read_line(&mut num1)
        .expect("Failed to read number 1");

    let mut num2 = String::new();
    io::stdin()
        .read_line(&mut num2)
        .expect("Failed to read number 2");

    let num1: i32 = num1.trim().parse().expect("Please enter a valid number");
    let num2: i32 = num2.trim().parse().expect("Please enter a valid number");

    let sum = num1 + num2;

    println!("Hello, {}!", name.trim());
    println!("The sum of {} and {} is: {}", num1, num2, sum);
    println!("Rust environment is working perfectly in VS Code!");
}

```

## OUTPUT:
<img width="542" height="276" alt="image" src="https://github.com/user-attachments/assets/04b140ed-e48f-459b-bb5d-4325bd426d8c" />


## RESULT:
The installation of Rust and Cargo tools was successfully completed, and the Rust environment was set up and tested in Visual Studio Code by executing a simple interactive program within a single fn main() function.

