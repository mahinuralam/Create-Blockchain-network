# Create-Blockchain-network

Resources used to create a Blockchai Network (Not perfectly ordered)

BLOCKCHAIN 


Node1


Public address of the key:   0x2101A88e38e1552f8B19a94725c4e4F6b95f2b1c
Path of the secret key file: node1/keystore/UTC--2023-03-23T18-27-27.733301000Z--2101a88e38e1552f8b19a94725c4e4f6b95f2b1c


Node2


Public address of the key:   0xcF95dC166a9753614a76DF36eeabD06e7441826e
Path of the secret key file: node2/keystore/UTC--2023-03-23T18-28-11.701223000Z--cf95dc166a9753614a76df36eeabd06e7441826e



./geth --datadir node1 --port 30306 --bootnodes enode://f7aba85ba369923bffd3438b4c8fde6b1f02b1c23ea0aac825ed7eac38e6230e5cadcf868e73b0e28710f4c9f685ca71a86a4911461637ae9ab2bd852939b77f@127.0.0.1:0?discport=30305  --networkid 123454321 --unlock 0xC1B2c0dFD381e6aC08f34816172d6343Decbb12b --password node1/password.txt --authrpc.port 8551



enode://6761e7ebed64fc3ff7f5e9a0e087395cbf8402f25842f23086cd881df621c209b713903d0c0cc9573a3f6fb66c0c7f7dfd06e564fb4989f359ba3a9496d0acdd@127.0.0.1:0?discport=30305

./geth --datadir node1 --port 30306 --bootnodes  enode://6761e7ebed64fc3ff7f5e9a0e087395cbf8402f25842f23086cd881df621c209b713903d0c0cc9573a3f6fb66c0c7f7dfd06e564fb4989f359ba3a9496d0acdd@127.0.0.1:0?discport=30305 --networkid 14333 --unlock 0x2101A88e38e1552f8B19a94725c4e4F6b95f2b1c --password node1/password.txt --authrpc.port 8551




sudo geth --networkid 14333 --datadir . --bootnodes enode://5da825b71814c50390d520c8fc777fd1e65277b37e6df34bad8b4f21b5d88635afceb3536efd6d5bbd54e2ff51b88509ee7aaf55e222fbf19690995163b30961@127.0.0.1:0?discport=30315 --port 30316 --ipcdisable --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "127.0.0.1" --http --http.addr "0.0.0.0" --http.vhosts "127.0.0.1" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8546 --unlock '0x2101A88e38e1552f8B19a94725c4e4F6b95f2b1c' --password password.txt --mine --miner.threads=1 -- miner.etherbase=0x2101A88e38e1552f8B19a94725c4e4F6b95f2b1c


sudo geth --networkid 14333 --datadir . --bootnodes enode://6761e7ebed64fc3ff7f5e9a0e087395cbf8402f25842f23086cd881df621c209b713903d0c0cc9573a3f6fb66c0c7f7dfd06e564fb4989f359ba3a9496d0acdd@127.0.0.1:0?discport=30305 --port 30304 --ipcdisable --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "127.0.0.1" --http --http.addr "0.0.0.0" --http.vhosts "127.0.0.1" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8547 --unlock '0xcF95dC166a9753614a76DF36eeabD06e7441826e' --password password.txt --mine --miner.threads=1 --miner.etherbase=0xcF95dC166a9753614a76DF36eeabD06e7441826e   sudo geth --datadir . --port 30307 --bootnodes enode://6761e7ebed64fc3ff7f5e9a0e087395cbf8402f25842f23086cd881df621c209b713903d0c0cc9573a3f6fb66c0c7f7dfd06e564fb4989f359ba3a9496d0acdd@127.0.0.1:0?discport=30305  --networkid 14333 --unlock 0xcF95dC166a9753614a76DF36eeabD06e7441826e --password password.txt --authrpc.port 8551  --mine --miner.threads=1 --miner.etherbase=geth --datadir . --port 30307 --bootnodes enode://6761e7ebed64fc3ff7f5e9a0e087395cbf8402f25842f23086cd881df621c209b713903d0c0cc9573a3f6fb66c0c7f7dfd06e564fb4989f359ba3a9496d0acdd@127.0.0.1:0?discport=30305  --networkid 14333 --unlock 0xcF95dC166a9753614a76DF36eeabD06e7441826e --password password.txt --authrpc.port 8551  --mine --miner.threads=1 --miner.etherbase=0xcF95dC166a9753614a76DF36eeabD06e7441826e








