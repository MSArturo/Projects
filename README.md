# Steganography_py is an executable created to save text in PNG images.
The project includes the executable (main.exe), the folder with the photos to work with and an extra folder with the background sound (audio).
The folder with the images has to be included to work correctly, but it's optional to delete the audio folder if no music is wanted.

# There's 3 different options in the main menu
Once the image is selected from the folder "Images" a menu will pop up to show the different options

# Save/Guardar
This mode is used to save text on the image using a password that the program will ask for

# Read/Leer
This mode is used to read the text on the image with the same password used to save the text.
If the password is wrong an error will pop up and the program will finalize 

# Delete content/Borrar contenido
This mode is used to delete the information saved on the image. Reading the content doesn't remove the text from the image, so this mode will do it. There's no way to recover the information after it's deleted. There's no need to used this mode before saving information, the information will be stored correctly anyway.

# Some more information
Only PNG images will be accepted, the console only shows images with this format.
There's a test image in the folder named "Images", the password for the image is "python".
To ensure the correct functionality is important to don't rename any of the folders.

# Encryption
There's multiple encryption sistems on this project. The main consists on lineal algebra combined with SHA256, so is highly secure.
Feel free to break the program and try to extract the text without the password.

# Report any problems.

MSArturo.

