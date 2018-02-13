## About

#### Sick of getting your Mega.nz Files Reported?

MegaCrypt.js lets you share your Mega.nz files without actually having to share any Mega.nz links. By encrypting your links, MegaCrypt will create a secure proxy to your files.

#### Sick of running out of Mega.nz Bandwidth?

Any files downloaded trought MegaCrypt.js wont affect your accounts Bandwidth, promised! Now you can download as many files as you want!

## Url Decryption Example:

![MegaCrypt Url Decryption Example](https://i.imgur.com/yR0EE1P.png)

## Server Setup Guide:

1. grab git repo: `git clone https://github.com/JohnDeved/megacrypt.js.git`
2. install dependencies: `npm i`
3. start Server: `npm start`

## Config Guide:

- [int] __port__: the port megacrypt.js will be running on
- [str] __serverKey__: Private Server Key (should be changed)
- [bool] __encryptionTool__: if true, the link encryption tool will on the base url
- [bool] __encrytionApi__: if true, the link encryption api will be enabled (nedded for the encryption tool)
- [bool] __returnCiphertext__: if true, the site will pipe the requested files without decryption them
