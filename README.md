# LxaNce👸🤴
# Extra_Keys
# 1-How to Enable All Arrow Keys in Termux:
# To launch this setting
Copy it 👇 and paste in your terminal

` mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout `

# 2-How to Enable PAGE UP AND PAGE DOWN + Arrow Keys in Termux:
Copy it 👇 and paste in your terminal

` mkdir $HOME/.termux/ ;echo "extra-keys = [['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 &&logout `

# 3-How to Enable Function Keys in Termux:
Copy it 👇 and paste in your terminal

` mkdir $HOME/.termux/ ;echo "extra-keys = [['F1','F2','F3','F4','F5','F6','F12'],['ESC','TAB','CTRL','ALT','-','DOWN','UP']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout `

# 4-How to Enable All Keys in Termux:
Copy it 👇 and paste in your terminal 

` mkdir $HOME/.termux/ ;echo "extra-keys = [['F1','F2','F3','F4','F5','F6','F7'],['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]" >> $HOME/.termux/termux.properties && termux-reload-settings && sleep 1 && logout `

## Conclusion:
Enabling Keys in termux takes 4-5 commands but I don't want to waste your time by separating the commands so that's why i have Created one command to do the job.if you are unable to find the key you are searching for you can check out `termux-wiki` for the name of your key and then you can edit the name of the key in any command to Enable your desired key.
