# elasticsearch-vuejs

## install dependeces
```bash
yarn # or npm install
yarn dev # or npm run dev
```

## install elasticsearch
- `curl -L -O https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-5.6.4.deb`
- `sudo dpkg -i elasticsearch-5.6.4.deb`
- `sudo /bin/systemctl daemon-reload`
- `sudo /bin/systemctl enable elasticsearch.service`
- `sudo systemctl start elasticsearch.service`
- `sudo service elasticsearch status`

or read [more info manual install](https://www.elastic.co/guide/en/elasticsearch/reference/current/deb.html)


## run project

```bash
node data.js
```
```bash
node index.js
```

on browser go to `http://localhost:3001/`

search any city
