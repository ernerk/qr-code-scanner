# QR Code Scanner

This Python script utilizes the OpenCV and Pyzbar libraries to scan a photo for QR codes and decode their contents.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Pyzbar (`pip install pyzbar`)

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/ernerk/qr-code-scanner.git
   ```

2. Navigate to the project directory:

   ```bash
   cd qr-code-scanner
   ```

3. Update the `photo_file` variable in the script with the name and path of the photo file you want to scan:

   ```python
   photo_file = "your_photo.png"
   ```

4. Run the script:

   ```bash
   python qr_code_scanner.py
   ```

   The decoded content of any QR codes in the specified photo will be displayed.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenCV](https://opencv.org/)
- [Pyzbar](https://github.com/NaturalHistoryMuseum/pyzbar)

Feel free to reach out with any questions or suggestions!

--- 

Make sure to replace "your-username" in the clone URL and update the `photo_file` variable in the script with the actual name and path of your photo file. Also, customize the README according to your specific project details.
