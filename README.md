# Install-Rust
## To install Rust on a Linux/Ubuntu system, follow these steps
1-Open the terminal. 

2-Update the package list by running the following command:
```bash
sudo apt update
```
3-Install the required dependencies by running the following command:
```bash
sudo apt install curl build-essential
```
4-Download the Rust installation script by running the following command:
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
5-Follow the on-screen instructions to complete the installation.

6-Restart the terminal or run the following command to apply the changes:
```bash
source $HOME/.cargo/env
```
7-Verify the Rust installation by running the following command:
```bash
rustc --version
```
This will display the installed Rust version.

For more detailed instructions, please refer to the official Rust documentation: [Install Rust](https://www.rust-lang.org/tools/install)

or more detailed documents: [Installation](https://doc.rust-lang.org/cargo/getting-started/installation.html)
## update Rust in Ubuntu/Linux
To update Rust in Ubuntu, you can use the `rustup` tool. Here's how to do it:
Open a terminal window.

Run the following command to update `rustup`:
```bash
rustup update
```
Verify that Rust is updated to the latest version by checking the version number:
```bash
rustc --version
```
This should display the version of Rust that you have installed

You have successfully updated Rust in Ubuntu




