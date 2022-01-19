# Hill_Cipher-Encryption_and_Decryption
A Python script to implement Hill's Cipher Encryption and Decryption.

Initially in the Encryption part, the Plain Text is enumerated and the blocks of 'N' alphabets is paired together and converted to the Cipher Text by the standard Hill Cipher's Formula.

For the Decryption part, initially the adjoint of the matrix is calculated using 'Sympy' library and using the 'adjugate' function.
Then the determinent is calculated with using the 'numpy' library function.
And then the inverse modulo is calculated and multiplied by the adjoint matrix, and then the same procedure is repeated as done in the encryption part.
