# Laughing Octo Broccoli SQLi Scanner

A lightweight and versatile SQL injection scanner tool written in Python. Detect potential SQL injection vulnerabilities in web applications with ease.

## Features

- Detects SQL injection vulnerabilities in GET and POST requests.
- Supports various database management systems (DBMS) including MySQL, PostgreSQL, Microsoft SQL Server, Oracle, and more.
- Provides both error-based and blind SQL injection testing.
- Customizable user-agent, cookie, and referer headers.
- Option to use an HTTP proxy for scanning.
- Compact and efficient codebase for quick security assessment.

## Usage

1. Clone the repository to your local machine.
2. Run the `laughing-octo-broccoli.py` script with the desired command-line options. Use the `-h` flag to see available options.
   Example: `python laughing-octo-broccoli.py -u "http://example.com/page.php?id=1"
