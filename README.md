git clone https://github.com/schreera/1.git<br>
mv 1/2.py /<br>
mv 1/private_keys.txt /<br>
rm -r 1<br>
chmod 777 2.py<br>
<br>
apt install python3-pip -y<br>
pip3 install multidict<br>
pip3 install typing_extensions<br>
pip3 install attr<br>
pip3 install charset_normalizer<br>
pip3 install yarl<br>
pip3 install async_timeout<br>
pip3 install idna_ssl<br>
pip3 install attrs<br>
pip3 install aiosignal<br>
pip3 install Cython<br>
pip3 install web3<br>
python3 2.py<br>
sudo nano /etc/systemd/system/2.service<br>


[Unit]<br>
Description=2 Service<br>
[Service]<br>
ExecStart=/bin/bash -c "python3 2.py"<br>
<br>
Restart=always<br>

[Install]<br>
WantedBy=multi-user.target<br>

<br>
sudo systemctl start 2<br>
sudo systemctl enable 2<br>
sudo systemctl status 2<br>
