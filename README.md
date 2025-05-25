# Sumber
- 

# Blockchain 1 Node (Part 1 s.d. 3)
- pip3 install flask
- pip3 install request
- touch blockchain.py
- python3 blockchain.py 5000
- [GET] http://localhost:5000/blockchain
- [GET] http://localhost:5000/mine
- [POST] http://localhost:5000/transactions/new

# Blockchain Sinkronisasi

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