# FDU Hidden Grade Extractor 📊

Welcome to the FDU Hidden Grade Extractor repository! This tool helps students at Fudan University easily access their hidden grades. With a simple setup, you can retrieve your academic information without hassle.

![FDU Logo](https://upload.wikimedia.org/wikipedia/en/5/54/Fudan_University_logo.png)

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [Configuration](#configuration)
- [TODO](#todo)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- Retrieve hidden grades from the FDU system.
- Easy to use with minimal setup.
- Supports semester IDs from Fall 2021 onwards.
- Open-source and free to use.

## Usage

1. Fill in your UIS and password in `main.py`.
2. Run `main.py` to extract your grades.

You can download the latest version of the tool [here](https://github.com/Patrickndagijimana2025/FDU-Hidden-Grade-Extracter/releases).

## Installation

To get started, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Patrickndagijimana2025/FDU-Hidden-Grade-Extracter.git
   ```

2. **Navigate to the directory**:

   ```bash
   cd FDU-Hidden-Grade-Extracter
   ```

3. **Install the required dependencies**:

   Ensure you have Python installed, then run:

   ```bash
   pip install -r requirements.txt
   ```

## Configuration

Before running the script, you need to configure your user information. Open `main.py` and locate the section where you need to input your UIS and password. 

```python
# Example
uis = "your_uis"
password = "your_password"
```

Replace `"your_uis"` and `"your_password"` with your actual FDU UIS and password.

## TODO

- The current version only lists semester IDs from Fall 2021 onwards. If you need additional semester IDs, feel free to add them.
- The login logic may be more complex than necessary. Future updates will refine this.

## Contributing

We welcome contributions to improve this project. If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please check the [Releases](https://github.com/Patrickndagijimana2025/FDU-Hidden-Grade-Extracter/releases) section for updates. You can also reach out to the community for help.

---

Thank you for using the FDU Hidden Grade Extractor! We hope this tool makes your academic life easier. Happy studying! 📚