bootnode -nodekey boot.key -verbosity 5 -addr :30305



Node1


Public address of the key:   0x0161e8ea3E4b2Cc18c8c3558285e2751aa1A1b77
Path of the secret key file: node1/keystore/UTC--2023-03-26T05-43-12.684443000Z--0161e8ea3e4b2cc18c8c3558285e2751aa1a1b77



Node2

Public address of the key:   0x1B0c161D9Fc8ff91CffFE5304D44b1C3011ea8Ae
Path of the secret key file: node2/keystore/UTC--2023-03-26T05-44-20.671501000Z--1b0c161d9fc8ff91cfffe5304d44b1c3011ea8ae


Bootnode

enode://84de2ecc484a6f4d393b9f796562f64199b27c233dfce4f4336debc06dfb6f5fe62bf11ece8a1f4b89a2e9bce54c29bbfc68e6922b99f1e6a4ab0830caeea016@127.0.0.1:0?discport=30305


Node1

sudo geth --datadir node1 --port 30306 --bootnodes enode://84de2ecc484a6f4d393b9f796562f64199b27c233dfce4f4336debc06dfb6f5fe62bf11ece8a1f4b89a2e9bce54c29bbfc68e6922b99f1e6a4ab0830caeea016@127.0.0.1:0?discport=30305  --networkid 14333 --unlock 0x0161e8ea3E4b2Cc18c8c3558285e2751aa1A1b77 --password node1/password.txt --authrpc.port 8551 

Node2

sudo geth --datadir node2 --port 30307 --bootnodes enode://84de2ecc484a6f4d393b9f796562f64199b27c233dfce4f4336debc06dfb6f5fe62bf11ece8a1f4b89a2e9bce54c29bbfc68e6922b99f1e6a4ab0830caeea016@127.0.0.1:0?discport=30305  --networkid 14333 --unlock 0x1B0c161D9Fc8ff91CffFE5304D44b1C3011ea8Ae --password node2/password.txt --authrpc.port 8552       ———————————————————————————————————  node1

Public address of the key:   0x7caF1F4cE525C9DA6095573b515B06a60b19C320
Path of the secret key file: node1/keystore/UTC--2023-03-26T06-14-25.134366000Z--7caf1f4ce525c9da6095573b515b06a60b19c320  
sudo geth --datadir node1 --port 30306 --bootnodes enode://4d0b1b5f9c65dde60e738cb5a747fe233b9009be1d77cd7e22cc871a5d6c7d1e4aa58bde1b51fb4467c10cf054e4e8b0ecef884c30d76d58c14619b51d9bf167@127.0.0.1:0?discport=30305  --networkid 14333 --unlock 0x7caF1F4cE525C9DA6095573b515B06a60b19C320 --ipcdisable --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "127.0.0.1" --http --http.addr "0.0.0.0" --http.vhosts "127.0.0.1" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8547 --unlock 0x7caF1F4cE525C9DA6095573b515B06a60b19C320 --password node1/password.txt --mine --miner.threads=1 --miner.etherbase=0x7caF1F4cE525C9DA6095573b515B06a60b19C320


——————
sudo geth --datadir node1 --port 30306 --nat extip:127.0.0.1 --networkid 14333 --unlock 0x7caF1F4cE525C9DA6095573b515B06a60b19C320 --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "127.0.0.1" --http --http.addr "0.0.0.0" --http.vhosts "127.0.0.1" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8547 --unlock 0x7caF1F4cE525C9DA6095573b515B06a60b19C320 --password node1/password.txt --mine --miner.threads=1 --miner.etherbase=0x7caF1F4cE525C9DA6095573b515B06a60b19C320



