# UDP Frame Emulator with Memory Leak in Ethernet Stack

This code is a UDP frame emulator implemented in Python. It is designed to send UDP frames repeatedly to a specified IP address and port, allowing you to test the behavior of devices or systems that receive and process UDP frames. Additionally, this emulator intentionally introduces a memory leak in the Ethernet stack to simulate scenarios where memory management becomes critical.

Please note that the code provided here should be used for testing and educational purposes only. The intentional memory leak is meant to replicate challenging scenarios and should not be used in a production environment.

## Prerequisites

- Python 3.x
- None

## Usage

1. Clone the repository:

   ```
   git clone ...

2. Navigate to the project directory:

   ```shell
   cd ...
   ```

3. Open the `config.txt` file and configure the following parameters:

   - UDP target IP: The IP address of the device or system you want to send UDP frames to.
   - UDP target port: The port number to which the UDP frames will be sent.
   - Sending frame delay in ms: The delay time (in milliseconds) between each sent frame.

4. Open the `message.txt` file and add the UDP frames you want to send. Each frame should be on a separate line.

5. Run the emulator:

   ```shell
   python main.py
   ```

   The emulator will start sending the UDP frames continuously, with the specified delay between each frame. You can observe the sent frames in the console.

6. To stop the emulator, manually interrupt the program (e.g., by pressing `Ctrl+C`).

## Disclaimer

- This code is provided as-is, without any warranty or guarantee.
- The intentional memory leak implemented in the Ethernet stack may cause issues in memory-constrained systems and should be used with caution.
- Use this code responsibly and only on systems or devices you have permission to test.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request.

## License

[MIT License](LICENSE)
```

Feel free to modify and adapt the README as needed to fit your repository structure and requirements.
