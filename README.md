## MetaConnect
A dashboard for Creators, for minting and image to a unique ERC-1155 token.

## Usage
How to use run this repository in your local host.

### Clone this repo
```bash
git clone https://github.com/buymekofi/Near-X-Encode 
```

### Deploy the smart contract
```bash
cd Near-X-Encode && cd buymekofi_contract 
npm run dev
```

### For DB Sync:
```
  python manage.py makemigrations metaconnect
  python manage.py migrate metaconnect
  
```

### Run the django server
Make sure you have `python` and `Django` install then run
```bash
cd ..
python manage.py runserver
```
