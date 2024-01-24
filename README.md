Try the new version of [Honeypot](https://github.com/ChrishSec/Honeypot) over [CaptureHoney](https://github.com/ChrishSec/CaptureHoney) for a better experience.

## Honeypot

Honeypot, a straightforward C program, logs connections and sends a custom message, offering no service to unwanted visitors.

### Requirements

- C compiler
- Unix-like operating system (tested on Ubuntu 20.04)

### Usage

1. Clone the repository:

```git clone https://github.com/ChrishSec/honeypot.git```

2. Compile the program:

```gcc honeypot.c -o honeypot```

3. Run the program:

```sudo ./honeypot```

By default, the program listens on port 80. You can change the port number by modifying the `PORT` constant in the source code.

## Disclaimer

This program is for educational and research purposes only. Use it at your own risk. The author is not responsible for any damage caused by the use or misuse of this program.

## License

This program is released under the GNU General Public License v3.0. Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed.

## Author

This program was developed by [ChrishSec](https://github.com/ChrishSec). Feel free to fork, modify, and distribute it. If you have any questions or suggestions, please reach out to the author on [Telegram](https://t.me/ChrishSec).
