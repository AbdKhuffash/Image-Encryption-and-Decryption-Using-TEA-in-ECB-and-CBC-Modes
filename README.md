# Image Encryption and Decryption Using TEA in ECB and CBC Modes

This repository demonstrates the encryption and decryption of images using the Tiny Encryption Algorithm (TEA) in both ECB (Electronic Codebook) and CBC (Cipher Block Chaining) modes. The implementation is done using Python and includes various utilities for image processing and handling.

## Features

- Encryption and decryption of images using TEA algorithm.
- Support for both ECB and CBC modes.
- Image conversion to blocks for encryption.
- Simple and easy-to-use command-line interface.

## Requirements

- Python 3.x
- Library (`pip install pillow numpy matplotlib requests`)
  

## Usage

1. **Clone the repository to your local machine:**
    ```
    git clone https://github.com/AbdKhuffash/Image-Encryption-and-Decryption-Using-TEA-in-ECB-and-CBC-Modes.git
    cd Image-Encryption-and-Decryption-Using-TEA-in-ECB-and-CBC-Modes
    ```

3. **Run the script:**
    
    Execute the Jupyter notebook or script provided in the repository to encrypt and decrypt images.
    
4. **Follow the instructions to enter the path or URL to the image, key, and IV (for CBC mode).**

7. **The encrypted and decrypted images will be displayed.**

## Functionality

### TEA Encryption and Decryption Functions

- **`tea_encrypt(plaintext, key)`**: Encrypts the plaintext using the TEA algorithm.
- **`tea_decrypt(ciphertext, key)`**: Decrypts the ciphertext using the TEA algorithm.

### ECB and CBC Mode Functions

- **`encrypt_ecb(plaintext_blocks, key)`**: Encrypts the plaintext blocks using ECB mode.
- **`decrypt_ecb(ciphertext_blocks, key)`**: Decrypts the ciphertext blocks using ECB mode.
- **`encrypt_cbc(plaintext_blocks, key, iv)`**: Encrypts the plaintext blocks using CBC mode with the given IV.
- **`decrypt_cbc(ciphertext_blocks, key, iv)`**: Decrypts the ciphertext blocks using CBC mode with the given IV.

### Image to Blocks Conversion Functions

- **`image_to_blocks(image)`**: Converts an image to a list of (L, R) blocks suitable for encryption.
- **`blocks_to_image(blocks, shape)`**: Converts a list of (L, R) blocks back into an image.

### Utility Functions

- **`download_image(url)`**: Downloads an image from a URL.
- Displays the original, encrypted, and decrypted images using `matplotlib`.

## Example

### Original Image

![task2](https://github.com/AbdKhuffash/Image-Encryption-and-Decryption-Using-TEA-in-ECB-and-CBC-Modes/assets/141878864/37e04de6-dacf-468c-befc-47405372ea17)


### Encrypted Image (ECB Mode)

![image](https://github.com/AbdKhuffash/Image-Encryption-and-Decryption-Using-TEA-in-ECB-and-CBC-Modes/assets/141878864/e1edca8e-b6f0-4d83-afc9-fb53903088ae)


### Decrypted Image (ECB Mode)

![image](https://github.com/AbdKhuffash/Image-Encryption-and-Decryption-Using-TEA-in-ECB-and-CBC-Modes/assets/141878864/5f42cb4e-5afd-41bf-b7b8-406a7c79e13e)


### Encrypted Image (CBC Mode)

![image](https://github.com/AbdKhuffash/Image-Encryption-and-Decryption-Using-TEA-in-ECB-and-CBC-Modes/assets/141878864/a3019766-dc47-4773-a552-8415b7a2f7fb)

### Decrypted Image (CBC Mode)
![image](https://github.com/AbdKhuffash/Image-Encryption-and-Decryption-Using-TEA-in-ECB-and-CBC-Modes/assets/141878864/09fb48e0-4a1c-4db5-9b2d-75dd8ea7c540)



## Contributing

Feel free to open issues or submit pull requests if you find any bugs or have improvements to suggest.

## Contact

For any questions or suggestions, please contact [AbdKhuffash](https://www.linkedin.com/in/khuffash1337).

