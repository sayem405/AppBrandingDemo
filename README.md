# AppBrandingDemo
A way of showing App branding instead Splash Screen

Protip from LaneLake : https://plus.google.com/+AndroidDevelopers/posts/Z1Wwainpjhd

Additional note from LaneLake : 

Note: if you want to specifically match what you see in Google apps, add android:bottom=”@dimen/product_logo_bottom” to the product_logo_144dp item where product_logo_bottom is 16dp, 48dp (land), 24dp (sw600dp & sw600dp-land), 64dp (port-v21) and 72dp (sw600dp-port-v21 & sw600dp-land-v21).

The brand name at the bottom (the ‘Google’ in Google apps’ launch screens) would be a 48dp high grayscale image with gravity center_horizontal|bottom and an android:bottom of 48dp, 56dp (sw600dp), 104dp (port-v21), and 96dp (sw600dp-port-v21 & sw600dp-land-v21). A visible brand name is certainly not required, but can provide consistency if your company has multiple apps.

We’re still tweaking numbers and would still suggest centering your image as in the post itself, particularly in cases where you are not using a brand name.

Meterial Design Speck : https://material.google.com/patterns/launch-screens.html#
