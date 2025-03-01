# Machine-Specific Key Generator

This Python script generates a unique, machine-specific encryption key based on the device's MAC address. The generated key is compatible with `cryptography.fernet` and is saved to a text file.

## Features

- Generates a unique key using the system's MAC address.
- Ensures compatibility with `cryptography.fernet` encryption.
- Saves the generated key to a file for future use.

## Prerequisites

Before running the script, ensure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)

## Installation

1. Clone the repository or download the script file.
 ```bash
  git clone https://github.com/ukihunter/Machine-Specific-Key-Generator
  ```

2. Navigate to the project directory:

   ```bash
   cd <project_directory>
   ```
Usage

Run the script:

```bash
python3 enKey.py
```
The script will display a machine-specific key on the screen:

```php-template
-Machine-Specific Key: <generated_key>
-The key will also be saved to a text file named key.txt in the same directory.
```
Example Output
```sql
Machine-Specific Key: aGVsbG93b3JsZGJ5dWtp...
```
## License
This project is licensed under the MIT License.









