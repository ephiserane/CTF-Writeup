![image](https://github.com/ephiserane/CTF-Writeup/assets/95566707/cae1cb71-42d9-4984-83b8-119a24e2d4b8)

Steps:
  1. Download the `cat.jpg`
  2. Check the file with command `file cat.jpg`
     ![image](https://github.com/ephiserane/CTF-Writeup/assets/95566707/94ab9c59-4473-4c66-8f7a-e58b68222d37)

  3. Check with other command `strings cat.jpg`
     ![image](https://github.com/ephiserane/CTF-Writeup/assets/95566707/2e768240-b308-4501-9c1e-a6e19195ebc8)
     
  4. Try with another command `exiftool cat.jpg`
     ![image](https://github.com/ephiserane/CTF-Writeup/assets/95566707/f32efcaa-1e1c-4a3f-b984-5635edf6a384)

  5. And I see a same pattern in the license so I try decode it with Base64
     ![image](https://github.com/ephiserane/CTF-Writeup/assets/95566707/1ca20f12-9291-4ba2-ac72-04330ae3fd64)

Flag: picoCTF{the_m3tadata_1s_modified}