enr:-KO4QIq9jBmKOpzqNcaTtSRGWPKZrhYesf8cbf6ctGrp4-cxBbNGj3gC5cdC3EFEZldpgM0GE7EHa3_GpBmJiZtoVxGGAYceVhj_g2V0aMfGhE7W2JCAgmlkgnY0gmlwhH8AAAGJc2VjcDI1NmsxoQKjFCSk781mjcpC5rS2XCoKuCoT3QTMR9XkUz23H2fj64RzbmFwwIN0Y3CCdmKDdWRwgnZi


Node2


Public address of the key:   0xEC424430e175b7D11B6fDC72411197A2150c80E6
Path of the secret key file: node2/keystore/UTC--2023-03-26T06-15-11.452530000Z--ec424430e175b7d11b6fdc72411197a2150c80e6



sudo geth --datadir node2 --port 30307 --bootnodes enode://4d0b1b5f9c65dde60e738cb5a747fe233b9009be1d77cd7e22cc871a5d6c7d1e4aa58bde1b51fb4467c10cf054e4e8b0ecef884c30d76d58c14619b51d9bf167@127.0.0.1:0?discport=30305  --networkid 14333 --unlock 0xEC424430e175b7D11B6fDC72411197A2150c80E6 --ipcdisable --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "127.0.0.1" --http.vhosts "127.0.0.1" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8546 --unlock 0xEC424430e175b7D11B6fDC72411197A2150c80E6 --password node2/password.txt --mine --miner.threads=1 --miner.etherbase=0xEC424430e175b7D11B6fDC72411197A2150c80E6

——————————————
sudo geth --datadir node2 --port 30307 --bootnodes enode://78197d8c0d586fece2ad4dd7ca334bf825d9ae67ca316fc710da9ad1f983c66244bea67e68190783e3fbe10fe1af46d73916e22ed3897104bf3c3b955d8f068f@127.0.0.1:30306 --networkid 14333 --unlock 0xEC424430e175b7D11B6fDC72411197A2150c80E6 --ipcdisable --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "127.0.0.1" --http.vhosts "127.0.0.1" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8546 --unlock 0xEC424430e175b7D11B6fDC72411197A2150c80E6 --password node2/password.txt --mine --miner.threads=1 --miner.etherbase=0xEC424430e175b7D11B6fDC72411197A2150c80E6



Bootnode

enode://4d0b1b5f9c65dde60e738cb5a747fe233b9009be1d77cd7e22cc871a5d6c7d1e4aa58bde1b51fb4467c10cf054e4e8b0ecef884c30d76d58c14619b51d9bf167@127.0.0.1:0?discport=30305








clique.propose("0x7caF1F4cE525C9DA6095573b515B06a60b19C320",true)

clique.propose("0xEC424430e175b7D11B6fDC72411197A2150c80E6",true)

eth.getBalance(‘0x7caF1F4cE525C9DA6095573b515B06a60b19C320’)


eth.getBalance("0xEC424430e175b7D11B6fDC72411197A2150c80E6")

clique.getSingers()

eth.




https://geth.ethereum.org/docs/fundamentals/private-network  https://geth.ethereum.org/docs/interacting-with-geth/rpc/ns-clique


https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.17+commit.8df45f5f.js&lang=en  https://github.com/anchorblock/attendance-management-system/blob/dev/fastapi_AMS/routes/setting.py


chrome-extension://nkbihfbeogaeaoehlefnkodbefgpgknn/home.html#

——————————————————————SAKIB SIR———————————————————————————
mkdir node1
mkdir node2

geth --datadir node1 account new  
geth --datadir node2 account new

password 123

0x2d6cCC30315B781516625e80636D685E11b85A55
0xE326390164D0e9B29f6F311b62bFD11666A35115


geth init --datadir node1 genesis.json
geth init --datadir node2 genesis.json

bootnode -genkey boot.key
bootnode -nodekey boot.key -addr :30305

enode://f8645a388cc831bd7e9420905f1e3789d95665b2d6bfc76b71b7596b9adb8960f899cfd7657740849ccd670889f26f87c3d0d3ee1ca2a678cd311fd900919662@127.0.0.1:0?discport=30305

create password.txt

**changing port address not enough, also ipc disable. 

