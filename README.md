

<div style="text-align: center; width: 100%;">
    <img src="assets/misc/Octaprobe.png" alt="OctaProbe Logo" style="max-width: 100%; height: auto;">
</div>

<br>
<div align=center> 

![Static Badge](https://img.shields.io/badge/Python-Lol?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Streamlit-badge?style=for-the-badge&color=%236200EA)
![Static Badge](https://img.shields.io/badge/Ollama-badge?style=for-the-badge&color=%23212121)

### Repository Statistics

![GitHub License](https://img.shields.io/github/license/NONAN23x/Octaprobe)
![GitHub repo size](https://img.shields.io/github/repo-size/NONAN23x/Octaprobe)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/NONAN23x/Octaprobe)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues-pr/NONAN23x/Octaprobe)
![GitHub last commit](https://img.shields.io/github/last-commit/NONAN23x/Octaprobe)

### Target Operating Systems

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

</div>

<br><br>

## 🎥 Demo Video

To see OctaProbe in action, click on the demo video below:

<div align="center">

[![Octaprobe](assets/misc/Octaprobe.png)](https://www.youtube.com/watch?v=13AFKNG8OL4)


</div>

>💡 **Test the App Online**  
You can try out OctaProbe directly in your browser by visiting [OctaProbe](https://octaprobe.streamlit.app/).
Note: Limited functionality on the testing version!

<br><br>

## ❓ What is it?

OctaProbe is a lightweight and efficient vulnerability scanner designed to identify security weaknesses in various systems. Built with Python and leveraging modern frameworks like Streamlit, it provides an intuitive interface for users to perform scans and analyze results. OctaProbe supports multiple operating systems, making it a versatile tool for developers, security analysts, and IT professionals.

<br><br>

## 🚀 How to Install?

> Before proceeding, ensure you have a basic understanding of the command line and that Git is installed on your system. If Git is not installed, follow the [official Git installation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).  (Not to be confused with GitHub Desktop!)

> 💡 **Need a tailored guide?**  
> Refer to the [Project Wiki](https://github.com/NONAN23x/Octaprobe/wiki) for detailed, platform-specific instructions.

<br>

1. Clone the repository:
    ```bash
    git clone https://github.com/NONAN23x/Octaprobe.git
    cd Octaprobe
    ```

2. Install `uv` package manager:
    
    For Windows:
    ```powershell
    pip install uv
    ```
    For Linux distros with pipx:
    ```bash
    pipx install uv
    ```
    > 💡 **Note**  
     For detailed installation instructions for specific operating systems, please refer to the [Project Wiki](https://github.com/NONAN23x/Octaprobe/wiki)! We're excited to help you get started!

    - (Optional) Run setup.py with uv to initialize local llm:
        ```bash
        uv run setup.py
        ```
        > ⚠️ The script ensures that all required libraries are installed and that the Ollama service is properly set up. The setup script will automatically check for Ollama's installation and configuration. If Ollama is not installed or configured, the script will redirect you to the [Ollama Documentation](https://ollama.com/) for guidance. Please ensure the service is active and accessible to avoid any runtime issues.

    - (Optional) Run setup.py with uv to initialize VirusTotal API:
        ```bash 
        uv run setup.py
        ```
        > ⚠️ The setup.py ensures that you have Virustotal API key installed and accessible, if not found; setup redirects you to webpage where you can sign up using google chrome and get your API key, you can have to add this to your OS Environment Variable

        - For Windows
        Go to Search Bar > Environment Variables > Add new variable `VIRUSTOTAL_API_KEY`
        - For Linux
        Open up a terminal, add the following to your .bashrc or .zshrc
            ```bash 
            export VIRUSTOTAL_API_KEY="Your API Key Here"
            ```


3. Run the application:  
    ```bash
    uv run streamlit run app.py
    ```

<br><br>

## 🤝 Contributing
> We welcome contributions from the community! Before you begin, please take a moment to read the [CONTRIBUTING.md](https://github.com/NONAN23x/Octaprobe/blob/main/CONTRIBUTING.md) and [ROADMAP.md](https://github.com/NONAN23x/Octaprobe/blob/main/ROADMAP.md) files in the repository to understand the project's guidelines and future plans.

After you've read the above documents, here's how you can contribute:

1. **Fork the Repository**:  
    Click the "Fork" button at the top-right corner of this repository to create your own copy.

2. **Clone Your Fork**:  
    ```bash
    git clone https://github.com/your-username/Octaprobe.git
    cd Octaprobe
    ```

3. **Create a Branch**:  
    Create a new branch for your feature or bug fix.  
    ```bash
    git checkout -b feature-name
    ```

4. **Make Changes**:  
    Implement your changes and commit them with a descriptive message.  
    ```bash
    git add .
    git commit -m "Add a brief description of your changes"
    ```

5. **Push Changes**:  
    Push your changes to your forked repository.  
    ```bash
    git push origin feature-name
    ```

6. **Submit a Pull Request**:  
    Open a pull request to the main repository. Provide a clear description of your changes and why they should be merged.
