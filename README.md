# Secured-Data-Transmission-SenderEnd-ReceiverEnd-With-Steganography--Text-hidden-in-Image--With-GUI.

Implementation of several algorithms including AES, 
RSA, SHA-256, PVD Steganography Algorithm, and many 
more for the creation of separate sender end and receiver 
end programs using which they can securely communicate. 
GUI implementation has been done for the ease of access. 
This project ensures CIA in Network Security and has been 
implemented in MATLAB 2019b.

%IMPORTANT%

Inorder to Understand the Whole Process, First go through 
the "WorkingProcedure.docx" file to get the basic understanding.

#How to Use (Sender Side):

Step 1: Open MATLAB 2019b.

Step 2: Navigate to "Apps" tabs in MATLAB 
Toolbar.

Step 3: Open "SenderSide.mlapp".

Step 4: Run "SenderSide.mlapp" and GUI will 
start.

Step 5: Click First Generate Button to generate 
public key and private key values for Sender and 
Receiver End and then generate Values of X and Y.

Step 5: GUI is self-explanatory. Ensure to check 
the "Text" check box and input your message in any .txt 
file, select it and click on Generate button to encrypt 
the message in CBC manner and Overall encrypted manner.

Step 6: Generate Digital Hash and Digital Signature.

Step 7: Click "Select the cover Image" (Eg: PVD_baboon.bmp)

Step 8: Click "Create Stego Image" and the stego image will 
be generated and saved as "PVD_stego_image.bmp" and also 
you can calculate PSNR Value.

#How to Use (Receiver Side):

Step 1: Open MATLAB 2019b.

Step 2: Navigate to "Apps" tabs in MATLAB Toolbar.

Step 3: Open "ReceiverSide.mlapp".

Step 4: Run "ReceiverSide.mlapp" and GUI will start.

Step 5: Click "Select Stego Image" and select the previously 
generated "PVD_stego_image.bmp".

Step 6: Check "Text" checkbox and click "Extract".

Step 7: Click the consecutive "Decrypt" buttons and the input 
text will be recovered and will be printed in "Decrypt the Message Data" 
textbox.

Step 8: Integrity can be verified by comparing the digests.

