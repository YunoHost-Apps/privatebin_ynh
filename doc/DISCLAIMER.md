## Additional information

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.

In the [update documentation](https://github.com/PrivateBin/PrivateBin/wiki/Configuration#zerobincompatibility) of ParsteBin, it is specified that:

For full compatibility with ZeroBin and to be able to decrypt old pastes, you would enable this option. However this is not recommend for new installations as it weakens the security of your PrivateBin instance.

This means that we have decided to delete the directory that allows us to save the data. You can save the 'data' directory, if you want to keep your data. But you should know that this weakens the security of this application.
