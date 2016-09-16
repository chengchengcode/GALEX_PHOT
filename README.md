# GALEX Photometry Codes

These are the code I write in Shanghai Shifan Daxue. I perform the GALEX photometry based on the CFHT U band source position in the COSMOS field.

I understand there are already several group working on the GALEX phot e.g. EMPHOT http://cesam.lam.fr/galex-emphot/ . 

But still, as I was just into the astronomy data for 1.5 yr then, it seems a very good exercise to me.

Thus I write these PSF fit/substract code.

#Algorithm

0, CFHT U band source detection

1, CFHT U and GALEX FUV/NUV PSF generate

2, GALEX PSF fitting with U band source position

3, Substract all the GALEX flux except the target

4, Aperture phot

5, Photometry uncentainty estimation

6, Combine all the GALEX data into one UV catalog.

