import cv2
from pyzbar.pyzbar import decode

# Specify the name of the photo file you want to scan for QR codes
photo_file = "qr.png"  # Update the name and path of the photo file

# Open the photo
image = cv2.imread(photo_file)

# Convert the image to grayscale
gray_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)

# Enhance the image
enhanced_image = cv2.equalizeHist(gray_image)

# Decode QR codes
decoded_objects = decode(enhanced_image)

for obj in decoded_objects:
    # Decode the QR code and retrieve the content
    data = obj.data.decode('utf-8')

    # Print the content of the QR code to the screen
    print("QR Code Content: ", data)
