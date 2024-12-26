# EC2 Setup Files

This repo just holds files I commonly use for AWS EC2 instances.

# Usage

To use, just click on a file of choice here in GitHub, click on the "Raw" button in the upper right, copy the URL, then use `wget` in the server console to retrieve the file.
```shell
wget https://raw.githubusercontent.com/joshua-holmes/ec2-setup-files/main/README.md -O /name/of/output/file
```

In some cases, you will need to either modify the file after it's copied and/or install the necessary program for the file to even work. For example, the `ddns.service` file is a systemd service that calls the command `cloudflare-ddns`, which means you need to have `cloudflare-ddns` installed on the server for it to even do anything.

