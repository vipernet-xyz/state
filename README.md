# State Download

1. Ensure you have `pip` installed. If not, install `pip` first:
```
sudo apt install python3-pip
```
Then, install `gdown`:
```
pip install gdown
```

2. Download the File (height: 15724):
(Delete the previous data file, if you have one)
```
sudo rm -r data
```
Create a new `data` folder and download the latest state:
```
mkdir data 
cd data
gdown 1OsAVmBeII-xsIHHnrkQhEv3rWFSrrgKB
```

If you spot the below `Error`:
`Command 'gdown' not found, did you mean:
  command 'cdown' from deb cdtool`

Update `PATH` and retry downloading: 
```
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gdown 1OsAVmBeII-xsIHHnrkQhEv3rWFSrrgKB
```

3. Unzip the downloaded file after successful download:
```
sudo apt install unzip
unzip data.zip
rm data.zip
```