geth --datadir node1 --port 30306 --bootnodes enode://f8645a388cc831bd7e9420905f1e3789d95665b2d6bfc76b71b7596b9adb8960f899cfd7657740849ccd670889f26f87c3d0d3ee1ca2a678cd311fd900919662@127.0.0.1:0?discport=30305 --networkid 2002 --unlock 0x2d6cCC30315B781516625e80636D685E11b85A55 --password node1/password.txt --authrpc.port 8551 --mine --miner.threads=1 --miner.etherbase=0x2d6cCC30315B781516625e80636D685E11b85A55

geth --datadir node2 --port 30307 --bootnodes enode://f8645a388cc831bd7e9420905f1e3789d95665b2d6bfc76b71b7596b9adb8960f899cfd7657740849ccd670889f26f87c3d0d3ee1ca2a678cd311fd900919662@127.0.0.1:0?discport=30305 --networkid 2002 --unlock 0xE326390164D0e9B29f6F311b62bFD11666A35115 --password node2/password.txt --authrpc.port 8552 --mine --miner.threads=1 --miner.etherbase=0xE326390164D0e9B29f6F311b62bFD11666A35115 --ipcdisable





https://ethereum.org/az/developers/docs/data-and-analytics/block-explorers/    ESS -> Role -> Module -> Group 


Added default mouse point focus on Multicode and added Employee ID (Config Based) filter on Movement Pass index page for Barcode Scanner, added Movement Pass/Register list page button, Auto check-in time from employee shift end time api permission given.

Fund Requisition separate list page for ESS user only to show ESS user fund requisition list.


clique.propose("0x64D15C718038C858FDe0f4F01C1A7Fe847909042",true)


sudo geth --datadir node2 --port 30307 --bootnodes enode://199c287ee7887e2b617539339b9497438cbaca74a9d8423a65bf92fe07b8fb724dec1a981fe2d3432f90104bb0096934aabbfda0590912d13aac7c0a7f5e6c57@127.0.0.1:30306 --networkid 14333 --unlock 0xF64F54c2BA0FBC7998A6aE1538262EaE35746ABc --ipcdisable --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "127.0.0.1" --http.vhosts "127.0.0.1" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8546 --unlock 0xF64F54c2BA0FBC7998A6aE1538262EaE35746ABc --password node2/password.txt --mine --miner.threads=1 --miner.etherbase=0xF64F54c2BA0FBC7998A6aE1538262EaE35746ABc



—————————————————————————————————————————————————————

Connecting with aws e2c

PC ONE 

3.109.209.119 ssh -i "grid_key.pem" ubuntu@ec2-3-109-209-119.ap-south-1.compute.amazonaws.com

Node1

sudo add-apt-repository -y ppa:ethereum/ethereum

sudo apt-get update
sudo apt-get install ethereum


mkdir node1

geth --datadir node1 account new  

Public address of the key:   0xA359A0974d39cC038E692A27D5A3eCd4Fccd1Cb8

password divine213

touch genesis.json


{
  "config": {
    "chainId": 14333,
    "homesteadBlock": 0,
    "eip150Block": 0,
    "eip155Block": 0,
    "eip158Block": 0,
    "byzantiumBlock": 0,
    "constantinopleBlock": 0,
    "petersburgBlock": 0,
    "istanbulBlock": 0,
    "muirGlacierBlock": 0,
    "berlinBlock": 0,
    "londonBlock": 0,
    "arrowGlacierBlock": 0,
    "grayGlacierBlock": 0,
    "clique": {
      "period": 5,
      "epoch": 30000
    }
  },
  "difficulty": "1",
  "gasLimit": "800000000",
  "extradata": "0x0000000000000000000000000000000000000000000000000000000000000000CFdc4619d7d99A99F84D6C86C65283Fe32F7cBF80000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  "alloc": {
    "0xCFdc4619d7d99A99F84D6C86C65283Fe32F7cBF8": {
      "balance": "10000000000000000000"
    }
  }
} 
touch password.txt  


geth init --datadir node1 genesis.json



