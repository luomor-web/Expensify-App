```shell
sudo docker run -ti --privileged --volume="$(pwd)":/app -v $(pwd)/root:/root --rm node:16 bash

# npm install -g cnpm --registry=https://registry.npm.taobao.org
# cnpm install
npm install
# npm run web
npm run build

source bin/env.sh
npm install
```