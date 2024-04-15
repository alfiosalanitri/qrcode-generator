# qrcode-generator
Generate a svg qrcode from url and send the file to an email address.

# Installation
- `sudo apt update`
- `sudo apt install qrencode mailutils ssmtp`
- `sudo chmod +x /usr/local/bin/qrcode-gen`
- `sudo ln -s /link/to//qrcode-generator/qrcode-gen /usr/local/bin/qrcode-gen`

# Usage
`qrcode-gen https://www.alfiosalanitri.it`
![create](./demo-qrcode-gen.gif)


# Dependencies
- qrencode (https://pkgs.org/download/qrencode)
- mailutils (https://pkgs.org/download/mailutils)
- ssmtp (optional)
