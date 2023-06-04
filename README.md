# **Dangun Feveron - No Voices**

This patch removes all of the voices from the Dangun Feveron MAME rom (except for the one at the opening Cave logo). It has no other effect.

There is also a "Plus" version of the patch, which does the same thing, but additionally also removes one sound effect (the one that plays whenever a discoman flies off-screen).


## Patching Instructions:

1 - Extract your MAME Dangun Feveron rom archive (dfeveron.zip). Look for two files named "cv01-u19.bin" and "cv01-u33.bin". If your dfeveron archive is missing one of these files, then you can most likely find and get a copy from your Fever SOS rom archive (feversos.zip).

2 - Using your xdelta patcher of choice, apply the df-nvup.xdelta patch to "cv01-u33.bin". Make sure that your patched file has the same filename as the original.

3 - Apply one of the two "no voices" xdelta patches to "cv01-u19.bin". Make sure that your patched file has the same filename as the original.

4 - Rezip the dfeveron rom archive with the two patched files (and whatever else was originally inside it).
  
  
##### NOTE: When you start up the patched rom, MAME will complain about wrong checksum. This is expected, and can be safely ignored. If necessary, the patching process can be verified using the hashes below:
  
cv01-u33.bin

(Original) &nbsp; CRC32:&nbsp; e53a7db3  
(Original) &nbsp; MD5:  &nbsp; &nbsp;   eafca7b46e5302f39f665715df5f5e4f  
(Original) &nbsp; SHA-1: &nbsp; ddced29f78dc3cc89038757b6577ba2ba0d8b041  
  
(Patched) &nbsp; CRC32:&nbsp; 68768afc  
(Patched) &nbsp; MD5:  &nbsp; &nbsp;   d2659fb05f3c3b0f38bfe6ba5a0727b9  
(Patched) &nbsp;  SHA-1: &nbsp; 7966f442320f500c36695b9d6fe5fa2ad48c5de0  

&nbsp; &nbsp;  

cv01-u19.bin (No Voices)

(Original) &nbsp; CRC32:&nbsp; 5f5514da  
(Original) &nbsp; MD5:  &nbsp; &nbsp;   ccbd7f7a536ad3fc4f7d5b04f324c6de  
(Original) &nbsp; SHA-1: &nbsp; 53f27364aee544572a82649c9ff29bacc642b732  
  
(Patched) &nbsp; CRC32:&nbsp; fd08bd24  
(Patched) &nbsp; MD5:  &nbsp; &nbsp;   c7a3304d28f893704ce983c8e4e20bd8  
(Patched) &nbsp;  SHA-1: &nbsp; 617e94d05d28c4f5db80de21b5d1a747fe2519d8  

&nbsp; &nbsp;  

cv01-u19.bin (No Voices Plus)

(Original) &nbsp; CRC32:&nbsp; 5f5514da  
(Original) &nbsp; MD5:  &nbsp; &nbsp;   ccbd7f7a536ad3fc4f7d5b04f324c6de  
(Original) &nbsp; SHA-1: &nbsp; 53f27364aee544572a82649c9ff29bacc642b732  
  
(Patched) &nbsp; CRC32:&nbsp; a974c2c1  
(Patched) &nbsp; MD5:  &nbsp; &nbsp;   49931f358bb864f63852df9da881d575  
(Patched) &nbsp;  SHA-1: &nbsp; 11d5c321494e79f0948f7697c32fd185bf31d238  

## &nbsp;

Patch by KMH  
2023-05-13 - Released  
2023-06-04 - Updated the patch to address a general Dangun Feveron audio issue (frequent audio crackling/popping when voices are triggered during gameplay)