sudo geth --datadir node1 --port 30306 --nat extip:3.109.209.119
 --networkid 14333 --unlock 0xA359A0974d39cC038E692A27D5A3eCd4Fccd1Cb8 --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "3.109.209.119" --http --http.addr "0.0.0.0" --http.vhosts "3.109.209.119" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8547 --unlock 0xA359A0974d39cC038E692A27D5A3eCd4Fccd1Cb8 --password node1/password.txt --mine --miner.threads=1 --miner.etherbase=0xA359A0974d39cC038E692A27D5A3eCd4Fccd1Cb8

enode://7fb4be62254a11453522bef045bff8a7d8e10853ac7f406ed48ecc4dce79668062783eedfea5b925147ab623e4d420d192b531c188ee3df89b3577a95989f943@3.109.209.119:30306

enode://e37954d795741fc174cc11c18c2bcbd98ed676324250996fd65d78fbe3e656fa2f10e3051e5166b5243dfaa231b45415e8348b9b6841613daf6df1bac3910066@3.109.209.119:30306



PC TWO 

ssh -i "grid_key.pem" ubuntu@ec2-3-110-114-38.ap-south-1.compute.amazonaws.com  Public address of the key:   0x5F651845D02CA5A13B07d51Df2E190EA7395F581    sudo geth --datadir node2 --port 30307 --bootnodes enode://c366352e5bf6f80d02f78bd90bff0fbe92a28d7684fe3a1c07bcd92194f199620717cd5a6e55310ac5920e33062eefa831209ccb20c37dd8e5495013bbe236d3@3.109.209.119:30306--networkid 14333 --syncmode 'full' —http —http.addr “0.0.0.0” --allow-insecure-unlock --http.corsdomain “*” --authrpc.port 8546 --unlock 0x5F651845D02CA5A13B07d51Df2E190EA7395F581 --password node2/password.txt --mine --miner.threads=1 --miner.etherbase=0x5F651845D02CA5A13B07d51Df2E190EA7395F581  






sudo geth --datadir node2 --port 30307 --bootnodes enode://e37954d795741fc174cc11c18c2bcbd98ed676324250996fd65d78fbe3e656fa2f10e3051e5166b5243dfaa231b45415e8348b9b6841613daf6df1bac3910066@3.109.209.119:30306 --networkid 14333 --syncmode 'full' --http --http.addr "0.0.0.0" --allow-insecure-unlock --http.corsdomain "*" --authrpc.port 8546 --unlock 0x5F651845D02CA5A13B07d51Df2E190EA7395F581 --password node2/password.txt --mine --miner.threads=1 --miner.etherbase=0x5F651845D02CA5A13B07d51Df2E190EA7395F581



clique.propose("0x4e76D75D2564501d4028fbAfc6f736F1e2010aDA",true)



0x0F1A9450aC1Fa67a27Adb6ACd59cFe22f5029218



0x4e76D75D2564501d4028fbAfc6f736F1e2010aDA





{
  "config": {
    "chainId": 14333,
    "homesteadBlock": 0,
    "eip150Block": 0,
    "eip155Block": 0,
    "eip158Block": 0,
    "byzantiumBlock": 0,
    "constantinopleBlock": 0,
    "petersburgBlock": 0,
    "istanbulBlock": 0,
    "muirGlacierBlock": 0,
    "berlinBlock": 0,
    "londonBlock": 0,
    "arrowGlacierBlock": 0,
    "grayGlacierBlock": 0,
    "clique": {
      "period": 5,
      "epoch": 30000
    }
  },
  "difficulty": "1",
  "gasLimit": "800000000",
  "extradata": "0x0000000000000000000000000000000000000000000000000000000000000000f30afBB3D2F25ef302D0Da725E5c9D85281529C30000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  "alloc": {
    "0xf30afBB3D2F25ef302D0Da725E5c9D85281529C3": {
      "balance": "10000000000000000000"
    }
  }
}


enode://e0a900fd72e44221c91c43f827faaf5ddd3c72c32ee9aa3f19d8e99bf42d6e40598aa5ef3b9c183920dc735adb4d0a22c52f5508af22ac6b7dc2f32905cf50dc@127.0.0.1:30306



geth attach node1/geth.ipc
geth attach node1/geth.ipc

bD2B5d72A92e0868354F0B644d784258cD8a2d71

