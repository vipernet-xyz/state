# State Download

1. Ensure you have `pip` installed. If not, install `pip` first:
```
sudo apt install python3-pip
```
Then, install `gdown`:
```
pip install gdown
```

2. Download the File (height: 14144):
```
sudo rm -r data (Delete the previous data file, if you have one)
mkdir data 
cd data
gdown 1V0___7Mf5GZ3_9K9GuiZQ0oSEaI_gakX
```

If you spot the below `Error`:
`Command 'gdown' not found, did you mean:
  command 'cdown' from deb cdtool`

Update `PATH`: 
```
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

3. Unzip the downloaded file after successful download:
```
sudo apt install unzip
unzip data.zip
```
