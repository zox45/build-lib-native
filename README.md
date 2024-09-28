# Flet-Native 🚀

**Flet-Native** is a cutting-edge tool designed to simplify the compilation of **non-pure Python** packages, which may include components written in languages like C, C++, or Rust. 🛠️

## Key Features 🌟

- **Easy Integration**: Compile popular packages like `firebase-admin` for iOS and Android with minimal effort.
- **Automated Workflow**: Just add your required libraries to the `requirements.txt` file, and Flet-Native handles the rest! 🔄
- **Automatic Dependency Management**: Flet-Native automatically adds any necessary dependencies of the libraries to avoid errors related to missing libraries. 📦
- **No Hacks or Patches**: Say goodbye to complex workarounds; our tool streamlines the process for you. 🙌

## Usage 📦
1. Add your non-pure Python package requirements to the `requirements.txt` file, and it will automatically add the dependencies of the libraries.
   
2. Run the workflow to automate the compilation process.
   
3. Download the library as a ZIP file. 📥

### Example `requirements.txt`:

```plaintext
firebase-admin
opencv-python
