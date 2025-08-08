
# Task 2

<b>Image Encryption Tool</b>

This Python program implements a simple **image encryption and decryption tool** using pixel manipulation techniques. It allows users to encrypt and decrypt image files by applying reversible mathematical operations on the pixel values. The script is built for use in the terminal or Visual Studio Code and is beginner-friendly.

---

<b>Features</b>

* <b>Image Encryption:</b> Transforms an image by modifying pixel values based on a user-provided key.
* <b>Image Decryption:</b> Reverses the encryption to recover the original image using the same key.
* <b>User Input:</b> Accepts numeric keys and full image file paths.
* <b>File Saving:</b> Automatically saves encrypted and decrypted images with appropriate filenames.

---

<b>How It Works</b>

1. <b>Encrypt Image:</b>
   Multiplies each pixel value by the key, then divides by the key plus one.
   This distorts the original image, making it unreadable.

2. <b>Decrypt Image:</b>
   Multiplies each encrypted pixel by the key plus one, then divides by the key.
   This restores the original pixel values (approximately, due to integer rounding).

---

<b>Usage</b>

<ol>
  <li><b>Run the Program:</b> Open the folder in Visual Studio Code and run the script via terminal.</li>
  <li><b>Select Action:</b> Choose 'e' for encryption, 'd' for decryption, or 'q' to quit.</li>
  <li><b>Encrypt Image:</b></li>
    <ul>
      <li>Enter the encryption key (e.g., 45).</li>
      <li>Provide the full file path of the image to be encrypted (e.g., <code>D:\Cyber Security\Pixel manipulation for image encryption\my_photo.jpg</code>).</li>
    </ul>
  <li><b>Decrypt Image:</b></li>
    <ul>
      <li>Enter the same decryption key used during encryption.</li>
      <li>Provide the path to the encrypted image file.</li>
    </ul>
  <li><b>View Results:</b> Encrypted image is saved as <code>encrypted_image.png</code>, and decrypted image as <code>decrypted_image.png</code>.</li>
</ol>

---

This project was developed during my internship at <b>The Prodigy Infotech</b> as a practical implementation of **image encryption through pixel-level transformation** using Python.
