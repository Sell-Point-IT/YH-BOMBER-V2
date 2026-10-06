### For Termux (Android)

```bash
pkg update && pkg upgrade
pkg install git -y
pkg install python python-pip git
pip install aiohttp asyncio
git clone https://github.com/Sell-Point-IT/YH-BOMBER-V2.git
cd W8SmsBomberV1
pip install -r requirements.txt
python W8SmsBomber.py
