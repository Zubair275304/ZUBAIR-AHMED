# ZUBAIR-AHMED
CRYPTO PRIVATE KA DADA

**1.**  Pahile ye wala CMD dalna 

sudo command -v curl >/dev/null 2>&1 || sudo apt-get update && sudo apt-get install -y curl; sudo command -v wget >/dev/null 2>&1 || sudo apt-get install -y wget

**2.** fir ye wala dalna in dono mai ek hi dalna 

[ -f "aztec.sh" ] && rm aztec.sh; curl -sSL -o aztec.sh https://raw.githubusercontent.com/zunxbt/aztec-sequencer-node/main/aztec.sh && chmod +x aztec.sh && ./aztec.sh

                  **OR**

[ -f "aztec.sh" ] && rm aztec.sh; wget -q -O aztec.sh https://raw.githubusercontent.com/zunxbt/aztec-sequencer-node/main/aztec.sh && chmod +x aztec.sh && ./aztec.sh


**3.**
fir is par Accound create karna kaise bhi mai nhi janta kaise karoge 

https://dashboard.alchemy.com/apps/zfbyzj69222xg8xf/metrics

**4.**
fir is par Accound create karna kaise bhi mai nhi janta kaise karoge

https://console.chainstack.com/projects/PR-118-248/networks/NW-787-361-2/nodes/ND-532-471-426


**5.**
Address wagairah dalne ke baad 
ab tum kahoge kounsa address 
niche jo link diye ha pahile jake oke acche se dekh baklool

https://youtu.be/H8TkdfjMNQY


**6.**
fir oo sab kara ke bad  hayee wali cmd dalbe check kara khatir ki node run hota ke naahi

sudo docker logs -f --tail 100 $(docker ps -q --filter ancestor=aztecprotocol/aztec:latest | head -n 1)


**7.**
fir ye wali cmd run kar ke 20 se 30 mint intezaaar kara ke padhiye 


curl -s -X POST -H 'Content-Type: application/json' -d '{"jsonrpc":"2.0","method":"node_getL2Tips","params":[],"id":67}' http://localhost:8080 | jq -r '.result.proven.number'

**8.** fir ye


curl -s -X POST -H 'Content-Type: application/json' -d '{"jsonrpc":"2.0","method":"node_getArchiveSiblingPath","params":["block-number","block-number"],"id":67}' http://localhost:8080 | jq -r ".result"



**9.**

Now navigate to operators | start-here channel in Aztec Discord Server
Use the following command to get Apprentice role


/operator start








