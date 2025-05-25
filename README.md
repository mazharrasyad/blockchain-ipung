# Sumber
- https://www.youtube.com/playlist?list=PLH1gH0TmFBBhvZi4kEqU6kCjyv_y8qBae

# Blockchain Node Single
- pip3 install flask
- pip3 install request
- touch blockchain.py
- python3 blockchain.py 5000
- [GET] http://localhost:5000/blockchain
- [GET] http://localhost:5000/mine
- [POST] http://localhost:5000/transactions/new

# Blockchain Node Sync

- python3 blockchain.py 5000
- python3 blockchain.py 5001
- [POST] http://localhost:5000/transactions/new
- [GET] http://localhost:5000/blockchain
- [GET] http://localhost:5001/blockchain
- [GET] http://localhost:5000/mine
- [POST] http://localhost:5000/nodes/add_nodes tambah 5001
- [POST] http://localhost:5001/nodes/add_nodes tambah 5000
- [GET] http://localhost:5000/nodes/sync
- [GET] http://localhost:5001/nodes/sync

# Blockchain Remix IDE

- https://ethereum.org
- https://remix.ethereum.org