clique.propose("0x7B2e0c1b0d459c2f77cb12FF0841EA88CBd007E9",true)


sudo geth --datadir node1 --port 30306 --nat extip:118.179.189.244 --networkid 14333 --unlock 0x7caF1F4cE525C9DA6095573b515B06a60b19C320 --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "118.179.189.244" --http --http.addr "0.0.0.0" --http.vhosts "118.179.189.244" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8547 --unlock 0x7caF1F4cE525C9DA6095573b515B06a60b19C320 --password node1/password.txt --mine --miner.threads=1 --miner.etherbase=0x7caF1F4cE525C9DA6095573b515B06a60b19C320


0xf30afBB3D2F25ef302D0Da725E5c9D85281529C3


0x7B2e0c1b0d459c2f77cb12FF0841EA88CBd007E9


Node1

0x433Ce4155d78d95E4947553D523902c4723a520f


{
  "config": {
    "chainId": 14333,
    "homesteadBlock": 0,
    "eip150Block": 0,
    "eip155Block": 0,
    "eip158Block": 0,
    "byzantiumBlock": 0,
    "constantinopleBlock": 0,
    "petersburgBlock": 0,
    "istanbulBlock": 0,
    "muirGlacierBlock": 0,
    "berlinBlock": 0,
    "londonBlock": 0,
    "arrowGlacierBlock": 0,
    "grayGlacierBlock": 0,
    "clique": {
      "period": 5,
      "epoch": 30000
    }
  },
  "difficulty": "1",
  "gasLimit": "800000000",
  "extradata": "0x0000000000000000000000000000000000000000000000000000000000000000A4f82d966406E5D6c7e78858D4635b7942a6Eb870000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  "alloc": {
    "0xA4f82d966406E5D6c7e78858D4635b7942a6Eb87": {
      "balance": "10000000000000000000"
    }
  }
}


————————————————————April 7 —————————————————————————————


Node1

0xD02Ea1122786A1FE9EEf26d42e489eD51fb4D4f0

{
  "config": {
    "chainId": 14333,
    "homesteadBlock": 0,
    "eip150Block": 0,
    "eip155Block": 0,
    "eip158Block": 0,
    "byzantiumBlock": 0,
    "constantinopleBlock": 0,
    "petersburgBlock": 0,
    "istanbulBlock": 0,
    "muirGlacierBlock": 0,
    "berlinBlock": 0,
    "londonBlock": 0,
    "arrowGlacierBlock": 0,
    "grayGlacierBlock": 0,
    "clique": {
      "period": 5,
      "epoch": 30000
    }
  },
  "difficulty": "1",
  "gasLimit": "800000000",
  "extradata": "0x0000000000000000000000000000000000000000000000000000000000000000A4f82d966406E5D6c7e78858D4635b7942a6Eb8700000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
  "alloc": {
    "0xA4f82d966406E5D6c7e78858D4635b7942a6Eb87": {
      "balance": "10000000000000000000"
    }
  }
} 

sudo geth --datadir node1 --port 30306 --nat extip:3.109.209.119 --networkid 14333 --unlock 0xD02Ea1122786A1FE9EEf26d42e489eD51fb4D4f0 --syncmode 'full' --graphql --graphql.corsdomain "" --graphql.vhosts "3.109.209.119" --http --http.addr "0.0.0.0" --http.vhosts "3.109.209.119" --allow-insecure-unlock --http.corsdomain "" --authrpc.port 8547 --unlock 0xD02Ea1122786A1FE9EEf26d42e489eD51fb4D4f0 --password node1/password.txt --mine --miner.threads=1 --miner.etherbase=0xD02Ea1122786A1FE9EEf26d42e489eD51fb4D4f0

 Node2  0x00ab3dAFCDC6CD3Ea959abC73E1b96eDA77d2fcF

geth init --datadir node2 genesis.json





NODE1

0xE015A9AF3b0fE1DA317179BDcD5EA9Fb5FB0C863

Node2

0x6eee41b2546002C303793dED3EAa20d15B29946C


clique.propose("0x6eee41b2546002C303793dED3EAa20d15B29946C",true)








