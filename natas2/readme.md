- natas2 seems very similar to natas 0 and 1, so i will try inspecting the html source again![](https://remnote-user-data.s3.amazonaws.com/TebBebreOcG_Cr2d1D7ureIJ8eoW1s60zeIGXjPKw2E7VHRauUNVBMdrWHqLxeGagSbUi2mmtKYkkKR35PxYzfYfICI7QPelQm-0nechdsuFgUFltNmI53IH2dZTSvJv.png)
- inspecting the html doesn't show much initially. at first i thought it was to do with the javascript, but that only shows the credentials for natas2, and there is a comment which says the stuff in the header has nothing to do with the level, which i will trust.![](https://remnote-user-data.s3.amazonaws.com/nM5-4MiVH6Iphy3y8grJSTnUFg35FheEm-dtoVjUIKiWY_MFNVf_DUdcFDj1jFDz0-4xURpGqQiyWJaTnHapxytoiixBLEFbe_eO6uetwrr8D1vpiya50I2cMuakUyeI.png)
- i didn't notice an image on the page however, and there seems to be a file stored at `files/pixel.png`, so i'll take a look at that first.
- ![](https://remnote-user-data.s3.amazonaws.com/vgNiN_3aAj8mSUGkV_Uuk5gdRU82_1NekxkAQ20Gskfj914NkG2wEAZP_zwicFjz4xJSsIMSzD_BPy1IT5bjJXOlVpYXNZ9uHXiTHIvUhJOXMhMQmH-C95JYuzibTzjz.png)
- the image is literally just a single pixel. not much use, so i'll look elsewhere for now. the image is being stored in a directory `files`, so i'll try navigating to `http://natas2.natas.labs.overthewire.org/files` in hopes of finding an open directory
- ![](https://remnote-user-data.s3.amazonaws.com/MFlGFYHzbu5q1NJHXGbaNOyewYebnnoM6pFNin451DbwaGsTlFfJfoJ7eGRPb--8s-D6QGqXG1Ur0JmIH5GfdWuH_0gLKX_BOfwTRZdI_nT1ZPvcTsUJq8vQ3xK0uFxg.png)
- doing this does reveal an open directory, and the file `users.txt` is also in the folder along with the image. i'll take a look at the file
- ![](https://remnote-user-data.s3.amazonaws.com/YdG75Q1xe4AeUdpkv4XHrRBDn7V5-D5Kr_pe1l5oxBiy-op2tMEksSGWq3DyPjqJ-BwbzMQ81LUg85TMslt8CgB7xmfYRYKBR_Zh7Qo1pykef5u9sdS6zloQp8MYVz4R.png)
- this reveals some users and their passwords, one of which is natas3 and its corresponding password.
- 
